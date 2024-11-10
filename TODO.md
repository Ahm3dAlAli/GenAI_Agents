# TODOs

1. List main open source repos for scientific papers:
    - arxiv
    - etc.
    and make sure they have an API.
2. Jupyter notebook:
    - input: user asks about a scientific paper or an aerea of research
    - find the paper or list of papers online
    - download the content and add to context window
    - generate a detailed answers


## Notes

- if the paper is short enough, just put it in the context window
- focus in results: the user can ask about a specific result or a general question
- paper download:
    - v0: use text directly
    - v1: download pdf and extract text, images, tables with unstructured.io
- add inline citations


# Nice to haves:

- allow the user to ask follow up in the notebook itself
- show tables or images in the response
- inline citations with highlited text