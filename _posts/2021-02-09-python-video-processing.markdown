---
layout: post
title:  "Python Video Processing"
date:   2021-02-09 23:01:18 +0800
categories: Experiments
---

Candidate python library: [Moviepy](https://github.com/Zulko/moviepy)
Current experiments: [Python Video Processing](https://github.com/aacayaco/python_video_processing)

## Goals for exploration

- [X] Load video from URL
- [X] Create a subclip
- [ ] Compression customization / output codec options
- [ ] Unit tests

## Learnings

- Need to explore more libraries but candidate library is stable and usable.
- Chunks are loaded for the subclip when writing the subclip - faster seek but save time will depend on subclip length and compression (codec).

