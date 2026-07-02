# Medical_Chatbot
AI Medical Assistant Chatbot with Secure Role-Based Access Developed a multilingual, speech-enabled Python chatbot that collects patient symptom summaries, automates PDF clinical reports, and stores encrypted telemetry data in MongoDB.

Developed an asynchronous, multilingual medical assistant chatbot utilizing Python, supporting audio and text interactions across 4 languages via integration with edge-tts and deep-translator.
Implemented secure data engineering practices using MongoDB's Field-Level Encryption (ClientEncryption) to deterministically encrypt patient contact details, adhering to healthcare privacy workflows.
Engineered dynamic reporting and automated workflows by leveraging FPDF to auto-generate structured, comprehensive clinical PDF summaries for healthcare providers.
Designed a multi-role access control model within a NoSQL database system, ensuring role-based decryption policies for admins and doctors.

Technologies Used:
Languages: Python
Database: MongoDB, PyMongo (Field-Level Encryption / AEAD AES-256)
Libraries/APIs: Asyncio, Edge-TTS, SpeechRecognition, Deep-Translator, FPDF, Pygame
