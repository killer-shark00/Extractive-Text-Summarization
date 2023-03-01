# Extractive-Text-Summarization

Extractive text summarization is a technique used to automatically generate a summary of a document by selecting the most important sentences or phrases from the original text. Unlike abstractive summarization, which generates a summary by creating new sentences that capture the essence of the original text, extractive summarization relies on selecting the most salient pieces of information directly from the source text.

The process of extractive summarization typically involves several steps, including text preprocessing, sentence extraction, sentence ranking, and summary generation. In the text preprocessing phase, the source document is cleaned, formatted, and prepared for analysis. Then, in the sentence extraction phase, individual sentences are identified and separated from the text.

The next step is sentence ranking, which involves assigning a score to each sentence based on its relevance and importance to the overall meaning of the text. Various algorithms and techniques can be used to perform sentence ranking, including frequency-based methods, graph-based methods, and machine learning approaches.

Finally, the summary generation phase involves selecting the top-ranked sentences and assembling them into a coherent summary. The length of the summary can be controlled by setting a desired word or character count, or by specifying a maximum number of sentences to include.

Overall, extractive text summarization is a powerful tool for quickly generating concise summaries of large volumes of text. It has numerous applications in fields such as news aggregation, social media monitoring, and legal document analysis.


This code takes in a text string and the desired number of summary sentences, and outputs a summary of the text using a simple word frequency-based approach
