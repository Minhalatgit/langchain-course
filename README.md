# LangChain Course

My notes and experiments while learning LangChain v1, using Google Gemini, Groq and OpenAI models.

## Notebooks

Found in `updatedlangchain/`:

1. Introduction to LangChain and agents
2. Model integration, streaming and batching
3. Tools and the tool execution loop
4. Messages
5. Structured output
6. Middleware (summarization, human-in-the-loop)

## Setup

Requires Python 3.13+ and [uv](https://docs.astral.sh/uv/).

```bash
uv sync
```

Create a `.env` file in the project root with your API keys:

```
GOOGLE_API_KEY=
GROQ_API_KEY=
OPENAI_API_KEY=
```
