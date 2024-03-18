# Scraping com Selenium

## Propósito

Este projeto é capaz de fazer scraping de dados usando o Selenium.

## Como Executar localmente

### Pré-requisitos
- Python 3.x
- Virtual Environment (virtualenv)
- Conexão com um banco mongoDB (pode se usar o banco dockerizado disponível acima, consultar as credencias no arquivo docker-compose.yml)
- Chrome atualizado

### Instruções

1. **Instalação do Python**:
   - Faça o download e instale o Python [aqui](https://www.python.org/downloads/).

2. **Criação do Ambiente Virtual**:
   - Execute `python -m venv venv` para criar um ambiente virtual.
   - Ative o ambiente virtual: 
     - Windows: `venv\Scripts\activate`
     - Linux/MacOS: `source venv/bin/activate`

3. **Instalação das Dependências**:
   - Execute `pip install -r requirements.txt`
  
4. **Rodando o projeto**
   - Certifique-se que o .env está com as credencias certas para o seu banco.
   - Uma vez no diretório raiz do projeto, execute o seguinte comando:
       - pyhton3 main.py

---

Este README oferece um guia básico para iniciar o projeto. Para mais detalhes, consulte o desenvolvedor:

- Albert Hanchuck: +55 35 99953 9008
