<!-- <p align="center"><img src = "./logoBot/logo.jpeg" style="border-radius:500px; height:500px; width:500px" /></p> -->
<p align="center"><img src = "https://github.com/danielyudicarvalho/sprint-5/blob/main/assets/logo.jpeg" width="500"></p>
<h1 align="center">Caramelo Bot</h1>

<h3 align="center">
Um chatbot criado por discentes da Universidade Federal do Mato Grosso Do Sul para a ONG Abrigo dos bichos.
</h3>
<p align="center">
<img src = https://img.shields.io/badge/RASA-Chatbot-blueviolet>
<img src = https://img.shields.io/badge/NLP-Machine%20learning-blue>
<img src = https://img.shields.io/badge/SpaCy-PT--BR-red>
<img src = https://img.shields.io/badge/Inteligência_Artificial-Tecnologia-yellow>
<img src = https://img.shields.io/badge/Python-Linguagem%20-brightgreen>
</p>

---

# 📝 Descrição
  * O assistente virtual denominado Caramelo Bot, é capaz de auxiliar a ONG [Abrigo dos Bichos](https://abrigodosbichos.com.br/) no atendimento ao cliente, estando disponível 24 horas, atuando como uma alternativa mais rápida e prática na  solução de dúvidas e em guiar o usuário em procedimentos como adoção, voluntariado, perda de pet ou até mesmo em informar o canal responsável por receber denúncias em casos de maus-tratos.   
---
# 📂 Documentação
 * Documentação do [Projeto](https://drive.google.com/drive/folders/1dRUavT9Ffybw4ubHF2y_UCjrheMY3YB9)
---
# ⚠ Pré-requisitos ⚠
 * Alguns arquivos do bot são apenas mocksups, estes são: `credentials.yml`, `endpoints.yml` e `secrets.py`
  - Em `credentials.yml` troque as informações entre " " de acordo com as credenciais disponibilizadas pelo @botfather!
  - Verify significa o nome do bot e webhook_url onde está hospedado o bot!
``` 
telegram_connector.TelegramInputChannel:
  access_token: "TELEGRAM_TOKEN"
  verify: "abrigo_bot"
  webhook_url: "https://bot-rasa-nome-okteto.cloud.okteto.net/webhooks/telegram/webhook"
``` 
  - Em `endpoints.yml` Troque a url pelo caminho onde está rodando as actions! Caso seja um uso local, usar a url comentada!
``` 
 action_endpoint:
  url: "https://server-bot-rasa-danielyudicarvalho.cloud.okteto.net/webhook"
  #url: http://localhost:5055/webhook
```
 - Em `secrets.py` troque todas as informações entre " " de acordo com suas credenciais.
 ```
# secrets.py
secrets = {
    'CLUSTER': "nome_do_cluster",
    'DB_NAME': "nome do banco",
    'COL_NAME': "nome da collection",
    'WHATSAPP': "numero do whats",
    'BOT_EMAIL': 'email.do.bot.para.enviar.emails',
    'BOT_EMAIL_PASSWORD': 'senhadobot',
    'EMAIL_ABRIGO': 'email.do.abrigo'
}
```
---
# 📌 Funcionalidades
|   Intenções   |   Intenções  |
| ------------- | ------------ |
| faq           | askAction    |
| /start        | ask_disease  |
| goodbye       | affirm       |
| greet         | deny         |
| ask_castration| thank_you    |
| volunteer     | out_of_scope |
| donation      | bot_purpose  |
| adopt         | human_service|

---
# 📺 Tecnologias
 * 🍀 [MongoDB](https://www.mongodb.com/) 
 * 🤖 [Rasa](https://rasa.com/) 
 * 🐍 [Python](https://www.python.org/) 
 * 🚇 [Ngrok](https://ngrok.com/)
 * 🐳 [Docker](https://www.docker.com/) 
 * ⚓ [Kubernetes](https://kubernetes.io/pt-br/)
 * ⚓ [Okteto](https://www.okteto.com/docs/getting-started/)
 * 🐱 [Git](https://git-scm.com/doc) 
 * 🪐 [Jupyter Notebook](https://jupyter.org/) 

---
# 📚 Bibliotecas Utilizadas
 * [bs4](https://pypi.org/project/bs4/)
 * [urllib3](https://pypi.org/project/urllib3/)
 * [numpy](https://numpy.org/)
 * [Spacy](https://spacy.io)
 * [pt_core_news_md](https://spacy.io/models/pt)
 * [pydantic](https://pydantic-docs.helpmanual.io/)
 * [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
 * [pymongo](https://pymongo.readthedocs.io/en/stable/)
 * [pytz](https://pypi.org/project/pytz/)
 * [scikit_learn](https://scikit-learn.org/stable/)
 * [SQLAlchemy](https://www.sqlalchemy.org/)
 * [smtplib](https://docs.python.org/3/library/smtplib.html)

---

# 🐕 Caramelo team 
- 👩‍💻 [Anália Beatriz](https://www.linkedin.com/in/an%C3%A1lia-beatriz-ferreira-913532225/)
- 👨‍💻 [Daniel Yudi Carvalho](https://www.linkedin.com/in/daniel-yudi-carvalho-608365a4/)
- 👨‍💻 [Filipe Camuso Fernandez](https://www.linkedin.com/in/filipe-camuso-3437841a7/)
- 👨‍💻 [João Paulo Wakugawa](https://www.linkedin.com/in/jpwakugawa/)
- 👨‍💻 [Leonardo Felipe Oliveira Freitas](https://www.linkedin.com/in/leonardo-oliveira-freitas/)
---
