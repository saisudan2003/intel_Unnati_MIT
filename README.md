# intel_Unnati_MIT
This project is a business contract classification tool designed to extract text from PDF files, compare clauses within the documents, classify the clauses and generate a report highlighting the differences. It uses `pdfplumber` for text extraction and `difflib` for comparing text. It uses `LSTM model` of Keras to classify and predict the type of clause. The front-end is done in `React` and the back-end in `Flask`.

## Table of Contents

- [PDF Clause Comparison Tool](#pdf-clause-comparison-tool)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
    - [Extracting Text from PDFs](#extracting-text-from-pdfs)
    - [Loading and Parsing Clauses](#loading-and-parsing-clauses)
    - [Comparing Clauses](#comparing-clauses)
    - [Generating the Report](#generating-the-report)
  - [Project Structure](#project-structure)
  - [Contributing](#contributing)
  - [License](#license)

## Features

- Extract text from PDF files uploaded.
- Identify and parse clauses from the extracted text.
- Compare clauses from two different PDF documents.
- Generate a report highlighting the differences between the clauses.
- Make a PDF with the deviations highlighted

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/saisudan2003/intel_Unnati_MIT.git
   cd intel_Unnati_MIT
   ```

2. To run the front-end:
   ```
   cd frontend
   npm dev
   ```
3. To run the python app:
   ```
   cd ..
   python app.py
   ```

## Video Link

The following is a video link showing the working of our solution.
https://drive.google.com/file/d/1Jk2WTyZikz67j6IhInnmo3tsekZYTA0s/view?usp=sharing

## Data Folder

The following is the drive link to the data folder we used for training the model.
https://drive.google.com/drive/folders/1LHpsZnK7DVCcpGwTVArYcSTKWIYY0jQj?usp=sharing

1. The 'raw' folder contains the raw legal agreement PDFs obtained by us.
2. The 'processed' folder contains the raw PDFs converted to textual format by our parser.
3. The 'annotated' folder contains the processed texts annotated into clauses through classification.

## 
