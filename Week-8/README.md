# Week 8 - Agentic AI Pipeline

## Overview

This project implements a Single Agent AI Assistant capable of understanding user queries, routing tasks based on intent, and invoking the appropriate tool. The agent returns structured JSON responses and demonstrates the fundamentals of Agentic AI.

## Features

- Intent-based query routing
- Mathematical calculation tool
- Keyword extraction tool
- Word counter tool (Bonus)
- Structured JSON responses
- Error handling
- Interactive command-line testing

## Technologies Used

- Python
- Conditional Routing
- JSON
- Google Colab

## Project Workflow

1. Receive user query
2. Detect user intent
3. Route request to the appropriate tool
4. Execute the selected tool
5. Return structured JSON output
6. Handle invalid inputs safely

## Tools Implemented

- Calculator
- Keyword Extractor
- Word Counter (Bonus)

## Bonus Enhancements

- Improved routing using multiple command keywords (calculate, compute, solve)
- Logging for request processing
- Additional Word Counter tool

## Sample Output

```json
{
    "type": "calculation",
    "result": "25"
}
```

```json
{
    "type": "keywords",
    "result": ["artificial", "intelligence", "industries"]
}
```

```json
{
    "type": "general",
    "result": "Hello! I am a Single Agent AI Assistant. I can perform calculations, extract keywords, and count words."
}
```

## Conclusion

This project demonstrates the implementation of a basic Single Agent AI system using intent-based routing. The agent successfully performs calculations, keyword extraction, and word counting while returning structured JSON responses. Additional improvements such as enhanced routing, logging, and an extra tool were implemented to demonstrate core Agentic AI concepts.
