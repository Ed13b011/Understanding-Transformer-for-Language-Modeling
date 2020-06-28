# Understanding-of-Transformer-for-Language-Modeling
Understanding of Transformers for Language Modeling in PyTorch

The paper "Attention Is All You Need" introduces a novel architecture called Transformer. As the title indicates, it uses the attention-mechanism. Like LSTM, Transformer is an architecture for transforming one sequence into another one with the help of two parts Encoder and Decoder Model (sequence to sequence model)

Encoder-It accepts a single element of the input sequence at each time step, process it, collects information for that element and propagates it forward.
Decoder- given the entire sentence, it predicts an output at each time step.
