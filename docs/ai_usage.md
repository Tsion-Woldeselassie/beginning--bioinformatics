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

## Entry 4: Rosalind INI5 – Working with Files
- Tool/model & version: ChatGPT
- What I asked for: Help solving Rosalind problem "INI5 – Working with Files"
- Snippet of prompt(s): "Given a file containing at most 1000 lines, return a file containing all the even-numbered lines from the original file."
- What I changed before committing: Wrote a Python script in Colab that uploads the dataset (`rosalind_ini5.txt`), reads all the lines into a list, and outputs only the even-numbered ones. Implemented two approaches:
  1. Using `.join()` with list slicing (`lines[1::2]`)
  2. Using a `for` loop with a counter to check even-numbered lines
- How I verified correctness (tests, sample data): First tested with the sample dataset from Rosalind and confirmed the output matched the expected even-numbered lines. Then uploaded the full Rosalind dataset and verified the final output matched the Rosalind submission format.

## Entry 5: Rosalind INI6 - Dictionaries
- Tool/model & version: Gemini
- What I asked for: Help solving Rosalind problem "INI6 - Dictionaries"
- Snippet of prompt(s): "Given a string of words, count the number of occurrences of each word and return each word with its count."
- What I changed before committing: Wrote a Python script in Colab that reads the Rosalind dataset file (`rosalind_ini6.txt`), splits the input into words, uses a dictionary to count occurrences, and prints out the key–value pairs.
- How I verified correctness (tests, sample data): Verified with the provided sample dataset (`We tried list and we tried dicts also we tried Zen`) → output matched sample (`and 1`, `We 1`, `tried 3`, …). Final dataset output was submitted and accepted by Rosalind.

## Entry 6: Rosalind DNA – Counting DNA Nucleotides
- Tool/model & version: ChatGPT
- What I asked for: Help solving Rosalind problem "DNA – Counting DNA Nucleotides"
- Snippet of prompt(s): "Given a DNA string, count the number of times that the symbols 'A', 'C', 'G', and 'T' occur."
- What I changed before committing: Wrote a Python script in Colab that reads the Rosalind dataset file (`rosalind_dna.txt`), stores the string, and uses `.count()` to calculate the occurrences of each nucleotide (A, C, G, T).
- How I verified correctness (tests, sample data): Verified with the provided sample dataset (`AGCTTTTCATTCTGACTGCAAC...`) → output matched sample (`20 12 17 21`). Final dataset output was submitted and accepted by Rosalind.

## Entry 7: Rosalind RNA – Transcribing DNA into RNA
- Tool/model & version: ChatGPT (GPT-5)
- What I asked for: Help solving Rosalind problem "RNA – Transcribing DNA into RNA"
- Snippet of prompt(s): "Given a DNA string t, return the transcribed RNA string formed by replacing all 'T' with 'U'."
- What I changed before committing: Wrote a Python script in Colab that reads the Rosalind dataset file (`rosalind_rna.txt`), replaces all occurrences of `T` with `U`, and prints the RNA string.
- How I verified correctness (tests, sample data): Verified with the provided sample dataset (`GATGGAACTTGACTACGTAAATT`) → output matched sample (`GAUGGAACUUGACUACGUAAAUU`). Final dataset output was submitted and accepted by Rosalind.

## Entry 8: Rosalind PROT – Translating RNA into Protein
- Tool/model & version: ChatGPT (GPT-5)
- What I asked for: Help solving Rosalind problem "PROT – Translating RNA into Protein"
- Snippet of prompt(s): "Given an RNA string, return the protein string encoded by it using the RNA codon table."
- What I changed before committing: Installed Biopython in Colab, uploaded the dataset file (`rosalind_prot.txt`), and wrote a script that uses `Seq` from `Bio.Seq` to translate the RNA sequence into a protein string.
- How I verified correctness (tests, sample data): Verified with the provided sample dataset (`AUGGCCAUGGCGCCCAGAACUGAGAUCAAUAGUACCCGUAUUAACGGGUGA`) → output matched sample (`MAMAPRTEINSTRING`). Final dataset output was submitted and accepted by Rosalind.

## Entry 9: Rosalind GC - Computing GC Content
- Tool/model & version: Colab + Biopython
- What I asked for: Help solving Rosalind problem "GC Content" (Problem 9)
- Snippet of prompt(s): "Given up to 10 DNA strings in FASTA format, return the ID of the string with the highest GC content, followed by its GC content (to six decimal places)."
- What I changed before committing: Wrote a Python script in Colab that uploads the dataset (`rosalind_gc.txt`), parses it with `SeqIO` from Biopython, computes GC% using `gc_fraction()`, tracks the highest GC%, and prints the ID and GC content of the sequence with the maximum value.
- How I verified correctness (tests, sample data): Verified with the provided sample dataset (Rosalind_6404, Rosalind_5959, Rosalind_0808) → output matched sample (`Rosalind_0808`, `60.919540`). Final dataset output was submitted and accepted by Rosalind.
