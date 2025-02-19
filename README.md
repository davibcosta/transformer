# Decoder-only Transformer
I implemented and trained a decoder-only Transformer model from scratch in pytorch. I use GPT-2 tokenizer for simplicity. 
First, I wrote some sample text for training and generated some gibberish (with some english resemblance due to GPT-2 tokenizer).
Then, I used 1% of OpenWeb dataset for training. This time, the output was in English, but sentences were meaningless.
Lastly, I used 10% of OpenWeb dataset and split it into training and validation. Comparing the loss I concluded that there is no overfitting. Output was in English, with somewhat more meaning.
