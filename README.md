# invokeai-colab

✨ This is a notebook for running an Invoke AI GUI in a free Google Colab GPU runtime. ✨

## Configuring the Notebook
This notebook requires the use of Hugging Face and NGROK tokens.

The Hugging Face token should be supplied where `HF_TOKEN_HERE` is specified.
Information on generating Hugging Face tokens is available [here](https://huggingface.co/docs/hub/security-tokens).
You may need to accept the licenses on the Hugging Face pages of the stable diffusion weights for the tokens to work.

The NGROK token should be supplied where `NGROK_TOKEN_HERE` is specified.
To get an NGROK token, sign up [here](https://dashboard.ngrok.com/signup).

Persistent GDrive storage can be configured by setting the `chosen_colab_path` to `persist_colab_path`. Be warned as Invoke-AI has many dependencies, it uses a lot of storage space.

Custom models can be imported locally or from Hugging Face.
Information on hosting your own models on Hugging Face and installing models into Invoke AI is available at the following URLs:
* https://huggingface.co/docs/transformers/model_sharing
* https://invoke-ai.github.io/InvokeAI/installation/050_INSTALLING_MODELS/

## Usage

1. Click "Run All" in Google Collab or click run on each code block descending.
2. The Invoke AI GUI site is available at the NGROK URL printed in the second to last code block.

The notebook was most recently verified to work with InvokeAI version 2.3.1.
