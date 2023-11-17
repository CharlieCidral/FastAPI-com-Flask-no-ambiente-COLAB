# [Projeto API Flask no Colab](https://colab.research.google.com/drive/1D1nxlZY7VuYu0VJ-_xHNB7GaKh56MWTh?usp=sharing)
Este projeto é um exemplo de como criar uma API usando o framework Flask, hospedada na plataforma Google Colab. O objetivo principal do projeto é ler e retornar dados de uma planilha no formato JSON.

## Recursos
- API Flask: A API foi desenvolvida usando o popular framework Flask para Python. Ele é leve, fácil de usar e muito flexível, tornando-o ideal para este projeto.

- Google Colab: O Google Colab é uma plataforma de desenvolvimento colaborativo baseada em nuvem que permite escrever e executar código Python no navegador. Ele também oferece recursos de computação gratuitos, tornando-o perfeito para projetos de aprendizado de máquina e ciência de dados.

- Leitura de Planilhas: A API é capaz de ler dados de uma planilha no formato CSV e retorná-los como JSON. Isso pode ser útil para uma variedade de aplicações, desde visualização de dados até aprendizado de máquina.

### Uso
Para usar a API, você pode enviar uma solicitação GET para o endpoint /home. Isso retornará todos os dados da planilha como JSON. Também precisará de uma conta [ngrok](https://ngrok.com/).

### '/home'
![home](https://github.com/CharlieCidral/FastAPI-com-Flask-no-ambiente-COLAB/assets/69029099/047c0472-2c9e-4a4c-8f1f-3db1feca6560)

Cada coluna da planilha também tem seu próprio endpoint, que pode ser acessado enviando uma solicitação GET para /{nome_da_coluna}. Isso retornará todos os dados daquela coluna como uma lista.

### '/city'
![city](https://github.com/CharlieCidral/FastAPI-com-Flask-no-ambiente-COLAB/assets/69029099/e9746022-dadb-4998-bcea-ffb72ca967b9)
