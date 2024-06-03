# local_llm_rag_pdf

To run the application download Ollama (https://www.ollama.com/download) and run the following commands in its terminal:
<ol>
  <li>ollama pull llama3</li>
  <li>ollama serve</li>
</ol>

Make sure you close the default server before running your own (check the system tray in your taskbar).

Run the model_cli.py file along with a query in "..." to retrieve the information from the PDFs stored in the data folder.

Requirements:
<ul>
  <li>chromadb</li>
  <li>langchain</li>
  <li>langchain_community</li>
  <li>pypdf</li>
</ul>
