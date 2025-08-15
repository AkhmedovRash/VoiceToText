'''
I built a simple Colab tool that lets me test how accurate speech recognition is for Russian. All I do is upload an audio file, and the script automatically converts it to a clean 16 kHz mono WAV using ffmpeg. Then it runs Google Speech Recognition to transcribe what was said, and compares that to the phrase I know was spoken.
It shows me the original phrase (REF), what the speech recognition heard (HYP), and calculates the Word Error Rate (WER) so I can see exactly how close it was. I use it to quickly check the quality of recordings, experiment with different audio formats, and see how speech recognition performs in different conditions.
It’s minimal, easy to run, and works with common audio formats like WEBM, OPUS, and WAV — perfect for quick testing without setting up a big AI model.
'''
