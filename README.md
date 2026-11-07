# Financial Stability Analysis Using Local Large Language Models


## Project Overview

This project uses Large Language Models (LLMs) to analyse Mexico's 2025 IMF Country Report and extract important economic and financial information. The project was developed using Python and Google Colab without requiring API keys.

## Models Used

Three models were used in this project:

1. **Qwen2.5-3B-Instruct:** Used for document summarisation, financial information extraction and RAG-based question answering.
2. **Phi-3.5-mini-instruct:** Used as an independent evaluation model to assess accuracy, completeness and consistency.
3. **all-MiniLM-L6-v2:** Used to generate sentence embeddings for FAISS-based semantic retrieval.

The project uses **two Large Language Models and one embedding model**.

## Project Objectives

- Extract and preprocess text from the IMF report.
- Generate summaries of document sections.
- Extract financial indicators in JSON format.
- Identify seven financial stability themes.
- Analyse economic strengths and vulnerabilities.
- Implement Retrieval-Augmented Generation (RAG).
- Evaluate model-generated responses.
- Develop a four-panel financial dashboard.

## Technologies Used

Python, Google Colab, Transformers, PyTorch, Sentence Transformers, FAISS, PyPDF, Pandas, NumPy and Matplotlib.

## Methodology

1. PDF extraction and text preprocessing.
2. Token-based document chunking.
3. Section summarisation using a local LLM.
4. Financial indicator and thematic information extraction.
5. FAISS-based semantic retrieval and RAG implementation.
6. Comparison of RAG and non-RAG responses.
7. LLM-as-a-Judge evaluation.
8. Verification of financial indicators against IMF source tables.
9. Four-panel dashboard visualisation.

## Results

The project generated document summaries, structured financial indicators, financial stability themes and economic risk insights.

The RAG system helped produce more source-grounded answers. However, some numerical extraction errors showed that human verification remains important.

A four-panel dashboard was developed to present financial themes, economic trends, model evaluation scores and banking indicators.

## How to Run

1. Open the project notebook in Google Colab.
2. Enable GPU acceleration.
3. Upload the IMF Country Report PDF if required.
4. Run the notebook cells sequentially.
5. Review the generated outputs and dashboard.

## Conclusion

This project demonstrates how local LLMs, sentence embeddings and RAG can support financial document analysis. The system provides a structured way to extract, summarise, evaluate and visualise economic information from lengthy IMF reports.

## Reference

International Monetary Fund (2025). *Mexico: 2025 Article IV Consultation*. IMF Country Report No. 25/286.

[Official IMF Report](https://www.elibrary.imf.org/view/journals/002/2025/286/002.2025.issue-286-en.xml)
