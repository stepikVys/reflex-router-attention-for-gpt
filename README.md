
# nanoGPT

The main work is presented in the [notebook](https://colab.research.google.com/drive/1of2F0kUKYTT3X20Nbt-ql2mUf2I-v-Au?usp=sharing). 

The code is borrowed from A. Karpathy’s repository.

## install

```
pip install torch numpy transformers datasets tiktoken wandb tqdm
```

Dependencies:

- [pytorch](https://pytorch.org) <3
- [numpy](https://numpy.org/install/) <3
-  `transformers` for huggingface transformers <3 (to load GPT-2 checkpoints)
-  `datasets` for huggingface datasets <3 (if you want to download + preprocess OpenWebText)
-  `tiktoken` for OpenAI's fast BPE code <3
-  `wandb` for optional logging <3
-  `tqdm` for progress bars <3


For more questions/discussions s.vysotskiy@edu.centraluniversity.ru, @stepan_vysotsky on telegram
