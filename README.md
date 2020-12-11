# NLP
## BERT
Tried Japanese pre-trained model.

### Usage
Follow [this article](https://qiita.com/kenta1984/items/7f3a5d859a15b20657f3) and test BERT.

I use the pre-trained model bert-base-japanese-whole-word-masking made by Tohoku Uni.([Github](https://github.com/cl-tohoku/bert-japanese))

It is already installed `Transformers>=4.0.0`(Reference: [link](https://huggingface.co/transformers/pretrained_models.html), [link2](https://github.com/huggingface/transformers))

#### requirements
- Pytorch: `conda install pytorch`
- Transformers: `conda install -c huggingface transformers>=4.0.0`
- `conda install -c conda-forge ipywidgets`
- Tokenizer: `pip install fugashi ipadic`