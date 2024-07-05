# InsightEngine: PythonAgentAI

## Overview
InsightEngine uses Python to deliver an advanced data querying platform, merging AI with robust data handling tools. 

## Modules

### main.py
- **Functionality**: Orchestrates overall interaction using custom query engines and AI models.
- **Key Components**:
  - Environment Variable Loading
  - Data Handling with pandas
  - Integration of Custom Tools (`note_engine`, `canada_engine`, `swiss_engine`)
  - AI Model Interaction
  - Interactive Command-Line Interface

### note_engine.py
- **Purpose**: Provides a utility to save textual notes.
- **Features**:
  - Manages a note file in a specific directory.
  - Appends user-provided notes to the file.

### pdf.py
- **Purpose**: Handles the extraction of data from PDF files and creates searchable indices.
- **Features**:
  - Reads data from specific PDF files (`Canada.pdf`, `Switzerland.pdf`).
  - Manages index creation for efficient query processing.

### prompts.py
- **Purpose**: Defines templates and instructional strings for formatting data queries.
- **Features**:
  - Instructional guide for transforming user queries into executable code.
  - Prompt template setup for pandas DataFrame operations.

## Installation

Clone this repository and install the required Python packages:

```bash
git clone <repository-url>
cd <repository-name>
pip install -r requirements.txt
```

## Usage
Run the main script to start the interactive command-line interface:

python main.py
