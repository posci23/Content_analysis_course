# Content Analysis Course

Self-guided activities for learning content analysis methods in political science.

## Getting Started

1. **Clone this repo:**
   ```
   git clone https://github.com/posci23/content_analysis_course.git
   ```

2. **Open the folder** in Google Antigravity

3. **Read the guide first:** Open `textblob_guide/what_is_textblob.txt`

4. **Do the activity:** Open `textblob_activity/prompts_and_exercises.txt` and follow the instructions

## Folder Structure

```
textblob_guide/
  what_is_textblob.txt       ← Read this first (explains TextBlob and content analysis)

textblob_activity/
  prompts_and_exercises.txt  ← Step-by-step activity (start here after the guide)
  sample_texts.txt           ← All sample texts in one browsable file
  speech_climate.txt         ← Climate policy speech
  speech_economy.txt         ← Economic policy speech
  headlines.txt              ← News headlines from 10 outlets (same event)
```

## Setup

You only need to install one thing (instructions are also in the activity file):

```
pip install textblob
python -m textblob.download_corpora
```
