# DocQnA-LangChain-Streamlit
Using LangChain for interactive Q/A over documents with a Gradio interface for optimal user experience
# Setup
1. Install the required dependencies:

        pip install -r requirements.txt | pip3 install streamlit  | pip install "unstructured[all-docs]"

3. Replace the API key in the main.py file with your actual OpenAI API key:

            openai_api_key='YOUR_API_KEY',

4. Run main.py and after that run the Streamlit application by writing this command in command propmt:

        streamlit run main.py


