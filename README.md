# xresnet-self-attn
Who said that Deep Learning models are a black box? Here we train an xResNet model with self-attention, inspired by  https://github.com/sdoria/SimpleSelfAttention.
As a result, we get to interpret the model to some extent by analysing the attention map for each input image. In other words, we get to see where the model is 'looking at' while making a prediction!

In the above notebook, we observe how models behave when classifying the suits of poker cards. The model cleverly looks at the suits at the four corners and in the middle of the cards.
