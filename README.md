# Text-to-Speech
make your computer speak 
- I used **`SpeechSynthesis`** to access the browser’s built-in text-to-speech capability.

- I created an instance of **`SpeechSynthesisUtterance`** to represent the text I wanted to convert to speech.

- I set the **`.text`** property of the **`SpeechSynthesisUtterance`** object to the message I wanted to speak.

- I used **`speechSynthesis.speak()`** to speak the utterance.

- I also customized properties like **`rate`**, **`pitch`**, and **`volume`** to control the voice output.

- The **`onend`** and **`onerror`** events helped me track when speech finished or failed.
