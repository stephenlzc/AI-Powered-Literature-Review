# AI-Powered-Literature-Review(DIFY workflow)

# <font color="red">**This project aims to explore the application of AI large language models (LLM) in workflows and the use of prompts. The generated content is intended solely for quickly understanding a certain field, method, or technology and must NOT be used for academic publication or any form of academic misconduct. We uphold academic integrity and reject any practices that violate academic ethics.**</font>


<p align="center">
  <a href="./README.md"><img alt="简体中文版" src="https://img.shields.io/badge/简体中文-d9d9d9"></a>
  <a href="./README_EN.md"><img alt="English" src="https://img.shields.io/badge/English-d9d9d9"></a>
</p>

## Overview

This repository contains a YAML configuration file for an automated literature review workflow using the Dify platform. The workflow, named "EXA", is designed to streamline the process of conducting comprehensive literature reviews by leveraging AI and natural language processing technologies.

## Key Features

1. **Keyword Generation**: Automatically generates relevant keywords based on a given research direction.
2. **Literature Search**: Utilizes the EXA API to search for and retrieve relevant academic papers.
3. **Outline Creation**: Generates a structured outline for the literature review.
4. **Content Writing**: Expands the outline into a full draft, incorporating information from the retrieved papers.
5. **Review and Refinement**: Includes an AI-powered review step to assess the quality and completeness of the draft.
6. **Final Polishing**: Refines the draft based on the review feedback and prepares it for submission.
7. **✓ Automated Citation and Bibliography Generation**: Automatically generates citations and bibliographies for the literature review.
8. **✓ Multi-language Support for Literature Search**: Supports literature search in multiple languages.
9. **✓ Collaborative Features for Team-based Reviews**: Provides collaborative features for team-based literature reviews.

## Detailed Workflow

1. **Input**: The user provides the research topic, publication year range, target language, and the number of papers to retrieve.
2. **Keyword Generation**: The system uses AI to generate relevant keywords based on the input research topic.
3. **Literature Search**: Using the generated keywords, the EXA API searches for and retrieves academic papers.
4. **Data Processing**: The retrieved papers are processed and summarized.
5. **Outline Creation**: An AI model creates a structured outline for the literature review.
6. **Content Writing**: The outline is expanded into a full draft, incorporating information from the retrieved papers.
7. **Review**: An AI-powered review step assesses the quality and completeness of the draft.
8. **Final Polishing**: Based on the review feedback, the draft is refined and prepared for submission.

## How to Use

1. Ensure you have access to the Dify platform and the necessary API keys.
2. Clone this repository to your local machine.
3. Configure the `exa_api_key` environment variable with your EXA API key.
4. Open the Dify platform and import the YAML configuration file.
5. Input the required parameters:
   - Search keywords
   - Publication year
   - Target language
   - Number of papers to retrieve
6. Run the workflow in the Dify platform.
7. Review the outputs and make any necessary adjustments.

## Output

The workflow produces several outputs:
- A summary of the retrieved papers
- A structured outline
- A draft of the literature review
- A review of the draft
- A final, polished version of the literature review

## Requirements

- Dify platform access
- EXA API key
- Access to various AI models (GPT-4, Claude, etc.)

## Development Approach

This project was developed entirely using AI tools such as ChatGPT and Claude. No traditional coding was involved in the creation of this workflow. This approach demonstrates the potential of AI-assisted development in creating complex, functional systems without extensive programming knowledge.

## Roadmap

We are constantly working to improve the EXA Literature Review Workflow. Here are some features we're planning to implement in the future:

- Integration with more academic databases
- Enhanced customization options for the review process
- Integration with reference management software
- Integration with FastGPT workflow
- Integration with CrewAI workflow
- Integration with AutoGen workflow

## Contributing

We welcome contributions to the EXA Literature Review Workflow! If you have suggestions for improvements or bug fixes, please open an issue or submit a pull request.

## Support

If you find this project helpful, consider buying me a coffee!

<a href="https://www.buymeacoffee.com/chicongliau"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=chicongliau&button_colour=FFDD00&font_colour=000000&font_family=Bree&outline_colour=000000&coffee_colour=ffffff" /></a>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
