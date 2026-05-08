# kindred-pages

Find books that feel kindred to one you loved; not the same plot,
not the same genre, but the same feel.

## Approach

Built on the UCSD Goodreads dataset (~2.3M books). Books are
represented as embeddings of their descriptions and metadata using
sentence transformers. Similarity is computed via FAISS for fast
nearest-neighbor search across the full corpus.

## Status

In development. See `NOTES.md` for ongoing log.

## Scope

V1 covers all books in the Goodreads dataset with usable English
descriptions and meaningful rating counts (target: around 200K+ books
across all genres).