# MultiLanguage-Invoice-Extractor

The MultiLanguage Invoice Extractor is a Streamlit web application that leverages Google's GenerativeAI to analyze and interpret invoice images. The application allows users to input prompts related to invoice details and upload invoice images. The underlying model, powered by the Gemini Pro Vision from GenerativeAI, processes the input and provides detailed responses, making it a versatile tool for extracting information from invoices.

# Dependencies
Streamlit
Pillow (PIL)
Google GenerativeAI

# Run Locally

git clone https://github.com/HarshSaxena837/MultiLanguage-Invoice-Extractor

# Go to the project directory
cd MultiLanguage-Invoice-Extractor
#Install dependencies
pip install -r requirements.txt

# Run the model
streamlit run app.py
