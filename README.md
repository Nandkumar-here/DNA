# 🧬 DNA

**DNA** is a Python program that identifies individuals based on **Short Tandem Repeats (STRs)** found in a DNA sequence and matches them to a DNA database.

---

## 📌 How It Works

- The database (`.csv`) contains names and STR counts
- The sequence (`.txt`) contains a long string of DNA
- The program:
  1. Reads the DNA sequence
  2. Counts max consecutive STR repeats
  3. Compares against each person’s STR profile in the database
  4. Prints the matching person’s name, or `"No match"`

## Usage

### Run the program

```bash
python dna.py str_database.csv sequence.txt
