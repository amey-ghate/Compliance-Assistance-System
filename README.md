# Compliance-Assistance-System

Organizations face an ongoing challenge to stay compliant with complex standards that are often packed with intricate details and regulations. Navigating these documents is time-consuming, frustrating, and can lead to misinterpretation.

## Solution Overview

The **Compliance Assistance System** is an AI-driven solution designed to streamline compliance by:

- **Effortlessly Summarizing Standards**: Providing quick, concise, and accurate answers from any standard, offering immediate clarity and reducing confusion.
- **Safeguarding Intellectual Property**: Operating entirely on your infrastructure, this solution gives you full control over your data, eliminating security risks associated with cloud-based LLMs.

### Example Use Case
Consider the **NIST IR 8199** standard. Our Compliance Assistance System allows you to:
- Effortlessly extract key insights
- Locate specific requirements
- Compare regulations to your current practices—all in real time and within your secure environment.

## Key Benefits

- **Reduced Compliance Time**: Obtain answers instantly, eliminating the need for manual searches through extensive documents.
- **Improved Accuracy**: Gain confidence with AI-driven interpretations and analyses, enhancing compliance reliability.
- **Enhanced Productivity**: Focus on applying insights rather than sifting through countless pages.

## Features

- **Rapid Standards Loading**: Load any PDF-based standard or regulation document.
- **Efficient Embedding and Retrieval**: Utilizes document embeddings to retrieve and interpret relevant sections accurately.
- **Customizable Queries**: Ask specific questions about compliance, and the system will generate tailored, AI-powered answers.

## Technical Requirements

- Python 3.8+
- Required packages:
  - `langchain_community`
  - `langchain_core`
  - `Ollama`
  - `Chroma`
  - `PyPDFLoader`

## Usage

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd compliance-assistance-system
  ```
2. **Set Up Standards Directory**:
   Place your standards documents (PDF format) in a folder named `standards`.

3. **Run the Application**:
   Run the main script to embed document content and query standards.

4. **Example Query**:
   ```python
   question = "What are federal and state restrictions on lead content in children's items?"
   answer = retrieval_chain.invoke({"input": question})
   print(answer['answer'])
  ```
## Looking Forward

The Compliance Assistance System provides a streamlined approach to managing compliance. Contact us today to discover how this solution can empower your organization.

