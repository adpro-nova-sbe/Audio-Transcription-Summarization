# Audio-Transcription-Summarization

Effortlessly Summarize Audio Content using AI.

## Dependencies

* whisper: For transcription, you need to install the OpenAI Whisper model.
* pytube: For downloading YouTube videos.
* IPython: For displaying outputs in Jupyter notebooks and other interactive interfaces.
* langchain_openai: For accessing OpenAI’s models through the LangChain wrapper.
* ffmpeg: multimedia framework that allows users to record, convert, and stream audio and video in various formats.

## Usage Example

```python

# create instance of AudioTuSummry with a youtube link
Veritasium = AudioToSummary(link ="https://www.youtube.com/watch?v=A5w-dEgIU1M",is_link=True)

# returns short summary of the text
Veritasium.summary

# returns more in depth description of the text
Veritasium.description

# returns a summary in bullet points
Veritasium.abridged_summary

```

## Features

* Audio transcription from files and YouTube links.
* Summarization in various styles (main topic, descriptive, abridged).
* Lazy loading of summaries to optimize performance.


## Contributors

* Hendrik Künnemann - 57995
* Guilherme de Oliveira Raimundo - 58053
* Tom Göring - 58535

## License

[GNU GENERAL PUBLIC LICENSE](https://github.com/adpro-nova-sbe/Audio-Transcription-Summarization/blob/main/LICENSE)