# Building a Voice-to-Text and Text Summarization AI App with Free & Easy Tools

## 🎯 *Workshop Objective:*
- To introduce practical AI tools through hands-on experience
- To build a functional dashboard that converts voice to text and summarizes the content
- To demonstrate real business applications using free, beginner-friendly AI tools

---

## 🗓️ **3-Day Workshop Syllabus (3 Sessions × 3 Hours)**


### 🧩 **Session 1 – Introduction to Voice-to-Text AI + Setup**
**Duration:** 3 hours

#### 🎯 *Learning Goals:*
- Understand how Voice-to-Text technology works
- Set up the development environment
- Load and test the Whisper model from Hugging Face

#### 🔍 *Topics:*
1. **Introduction to Voice-to-Text**
   - What is speech-to-text and how it’s used in business
   - Real-world applications (e.g., call centers, meeting notes, content creators)
2. **Overview of the Whisper Model**
   - Key concepts and capabilities
   - Accessing the model via Hugging Face
3. **Installation and Quick Test**
   - Install: `transformers`, `torchaudio`, `streamlit`, `pydub`
   - Test the model with short audio files (e.g., .wav or .mp3)
4. **Hands-on Practice**
   - Transcribe your own short audio file
   - Try transcribing in English vs. Indonesian

---

### 🧱 **Session 2 – Building the Voice-to-Text Dashboard with Streamlit**
**Duration:** 3 hours

#### 🎯 *Learning Goals:*
- Build an interactive user interface
- Connect audio inputs to the AI model

#### 🔍 *Topics:*
1. **Designing the Streamlit UI**
   - Sidebar: file upload, language selection
   - Main panel: audio player and transcription box
2. **AI Integration**
   - Create `transcribe(audio_file)` function
   - Handle different audio formats and duration limits
3. **User Experience Enhancements**
   - Display transcription output
   - Add “Copy to clipboard” and “Download as .txt” options
4. **Hands-on Practice**
   - Upload personal audio and transcribe
   - Customize layout and visual elements

---

### 🧠 **Session 3 – Adding Summarization + Business Use Case Simulation**
**Duration:** 3 hours

#### 🎯 *Learning Goals:*
- Connect transcription results to text summarization
- Wrap up a complete end-to-end solution

#### 🔍 *Topics:*
1. **Introduction to Summarization**
   - What is summarization and why it’s useful
   - Common use cases: meeting summaries, insights extraction
2. **Free Summarization Models**
   - Load models from Hugging Face (`facebook/bart-large-cnn`, `t5-small`, etc.)
   - Create a `summarize(text)` function
3. **Integrate into Streamlit App**
   - Add “Summarize Text” button
   - Display summary below the transcript
4. **Simulated Business Scenario**
   - Use transcribed meeting notes to generate summaries
   - Group discussion on how to apply this in their own industries
5. **Project Finalization**
   - Export output (Transcription + Summary) as `.txt` or `.csv`
   - Optional: Deploy app to Streamlit Cloud (time permitting)

---

## 📁 **Bonus Materials:**
- Sample public datasets (e.g., OpenVoice, LibriSpeech short clips)
- Starter code templates for each session
- Google Colab setup guide (for participants with local environment issues)
- Introductory slide deck on AI & project flow

---

## 🏁 **Final Output:**
- A working Streamlit web app that:
  - Accepts audio input → Generates transcription → Summarizes the content
  - Can be reused and extended by participants
- Source code with comments and documentation
- A clear understanding of how to build simple AI apps using real tools
