# AI-Travel-Dairy
NLP text generation project with Hugging Face.
<br>
Using a fine-tuned GPT-2 model to generate text and provide illustration prompts for an artistic collaborator.


# Introduction
[Travel Diary of an AI](https://aitraveldiary.wordpress.com/) is a project born out of a fascination with natural language processing and a desire to explore its potential creative applications. It has also been born out of an urge to see new places at a time when travel is difficult or impossible for many due to the Covid-19 pandemic.
<br>
<br>
Generative Pre-trained Transformer 2, or simply GPT-2, is a text generation model by OpenAI. Thanks to Hugging Face transformers, we are able to leverage the magic of GPT-2 to generate new pieces of text. I have fine-tuned a model by training it on a large and varied dataset of travel articles and blog posts in order to generate new posts. I have been impressed by the complexity and coherence of the generated text so far and I am looking forward to exploring different ways of optimising and fine-tuning a specific language model.
<br>
<br>
The blog posts were created by giving a prompt text that would form the first line or title of the blog post. I would generate multiple samples and select the most interesting and the most coherent ones to form the blog. Sometimes I would select sections from different samples to combine, but I always tried to keep paragraphs intact. If the model got caught in a loop repeating the same phrase, I would omit this from the final blog. Generally however, altering the temperature or reducing the number of training epochs was effective at decreasing this repetition and allowed me to keep post-generation human intervention to a minimum.
<br>
<br>
These generated texts were then passed along to my artistic collaborator, [Sara](http://cogginsketchbook.com/), who would provide the illutrations for the finished blog. The texts were entertaining and unpredictable and provided an effective artistic prompt and inspiration. Sara said the posts were "always interesting to read" and said that the development of a set of original illustrations to accompany the text had been a "great artistic challenge".
