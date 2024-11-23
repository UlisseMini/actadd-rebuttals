# actadd-rebuttals

Setup instructions:

1. Rent a h100 instance from vast.ai with the `pytorch/pytorch:2.5.1-cuda12.4-cudnn9-runtime` docker image.
2. Connect with vscode ssh
3. Clone this repo, open its dir in vscode
4. Put OPENAI_API_KEY in `.env` like so: `export OPENAI_API_KEY="sk-..."`
5. Run `main.ipynb` it will install deps and do everything
