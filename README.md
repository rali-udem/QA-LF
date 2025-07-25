# QA-LF

Q&A-LF : A French Question-Answering Benchmark for Measuring
Fine-Grained Lexical Knowledge

We introduce Q&A-LF, a French, question-
answering benchmark designed to assess the
extent to which large language models capture
fine-grained lexical knowledge. We investigate
the ability of ChatGPT-4o mini, Qwen2.5-14B,
Llama3.0-8B, and Llama3.1-8B to answer
questions based on lexical functions from
Meaning-Text Theory. Using various prompt-
ing setups with different levels of examples
and context, we find that Qwen and ChatGPT
generally outperform Llama models, achiev-
ing up to 70% accuracy, while Llama models
reach just above 60%. We identify LFs that
are particularly easy or especially challenging
for the models. We further investigate whether
providing sentence-level context and one-shot
prompting improve performance, especially on
semantically complex functions.


This repository contains a directory (keyword + accepted answers).
In it, there are files for each LF used. The pattern is as follows
keyword 1 --> [accepted answer 1, accepted answer 2, ..., accepted answer n1]
...
keyword 100 --> [accepted answer 1, accepted answer 2, ..., accepted answer n100]

The keywords are meant to replace the <L> tags in the question_patterns_used.txt file, while the "accepted answers" are considered correct answers to the resulting question.










