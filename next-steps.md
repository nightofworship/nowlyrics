# How to Format Lyrics for OpenLP

## Step 1: Copy the Prompt
1. Open the `README.md` file in this repo
2. Copy the entire prompt (from "Help me convert..." to the empty `<plain_text_lyrics>` tag at the end)

## Step 2: Set Up Google AI Studio
1. Go to [aistudio.google.com](https://aistudio.google.com)
2. On the right side menu:
   - Select **Gemini 3 Pro**
   - Turn ON **"Grounding with Google Search"**

## Step 3: Find the Lyrics
1. Search Google for the song lyrics
2. **Best sources** (in order of preference):
   - Genius.com (best formatting)
   - LyricFind
   - Musixmatch
   - Google's direct lyrics display
3. Copy the plain text lyrics

## Step 4: Generate Formatted Lyrics
1. Paste the README prompt into AI Studio
2. Paste your lyrics inside the `<plain_text_lyrics>` tag
3. Submit the prompt
4. Copy the XML output from Gemini

## Step 5: Save and Import
1. Save the XML output as a `.xml` file in the `songs/` folder
2. Import the XML file into OpenLP

---

**TODO:** Document the exact steps to import XML files into OpenLP
