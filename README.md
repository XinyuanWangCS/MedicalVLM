# Read Me
1. I upload the data directory and the .ipynb file.
2. For task2 and task3, since I don't know the ground-truth label for these images, I take the classification result of the original model using generate_chexpert_class_prompts as ground-truth and then analyse the results.
3. For task3, I change the text model's tokenizer and model to "dmis-lab/biobert-v1.1"'s tokenizer and model, then do the same classification analysis as task2.