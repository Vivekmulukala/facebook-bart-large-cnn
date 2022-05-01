# **Facebook bart model (facebook/bart-large-cnn)**

> **link for model: https://huggingface.co/facebook/bart-large-cnn**

### **What i have done:**
1. **First loaded the pretrained model and tried to generate the summary(with pipeline object).**
2. **Later tried to manually tokenize the article and tried to predict the output by directly passing it to the loaded model.**
3. **Then tried to train a custom model from pretrained model with cnn-dailymail dataset(@https://huggingface.co/datasets/cnn_dailymail).**
4. **Due to cuda out of memory issue, unalbe to train the model for atleast an epoch. As the mentioned issue made me constrained for batchsize=1.**

### **Refernces:**
1. **https://huggingface.co/docs/datasets/v1.12.1/load_hub.html --> datasets**

2. **https://huggingface.co/docs/transformers/tasks/summarization -->summarization @ transformers**

3. **https://huggingface.co/datasets/cnn_dailymail --> chosen dataset**

4. **https://huggingface.co/facebook/bart-large-cnn -->chosen model**