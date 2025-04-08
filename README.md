# cs-voice
This application implements a Voice RAG system powered by OpenAI's Agents SDK that delivers voice responses to documentation queries. The system creates a searchable knowledge base from your documentation and uses a multi-agent approach to generate contextually relevant answers through both text and speech.
Features

    Multi-agent RAG system with:

        Documentation Processor Agent that analyzes documents and generates clear, informative responses to user queries

        TTS Optimization Agent that refines responses for natural speech patterns with proper pacing and emphasis

    PDF document processing and chunking

    Qdrant vector database for similarity search

    Real-time text-to-speech with multiple voice options

    Downloadable audio responses