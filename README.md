# Computational theory assessment

My work for the Computational Theory module at ATU Galway.
All the problems are in [`problems.ipynb`](problems.ipynb).
They're based on the [Secure Hash Standard (FIPS 180-4)](https://doi.org/10.6028/NIST.FIPS.180-4), the NIST document that defines SHA-256.

## What's in the repo

| File | What it is |
|------|------------|
| `problems.ipynb` | The notebook with all the problems |
| `requirements.txt` | The Python packages needed to run the notebook |
| `AGENTS.md` | Instructions for AI tools used on this repo |

Each problem is tracked as a GitHub [Issue](https://github.com/qahramantaha/computational-theory/issues).

## How to run it

1. Clone the repo and go into the folder:

   ```bash
   git clone https://github.com/qahramantaha/computational-theory.git
   cd computational-theory
   ```

2. Install the packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter lab problems.ipynb
   ```

4. Run everything from the top with **Kernel > Restart Kernel and Run All Cells**.