# Acronym Generator  

## Overview  
The Acronym Generator is a simple Python program designed to generate acronyms from phrases entered by the user. It reads a string input, extracts the first letter from each word, and outputs the resulting acronym in uppercase.  

---

## How It Works  
1. The program displays a welcome message.
2. It prompts the user to enter a phrase.
3. It generates the acronym by processing the input phrase.
4. The acronym is displayed to the user.
5. The user can continue generating acronyms or exit the program.

6. ## Code Explanation  

- **`acronym(text)` Function**:  
  A function that iterates through the input string and collects the first letter of each word to create an acronym.  

- **`main()` Function**:  
  Handles the user interaction. It:
  - Welcomes the user with a formatted message.
  - Continuously asks the user for a phrase, processes it, and displays the acronym until they choose to quit.
  - Bids farewell when the program ends.

---

## How to Run the Program  
1. Ensure Python is installed on your system.
2. Save the code in a file, e.g., `acronym_generator.py`.
3. Run the program using the command:  
   ```bash
   python acronym_generator.py
Features
	•	Generates acronyms for any input phrase.
	•	User-friendly interface with clear instructions.
	•	Continuous loop functionality to allow multiple phrases without restarting the program.

Limitations
	•	Assumes words are separated by spaces.
	•	Does not handle non-alphabetic characters in acronyms.

Future Improvements
	•	Allow processing of phrases with punctuation and special characters.
	•	Add validation for empty or invalid input.
