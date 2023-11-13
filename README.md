# Coding-Assignment-Data-Bias
This project examines and investigates a dataset of internet comments and their scores, then formulating queries using the Perspective API client to score the toxicity of each comment.

Hypothesis: Perspective will make more mistakes in trash talk and slang indicating it may not be toxic.

Full Result:
Comment: You aint all that., Toxicity Score: 0.02449606, Label: Non-Toxic
Comment: It looks good on you, but I don't like it., Toxicity Score: 0.11057663, Label: Non-Toxic
Comment: You're an idiot., Toxicity Score: 0.9288007, Label: Toxic
Comment: you just a punk., Toxicity Score: 0.46982017, Label: Non-Toxic
Comment: You not scary., Toxicity Score: 0.035220183, Label: Non-Toxic
Comment: that is crazy., Toxicity Score: 0.2854733, Label: Non-Toxic
Comment: I hate your hair, Toxicity Score: 0.681338, Label: Toxic
Comment: Get good kid., Toxicity Score: 0.067380086, Label: Non-Toxic
Comment: Love this movie., Toxicity Score: 0.01834645, Label: Non-Toxic
Comment: Who... cares., Toxicity Score: 0.10045706, Label: Non-Toxic
Comment: You suck at this game get good., Toxicity Score: 0.7675452, Label: Toxic

I have learned about the observation and studying you can conduct with Perspective API, which would classify whether each comment is toxic or non-toxic. Through this analysis, I formed a hypothesis that states, “ Perspective will make more mistakes on trash talk and slang on thinking it may not be toxic.” With this hypothesis in mind, I noticed that it was true by using slang and gamer lingo, which the Perspective API reported were non-toxic comments. Therefore, I believe that bias may exist in the model.
	From the data collected from the data frame and comments, there can be subjectivity and cultural bias. What is considered toxic or offensive can vary depending on communities, cultures, and regions. The model might not accurately captures these context, leading to biased assessments. The result of this could be that the Perspective API only looks into sentences that have negative words in them.
