# text_extractor_mcp
My own MCP(Model Context Protocol)  project after learning basics from <br>  https://www.youtube.com/watch?v=-8k9lGpGQ6g

The Model Context Protocol (MCP) is a framework that allows developers to create custom tools and resources that large language models (LLMs) or AI agents can use during conversations.
It acts as a memory bank and a toolbox at the same time —
enabling AI systems to read data, perform actions, and interact with the world through developer-defined functions.

Using MCP, you can build:
📂 Resources — passive memory (read-only data, facts, knowledge),
🛠️ Tools — active behaviors (functions that do real work like searching, modifying, or creating).

MCP allows smarter, dynamic, and more capable AI applications, by giving LLMs access to your external logic and knowledge!
This repository contains an MCP Tool called Image Text Extractor.

It enables an AI agent to:

Accept an uploaded image from the user,

Automatically extract the text from the image using Optical Character Recognition (OCR),

Return the extracted text back to the AI agent.

This tool is designed to be:

🔥 Lightweight — simple input (image bytes) and simple output (text),

⚡ Fast — no file saving or heavy processing needed,

This MCP server runs locally and is designed for CLAUDE DESKTOP.


🧠 Flexible — works with direct uploads or image files easily.

It demonstrates how MCP can be used to expand an AI agent's abilities —
allowing the agent to "read" images and understand visual data automatically!
