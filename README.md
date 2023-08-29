# Knights and Knaves Puzzle Solver
(a part of CS50 AI course)

## Background

Inspired by the logical puzzles presented in Raymond Smullyan's 1978 book "What is the name of this book?", this project tackles the "Knights and Knaves" puzzles. In these puzzles, you meet characters who are either knights, who always tell the truth, or knaves, who always lie.

The objective is to figure out who is a knight and who is a knave based on the statements they make.

For example, if A says "I am both a knight and a knave," we can determine that A must be a knave, because the statement is contradictory.

## Specification

The project can solve various puzzles with different complexity levels:

- **Puzzle 0**: Single character, A.
    - A says, "I am both a knight and a knave."
- **Puzzle 1**: Two characters, A and B.
    - A says, "We are both knaves."
    - B says nothing.
- **Puzzle 2**: Two characters, A and B.
    - A says, "We are the same kind."
    - B says, "We are of different kinds."
- **Puzzle 3**: Three characters, A, B, and C.
    - A's statement is unknown.
    - B says, "A said 'I am a knave.'"
    - B also says, "C is a knave."
    - C says, "A is a knight."

## Running the Solver

After setting up your knowledge base for a puzzle, run the following command to solve it:

```bash
python puzzle.py
