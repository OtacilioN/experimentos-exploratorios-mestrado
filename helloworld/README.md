Projeto Helloworld — autenticação Hugging Face via .env

1. Gerar token

   - Vá para https://huggingface.co/settings/tokens e gere um token com permissão 'read'.

2. Usar o template

   - Copie `env.template` para `.env` e preencha HF_TOKEN:
     cp env.template .env
     # abra .env e adicione o token: HF_TOKEN=seu_token_aqui

3. Executar o notebook
   - Instale dependências: pip install python-dotenv huggingface_hub datasets
   - Abra e execute `helloworld.ipynb`.
