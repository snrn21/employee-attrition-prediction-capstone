# GenAI-Powered News Reader with Text-to-Speech (VITS)

## Project Overview

This project is a GenAI-powered news reader that fetches the latest headlines from The Guardian API and converts them into speech using the VITS (Variational Inference Text-to-Speech) model. It provides an accessible and convenient way to consume news in an auditory format, making it ideal for busy users or those with visual impairments.

---

## Technology Stack

- **News Source API:** The Guardian Open Platform API  
- **Text-to-Speech Model:** VITS model from Coqui TTS  
- **Framework:** Streamlit for UI development  
- **Programming Language:** Python  

---

## Features

- Fetches the latest 20 news headlines from The Guardian API  
- Converts headlines to natural-sounding speech using the VITS model  
- Plays audio directly within the app  
- Provides downloadable MP3 and text files containing the headlines  

---

## Setup Instructions

### Prerequisites

- Python 3.6 or higher installed on your system  
- Internet connection to access The Guardian API and download TTS models  

### Installation Steps

1. **Clone the repository** (or download the source files) to your local machine.

2. **Install required Python packages** by running the following command in your terminal or command prompt:pip install streamlit requests TTS

3. **Obtain The Guardian API Key:**

- Visit [The Guardian Open Platform](https://open-platform.theguardian.com/access/)  
- Sign up for a free API key.

4. **Create a `config.json` file** in the project directory with the following content:
{ “API_KEY”: “your_guardian_api_key_here” }


Replace `"your_guardian_api_key_here"` with your actual API key.

---

## Running the Application

Run the following command in your terminal from the directory containing `genai_news.py` and `config.json`: streamlit run genai_news.py


This will launch the Streamlit app in your default web browser. You will see the latest headlines displayed, with options to listen to the audio or download the headlines as MP3 and text files.

---

## Future Enhancements

- Support for multiple news sources beyond The Guardian  
- User preferences for filtering news categories (e.g., Business, Technology, Sports)  
- Multilingual support for broader accessibility  
- Improved UI with interactive elements and voice commands  

---

## References

- [The Guardian Open Platform API](https://open-platform.theguardian.com/access/)  
- [Coqui TTS VITS Model Documentation](https://docs.coqui.ai/en/latest/models/vits.html)  

---

## Contact

For questions or contributions, feel free to open an issue or submit a pull request.

---

*Developed by Satya Narayana Gattu as part of a Master's project.*


