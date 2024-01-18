# Building a Mitre Attack Navigator Layer and TTPs Timeline using Azure OpenAI

## Introduction
Drawing inspiration from cybersecurity experts like Oleksiy Meletskiy, this Jupyter Notebook, developed by Antonio Formato, enhances the analysis of intelligence reports. It leverages Azure OpenAI for the automatic extraction of critical data from available reports or articles, streamlining the process of creating visual Mitre Layers. Additionally, the notebook employs Large Language Models to construct timelines that detail attack strategies, showcasing the impactful role of Generative AI in cyber defense.

This guide details the use of Azure OpenAI for extracting TTPs (Tactics, Techniques, and Procedures) and the visualization of cyber attack timelines using tools such as Mitre Attack Navigator and Mermaid.js. Our objective is to equip cybersecurity professionals with tools that are not only efficient but also deepen their insight into cyber threat management.

## Notebook Details
- **Version**: 0.1
- **Author**: Antonio Formato
- **Inspiration**: Oleksiy Meletskiy

## Technical Requirements
- **Python Version**: >=Python 3.8
- **Data Source Required**: None
- **GPU Compute Required**: No

## Python Packages
- requests
- BeautifulSoup (bs4)
- pandas
- os
- json
- uuid
- BlobServiceClient (azure.storage.blob)
- DefaultAzureCredential (azure.identity)
- IFrame (IPython.display)
- base64
- Image (IPython.display)
- display (IPython.display)
- matplotlib.pyplot

## Prerequisites
- Sequential Execution: Ensure to run the notebook cells one after the other. Each cell must be successfully executed before moving to the next.
- Library Installation: Confirm that all required libraries are installed. Use `pip install` for any missing packages.
- Azure Blob Storage: Integration with the Mitre Attack Navigator in this notebook is achieved through the use of Azure Blob Storage.

## Getting Started
1. Clone this repository to your local machine.
2. Open the notebook in a Jupyter environment.
3. Ensure Python 3.8 or higher is installed.
4. Install necessary Python packages.
5. Follow the instructions within the notebook for a step-by-step guide.

## Contribution
Your contributions are welcome! Please read the contribution guidelines for more information.

## License
This project is licensed under the [MIT License](LICENSE.md) - see the LICENSE file for details.

## Acknowledgments
Special thanks to Oleksiy Meletskiy for the inspiration behind this project.
