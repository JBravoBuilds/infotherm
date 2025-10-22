# Semantic Diff - Information Heat Analysis

A sophisticated web application that quantifies and visualizes the semantic and structural differences between two blocks of text using advanced NLP techniques.

## Features

- **Five Analytical Proxies**: Uses CR, LRF, SCD, SSD, and TDS to measure different aspects of text similarity
- **Real-time Analysis**: HTMX-powered dynamic updates without page refreshes
- **Modern UI**: Clean, responsive design with Pico.css
- **API Endpoint**: JSON API for programmatic access
- **Error Handling**: Comprehensive validation and error reporting
- **Example Texts**: Built-in examples to demonstrate different types of changes

## Technology Stack

- **Backend**: Python Flask with HTMX integration
- **Frontend**: Jinja2 templates with HTMX for dynamic updates
- **Styling**: Pico.css framework with custom enhancements
- **NLP Libraries**: spaCy, sentence-transformers, scikit-learn, tiktoken, lz4


## Analytical Proxies

The application uses five different proxies to measure text differences:

1. **CR (Compressibility Ratio)**: Measures structural redundancy differences using LZ4 compression
2. **LRF (Local Redundancy Factor)**: Measures n-gram similarity using trigram cosine similarity
3. **SCD (Semantic Coherence Divergence)**: Measures meaning similarity using sentence transformers
4. **SSD (Syntactic Structure Divergence)**: Measures grammar pattern differences using spaCy dependency parsing
5. **TDS (Token Distribution Skew)**: Measures vocabulary usage differences using tiktoken tokenization


