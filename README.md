# Transpoemer
## Poetry generation using Transformer-based architectures 

This repo holds my experiments on using pre-trained Transformer-based architectures for Poetry generation. All of the experiments are done on *Arabic* Poetry.

# Poetry Generation
I follow a simple approach for poetry generation. Conditioned on a verse, the model should generate the next verse. Then, this generated verse is used as an input to the model and so on. There are more complicated approaches that would take into account an extended left context, but I leave such approaches for later.

|  **timestep** | **input**  | **output**  |
|---|---|---|
| 1  | فيرجع الصدى  |  كأنه النشيج|
|  2 |  كأنه النشيج  |  وهو المراد |
|  3 |  وهو المراد |  ... |
|  4 |  .. |  ... |



# [BERT](https://github.com/google-research/bert)
BERT's original uses do not include language generation. Actually, its Masked Language Modelling objective makes it very difficult to sample from it. Anyway, I thought it would be a worthy experiment to generate 



# GPT-2
TODO



