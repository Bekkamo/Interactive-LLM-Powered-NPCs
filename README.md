# Interactive LLM Powered NPCs ✨: Enabling Realistic Dynamic Dialogue with LLM-Powered NPCs in Any Game 🎮🤖🚀

## Overview 😄📜

Interactive LLM Powered NPCs, is an open-source project that completely transforms your interaction with non-player characters (NPCs) in any game! 🎮🤖🚀 Say goodbye to static and repetitive conversations, and prepare for realistic and dynamic dialogue adventures. With this project, you can engage in immersive and captivating conversations with NPCs, utilizing your microphone to speak, listen to their voices, and witness their lifelike facial animations. 😄🔊✨

The project incorporates various techniques to enhance the overall experience and make it more immersive. It employs facial animation to synchronize character lip movements👄, facial recognition to identify different characters😊, vector stores to provide limitless memory capacity for NPCs🧠, and pre-conversation files to shape the dialogue style of each character, resulting in a truly lifelike interaction. By analyzing the specific NPC you're engaging with, including their personality, knowledge, and communication style, the system adapts accordingly. Moreover, the NPCs are even capable of perceiving your facial expressions through your webcam👀🎥, adding an additional layer of depth to the interactions.💬🔍💡

This project targets previously released games like Cyberpunk 2077, Assassin's Creed, GTA 5, and other popular open-world titles 🎮🚀. These games, with their plentiful NPCs and beautiful environments, have long been yearning for a missing feature: the ability for players to engage in conversations with any NPC they want to talk to. 😔 With this project, we aim to fill that void and bring immersive dialogue adventures to these games, allowing players to unlock the untapped potential within these virtual worlds. 🌟🎭 The goal is to enhance the gaming experience of already-released titles that are unlikely to receive this feature from their original developers. ⭐

One of the remarkable aspects of this project is its versatility. You don't need to modify the game's source code or engage in complex modding procedures. Instead, it works its magic by replacing the facial pixels generated by the game, seamlessly integrating the facial animation into your gaming environment. ✨😉

Whether you're exploring ancient dungeons in Assassin's Creed Valhalla or walking the neon lit streets of Cyberpunk 2077, Interactive LLM Powered NPCs takes your gaming experience to new heights. Prepare yourself for engaging, realistic, and meaningful interactions with NPCs that bring your virtual world to life. 🙌🚀🔥

## Demo 🚀✨
![thumbnail](https://github.com/AkshitIreddy/Interactive-LLM-Powered-NPCs/assets/90443032/feb9590f-3cde-476c-93ef-b0408169c150)

Demo link: https://twitter.com/Akshit2089/status/1673687342438051847

Tutorial Video: https://youtu.be/6SHTlKYKCbs

Discord Server: https://discord.gg/CfK7DCWKwy

## How It Works 🤔💭

The project's functionality is as fascinating as the conversations it enables. Here's a breakdown of how Interactive LLM Powered NPCs works its magic:

🎙️ Microphone Input: Speak into your microphone, and your voice is converted to text.

👥 Facial Recognition: The system employs facial recognition technology to identify which NPC you're interacting with, whether it's a background character or a side character.

🔍 Character Identification: Based on the dialogue and character recognition, a unique personality and name are generated for background NPCs. For side characters, their specific character traits and knowledge are accessed.

🧠 LLM Integration: The transcribed text and character information are passed to a Large Language Model (LLM), which generates a response based on the given context. The LLM also utilizes vector stores containing character-specific and world information.

📁 Pre-Conversation Files: To ensure the NPCs speak authentically, the project utilizes a pre-conversation.json file containing the character's iconic lines and lines that reflect their talking style. Random lines from this file are passed to the LLM while generating response, enhancing the generated dialogue.

🗣️ Facial Animation and Speech Generation: The LLM's response is converted to speech using text-to-speech. Then a facial animation video is generated, using the extracted face image of the NPC with the audio.

🕹️ Integration with the Game: The facial animation video and audio are seamlessly integrated into the game by replacing the displayed face pixels with the generated facial animation, making it appear as if the NPC is speaking naturally.

😃 Emotion Recognition: Using your webcam, the system captures your facial emotions, allowing the NPCs to adjust their responses accordingly, creating a more personalized and immersive experience.

🐎 Non-Visual Interactions: The project goes beyond face-to-face conversations by enabling interactions even when the NPC's face is not visible, such as during horseback riding or intense combat sequences. To engage with the NPC, simply say their name first, followed by your dialogue. The system will then follow the same process of transcribing, generating responses, and converting them into speech, providing a seamless and uninterrupted conversation experience, even in action-packed moments. So, whether you're galloping through the countryside or battling formidable foes, you can still communicate with NPCs and enjoy the full range of interactive dialogue features.

🌐 Game Compatibility: Works seamlessly with any game, without the need for game modifications or altering the game's source code.

## Prerequisites 🚀🔧

### 🐍 Python 3.10.6

You can download and install this version of Python from here https://www.python.org/downloads/release/python-3106/

### 🐙 GIT

Install GIT, a version control system, to easily manage your code and collaborate with others. https://git-scm.com/downloads

### 🌐 wget

Install wget, a command-line utility, to conveniently download files from the web.

### 🛠️🔍 Microsoft Build Tools and Visual Studio

Install Microsoft Build Tools and Visual Studio, which are essential for compiling and building projects on Windows.

https://visualstudio.microsoft.com/downloads/?q=build+tools#visual-studio-professional-2022

https://visualstudio.microsoft.com/downloads/?q=build+tools#build-tools-for-visual-studio-2022

### 🎥🔊 FFmpeg

Install FFmpeg, a powerful multimedia framework, to handle audio and video processing tasks.

Follow the instructions here https://www.wikihow.com/Install-FFmpeg-on-Windows

## Installation 🔌✨

1. Open a terminal.
2. Clone the repository by executing the following command:

```sh
git clone https://github.com/AkshitIreddy/Interactive-LLM-Powered-NPCs.git
```

3. Navigate to the cloned repository:

```sh
cd Interactive-LLM-Powered-NPCs
```

4. Create a Python virtual environment named .venv:

```sh
python -m venv .venv
```

5. Activate the virtual environment:

```sh
.venv\scripts\activate
```

6. Install the required dependencies:

```sh
pip install -r requirements.txt
```

7. Open a Git Bash terminal.
8. Change the directory to the "Interactive-LLM-Powered-NPCs" folder:
9. Go inside the SadTalker directory

```sh
cd sadtalker
```

10. Download the necessary models

```sh
bash scripts/download_models.sh
```

11. Open the "sadtalker" directory in file browser, locate the file named "webui.bat" and double-click on it. This will create another Python environment called "venv". Wait until the message WebUI launched is displayed, and then close the terminal that was opened by webui.bat.

12. Make a Cohere account (Free) and add your Cohere Trial API key to apikeys.json . (Optionally, if you have GPT-4 access and would like to use it, you'll need to make a few small changes to the code)

## Vscode Installation with Jupyter Notebook Support 👨‍💻📔

Download and install Visual Studio Code on your device. Click on the Extensions icon on the left sidebar. It looks like a square icon made up of four squares. In the Extensions pane, search for "Jupyter" using the search bar at the top. Look for the "Jupyter" extension provided by Microsoft in the search results and click on the "Install" button next to it. This extension enables Jupyter Notebook support in Visual Studio Code. Open your terminal and navigate to the root directory of the project. This is the main folder that contains the project files. In the terminal, type code . and hit Enter. This command opens the current directory in Visual Studio Code. Alternatively, you can use the file explorer in Visual Studio Code to navigate to the root directory of the project. Once the project is open in Visual Studio Code, you should see the project files displayed on the right-hand side of the editor.

While running the Jupyter Notebooks, make sure to select the kernel as .venv (present in top right corner). 

## Directions for Use 🛠️🤓

1. 📁 Create a folder in the root directory of your project. The folder name should be your game name with spaces replaced by underscores, and avoid using special characters. For example, if your game name is "Assasins Creed Valhalla" the folder name could be "Assasins_Creed_Valhalla" .

2. 📝 Inside the game folder, create a text file called "world.txt" to describe the game and the game world. You can gather in-depth information about your game from websites like https://www.fandom.com/.

3. 📝 Create another text file called "public_info.txt" inside the game folder. This file should contain information about the game world, major events, and any details that a person living in that game world should know. You can find this information on the website mentioned earlier.

4. 📔 Open the Jupyter Notebook called "create_public_vectordb.ipynb" located in the root directory. Set the variable "game_name" in the first cell to your game's name. Run the first cell to create the public vector database. Then run the second cell to test its performance. Vector databases are like living libraries that provides relevant information about various topics.

5. 📝 Create a folder called npc_personality_creation in your game folder and then copy both the files from Cyberpunk_2077 folder audio_mode_create_personality.py and video_mode_personality.py. These files are responsible for generating unique personalities for background NPCs, so you need to modify the template variable according to your game. The template variable has three names and personalities for those names, you need to replace the names with npc names that are common in your game and replace the personalities with personalities common in your game, you can take ChatGPT's help for creating the personalities. These examples will guide the way the LLM will generate the personalities. Once done copy these files into the functions directory replacing the previous personality creation files.

6. 📂 Create a folder named "characters" inside the game folder. Copy the "default" folder from the "Cyberpunk_2077/characters" folder and paste it into the newly created "characters" folder. You will need to modify the "pre_conversation.json" file present in the "default" folder. This file should contain common lines that people speak in your game's world. You can ask ChatGPT to provide dialogues in this JSON format specific to your game. Here's a prompt you can use:

```sh
Give 30 Common dialogue that people in Cyberpunk 2077 say, it should be in this format
{
  "pre_conversation": [
    { "line": "dialogue 1" },
    { "line": "dialogue 2" }
  ]
}
```

Replace the content of the "pre_conversation.json" file with the generated dialogue.

The default folder is used by background NPCs, the bio, name, voice and photo keep changing as you talk to different NPCs.

7. 📂 Create a folder in characters with the name of any side character you would like to talk to, replacing spaces with underscores. Inside this character folder, create an "images" folder and place 5 JPG photos of your character (without any other person present in these pictures).

8. 📔 Open the "create_face_recognition_representation.ipynb" notebook and set the variables "character_name" and "game_name" in both cells. Run both cells to create representations of your character's face. This step helps the project recognize which character you are interacting with when you are playing the game.

9. 📝 Create a text file called "bio.txt" inside the character's folder. This file should contain a small summary about your character, which you can gather from fandom or similar sources.

10. 📝 Create a text file called "character_knowledge.txt" inside the character's folder. This file should include information that your character knows but isn't present in the public vector database. You can find this information from fandom or similar sources.

11. 📔 Use the "create_character_vectordb.ipynb" notebook to create the character's vector database. Open the notebook, set the variables "character_name" and "game_name" in the first cell, and run the cell.

12. 📝 Create a "pre_conversation.json" file inside the character's folder with common dialogues that this character says. The dialogues should capture the essence of the character and will be used to guide the style of responses. You can refer to the existing "pre_conversation.json" file in Cyberpunk 2077's character folder for reference.

13. 📝 Create a "conversation.json" file in the character's folder. You can copy this file from Jackie Welles' character folder in Cyberpunk 2077, and change the first dialogue to match your character.

14. 📂 Create a "voice" folder. Inside this folder, place a Python script called "voice.py" with a function named "create_speech." The function should take text and an output path as parameters to store the generated audio file. You can copy the script from Jackie Welles and modify the voice to match your character's voice. You can use the voice_selection.ipynb to find a voice that is similar to your characters voice. If you want to use voice cloning or other techniques, ensure that the "voice.py" file in your character's voice folder has the same "create_speech" function signature and doesn't use relative paths.

15. ♾️ Repeat the above steps for any other character you would like to interact with in the game.

Once you have completed these steps, you're ready to play the game. Make sure your webcam and microphone are on to fully experience the interactive elements. 🎮🌟

## Play the Game! 🎮🚀

To begin, launch your game and open the "main.ipynb" file. In the first cell, you'll find the variables "player_name," "game_name," and "interact_key." Set these variables according to your preferences. Once you've done that, run the second cell. If your GPU is struggling to render the facial animation smoothly, you can choose to disable it in parameters.

By running the second cell, a new window will appear. Drag this window to a separate monitor from the one displaying your game. Now, direct the camera in your game towards the non-playable character (NPC) you wish to talk to.

Click on the new window and hold down the interact key until you see the word "speak" appear in the right-hand corner. Speak your message, and you will notice the text you said appear in the corner. After a moment, the character will respond to you with both facial animation and voice.

If, for some reason, the character you want to talk to is not visible on the screen, you can still follow the same steps. You will receive an audio response even if you can't see the character. This feature comes in handy when riding a horse with another NPC or engaging in combat with your companion.

## Conclusion and Contribution 🤝🎮

Interactive LLM Powered NPCs opens up exciting possibilities for enhancing NPC interactions in any game, bringing a new level of realism and immersion to your gaming experience. 💫🎮 By leveraging advanced technologies and the power of language models, this project allows for dynamic and engaging dialogue with NPCs, making each conversation feel unique and lifelike. 💬🌟

We invite you to join us in expanding the compatibility of Interactive LLM Powered NPCs by adding games to the "Games" folder. 📁🎁 By doing so, you can help save others the effort of adapting the project to new games and increase the number of available games that are compatible. 🚀🔗

If you've created a game compatible with Interactive LLM Powered NPCs, we encourage you to make a pull request and share your game with the community. 🙌🎮 By adding your game to the collection, you contribute to the growing library of supported games and enable more players to enjoy dynamic and realistic NPC interactions. 🎉🌍

Additionally, you can contribute to the project by improving existing features, fixing bugs, or suggesting new ideas. Feel free to explore the codebase, join discussions, and collaborate with fellow developers to enhance the project further. 💡💪👥

Together, we can shape the future of NPC interactions in gaming and create memorable experiences for players worldwide. So, join us on this exciting journey and let's make gaming dialogue more interactive and captivating for everyone! 🚀✨🌟

## Tools Used 🚀🔧

- 🍪 Cohere's Language Models and Langchain for LLM Agent
- 🍩 SadTalker For Facial Animation
- 🍰 Edge-TTS for default voices
- 🧁 DeepFace for facial recognition, detection, gender, age, emotion detection
- 🍭 Chromadb for local vectorstores
- 🍬 SpeechRecognition package for speech recognition

## ❤️ Thanks

If you found this interesting check out Alystria AI for more fun projects

```sh
https://www.linkedin.com/company/alystria-ai
```

- 🌐 Github: https://github.com/AkshitIreddy
- 💡 LinkedIn: https://www.linkedin.com/in/akshit-ireddy
- ✍️ Medium: https://medium.com/@akshit.r.ireddy
