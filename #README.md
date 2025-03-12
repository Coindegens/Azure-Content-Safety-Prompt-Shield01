**Implement Azure AI Content Safety - Prompt Shield**

This project demonstrates the implementation of Azure AI Content Safety service to detect and shield against potential jailbreak attacks and unsafe content in prompts and documents.

## Features

- Detect jailbreak attempts in user prompts
- Analyze documents for potential security risks
- Integrate with Azure AI Content Safety API
- Handle API responses for content analysis

## Prerequisites

- Azure subscription
- Azure AI Content Safety resource - Prompt Shield
- Python 3.x

## Setup

1. Clone the repository
2. Install dependencies:
```bash
pip install requests
```
3. Update the configuration in `mslearn-content-safety-prompt-shield01.py`:
   - Replace `subscription_key` with your Azure AI Content Safety key
   - Update `endpoint` with your service endpoint

## Usage

Run the script with:
```bash
python mslearn-content-safety-prompt-shield01.py
```

## Configuration

The script accepts two main inputs:
- `user_prompt`: The text to analyze for potential jailbreak attempts
- `documents`: List of documents to scan for security risks

## Response Format

The API returns:
- Analysis results for prompt safety
- Document security assessment
- Risk categories and confidence scores

## License

Copyright (c) All rights reserved.

## Additional Resources

- [Azure AI Content Safety Documentation](https://learn.microsoft.com/azure/ai-services/content-safety/)
- [Azure AI Studio](https://oai.azure.com/portal)
