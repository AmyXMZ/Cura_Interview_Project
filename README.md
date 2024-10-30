# Cura_Interview_Project ReadME
The overall structure of my solution consists of two parts (named Cure Interview Project Part 1 and Part 2). Please run them in order.

Part 1 contains code that estimates the input answer tokens (average tokens, median tokens, maximum, and minimum tokens), followed by a default GPT-4o mini model trained on the dataset using K-Fold cross-validation for evaluation, with BERTScore and ROUGE-L as metrics. This part serves as the "baseline" model.

Part 2 contains code that fine-tunes the model's parameters, such as max_tokens, temperature, presence_penalty, and top_p. It uses the same evaluation method and metrics as Part 1. At the beginning of Part 2, some input (rubric) modifications were tested to observe any changes in model performance. Each code block includes comments explaining its purpose.

At the end of Part 2, there are two markdown sections explaining the rationale behind my code, with a detailed analysis of the evaluation results. The second markdown section discusses "creative ways" I thought could be used to evaluate out-of-sample or unseen data.

This project was completed on Jupyter notebook. It is advised to download and use Jupyter notebook to run the code. Thank you!
