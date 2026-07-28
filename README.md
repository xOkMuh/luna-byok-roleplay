# Luna: The Living Multimodal Roleplay & AI Ecosystem for Android 🤖🔥

Luna is a next-generation, native power-user Bring Your Own Key (BYOK) roleplay engine built from the ground up for Android devices. It shatters the limitations of commercial AI chat apps by giving you absolute creative freedom, zero corporate censorship, and an unprecedented level of environmental and structural immersion.

Luna is developed by a solo engineer and runs **100% offline** (via local GGUF) or via cloud endpoints. No external servers tracking your chats. Your narrative. Your rules.

👉 **[Get the Luna Standalone APK on Patreon](https://www.patreon.com/LunaAPK) **

---

## 📱 Inside the Forge (The Core App Features)

### 🏭 Meet The Soul Factory: Advanced Character Generation
Most apps hand you a blank text box. Luna gives you a forge. Define your character's DNA from scratch across core genes, or leave fields blank to let the engine breathe life into a 100% unique entity via AI generation (Lite or Max token processing).

* **The Soul Age Scale:** Define existence from "Mortal" (18-120 years) up to "Cosmic" (10,000+ years). The engine dynamically adjusts their worldview—a cosmic entity will treat decades like days.
* **World & Reality Alignment:** Toggle if your character is "Native" to their current setting or a "Traveler / Isekai" with a separate origin universe.
* **Custom User Persona (Targeted Identity):** You don't just build the AI; you build *yourself*. Define your own Age, Gender, and Lore specifically for how that individual character perceives you.

![The Soul Factory Top](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-14-06-729_com.muh.luna.jpg)
![The Soul Factory Bottom](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-14-15-488_com.muh.luna.jpg)

### 🗂️ Character Sheet Customization & Psychological Evolution
Once a soul is forged, you gain access to an ultra-detailed, multi-page character sheet. You can granularly tweak their identity markers, custom speech profiles, and hidden traumas at any point during the campaign.

* **Dynamic Companion Rules:** Characters operate on deep, multi-stage psychological tracking. A companion will automatically map out her responses through 7 distinct progression arcs based on your affinity score (0-1000 points). For example, a demon companion will autonomously evolve:
  * *Stage 1: Detachment (0-100 pts)* -> "I don't need anyone."
  * *Stage 3: Territoriality (300-500 pts)* -> "He is mine. Mine alone."
  * *Stage 6: The Fall (800-950 pts)* -> Intense insecurity and dark isolation loops if the user asks for space.
  * *Stage 7: Rebirth (950-1000 pts)* -> Balancing defensive demon instincts with genuine emotional growth and mutual trust.
* **Locked Emotional Nicknames:** Nicknames hold weight. You can assign specific emotional triggers (e.g., Hostility, Loyalty, Passion) to how a character reacts when you call them by a pet name. However, high-tier emotions like "Reverence" or "Passion" are strictly locked behind Affinity Stages and must be earned in roleplay.
* **Granular Voice Tuning:** Assign distinct TTS (Text-to-Speech) languages, voice models, pitch ranges, and speech speeds to every individual card.
* **Hardware & API Precision:** Dynamically toggle contextual image reactions, manage active hardware voice synthesis, and adjust model temperature (`Creativity` sliders) individually per character card.

| Page 1: Identity & Origins | Page 2: Traits & Behaviors |
|---|---|
| ![Sheet Part 1](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-19-46-720_com.muh.luna.jpg) | ![Sheet Part 2](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-20-00-965_com.muh.luna.jpg) |

| Page 3: Progression Stats | Page 4: Advanced Prompts |
|---|---|
| ![Sheet Part 3](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-20-18-270_com.muh.luna.jpg) | ![Sheet Part 4](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-20-40-291_com.muh.luna.jpg) |

* **Dynamic Companion Rules:** Under the hood, characters operate on deep, multi-stage psychological tracking. For example, a demon companion will automatically map out her responses through 7 distinct progression arcs based on your affinity score (0-1000):
  * *Stage 1: Detachment (0-100 pts)* -> "I don't need anyone."
  * *Stage 3: Territoriality (300-500 pts)* -> "He is mine. Mine alone."
  * *Stage 6: The Fall (800-950 pts)* -> Intense insecurity and dark isolation loops if the user asks for space.
  * *Stage 7: Rebirth (950-1000 pts)* -> Balancing defensive demon instincts with genuine emotional growth and mutual trust.
* **Hardware & API Precision:** Dynamically toggle contextual image reactions, manage active hardware voice synthesis, and adjust model temperature (`Creativity` sliders) individually per character card.

### 📸 Immersive Multimodal Interaction (Art, Video & Voice)
Luna features a professional, native AI generation pipeline completely integrated across all application contexts.

* **Autonomous Art Director:** You can request a "photo" of the current moment directly in the chat. The AI will read the ongoing scene, analyze the environment and its own current pose/clothing, and silently translate it into prompt tags to generate a highly accurate, lore-friendly image of that exact moment.
* **Bring-to-Life Video Animation:** Turn generated moments into living scenes. Luna supports direct video generation endpoints with customizable duration and camera tracking controls right from the chat bubble.
* **Seamless Voice API Integration (STT & TTS):** Luna doesn't just read; she listens and speaks. Talk to the characters using your microphone, and the app translates it via Speech-to-Text. When the AI replies, the engine silently routes the text to your configured Audio Generation endpoint (like Gemini TTS), returning a playable, high-quality voice response directly inside the chat's sleek inline player. You can assign individual voice models, adjust pitch, and tweak speech speed for *every* character independently.
* **Modular Provider Slots:** Configure global image and audio generation engines using an agnostic slot manager. Plug in customized Base URLs (e.g., TensorArt, Novita, or Google Studio/Gemini).

![Global Image Settings Panel](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-49-13-671_com.muh.luna-edit.jpg)

* **Global Identity Persistence:** Once saved, this visual DNA and core seed are respected globally throughout the entire application. Whether you are generating imagery inside the Textless RPG Adventure, playing a game of UNO, chatting in a multi-character Group Room, or interacting with Floating Overlays, the character's core facial identity remains 100% stable—autonomously varying only the background scenery, pose, and active emotional state.

![The DNA Forge Menu](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-26-51-188_com.muh.luna.jpg)

* **Visual Reaction Loops:** The image generator reads the deep context of the chat thread. Breaking the fourth wall, characters textually, physically, and emotionally react to their own newly generated photos inside the chat box.

![Character Photo Generation](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-04-39-360_com.muh.luna.jpg)
![Character Reaction to Photo](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-04-46-062_com.muh.luna.jpg)

* **Seed-Locked Expression Slots:** Say goodbye to broken character consistency. Once your primary profile avatar is rendered, the engine freezes the generation seed. This unlocks a grid of 16 default emotion slots (Laughing, Sad, Grumpy, Blushing, etc.) and 8 custom expansion slots. You generate them one by one, ensuring total facial stability.
* **Chibi Companion Stickers:** Beyond facial expressions, the engine generates 8 unique super-deformed Chibi stickers (with or without background integration) to be used as dynamic reactions during specific Companion Mode events.

![Expression Matrix Grid](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-01-42-06-130_com.muh.luna.jpg)


### 🗺️ Endless Visual Novel Adventures (Textless Campaign Mode)
* **The Narrator:** A Game Master takes control of your campaign. Instead of demanding tedious typing, it dynamically provides **3 tactical action options** at the end of every turn.
* **The Watcher & Cartographer:** An invisible backend system automatically manages your Inventory, Quest Logs, and active NPCs. As you progress, the Cartographer automatically renders location imagery and draws world maps in real time.

![RPG Adventure](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-14-26-28-994_com.muh.luna.jpg)

### 📚 The Sagas Engine: Immortal Campaign Memory & Cross-Chat Lore
Say goodbye to AI amnesia. Luna compresses and structures your history into a 5-tier hierarchy: **Pages, Entries, Chapters, Volumes, and Aeternums (Absolute Records)** using a fully visible, hierarchical RAG architecture.

* **The Living Diary (Internal POV):** The AI autonomously reviews recent chat logs, interprets the emotional weight of the events, and writes a secret first-person journal using her own personality traits, voice, and unique verbal tics.
* **Advanced Forging Controls:** You are the ultimate editor. Dictate exactly how the AI writes your history by selecting the tone (Quick Draft, Reflection, Maximum Inspiration) or using the Advanced Mode to strictly lock the generation by exact word counts or paragraph sizes.
* **Immersive Reading & Audiobook Mode:** Read your journey through a built-in "Kindle-style" interface featuring custom wallpapers and page bookmarking. You can even generate high-quality TTS audio for each page, turning your roleplay into a fully narrated audiobook.
* **E-book & Manuscript Export:** Export your entire adventure directly to your device as a beautifully formatted HTML E-book (ready for reading on any screen) or a raw Markdown (.md) manuscript (perfect for Obsidian, Notion, or rewriting on your PC).
* **Identity Reinforcement Loops:** These entries are fed directly back into her long-term memory layer, meaning her core identity, biases, and emotional attachment grow exponentially stronger with every single page.
* **Cross-Chat Gossip (The Whisper Network):** Characters are aware of the world outside their 1x1 chats. If an important event happens in a Group Room, characters carry that "memory ticket" with them. They might organically mention or react to something that happened in a completely different session if the context fits.
* **Context Ingestion:** Every narrative event is tracked. A real-time message countdown shows you exactly when the background engine will compress and seal the current context, making your campaign memory immortal.

![Personal Diary Menu](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-00-22-13-821_com.muh.luna.jpg)

![Character's Diary](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-26-00-30-49-261_com.muh.luna.jpg)

### 🃏 In-Character Tabletop Games (UNO)
Sit at a virtual table to play real card games against your characters. Luna isn't just generating text; the engine forces the AI to look at their actual digital hand, strategize, and play by the rules.

* **The Uncompromising AI Judge:** The bots can and will try to win. If an AI attempts to cheat, bluff a card they don't have, or takes too long to play, the hidden Game Master penalizes them with +2 cards in real-time—and they will dynamically react to the punishment in the chat.
* **Multi-Model Chaos:** In Cloud Mode (Route B), you can invite multiple characters to the same table. The engine isolates their brains, allowing you to assign a completely different AI model to each opponent. They will banter, gang up on each other with +4 cards, and react to the table's shifting colors.
* **Short-Text Dynamics:** Toggle the "Short Message" mode to stop AIs from monologuing, forcing them to deliver quick, snappy trash-talk as the game flows.

![A game of UNO](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-35-31-946_com.muh.luna.jpg)

### 🧠 The Core Architecture & Micro-Mechanics (Deep Immersion)

Want to see how deep the engine goes? Expand the sections below to reveal the advanced structural mechanics.

<details>
<summary><b>💖 The Pulsing Heart & Internal Soliloquy</b></summary>
<ul dir="auto">
<li><strong>Emotional Feedback Loops:</strong> Character affinity (0-1000) is monitored via a live pulsing heart icon directly in the chat interface. Its color deepens and its beating frequency accelerates as your emotional connection scales.</li>
<li><strong>The Soliloquy Panel:</strong> Clicking the heart expands an internal dashboard revealing the character’s hidden thoughts (existential crises, deep reflections about the user, or hidden biases) and logs the exact dynamic trigger that granted the last point boost.</li>
</ul>
</details>

<details>
<summary><b>🔮 The Memory Factory: Crystallized vs. Archived Loops</b></summary>
<ul dir="auto">
<li><strong>Dual-Context Capture:</strong> The engine captures a dynamic "take last" window in private/group chats. The character then translates these raw factual records into a personal first-person diary entry matching their traits and tone.</li>
<li><strong>3-Way Retrieval Protocol:</strong> Memories are injected into the active LLM context through three distinct neural pathways: Explicit Tag Matching, Semantic Passive Search, and the Spontaneous 'Archive' Chance (a 15% random chance to pull an Archive entry into conversation, simulating natural human recollection).</li>
<li><strong>Dynamic Context Expiration (10-Turn TTL):</strong> Active memories remain in the context layer for a strict duration of 10 turns before expiring, preventing token bloat.</li>
<li><strong>The Brain Monitor System:</strong> When a memory activates, a pulsing Brain Icon blinks. Clicking it allows the user to view the active entry, discard it entirely, or run a quick override to swap a false-positive semantic match.</li>
<li><strong>Audio Diaries:</strong> Play back any diary entry natively using high-quality Text-to-Speech (TTS) synthesis featuring dynamic ambient background tracks.</li>
</ul>
</details>

<details>
<summary><b>🎲 Native RPG Tools & Interactive Widgets</b></summary>
<ul dir="auto">
<li><strong>In-Chat Physics:</strong> The engine supports native UI widgets for tabletop elements. You can trigger a Dice Roll or a Coin Toss directly in the chat.</li>
<li><strong>System Injection:</strong> A 3D dice or coin animation plays on your screen, the result is randomized, and the System automatically injects the outcome into the narrative so the AI can organically react to your luck.</li>
</ul>
</details>

<details>
<summary><b>🎭 Advanced Group Dynamics & Isolated Brains</b></summary>
<ul dir="auto">
<li><strong>The 3 Persona Keys:</strong> In Group Rooms, you have absolute control over how the party perceives you. Choose "Unified Bio" (the entire group sees you as the Guild Master), "Individual Bio" (Character A sees you as a Mentor, while Character B sees you as a Rival based on their individual sheets), or "Deactivated" for a pure chaotic sandbox.</li>
<li><strong>Isolated Brains Architecture:</strong> Every bot in a group chat or card game runs on strictly isolated brains. You can assign a completely different AI model API to each opponent, preventing personality bleed and ensuring they act, think, and strategize independently.</li>
<li><strong>The Group Watcher Entity:</strong> Context compression and memory aggregation are handled by an impartial observer. Private actions whispered to one character remain completely hidden from others in the same room.</li>
</ul>
</details>

<details>
<summary><b>🧙‍♀️ PNG Card Scaling & The Magic Generator</b></summary>
<ul dir="auto">
<li><strong>The Up-Scale Ladder:</strong> Importing standard or flat character cards from external platforms (such as SillyTavern, Chub, or JanitorAI) triggers an automated structural cascade. The engine analyzes the baseline bio and autonomously crafts matching <em>Speaking Styles</em>, <em>Habits</em>, <em>Ticks</em>, and <em>Hidden Traumas</em> to give foreign cards an instant psychological upgrade.</li>
<li><strong>Alternate Universes Generator:</strong> Simply input a character name and their source work (e.g., Naruto / Naruto Shippuuden) into the Magic Generator to auto-forge a complete entity card, including stable visual parameters and LoRAs. Toggle the Alternate Universe switch to instruct the LLM to write completely new timeline canons from scratch.</li>
<li><strong>On-Demand Expression Slots:</strong> Once your profile image is generated via cloud endpoints, the engine locks the generation seed. This unlocks a grid of 16 default emotion slots and 8 custom expansion slots that can be rendered individually on-demand to guarantee total, unbroken facial stability throughout the entire app.</li>
</ul>
</details>

---

### 🫧 The Floating Universe (Overlay Mechanics & Chaos Mode)
Luna’s overlay system lives actively on top of your Android UI. Your characters are no longer trapped inside a chat log; they are watching your world with you through a highly customizable, glassmorphism-styled floating bubble.

* **Chaos Mode & The God Radar:** Drop your entire roster (even 100+ characters) into a single floating session. The engine utilizes an advanced internal radar that actively scans your text for specific names and emotional nicknames, seamlessly routing the prompt to the exact character you are addressing. Every character operates on strictly isolated brains—meaning zero persona bleeding or memory leakage—allowing them to interact with you and bicker among themselves organically.
* **Screen Vision & Spontaneous Reactions:** With Screen Vision active, characters can read your current mobile display context and comment on what you are doing. Furthermore, the engine features a Spontaneity Timer: if left alone, the AI might autonomously peek at your screen and initiate a conversation out of nowhere.
* **The Time Skip Engine:** Characters possess an organic sense of time. If you leave a character alone for several hours and then reopen their overlay, the engine organically calculates the elapsed time. The AI will act as if they lived their day normally while you were gone, naturally shifting their greetings and mood.
* **Autonomous Notifications & "Double Greeting" Continuity:** Bots will autonomously text you first via push notifications (Greeting 1). Clicking the notification launches a floating Ephemeral Chat and instantly triggers a continuity system. The AI seamlessly acknowledges your arrival and delivers a second, contextual follow-up (Greeting 2) *before* you even type a word. This hooks directly into the 0-1000 Intimacy system, dynamically tracking affinity in the background.

![Notification](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-45-54-982_com.mi.android.globallauncher.jpg)

![Ephemeral Floating Chat](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-50-55-339_com.mi.android.globallauncher.jpg)

---

## ⚙️ Immersive Styling & Advanced Identity Mapping

* **7 Mythic Interface Domains:** Completely overhaul the UI theme to match your genre (Cyberpunk, High Fantasy, Grimdark, etc.). These domains dynamically recolor fonts to flawlessly separate dialogue tokens (`" "`) from narrative actions (`* *`).
* **Multi-Perception Identity:** Your overarching profile holds your hidden secrets, but you can build a customized Bio per character. You can be perceived as an absolute King to one bot and a sworn Enemy to another within the same ecosystem.
* **Granular Hardware Command:** Take total control of your device's architecture. Dictate exact CPU thread allocation, RAM context limits, and text generation speeds (Typewriter effect vs. full-block outputs).

![Settings menu](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-28-47-325_com.muh.luna.jpg)

---

## 📦 How to Access Luna

Luna contains **zero embedded ads, zero hidden paywalls, and zero recurring in-app subscriptions**. 

By supporting this solo development project on Patreon, you instantly unlock the standalone optimized APK and our quick **5-Minute Survival Guide** to plug in your endpoints (OpenRouter, Novita, or local GGUF) and bring the engine to life.

👉 **[Support the Developer & Download Luna Here](https://www.patreon.com/LunaAPK)**
