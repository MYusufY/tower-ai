# tower-ai
Tower for RC Planes, for a better flight simulation.

# AI Model
TowerAI is a custom LLM model based on *LLaMA3.2 3B.* Thanks to OLLaMA and the custom AI model, it's working at least *36.36%* faster than the old version which uses the Gemini 1.5 Flash API. Also, the old version uses WiFi, and this model can work on an average laptop locally. It doesn't need supercomputers; it has only 3B parameters. It works perfectly on a MacBook Air 2017 and Lenovo ThinkPad. You can even use Nvidia's new Jetson Nano Super for improved portability. Of course, it's not tested, and it should work 99%.

# Software
There are 2 programs. One of them is the API, and the other is the AI. The AI uses our custom TowerAI model, which is recommended. It's faster and better. **It runs locally.** The other one is the Gemini 1.5 Flash API. You need a custom API key, etc., for that, and **it needs an internet connection.** You can test them both to see the performance of our TowerAI model.

# What software does
It converts Speech-To-Text first. Then it sends the result to the chosen AI model as a prompt. After that, it converts the response into a regular sound file (as mp3). Then it adds a radio effect to it to improve the experience. So it feels like you are really talking with the tower.
