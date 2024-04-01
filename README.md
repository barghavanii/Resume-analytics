# Resume-analytics-

This tool allows you to upload a PDF resume and convert it into a YAML format. It utilizes OpenAI's GPT-3.5 model for parsing and formatting the resume content.

How It Works

PDF Parsing: The tool extracts text from the uploaded PDF resume using PyPDF2 library.

Formatting: The extracted text is formatted into a YAML template, covering various sections such as name, contact information, education, work experience, skills, etc.

OpenAI Model: The LangChain model, powered by OpenAI's GPT-3.5, is used for parsing and structuring the resume content. The model is trained on a large corpus of resumes to understand the semantics and structure of different resume sections.

Conversation Memory: The tool maintains a conversation buffer memory to keep track of previous interactions, ensuring coherence in the parsed content.

Dependencies

gradio for building the web interface.

PyPDF2 for extracting text from PDF files.

Limitations

The accuracy of parsing and formatting may vary depending on the complexity and formatting of the input resume.

The tool relies on external services like OpenAI's GPT-3.5, so network connectivity and API availability are necessary for proper functioning.

Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Snkgx8aGuo04P9-5D02QL7xKJrN0HnoB#scrollTo=HWD2E6BxRGDV)


# Demo Upload a pdf and the parsed result will be provided as YAML

[![Hugging Face](https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo.svg)](https://huggingface.co/spaces/barghavani/Resume_ATS)

# Demo Upload a pdf and your target job description and get matching score 

[![Hugging Face](https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo.svg)](https://huggingface.co/spaces/barghavani/resumescoresystem)

