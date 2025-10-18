# Legislative Text Parser

> **Note:** This repository contains the code developed as part of our diploma thesis at the University of Ioannina.  
> Originally hosted under the [DAINTINESS Group](https://github.com/DAINTINESS-Group) organization, this tool was co-developed by **Kostas Papadopoulos**, **Vasileios Ioannis Bouzampalidis**, and **Elias Papathanasiou** as a foundational component for our respective research pipelines.

---
**Legislative Text Parser** is a Java-based application designed to process legislative documents, extract key entities, and visualize the results in an intuitive graphical interface. This tool is particularly useful for legal experts, policymakers, and researchers working with legal texts.

---

## Features

### Legislative Text Processing:
- Processes legislative documents (PDF format).
- Extracts entities from articles with definitions.

### Entity Extraction:
- Dynamically identifies key entities in legislative documents.
- Supports custom definition locations (chapter/article selection).

### Visualization:
- Displays extracted entities in a user-friendly list view.
- Visualizes the hierarchical structure of legislative documents in a DefaultMutableTreeNode Swing-component.

### Interactive GUI:
- Built using Java Swing for intuitive and responsive interaction.
- Features input validation, progress tracking, and error notifications.

---

## Prerequisites

Before running the application, ensure the following software is installed:

- **Java Development Kit (JDK) 19 or higher**
- **Apache Maven** (for dependency management)
- **JSON library (`org.json`)** included in `pom.xml`

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/legislative-text-parser.git
   cd legislative-text-parser

2. Compile the project using Maven:
    
    ```bash
    mvn clean compile
    
3. Run the application:
     
     ```bash
    java -cp target/legislative-text-parser-1.0.jar org.uoi.legislativetextparser.gui.MainMenu


# How to Use

### 1. Input a Legislative Document

- Select a legislative document (`PDF` format) using the **Input Path** field.
- Specify the output path for the processed document (`JSON` format).

### 2. Extract Entities

- (Optional) Specify the chapter and article number for definitions.
- Click **Start** to process the document.

### 3. Visualize Results

- Upon successful processing, a popup notification confirms that the operation completed successfully.
- **Entity Visualizer**: Displays a list of extracted entities.
- **Tree Visualizer**: Shows a hierarchical structure of the document.

## 🧠 Acknowledgment

This tool served as the first component of our diploma thesis pipeline, forming the foundation for subsequent tools and research work.  
It represents the combined effort of three contributors and is shared publicly for academic reference and potential adaptation.

---

## 📬 Contact

For inquiries, collaborations, or academic references:

| Name | Email | GitHub |
|------|--------|--------|
| **Kostas Papadopoulos** | konstantinos.d95@gmail.com | [@kostaspapadopoulos](https://github.com/kostaspapdopoulos) |
---

### 🏛️ Provenance

Originally developed as part of the **"Diploma Thesis “A Software System for Automatically Encoding Legislative Rules in Checklists using OpenAI’s GPT-4o-mini."**  
at the **Department of Computer Science & Engineering, University of Ioannina (Greece)**.  
Supervised by **Dr. Panos Vasiliadis**.
