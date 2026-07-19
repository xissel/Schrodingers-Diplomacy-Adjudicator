# Schrodingers-Diplomacy-Adjudicator
This repository contains Python code (as a Notebook file) and 4 additional files to adjudicate a game of Schrödinger's Diplomacy. The adjudicator does nothing but print out when an order is invalid and the reason for invalidity, as of yet. Feel free to fork adjudicators written in other programming languages or to extend its functions.

Extra files include :
- map_data.dot : a file formatted to contain a graph of the variant's map adjacencies and province types.
- entanglements.dot : a file (initially empty) that is progressively filled during the game with a graph of units entangled to one another. Additional manual checks are required to ensure every entangled unit is measured at once (the adjudicator is flawed in that respect).
- units.json : a file containing a dictionary of every unit. Keys are formatted with a number and letter ; the number (from 1 to 6) designates the country, and the letter is the unit's unique identifier/name. To build, one must simply add a new key with the appropriate properties. Disbands are not handled automatically (one must manually remove the unit from the file).
- orders.json : a file containing a list of orders and their properties. The provided file has an example of the syntax expected for each move type.
