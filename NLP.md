## Older

* Neural networks in machine translation:
  https://research.googleblog.com/2016/09/a-neural-network-for-machine.html

* A survey of cross-lingual embedding models:
  http://sebastianruder.com/cross-lingual-embeddings/index.html

* Active research directions in NLP:
  https://docs.google.com/presentation/d/1O-Ics69y445aWuxQ_VW6SDvKT9BGl3ZXLLZDG9tUiUY/edit#slide=id.p

## 20.12.2016

* History of developing neural translation in Google:
  http://www.nytimes.com/2016/12/14/magazine/the-great-ai-awakening.html

* Good article about AI hype:
  https://medium.com/the-mission/rocket-ai-2016s-most-notorious-ai-launch-and-the-problem-with-ai-hype-d7908013f8c9#.9u1wjqv3w

* Awesome NIPS demo of automatic music generation
  https://magenta.tensorflow.org/2016/12/16/nips-demo/

* Useful NLP dataset from Microsoft
  http://www.msmarco.org/

## 16.01.2016

Wrap ups from DeepMind and Google Brain teams, very good summary of latest developments in Machine Learning:
- https://deepmind.com/blog/deepmind-round-up-2016/
- https://research.googleblog.com/2017/01/the-google-brain-team-looking-back-on.html

## 30.04.2017

- [A Structured Self-attentive Sentence Embedding](https://arxiv.org/abs/1703.03130):
This paper proposes a new model for extracting an interpretable sentence embedding by introducing self-attention. Instead of using a vector, the authors use a 2-D matrix to represent the embedding, with each row of the matrix attending on a different part of the sentence

- https://github.com/facebookresearch/fastText:
Word vectors for 90 languages trained on Wikipedia using fastText using the skip-gram model. Could be a good addition to any multilingual NLP pipeline.

- [Unsupervised sentiment neuron](https://blog.openai.com/unsupervised-sentiment-neuron/):
A team at OpenAI trained a large character prediction model on Amazon Reviews and discovered that a single neuron contains almost all of the sentiment signal.

- [Natural Language Processing with Deep Learning (lectures)](https://www.youtube.com/watch?list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6&v=OQQ-W_63UgQ):
Stanford’s “Natural Language Processing with Deep Learning” lectures video are now freely available on YouTube, covering everything from word vectors to Question Answering models.

## 06.05.2017

- [Learning to Skim Text](https://arxiv.org/abs/1704.06877):
An approach of reading text while skipping irrelevant information if needed. The underlying model is a recurrent network that learns how far to jump after reading a few words of the input text. Employs a policy gradient method to train the model to make discrete jumping decisions.

## 10.06.2017

- [ParlAI](https://code.facebook.com/posts/266433647155520/parlai-a-new-software-platform-for-dialog-research) An open source platform for training and testing dialog models across multiple tasks at once. Researchers can submit new tasks and training algorithms to a single, shared repository.
