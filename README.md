# Coding-Assignment-Data-Bias
This project examines and investigates a dataset of internet comments and their scores, then formulates queries using the Perspective API client to score the toxicity of each comment.

Hypothesis: Perspective will make more mistakes in trash talk and slang indicating it may not be toxic.


I have learned about the observation and studying you can conduct with Perspective API, which would classify whether each comment is toxic or non-toxic. Through this analysis, I formed a hypothesis that states, “ Perspective will make more mistakes on trash talk and slang on thinking it may not be toxic.” With this hypothesis in mind, I noticed that it was true by using slang and gamer lingo, which the Perspective API reported were non-toxic comments. Therefore, I believe that bias may exist in the model.
There may be subjectivity and cultural bias in the data collected from the data frame and comments. What is toxic or offensive varies according to community, culture, and region. The model may not capture these contexts accurately, resulting in biased assessments. The result of this could be that the Perspective API only looks into sentences that have negative words in them.
