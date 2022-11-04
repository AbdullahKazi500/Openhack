   # Openhack
    Qbraid open hack
     Team members
                 Rohit Saini
                 Abdullah Kazi
                 Pranav Maheshwari
                 Rishabh Singh
                 Vansh Jhunjhunwala
                 Soubhadra Maiti
        Submission summary
        open submission
        A Quantum Version of the classic TicTacToe Game
       Additional comments
              Check Qmodel_version2.ipynb
              & README.md
       General Rules: 
        Instead of placing normal crosses and noughts, you will be placing superpositions of crosses and noughts called Qubits.
         The 3x3 Grid is numbered from 0-8 (Top-Left to Bottom-Right, row-wise)
         You and the Computer take turns placing your Qubits (You can only choose to place from a pre-defined set of Qubits)
          You and the Computer can both choose to "Measure" any 3 Qubits along a row, a column or a diagonal. By Measuring, you force the Qubits to collapse onto                 either a cross or a nought, in accordance to the probabilities of the Qubit. The goal is to measure and find either three crosses or three nuts.
          You and the Computer can both choose to measure a maximum of 5 times. If a measurement is successful, you win, otherwise the 3 Qubits you measured are                  removed from the grid, and the game continues.
         If you (or the computer) make 5 unsuccessful Measurements, you lose!
    Quantum Edge:
            As it stands right now, this a game of odds, and in order to make it strategic, we added the following Quantum advantages for the user:
            The user has an option to Entangle Qubits. Entanglement means that the user can guarantee two Qubits at a given time would either both have the same result             or the opposite result (as per the user's choice). For example, if you have a Qubit 75/25 on Grid Square 3, and you choose to place a positively Entangled             Qubit on Grid 7, the computer is simply going to interpret it as a 75/25 Qubit (It cannot see Entanglement, it's your secret Superpower!) Therefore,        statistically the computer still believes there is a 0.75x0.25x2 chance they might be opposite, and would factor those into its calculations. However, when actually measured, there is A 75% chance you will measure both positive, or a 25% chance you would measure both negative. Use this to your advantage by strategically placing Entangled Qubits! Note However, if you ever measure the source Qubit without measuring the Entangled one, it would still be removed from the Grid. You cannot have an Entangled Qubit on the Grid when the source has been removed.

           You, also have the ability to Super Measure! Basically, you can measure all existing Qubits on the Grid, and if anywhere you manage to measure three same               in a row, you win! However, be cautious, Super Measure is a gamble, and if you fail, you lose instantly!
      
