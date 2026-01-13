#Legal & Policy Explainer Bot
Understanding legal and policy documents shouldn’t feel overwhelming. The Legal & Policy Explainer Bot is a small step toward making dense legal text easier to read, search, and understand—especially for students, researchers, and anyone curious about how laws actually work.

This project takes legal PDFs (like the Constitution, IPC, CrPC, RTI, NEP, etc.), searches through them intelligently, and then explains the most relevant parts in simple language—without changing their original meaning.

The focus is not on giving legal advice, but on improving accessibility and clarity.

What This Project Does

Reads legal and policy PDFs stored on Google Drive

Breaks large documents into structured, searchable sections

Uses semantic search to find the most relevant law text for a question

Simplifies legal language using Google Gemini

Shows where the answer came from (articles / sections)

Runs as an interactive chatbot in a notebook environment

How It Works (In Simple Terms)

Legal PDFs are loaded and converted into text

The text is cleaned and split into meaningful chunks

Each chunk is converted into embeddings for semantic search

FAISS helps quickly find the most relevant text for a query

Gemini rewrites that text in simpler language

The bot displays the explanation along with the source reference

Everything is designed to stay grounded in the original document.

Tech Used

Python

PyPDF2

SentenceTransformers

FAISS

Google Gemini

Google Colab
