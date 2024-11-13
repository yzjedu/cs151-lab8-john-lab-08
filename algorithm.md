
John Elehwany

Lab 08 Algorithm


1. Import random module
2. Make sum_counts a list of 11 zeros

- Pupose: Main game function. Does everything below.
- Name: main_game
- Parameters: none
- Return: none
    - Purpose: Simulates a roll of one die
      - Name: roll_die
      - Parameters: None
      - Return: None
      - Roll is a random integer 1-6
    
    
    - Purpose: Simulates a roll of two dice
      - Name: roll_dice
      - Parameters: None
      - Return: None
      - Calls roll_die twice and gives sum
    
    
    - Purpose: Asks for roll input from user
      - Name: roll_input
      - Parameters: None
      - Return: num_rolls
      - While True:
      - Ask for input of number of rolls fom user (num_rolls)
      - Check if answer is integer
      - Repeat until a correct answer is provided -- "Invalid answer! Please input a number"
      - Return num_rolls
    
    
    - Purpose: Rolls dice for a number of times. Calculates the sum afterward.
      - Name: rolls 
      - Parameters: num_rolls
      - Return: sum_list
      - Loop for as many times as num_roll:
      - Call roll_dice
      - Put sum corresponding to index. (sum is 2-12 and list is 1-13)
      - Return sum_list
    
    
    - Purpose: Display a graph of results of rolls
      - Name: results
      - Parameters: sum_list
      - Return: None
      - Print "You rolled {roll_input} times. Here are the results:"
      - For each sum 2-12:
        - Output number of asterisks depending on how many times number was rolled
