# Smart Word Redactor
The web app redacts the sensitive words in documents

https://github.com/user-attachments/assets/bedbd7e2-1654-4120-bfca-c23bc6c39526

## User useflow
1. Upload PDF document 
2. Enter the words to redact
3. Review and Download redacted PDF

## Technical Consideration
- Built without the use of AGPL-licenced libraries, such as Pymupdf, to ensure future business flexibility.
- Utilizes four different open-source libraries for PDF handling: `pypdfium2`, `pdf_redactor`, `pdfminer`, and `PyPDF2`.
- Source code is proprietary and cannot be shared, as it is a resource of Jigo Incorporation.

## Stack
- Streamlit
- Python
