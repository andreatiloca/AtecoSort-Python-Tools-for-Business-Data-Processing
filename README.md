# IRAP-Calc – Python System for Municipal Business Tax Assessment

This Python project is designed to calculate the IRAP (Italian Regional Tax on Productive Activities) for companies registered in one or more municipalities. The system uses structured class definitions to manage business data, and processes company records sorted by ATECO code.

## 📌 Project Overview

The system is composed of three main scripts:

1. **`primo_programma.py` – ATECO Sorting**
   - Reads a text file containing raw business data.
   - Sorts the companies by their ATECO classification code.
   - **Input**: `lista_imprese_test.txt`
   - **Output**: `dati_imprese_ordinate`

2. **`secondo_programma.py` – IRAP Calculation**
   - Performs financial operations and computes the IRAP tax on the sorted business dataset.
   - **Input**: `dati_imprese_ordinate`

3. **`terzo_programma.py` – Municipality-Level Aggregation**
   - Simulates one or more municipalities.
   - Aggregates and reports IRAP data per municipality.

4. **`classi.py` – Class Definitions**
   - Defines all core classes representing businesses, financial records, and municipalities.

## 🗂 Repository Structure

- `classi.py`: Object-oriented class definitions
- `primo_programma.py`: Sorts companies by ATECO code
- `secondo_programma.py`: Computes IRAP based on business financials
- `terzo_programma.py`: Groups businesses by municipality and summarizes tax data
- `lista_imprese_test.txt`: Sample business input
- `dati_imprese_ordinate`: Output used for taxation and aggregation

## ▶️ How to Run

Each script can be executed independently from the command line:

```bash
python primo_programma.py
python secondo_programma.py
python terzo_programma.py
