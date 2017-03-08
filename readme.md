This is a tokenizer for processing the software-specific natural language text in Stack Overflow. 
Such text is both social, e.g., people use ungrammatical and informal language in Stack Overflow like what they do in tweets, and domain-specific, e.g., printf() should be recognized as one token rather than 3 tokens printf, '(' and ')'.

This tokenizer is based on a Twitter tokenizer. Acknowledgement goes to Brendan O'Connor, Kevin Gimpel and Daniel Mills, who are the authors of the original Twitter tokenizer. This tokenizer modifies their Twitter one. 
