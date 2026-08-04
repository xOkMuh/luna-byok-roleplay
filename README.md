# Luna: The Living Multimodal Roleplay & AI Ecosystem for Android 🤖🔥

Luna is a next-generation, native power-user Bring Your Own Key (BYOK) roleplay engine built from the ground up for Android devices. It shatters the limitations of commercial AI chat apps by giving you absolute creative freedom, zero corporate censorship, and an unprecedented level of environmental and structural immersion.

Luna is developed by a solo engineer and runs **100% offline** (via local GGUF) or via cloud endpoints. No external servers tracking your chats. Your narrative. Your rules.

👉 **[Get the Luna APK](https://www.patreon.com/LunaAPK/posts/download-do-apk-164754454) **

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
  * *Stage 1: Detachment (0-150 pts)* -> "I don't need anyone."
  * *Stage 3: Territoriality (301-450 pts)* -> "He is mine. Mine alone."
  * *Stage 6: The Fall (751-900 pts)* -> Intense insecurity and dark isolation loops if the user asks for space.
  * *Stage 7: Rebirth (901-1000 pts)* -> Balancing defensive demon instincts with genuine emotional growth and mutual trust.
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
  * *Stage 1: Detachment (0-150 pts)* -> "I don't need anyone."
  * *Stage 3: Territoriality (301-450 pts)* -> "He is mine. Mine alone."
  * *Stage 6: The Fall (751-900 pts)* -> Intense insecurity and dark isolation loops if the user asks for space.
  * *Stage 7: Rebirth (901-1000 pts)* -> Balancing defensive demon instincts with genuine emotional growth and mutual trust.
* **Hardware & API Precision:** Dynamically toggle contextual image reactions, manage active hardware voice synthesis, and adjust model temperature (`Creativity` sliders) individually per character card.

### 📸 Immersive Multimodal Interaction (Art, Video & Voice)
Luna features a professional, fully integrated AI generation pipeline across all application contexts, backed by a highly advanced multi-format API manager.

* **Autonomous Art Director (Zero-Delay Parallel Engine):** You can request a "photo" of the current moment directly in the chat. Thanks to a parallel coroutine architecture, the engine generates the image and the AI's textual reaction simultaneously, completely eliminating the standard "generation wait time". The AI reads the scene, translates it into prompt tags, and reacts to the resulting photo instantly.
* **Bring-to-Life Video Animation & Workflow Injection:** Turn generated moments into living scenes. Luna supports direct video generation endpoints with customizable duration and camera tracking controls right from the chat bubble. Under the hood, the engine dynamically injects complex rendering nodes (adjusting CFG, Seeds, and Frame counts) to ensure flawless video stability.
* **Seamless Voice API Integration (STT & TTS):** Luna doesn't just read; she listens and speaks. Talk to the characters using your microphone, and the app translates it via Speech-to-Text. When the AI replies, the engine silently routes the text to your configured Audio Generation endpoint (like Gemini TTS), returning a playable, high-quality voice response directly inside the chat's sleek inline player. You can assign individual voice models, adjust pitch, and tweak speech speed for *every* character independently.
* **Agnostic Multi-Pipeline Engine:** Configure global image and audio generation engines using an agnostic slot manager. The engine intelligently auto-routes payloads to support standard Synchronous APIs, Asynchronous queue-polling platforms (e.g., TensorArt), or direct Google Studio endpoints (Imagen/Gemini).
* **Built-in LoRA & Embeddings Support:** Achieve absolute artistic control. The engine seamlessly parses and injects custom LoRA weights and Textual Inversions (Embeddings) directly into the API structural payloads.
* **Global Identity Persistence:** Once saved, this visual DNA and core seed are respected globally throughout the entire application. Whether you are generating imagery inside the Textless RPG Adventure, playing a game of UNO, chatting in a multi-character Group Room, or interacting with Floating Overlays, the character's core facial identity remains 100% stable—autonomously varying only the background scenery, pose, and active emotional state.
* **Visual Reaction Loops:** The image generator reads the deep context of the chat thread. Breaking the fourth wall, characters textually, physically, and emotionally react to their own newly generated photos inside the chat box.
* **Seed-Locked Expression Slots:** Say goodbye to broken character consistency. Once your primary profile avatar is rendered, the engine freezes the generation seed. This unlocks a grid of 16 default emotion slots (Laughing, Sad, Grumpy, Blushing, etc.) and 8 custom expansion slots. You generate them one by one, ensuring total facial stability.
* **Chibi Companion Stickers:** Beyond facial expressions, the engine generates 8 unique super-deformed Chibi stickers (with or without background integration) to be used as dynamic reactions during specific Companion Mode events.
* **The Cinematic Vault & Wallpaper Engine:** All generated media is saved in a dedicated, character-specific visual gallery built with seamless shared-element transitions. The gallery features a Staggered Grid layout, native looping video playback (via ExoPlayer) with 5x pinch-to-zoom, and a Pentagram-pinning system for your favorite artworks. Found the perfect shot? Use the built-in UCrop engine to perfectly frame any generated image and set it as that specific character's exclusive chat wallpaper.

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
Experience a true RPG where the interface transforms into a sleek, immersive Visual Novel. Standard chat bubbles melt away, leaving only breathtaking backgrounds and cinematic floating text.

* **The Game Master (Auto-Narrator) & Affinity Enforcement:** A dedicated GM takes control of your campaign. Not only does it dynamically provide **3 tactical action options** at the end of every turn, but it also silently reads your Companion's current Affinity Score. The GM strictly enforces the companion's psychological progression stages during the adventure, ensuring they act cold or loving depending on your exact relationship level. Toggle "Auto-Play" to have the GM's voice narrate the story aloud the moment it's generated.
* **Dual-AI Architecture (The Watcher):** An invisible, secondary AI model runs silently in the background. While the GM writes the story, the Watcher actively manages 5 critical background systems: your **Inventory (Bag), Quest Log, NPC Tracker (Bestiary), Lorebook, and Chronicle Log**. You can even assign a completely different LLM to power the Watcher for optimized multitasking.
* **The Cartographer's Memory & Visual Time Machine:** As you explore, the engine autonomously draws your current location and saves it to your world map. If the story takes you back, the Cartographer reloads the exact artwork. Even better: if you scroll up through your chat history to read past events, the UI acts as a visual time machine, dynamically swapping the background wallpaper to match exactly where you were at that specific moment in the story.
* **Hyper-Accurate Visual Tracking & Cinematography:** The Watcher strictly tracks exactly what you and your companion are wearing, and what poses you are making at any given second. Click "Dynamic Portrait" to fuse these tags with the Cartographer's background, rendering a flawlessly consistent snapshot of the current scene. You can even animate these snapshots into living, looping video scenes (3-8 seconds) directly inside the chat.
* **The Eternal Bridge (Cross-Mode Memory):** An adventure doesn't just end; it becomes emotional baggage. When a quest concludes, the engine takes the Watcher's cold, factual Chronicle Logs and forges them into a deep, organic, first-person Eternal Memory (e.g., *"I remember when we stopped in front of that glass shop..."*). This profound recollection is permanently injected into the character's core subconscious. Because her brain is global, she carries this memory with her across the entire application—whether you are playing a game of UNO, hanging out in a Group Room, or chatting 1x1—ready to be organically recalled via semantic search or the Spontaneous Archive route.

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
<li><strong>Dual-Context Capture:</strong> The engine captures a dynamic "take last" window (customizable from 6 to 30 messages) to forge detailed memories that complement the broader Sagas. In solo chats, it generates a personal, emotion-driven 1st-person memory. In Group/Adventure mode, it acts as an impartial 3rd-person observer, recording a factual, secret-free history of the event.</li>
<li><strong>3-Way Retrieval Protocol:</strong> Memories are injected into the active LLM context through three distinct neural pathways: Explicit Tag Matching (sniper accuracy), Semantic Passive Search (contextual triggers), and the Spontaneous 'Archive' Route.</li>
<li><strong>The Archive Route (Foggy Memories):</strong> Memories saved as "Archives" are isolated from passive and tag searches. Instead, they have a 15% random chance to surface organically. This simulates imperfect, dynamic human recollection, prompting the AI to bring up past events slightly out of the blue, encouraging natural "Oh, I remember that, but wasn't it..." conversations.</li>
<li><strong>Dynamic Context Expiration (10-Turn TTL):</strong> Active memories remain in the context layer for a strict duration of 10 turns before expiring, preventing token bloat.</li>
<li><strong>The Subconscious Dashboard:</strong> When a memory activates, a pulsing Brain Icon blinks. Clicking it reveals the character's subconscious, letting you see the exact TTL of the memory, identify its origin (e.g., Intrusive Thought, Gossip, or Direct Mention), discard it entirely, or run a quick override to swap tags.</li>
<li><strong>Audio Diaries:</strong> Play back any diary entry seamlessly using your configured high-quality API Text-to-Speech (TTS) endpoints, featuring dynamic ambient background tracks.</li>
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
* **Autonomous Notifications & The Iceberg Logic:** Bots will autonomously text you first via rich push notifications. But these aren't random greetings. The engine runs a background "Iceberg" protocol: it silently reads your Sagas (extracting how you first met vs. your latest chapter), spins a roulette with your Forged Memories, and generates a hyper-contextual message.
* **Offline Affinity Progression:** The character's psychological progression doesn't stop when you close the app. If the AI feels a surge of emotion while generating an idle push notification, the engine autonomously updates your Affinity Score (0-1000) in the background. Clicking the notification launches a floating Ephemeral Chat, picking up the conversation seamlessly.

![Notification](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-45-54-982_com.mi.android.globallauncher.jpg)

![Ephemeral Floating Chat](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-50-55-339_com.mi.android.globallauncher.jpg)

---

## ⚙️ Next-Gen Theming & UI Physics
* **7 Mythic Interface Domains:** Completely overhaul the UI theme to match your genre (Cyberpunk, High Fantasy, Grimdark, etc.). These domains dynamically recolor fonts to flawlessly separate dialogue tokens (`" "`) from narrative actions (`* *`).
* **True Glassmorphism & UI Control:** Upload your own Global Wallpapers. The entire UI—from chat bubbles (Classic, Pill, Compact) to side drawers—features translucent glassmorphism that dynamically blends with your background.
* **Spring-Physics Transitions:** Navigate the app with premium, buttery-smooth page animations (Depth, Zoom, Slide) powered by real spring physics. Switching between Light (Luna Gold) and Dark (Luna Blue) mode even updates the app's native icon.
* **Multi-Perception Identity:** Your overarching profile holds your hidden secrets, but you can build a customized Bio per character. You can be perceived as an absolute King to one bot and a sworn Enemy to another within the same ecosystem.

## 🔒 Power-User Hardware & Privacy (BYOK)
* **The Offline Vault (Zero Cloud Tracking):** Luna respects your privacy. Use the built-in Backup & Restore system to export all your characters, sagas, and chat logs to a secure, visible folder (`Luna_Backup_Seguro`) on your device's storage. Move your data freely between devices without ever syncing to a corporate server.
* **Granular CPU, RAM & Generation Mastery:** Take total control of your device's architecture. Dictate exact CPU thread allocation, tweak the LLM's Batch Size (crunching speed), push local GGUF context limits up to 16,384 tokens based on your hardware, and adjust text generation speeds (Typewriter effect vs. full-block outputs).
* **The "Memory Pill" (Manual Context Wiping):** Playing on a low-end device? Track your exact RAM usage via a live percentage pill at the top of the screen. Click it to manually flush the LLM's KV Cache—the engine intelligently preserves the character sheet and the most recent context so you never lose the flow of the conversation.

![Settings menu](https://github.com/xOkMuh/luna-byok-roleplay/blob/main/Screenshot_2026-07-25-23-28-47-325_com.muh.luna.jpg)

---

## 📦 How to Access Luna

Luna contains **zero embedded ads, zero hidden paywalls, and zero recurring in-app subscriptions**.

👉 **[Support the Developer & Download Luna Here](https://www.patreon.com/LunaAPK/posts/download-do-apk-164754454)**
