# ehartford/dolphin-2.1-mistral-7b-v0.1 Cog model

This is an implementation of the [ehartford/dolphin-2.1-mistral-7b](https://huggingface.co/ehartford/dolphin-2.1-mistral-7b) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    og predict -i prompt="Explain in a short paragraph quantu field theory to a high school student"
