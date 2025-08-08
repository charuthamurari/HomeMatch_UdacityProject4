# HomeMatch: End-to-End Personalized Real Estate Matching Solution

##  Project Goal
Build a real estate app called "HomeMatch" that creates personalized property listing descriptions using Large Language Models (LLMs) and vector databases. Instead of just showing filters, it will understand buyer preferences in natural language and match properties to these preferences in a personalized, engaging way.

##  Features
- **AI-Generated Listings** using OpenAI's GPT models.
- **Vector Database Search** with ChromaDB for semantic similarity.
- **Personalized Recommendations** tailored to user preferences.
- **Command-Line Interface** for easy interaction.

## How it works (Step-by-Step)
1. Understand Buyer Preferences
Buyers enter what they want in natural language.

The system uses LLMs (like GPT) to interpret these nuanced requirements (e.g., “a quiet neighborhood with good schools”).

2. Store Listings in a Vector Database
Real estate listings are converted to embeddings using models like SentenceTransformers.

Listings are stored in a vector database (e.g., ChromaDB) for fast, similarity-based searches.

3. Match Listings to Preferences
Preferences are also converted to embeddings.

Semantic search is done in the vector DB to find most relevant listings.

4. Rewrite Listings to Match Buyer’s Style
The LLM rewrites each listing to highlight what the buyer cares about.

This makes listings feel more personal and relevant, while keeping all facts intact.
