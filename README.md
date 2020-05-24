# voiceassistant
Basic voice assistant script

The program starts by greeting you. Speak() method is responsible for that.

After that, takeCommand() is responsible for taking audio input and searching for the said command from the specified commands it knows. 
Just to make things simple, we will convert whatever is being said to lower-cased string.

We are using Microsoft speech api for voice assistant. You can change the voice to a female one by changing the value of voices[0] to voices[1].

The voice assistant still is not able to recognize words like "work", "python" etc., so setting them up for querying won't help much.
