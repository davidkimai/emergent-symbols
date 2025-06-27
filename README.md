# [Emergent Symbols](https://openreview.net/forum?id=y1SnRPDWx4)
Building on the 2025 ICLR paper by Yang et al
> TL;DR: A three-stage architecture is identified that supports abstract reasoning in LLMs via a set of emergent symbol-processing mechanisms


## Abstract:
Many recent studies have found evidence for emergent reasoning capabilities in large language models (LLMs), but debate persists concerning the robustness of these capabilities, and the extent to which they depend on structured reasoning mechanisms. To shed light on these issues, we study the internal mechanisms that support abstract reasoning in LLMs. We identify an emergent symbolic architecture that implements abstract reasoning via a series of three computations. In early layers, symbol abstraction heads convert input tokens to abstract variables based on the relations between those tokens. In intermediate layers, symbolic induction heads perform sequence induction over these abstract variables. Finally, in later layers, retrieval heads predict the next token by retrieving the value associated with the predicted abstract variable. These results point toward a resolution of the longstanding debate between symbolic and neural network approaches, suggesting that emergent reasoning in neural networks depends on the emergence of symbolic mechanisms.


![Screenshot 2025-06-27 at 12 01 33 PM](https://github.com/user-attachments/assets/cd223f7e-d0bf-4a2d-8f58-c5875aee9fa5)
