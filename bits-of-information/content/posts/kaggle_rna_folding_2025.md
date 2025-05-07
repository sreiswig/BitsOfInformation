Given a sequence predict 5 3d structures for that sequence. 
Sequences are given as a string of A, C, G, U. 
Some of the training sequences have other characters.

Steps to begin.

1 Custom Tokenizer: 
Reasoning: Each of the letters have a different meaning from regular 
Language usage that isn't guranteed to be captured in LLM training. 
Probably more efficient too.
Can skip this if using an LLM because it's build to handle the tokens it was trained on.

2 Custom Embedding:
The meaning of these sequences are different from Language useage.
Piggybacking off of Language embedding of the letter A should not be useful.
What does the relation of A to C to G to U even mean?
And going back to the tokenizer what's a good subsequence?
How doe they affect the larger sequence?
Sequences of subsequences? how will this be captured?
Attention to get the most relevant pieces of the sequence?

Anyway

3 creating the points
What does this mean?
What is our current goal? Sequence -> Set (Class Point)

Should I use an LLM?
No
I will try: 
Graph attention -> 3d Conv -> points
Logically thinking about things I feel this is the way.

