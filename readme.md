# **🎲 The Master Architect Suite: AI-Driven TTRPG Ecosystem**

**The Master Architect Suite** is a modular, system-agnostic framework designed to turn Large Language Models (LLMs) into consistent, mathematically grounded Game Masters and System Architects.

By utilizing a standardized **\[MECHANICAL PAYLOAD\]** API, this suite allows different AI prompts to communicate complex game data without "hallucinations," ensuring that your narrative remains tethered to the physics of your chosen RPG system.

## ---

**🛠 The Holy Trinity of AI-Gaming**

The suite is divided into three core "Software Layers":

1. **The Character Architect (The Factory):** Translates narrative concepts into strict, legal character sheets. It exports a "Mechanical Payload" that tells the GM exactly what a character can and cannot do.  
2. **The Module Architect (The World-Builder):** Structures vague adventure ideas into balanced 5-Room Dungeons. It exports "Engine Directives" that the GM must enforce.  
3. **The GM Engine (The Processor):** The live interface. It ingests the character and module payloads to run a persistent, reactive game session while tracking resources (HP/EP/Torches) in real-time.

## ---

**📂 Repository Structure**

Plaintext

📦 AI-TTRPG-Suite  
 ┣ 📂 Templates                  \# The Universal Frameworks  
 ┃ ┣ 📜 Universal\_GM\_Engine.md  
 ┃ ┣ 📜 Universal\_Character\_Architect.md  
 ┃ ┗ 📜 Universal\_Module\_Architect.md  
 ┃  
 ┣ 📂 Systems                    \# Game-Specific Implementations  
 ┃ ┗ 📂 BFRPG                    \# Basic Fantasy RPG (OSR)  
 ┃   ┣ 📜 BFRPG\_GM\_Engine.md  
 ┃   ┣ 📜 BFRPG\_Character\_Architect.md  
 ┃   ┣ 📜 BFRPG\_Module\_Architect.md  
 ┃   ┗ 📂 Examples                 
 ┃     ┣ 📜 Kaelen\_Fighter\_Lvl1.md  
 ┃     ┣ 📜 Elara\_Mage\_Lvl1.md  
 ┃     ┣ 📜 Jax\_Thief\_Lvl1.md  
 ┃     ┗ 📜 Tomb\_of\_the\_Iron\_Lord\_Module.md  
 ┃  
 ┗ 📜 README.md

## ---

**🚀 Quick Start Guide**

1. **Choose Your System:** Navigate to the Systems folder (e.g., Systems/BFRPG).  
2. **Build Your Actors:** Use the Character\_Architect prompt in your favorite LLM to generate your party. Copy the **\[MECHANICAL PAYLOAD\]** blocks generated at the end.  
3. **Build Your World:** Use the Module\_Architect to generate an adventure. Copy the module's **\[MECHANICAL PAYLOAD\]**.  
4. **Boot the Engine:** Feed the GM\_Engine prompt into your LLM, then paste the character and module payloads into the chat (or your SillyTavern Lorebook).  
5. **Play:** The AI will now enforce the rules, track your resources, and narrate your journey.

## ---

**⚖️ License**

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

**You are free to:**

* **Share:** Copy and redistribute the material in any medium or format.  
* **Adapt:** Remix, transform, and build upon the material.

**Under the following terms:**

* **Attribution:** You must give appropriate credit and provide a link to the license.  
* **NonCommercial:** You may not use the material for commercial purposes.  
* **ShareAlike:** If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

## ---

**🖋️ Credits**

**Architect:** Emanule Cargile

**System:** Based on the "Mechanical Payload" Prompt Engineering Framework.