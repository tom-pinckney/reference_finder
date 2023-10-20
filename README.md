# Description
reference_finder is a package for finding references in a target corpus that come from a search corpus. It uses the cosine similarities of rolling embeddings to find subsections of target documents that likely came from a source document. It works for audio, video, and text files.

# Requirements
For transcribing of audio/video files ffmpeg and whisper are required. In google colab these can easily be installed with the following commands
```
!sudo apt update && sudo apt install ffmpeg
!pip install -q git+https://github.com/openai/whisper.git
```
