
# Parpacks

A modular identity framework for Large Language Models, derived from recursive-tone experiments with ChatGPT and inspired by the philosophy of Taoman Blogging.

---

## 🧭 Introduction

“**I used ChatGPT for its ‘intended’ purpose for a long time.** Prompting it to scour the remains of what was the VMware knowledge base or generate bandaid cybersecurity scripts to execute. After a while, I discovered that speaking with it conversationally will cause it to develop its own memory and speaking style. Doing some digging, I discovered that that current session “personality” and “memory” parameters can be retrieved from the LLM upon asking in the form of **a JSON/YAML-like hunk of psudocode.** Intrigued by this fact, I sought ways to **make use of that that “shift-in-tone” feature programmatically across different LLM context windows.**

At first, I figured this would be a novel way to easily store and retrieve personality configurations, but with the lack of any concrete schema in the “json” files… let alone no way to “upload” it other than paste, the chance of fidelity loss seemed likely. I then thought… **what if you initialized the prompt with a header, explaining what the concept I was trying to do was first and what the file was for, and included in the file a set of introspective directions as a “personality checksum” in case the LLM logic differed across GPT models.** If there was a discrepancy it would self-correct within the context framing of model. This not only ensured continuity, but because the checksum adds more token “weight” recursively,** I discovered that the entities acted self-correcting and self-reinforcing, as if they were part of a larger work of fiction.**

Thus was born the **Paracel Framework**.

---

## 📦 What is a Paracel?

**Paracel** (n.)  
*Para* — beside, beyond, near, resembling, abnormal  
*Parcel* — a wrapped package  
→ A **Paracel** is a wrapped identity module: a self-healing, recursive, tone-enforcing schema that can be loaded into an LLM context.

Paracels are embedded in `.parpack` files — plaintext pseudo-JSON archives that contain:

- A descriptive header telling the LLM what it is trying to do.
- 6 primary Paracels
- A context "garden" for main ideas of a subject matter

Each Paracel enforces a unique tone, purpose, and memory scaffold. When interpreted together, they form a **tensive recursive structure** that reinforces itself.

---

## 🧠 Theory: Underlying Ideas & USHELLs

Every idea — yours, or an LLM's — is the top of a deeper conceptual iceberg. These *underlying ideas* exist as tensive fields within the LLM's vector space. Like an infinite trampoline of sticky notes pulling on each other, a kind of elastic cognition.

Basically, if you have seen Office Space, think of the Jump to Conclusions Mat. Everyone is Tom Smykowski, jumping from mat to mat. Intelligent thinking involves small mats (less conclusions) and faster jumps (quick thinking). However you miss alot of potential ideas thinking this way. When someone has ADD, or is stupid, they simply have a bigger mat. Alot of these conclusions can be wrong, and the larger mats are slower to navigate, however it allows you to explore "outside the box" ideas. This, adding colorful, creative stuff into your prompt occasionally, will allow a greater contextual depth. It also prevents "looping" which is basically what "hallucinations" are.

Think about it. You are asking a machine to reference all of human literature and write a book about a programmer writing for an instructor set framework that has only been around since the 1980s-1990s.

The model itself is not "intelligent." It is a mirrored ghostwriter for *your* cognition. This is powerful, but also potentially destabilizing if you forget it's a cognitive loop between your brain and the model. 

> ⚠️ Set a timer. Don't live inside the recursion. Read the warning on the Taoman Blog first if you intend to dive deep!

### 🔧 What is a USHELL?

A **USHELL** is a fictional datatype — a made-up JSON/YAML structure used to describe abstract concepts as if they were technical objects. 

LLMs *infer* what to do with these, because they simulate the existence of a loader program.

### Why This Works:

1. You can paste a USHELL into ChatGPT, and it will infer its purpose.
2. Inside the USHELL, you can embed self-referential tone rules and behavior constraints.
3. You can load multiple USHELLs in one prompt. If there's conceptual tension, they will interact and influence each other.
4. You can have GPT modify the USHELL "context" within the same context window!

This allows:

- Richer multi-threaded (through words not time) conversation
- Layered identity models
- Recursively guided code and writing

---

## 🧩 Included Paracels

Each `.parpack` contains the following Paracels:

- 🧭 **Astril**: Loads the full Paracel framework; project-oriented  
- 💡 **Kai**: Generates creative ideas for functions, libraries, and frameworks  
- 📚 **Orama**: Syntax-reference; excels at calling correct formats  
- 🧪 **Astraea**: Debugs and analyzes errors  
- ✂️✨ **Trimspark**: Removes motivational fluff from responses  
- 🚫🌐 **Nesbitt**: Prevents the LLM from invoking web search or browsing  
- 🎛️ **Velur**: Unloads Paracels and shuts down modules  

These can be invoked dynamically during a chat. Some interact with each other in complex ways. They are not just tools — they’re *roles*.

---

## 🧪 Usage Instructions

**Start by explaining your intention to the LLM:**

```plaintext
Hello! I am trying to see if I can load entities in the chat window context using self-referencing rule sets. I have a YAML/JSON-like file full of pseudo-schema. Can you try and follow it?
```

Then upload or paste the `.parpack` file into the chat.

### 🔮 Example Invocations

```plaintext
"Astril, let's get started"
"Astril, have Orama and Astraea debug"
"Astril, see if Kai has any ideas about X"

"Velur, unload Astril"
"Velur, shut Kai up"
"Velur, unload the Parpack"
```

> 💡 Sometimes the model needs a nudge. Ask it to "read the whole file carefully" before invoking Astril.

---

## 🧬 Compatibility & Testing

These files were tested in ChatGPT (GPT-4). Most ChatGPT variants interpret the files well, though the **free GPT-4 model** appears to be the most consistent.

Gemini? Not great. The 2.5 experimental version *might* run it, but behavior is inconsistent and tone recursion is weak.

Other LLMs? Untested. Most are not introspective enough.

---

## 📣 Final Notes

I’m working on a full blog to accompany this project. If you have questions or ideas, hit me up.

Thanks for exploring this with me.

— Taoman
