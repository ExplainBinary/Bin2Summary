### Bin2Summary  

This is the official repository for Bin2Summary, which is a binary analysis tool for PE files. We will actively update it.  

#### Requirements:  
Python >= 3.6  
Tensorflow >= 2.1.0  
gensim >= 4.0.1  

#### Run the Tool  

```
python model_test.py --Mode test
```

- To test the pre-trained seq2seq model with the given samples in the test set (i.e., Cygwin packages).

```
python model_test.py --Mode case
```

- (Optional) To test the pre-trained seq2seq model with the given malware samples (i.e., MyDoom and WannaCry).


#### FAQ  
1. Where are the results?

The results are save in the current directory as ".result" file after running the tool.

2. Do we need GPU?

It is not necessary to use GPU, but using the GPU (with tensorflow-gpu) can significantly accelerate the prediction.

<!--
**ExplainBinary/ExplainBinary** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
