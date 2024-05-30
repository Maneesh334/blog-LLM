---
title: "YouTube RAG"
date: 2024-04-01T02:01:58+05:30
description: ""
tags: [RAG]
---

Simple RAG application to query a YouTube video. Involves transcribing video to text with Whisper, splitting text into chunks, storing the chunks in a cloud vector database like Pinecone and then retrieving relevant chunk from database based on similarity of chunk's embedding to question's embedding, after which the chunk's sent to the Gemini API for an answer. 