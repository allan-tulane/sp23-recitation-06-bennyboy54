# CMPS 2200 Recitation 6
## Answers

**Name:**_________________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt      |   3216             |  630           | 630/3216 = 0.2
alice29.txt |   5345316          |  457141        | 457141/5345316 = 0.09
asyoulik.txt|   4256086          |  404752        | 404752/4256086 = 0.1
grammar.lsp |   141398           |  11730         | 11730/141398 = 0.08
fields.c    |   501750           |  37198         | 37198/501750 = 0.07

Clearly Huffman encoding is faster than Fixed-Length coding, especially as the alphabets get bigger.

- **e.**
The cost would be frequency*total depth of tree, so the cost would vary on the length of the document.

