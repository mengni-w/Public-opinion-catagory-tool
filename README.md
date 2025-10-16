# Public Opinion Category Tool

## Overview

This repository contains a proposal and implementation framework for an **AI-Assisted Decision-Making System** designed to deliver low sensitivity and high accuracy in classifying and analyzing public opinion based on seven advanced public opinion scenarios. The project leverages AI workflows, structured logic, and categorization algorithms to help extract, classify, and organize key information from public opinion texts.

## Main Components

- **AI_Organization_System_Public_Opinion_Judgment_System.yml**  
  This YAML file outlines the architecture and workflow of the AI judgment system. It details the application setup, enabled features, workflow logic, and connections between modules such as language models and knowledge retrieval. The workflow is designed to process input texts, extract comprehensive keywords, and classify them according to public opinion scenarios.  
  Seven main categories are defined, each covering critical aspects of public opinion:
  1. Ideological Security & Political Risk
  2. Cadre Selection & Supervision
  3. Party Member Education & Supervision
  4. Talent Work & International Talent Security
  5. Organizational System & Policy Implementation
  6. Organizational Self-building & Emergency Response
  7. Regional & Special Domain Party Building

  The workflow uses example prompts and responses to guide the extraction and classification of keywords from input texts, with a strong emphasis on logical accuracy and coverage of vital information.

- **mainAlgorithm**  
  This file contains the main logic and formulas used for categorizing public opinion scenarios. It includes mathematical models, classification logic, and documentation for how the system processes and evaluates public opinion data. The algorithm is structured to enable precise extraction and assignment of information to the seven scenario categories, supporting both high-level analysis and granular keyword extraction.

## Features

- **Automated Keyword Extraction:** Utilizes AI language models to extract multiple sets of relevant keywords from supplied public opinion texts.
- **Scenario-Based Classification:** Assigns extracted information to one of seven advanced public opinion categories for structured analysis.
- **Configurable Workflow:** The YAML workflow supports customization, enabling or disabling features like file upload, speech-to-text, and sensitive word avoidance.
- **Sample Inputs and Outputs:** Included examples demonstrate how the system processes real-world public opinion texts and generates categorized keywords.

## Usage

1. **Input:** Supply a public opinion text to the system.
2. **Processing:** The system reads the text, extracts key events, subjects, time, location, behaviors, emotions, policy links, and societal relevance.
3. **Keyword Extraction:** AI models generate logical, comprehensive keyword lists.
4. **Categorization:** Keywords are assigned to one of the seven defined scenarios using the main algorithm logic.
5. **Output:** Pure keyword strings are produced for further analysis; no additional explanations or formatting are included.

## Files

- [`AI_Organization_System_Public_Opinion_Judgment_System.yml`](https://github.com/mengni-w/Public-opinion-catagory-tool/blob/main/AI_Organization_System_Public_Opinion_Judgment_System.yml): Main workflow configuration.
- [`mainAlgorithm`](https://github.com/mengni-w/Public-opinion-catagory-tool/blob/main/mainAlgorithm): Algorithm and documentation.
- [`LICENSE.txt`](https://github.com/mengni-w/Public-opinion-catagory-tool/blob/main/LICENSE.txt): Licensing information.
- [`final version - Online LaTeX Editor Overleaf.webarchive`](https://github.com/mengni-w/Public-opinion-catagory-tool/blob/main/final%20version%20-%20Online%20LaTeX%20Editor%20Overleaf.webarchive): Proposal and supporting documentation (web archive).

## License

This project is licensed under an "Other" license. See [`LICENSE.txt`](https://github.com/mengni-w/Public-opinion-catagory-tool/blob/main/LICENSE.txt) for details.

---

For more details, visit the repository: [mengni-w/Public-opinion-catagory-tool](https://github.com/mengni-w/Public-opinion-catagory-tool)
