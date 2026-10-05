# 📝 AI-Based Meeting Audio Transcription & Summary System

## 📌 Project Overview

The **AI-Based Meeting Audio Transcription & Summary System** is a Text and Speech Analysis application that converts meeting audio into a structured textual report.

The system uses **Speech Recognition and Natural Language Processing** to:

* Transcribe meeting audio
* Generate an extractive summary
* Identify important keywords
* Detect possible action items
* Calculate meeting duration
* Calculate word count
* Generate a structured analysis report

The application runs in **Google Colab** using Python and Gradio.

---

## 🎯 Objectives

* Convert meeting speech into text automatically.
* Reduce the need for manual note-taking.
* Extract important information from meetings.
* Identify possible action items.
* Generate a concise meeting summary.
* Demonstrate practical applications of TSA and NLP.

---

## ✨ Features

### 🎙️ Audio Transcription

Converts the complete meeting audio into text.

### 📄 Automatic Summary

Extracts important sentences from the meeting transcript.

### 🔑 Keyword Extraction

Identifies frequently occurring meaningful words.

### ✅ Action Item Detection

Detects sentences containing terms such as:

* Need to
* Should
* Must
* Will
* Complete
* Submit
* Deadline
* Prepare
* Send

### 📊 Meeting Statistics

Displays:

* Meeting duration
* Word count
* Keyword count
* Action item count

---

## 🔄 System Workflow

```text
Meeting Audio
      ↓
Speech Recognition
      ↓
Full Transcript
      ↓
Text Preprocessing
      ↓
NLP Processing
      ↓
 ┌─────────────────────┐
 │ Keyword Extraction  │
 │ Sentence Analysis   │
 │ Action Item Detect. │
 │ Summary Generation  │
 └─────────────────────┘
      ↓
Structured Meeting Report
```

---

## 🛠️ Technologies Used

* Python
* Faster-Whisper
* Natural Language Processing
* Speech Recognition
* Text Processing
* Gradio
* Google Colab

---

## ▶️ How to Run

1. Open Google Colab.
2. Create a new notebook.
3. Paste the complete one-cell code.
4. Run the cell.
5. Wait for installation and model loading.
6. Open the generated `gradio.live` URL.
7. Upload or record meeting audio.
8. Click the analysis button.
9. View the generated meeting report.

---

## 📊 Example Output

```text
MEETING ANALYSIS

Duration:
12 minutes

Word Count:
1,245

Important Keywords:
project, deadline, testing, development, report

Action Items:
1. Complete the project testing.
2. Submit the report before Friday.
3. Prepare the final presentation.

Summary:
The team discussed project development,
testing activities, upcoming deadlines,
and final presentation preparation.
```

---

## 🎓 TSA Concepts Used

* Speech Recognition
* Speech-to-Text
* NLP
* Text Preprocessing
* Keyword Extraction
* Frequency Analysis
* Extractive Summarization
* Action Item Detection
* Sentence Analysis

---

## 📁 Project Structure

```text
Meeting-Transcription-Summary/
│
├── meeting_analyzer.ipynb
└── README.md
```

---

## 🚀 Future Enhancements

* Speaker identification
* Speaker-wise transcription
* Real-time meeting transcription
* Advanced abstractive summarization
* Automatic task assignment
* Meeting sentiment analysis
* Calendar integration
* PDF meeting report
* Email report generation
* Multilingual transcription

---

## ⚠️ Limitations

The current version uses extractive summarization and rule-based action-item detection. Therefore, the generated summary may not always understand complex context like a human.

Audio quality and background noise can also affect transcription accuracy.

---

## 🏢 Applications

This system can be used for:

* College project meetings
* Business meetings
* Team discussions
* Online classes
* Interviews
* Group discussions
* Conference recordings

---

## 🏁 Conclusion

The **AI-Based Meeting Audio Transcription & Summary System** demonstrates a practical application of Text and Speech Analysis.

It converts spoken meeting content into a structured report containing the transcript, summary, keywords, statistics, and possible action items, reducing manual meeting documentation.
