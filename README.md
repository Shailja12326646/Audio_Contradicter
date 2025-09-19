# Audio_Contradicter

**Input Pipeline:**

1. **Audio Files** → **Speech-to-Text** → **Raw Transcripts** → **Text Processing** → **Analysis Engine** → **Output Files**

Phase 1: Audio Processing & Transcription
2. Audio Files (5 sessions per subject)
    ↓
Speech-to-Text Model (Whisper/SpeechRecognition)
    ↓
Raw Transcripts with timestamps
    ↓
Audio Quality Assessment & Noise Filtering
    ↓
Clean Transcripts (.txt output)


Phase 2: Text Analysis & Feature Extraction
Clean Transcripts
    ↓
NLP Preprocessing (tokenization, POS tagging)
    ↓
Named Entity Recognition (extract skills, experience, etc.)
    ↓
Sentiment Analysis (detect confidence/nervousness)
    ↓
Claim Extraction (identify factual statements)


Phase 3: Contradiction Detection Engine
Extracted Claims from All Sessions
    ↓
Cross-Session Comparison Matrix
    ↓
Semantic Similarity Analysis
    ↓
Contradiction Pattern Detection
    ↓
Confidence Scoring


