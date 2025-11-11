# 🧠 MAGi
Mistral Augmented General intelligence using a local Mistral 7B parameter model and embedding models and lots of files turned into a vector database. 

## RAG
Retrieval-Augmented Generation

I will store files like:
- lecture notes
- KiCad schematics
- textbook chapters
- anime lore (because priorities)
- personal ideas
- documentation

Then a embedding model turns everything into vectors.
The main model doesn’t have to “memorize” anything, it just retrieves the right chunks.
This means I can tell me AI to remember whatever I want it to and use it for local knowledge. 

## YouTube Transcript
I also want to use Voxtral 3B to be able to transcribe YouTube videos and turn them into notes. So I would download a YouTube video and it will:
1. Transcibe the video (Using Speech-to-text)
2. Turn the transcript into a prompt along with a extra "Make notes from the transcibes of this video"
3. Generate a `.pdf` file summarizing the video (Using Mistral 7B)

## Code assistant
Apperantly, despite being only 7 billion parameters big (which isn't big at all by 2025 standards), it can do well with code. So I will use it to assist me in coding. 
It could help with:
- troubleshooting Arch Linux
- code simple Python scripts
- code simple bash scripts for automation
- basic Flask APIs
- data-cleaning code

And even if it is incapable, I could always just use Google's Gemini CLI.
