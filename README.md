#  Speech-to-Text Language Translator  

This Python project captures speech, detects the language, translates it into the desired target language, and generates speech output using Google Text-to-Speech (gTTS).

##  Features  
-  Converts speech to text using `SpeechRecognition`  
-  Detects the language of the spoken text  
-  Translates the text into a target language using `googletrans`  
-  Generates audio output for the translated text using `gTTS`  
-  Saves the translated speech as an MP3 file  

---

## 🛠️ Installation  

### **1. Clone the Repository**  
bash
git clone https://github.com/abhigyanvarma/Speech-to-Text-Language-Translator

cd Speech-to-Text-Language-Translator



### **2. Install Dependencies**  
Make sure you have Python installed, then run:  
bash
pip install -r requirements.txt


### **3. Run the Script**  
bash
python app.py




## 📌 Usage  
1. Run the script and enter the target language (e.g., `Hindi`, `Telugu`, `Tamil`).  
2. Speak into the microphone when prompted.  
3. The program will detect your language and translate it to the target language.  
4. The translated text will be displayed and converted into speech.  
5. An audio file will be generated in the `outputs/` folder.  



## 📂 Project Structure  

📂 LANGUAGE-TRANSLATE-MAIN

├── 📄 app.py              # Main Python script
├── 📄 requirements.txt    # Required dependencies
├── 📂 outputs             # Folder where translated speech MP3 files are stored
└── 📄 README.md           # Project documentation




## Dependencies  
- `SpeechRecognition` – For speech-to-text conversion  
- `googletrans` – For translation  
- `gTTS` – For text-to-speech conversion  
- `pyaudio` – For capturing microphone input  

Install dependencies using:  
bash
pip install -r requirements.txt




## Example Output  

Enter the target language (e.g., 'Hindi', 'Telugu', 'Tamil'): Telugu  
Speak now for language detection and translation...  
Recognized Text: "Hello, how are you?"  
Detected Language: English (en)  
Translated Text in Telugu: "🙋‍♂️, మీరు ఏలా ఉన్నారు?"  
```
Audio file generated: `outputs/captured_voice_Telugu.mp3`

### ⭐ If you like this project, give it a star on GitHub! 🌟  

