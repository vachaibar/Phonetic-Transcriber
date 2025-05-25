# Phonetic-Transcriber


This Java application was created as a final project for a course. The goal was to explore phonetics through Java-programming by converting English words into their phonetic representations using a JSON-based API.

## 📌 Project Description

When the program is run, it prompts the user to input an English word. It then makes a call to a phonetic API (like WordsAPI or similar) and returns the phonetic transcription of the word using the International Phonetic Alphabet (IPA).

This project demonstrates the use of:
- User input handling in Java
- External JSON-based APIs
- Parsing API responses using the `org.json` package

## 🧪 Technologies Used
- **Java**
- **JSON-Java Library** (`org.json`)
- **External Phonetic API** (e.g., WordsAPI, Free Dictionary API)

## 🚀 How to Run

1. Clone or download the repository.
2. Ensure you have Java installed (Java 8+ recommended).
3. Include the JSON-Java library (`json-java.jar`) in your classpath.
4. Compile and run the program:

```bash
javac -cp .;json-java.jar PhoneticTranscriber.java  # Windows
javac -cp .:json-java.jar PhoneticTranscriber.java  # macOS/Linux

java -cp .;json-java.jar PhoneticTranscriber        # Windows
java -cp .:json-java.jar PhoneticTranscriber        # macOS/Linux
