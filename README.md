# Classification of Japanese news with BERT_multi


BERT, or Bidirectional Encoder Representations from Transformers by Google, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing (NLP) tasks.

Our academic paper by Google which describes BERT in detail and provides full results on a number of tasks can be found here: https://arxiv.org/abs/1810.04805.

I write the article of BERT, which a new natural language model, again because it works so well in question and answering task. In my last article, I explained how BERT works.

For this experiment, I use SQuADv1.1data as it is very famous in the field of question and answering.  The details of the experiment is explained in this blog.



### Evaluation results

eval_accuracy = 0.92424244,
eval_loss = 0.36567232,
global_step = 198,
loss = 0.53717786,


finetuned with data of livedoor news corpus (training 2114 samples, test 529 samples)
