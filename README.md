# Theatre Script Processor

<!-- ![Theatre Script Processor](https://placehold.it/200x100) -->

Theatre Script Processor is a Python tool that allows you to process theatre scripts, extract character dialogues, predict emotions using a BERT model, and generate a CSV file with structured data. This tool helps you analyze and organize the content of theatre scripts for further analysis or data-driven insights.

## Table of Contents
- [Features](#features)
- [Examples](#examples)

## Features

- **Script Processing**: Extract character dialogues and associated information from theatre scripts.
- **Emotion Prediction**: Utilizes a BERT model to predict emotions associated with each character's dialogue.
- **CSV Generation**: Creates a structured CSV file containing character dialogues, emotions, and other script information.
- **Customization**: Easily configure the tool to adapt to different script formats and character attributes.


## Examples

Here's an example of what the generated CSV might look like:

```csv
Type,Character,Content,Emotion
Dialogue,Character1,"Hello, how are you today?",Happy
Dialogue,Character2,"I'm doing well, thank you!",Excited
Advice,None, "Character2 exits stage left.",None
Dialogue,Character1,"That's great to hear!",Joyful
```