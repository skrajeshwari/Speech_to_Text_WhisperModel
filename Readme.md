Whisper

Whisper is a general-purpose speech recognition model. 
It is trained on a large dataset of diverse audio and is also a multitasking model that can perform multilingual speech recognition, speech translation, and language identification.

Approach

A Transformer sequence-to-sequence model is trained on various speech processing tasks, including multilingual speech recognition, speech translation, spoken language identification, and voice activity detection. 
These tasks are jointly represented as a sequence of tokens to be predicted by the decoder, allowing a single model to replace many stages of a traditional speech-processing pipeline.
The multitask training format uses a set of special tokens that serve as task specifiers or classification targets.

Objectives of the project:

1) perform speech-to-text using whisper model
2) perform text-to-speech using tts-1 model
3) perform audio to audio translation
4) extract text of different speakers from a conversation
5) create a gradio interface
