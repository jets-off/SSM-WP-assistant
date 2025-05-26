# Sport Science - Workout Planning - Assistant

## Description

Creating an AI powered assistant able to help, give scientifically proven insights in regards to sports - wellness - healthiness, plan optimal workout based on science and quantitative data, using peer reviewed sports science papers.

### Architecture

- Data miner
    - access to database such as PubMed, jssm, consensus ai
- Data parser
    - colpali style of parser (cloud hosted)
- (minimal) Vector database
    - Locally hosted using Weaviate or FAISS
- LLM hosted by Nscale
    - prompt engineering