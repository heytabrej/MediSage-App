# MediSage

MediSage is a Streamlit web application that provides detailed information on medicines or medical conditions in multiple languages using the Google Generative AI model.

## Usage

1. **Select Language:**
   Choose the language in which you want to receive the information.

2. **Enter Medicine or Disease Name:**
   Input the name of the medicine or medical condition for which you need information.

3. **Get Details:**
   Click the button to retrieve detailed information about the medicine or medical condition.

## Configuration

Make sure to configure the Google Generative AI API key before running the application. You can do this by setting the `api_key` parameter in the `genai.configure()` function.

## Dependencies

Ensure that you have the necessary dependencies installed. You can install them using the following command:

```bash
pip install streamlit google-generativeai
```

## How to Run

To run the MediSage application, execute the following command in your terminal:

```bash
streamlit run app.py
```
Replace app.py with the name of your Streamlit Python script.

## About the Model

MediSage uses the Google Generative AI model, specifically the Gemini 1.5 Pro version, to generate detailed information about medicines or medical conditions.

## Contribution
Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or submit a pull request.