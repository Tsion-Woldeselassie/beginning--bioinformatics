# AI Use Log
- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):

---

## Entry 1: Rosalind INI2 - Variables and Arithmetic
- Tool/model & version: Gemini
- What I asked for: Help solving Rosalind problem "INI2 - Variables and Arithmetic"
- Snippet of prompt(s): "Given two positive integers a and b, each less than 1000. Return the integer corresponding to the square of the hypotenuse..."
- What I changed before committing: Adjusted the file path in Python so Colab could read my uploaded dataset.
- How I verified correctness (tests, sample data): Checked with sample input (3, 5 → 34). Confirmed final dataset result was 1569992.

## Entry 2: Rosalind INI3 - Strings and Lists
- Tool/model & version: ChatGPT
- What I asked for: Help solving Rosalind problem "INI3 - Strings and Lists"
- Snippet of prompt(s): "Given a string s and four integers a, b, c, d, slice the string into two parts and return them separated by a space."
- What I changed before committing: Fixed my dataset file (rosalind_ini3.txt) so it had both the string and the four integers on separate lines. Ran code in Colab to slice and output correctly.
- How I verified correctness (tests, sample data): Confirmed with the provided dataset. The final output was `Tryngites strepera`, which matched Rosalind’s expected answer format.

## Entry 3: Rosalind INI4 - Conditions and Loops
- Tool/model & version: Gemini
- What I asked for: Help solving Rosalind problem "INI4 - Conditions and Loops"
- Snippet of prompt(s): "Given two integers a and b, return the sum of all odd integers between them inclusive."
- What I changed before committing: Wrote a Python script in Colab that reads two integers from `rosalind_ini4.txt` and calculates the sum of odd numbers between them using a list comprehension.
- How I verified correctness (tests, sample data): Verified with small inputs (e.g., a=1, b=10 → sum=25). Confirmed dataset output matched Rosalind submission (16546929).
