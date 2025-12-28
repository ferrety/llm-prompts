# LLM Prompt & Instruction Repository

A version-controlled library for storing Large Language Model (LLM) system instructions, Custom GPT configurations, and task-specific prompts.

## Project Structure

The repository is organized by domain and specific use cases:

* **/ttrpg**: Directories for Tabletop RPG systems.
    * `/{system}/gpts/`: System-level instructions for Custom GPTs or Claude Projects (e.g., `overseer-config.md`).
    * `/{system}/prompts/`: Specific execution prompts for active sessions.
    * `/{system}/reference/`: Technical lore and mechanics snippets.
    * **/shared**: Universal utilities for text processing, NPC generation, and general assistance.

## Management Guidelines

### File Naming Conventions
* Prefer using standard filenames, e.g., copilot instructions files, AGENDS.md, etc.
* **`*-config.md`**: Full system instructions intended for the "Instructions" field of a model.
* **`*-graphics.md`**: Dedicated instructions for image generation models (DALL-E, Midjourney).
* **`*.json` / `*.yaml`**: Structured data for few-shot examples or programmatic access.


## 📋 Best Practices
1. **Model Tagging**: Include the intended model (e.g., GPT-4o, Claude 3.5 Sonnet) at the top of markdown files.
