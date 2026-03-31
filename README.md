# HEARTBEAT
A biological AI memory system that transforms conversations into permanent, searchable memory cells.
💓 Heartbeat — Biological AI Memory System

Heartbeat is a local AI memory engine designed around a biological metaphor.
Most AI chatbots forget everything the moment a session ends. Heartbeat solves
this by routing every conversation through a multi-stage intelligence pipeline
that extracts, filters, and permanently stores memories as "Blood Cells".

🧬 How It Works

Every message you send passes through 3 stages:

  L1 Sieve      → Filters out noise, filler words, and small talk
  L2 Valve      → Detects intent, ambiguity, and splits multi-part questions
  L3 Purifier   → Extracts core memory, assigns topic, importance score & expiry

Purified memories are stored as Blood Cells in a local SQLite + ChromaDB
database and can be monitored live on a real-time dashboard via WebSockets.

🛠️ Built With

  Backend   →  Python, FastAPI, SQLite, ChromaDB, Sentence Transformers
  LLM APIs  →  Groq (primary), OpenRouter (fallback)
  Frontend  →  Vanilla HTML, CSS, JavaScript, WebSockets
  NLP       →  NLTK for lexical filtering

💡 Key Concepts

  • Blood Cells     — Individual memory units with topic, score & expiry
  • Immune System  — Blocks prompt injection and malicious input
  • Metabolism     — Background job that decays old/irrelevant memories
  • Fact Supremacy — Newer facts automatically overwrite outdated ones
  • Artery / Vein  — Queue and pub-sub system for cell circulation

⚡ The idea and architecture were designed by me. The goal was to give
   AI a persistent subconscious — not just a context window.
