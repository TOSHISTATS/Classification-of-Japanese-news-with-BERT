# Classification of Japanese news with BERT_multi


BERT, or Bidirectional Encoder Representations from Transformers by Google, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing (NLP) tasks.

Our academic paper by Google which describes BERT in detail and provides full results on a number of tasks can be found here: https://arxiv.org/abs/1810.04805.



For this experiment, I use SQuADv1.1data as it is very famous in the field of question and answering.  The details of the experiment is explained in this blog.
https://toshistats.wordpress.com/2019/04/30/bert-performs-very-well-in-japanese-in-our-experiment/




### Evaluation results

eval_accuracy = 0.92424244,
eval_loss = 0.36567232,
global_step = 198,
loss = 0.53717786,


finetuned with data of livedoor news corpus (training 2114 samples, test 529 samples)
