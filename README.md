# Supermarket Price Scraper

Este projeto automatiza a coleta de preços de produtos em diferentes supermercados online utilizando Selenium e Python. O objetivo é facilitar a comparação de preços para encontrar as melhores ofertas.

## Tecnologias Utilizadas

- Python 3
- Selenium WebDriver
- Pandas

## Estrutura do Projeto

```
Supermarket-Scraper/
│-- app.py  # Script principal
│-- requirements.txt        # Dependências do projeto
│-- README.md               # Documentação do projeto
│-- .gitignore              # Arquivos ignorados pelo Git
```

## Requisitos

Antes de iniciar, instale os seguintes requisitos:

- Python 3.11.1 instalado
- Google Chrome instalado
- ChromeDriver compatível com a versão do seu Chrome
- Biblioteca Selenium
- Biblioteca Pandas
- Biblioteca Virtualenv

## Instalação

1. Clone o repositório:

```sh
git clone <URL_DO_REPOSITORIO>
cd webscraper-precos-supermercados
```

2. Crie e ative um ambiente virtual:

```sh
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Instale as dependências:

```sh
pip install -r requirements.txt
```

4. Certifique-se de configurar corretamente o caminho do ChromeDriver no script.

## Uso

1. Modifique a lista de supermercados e produtos no script `app.py`.
2. Execute o script:

```sh
python app.py
```

3. Os dados coletados serão armazenados e exibidos no terminal.

## Contribuição

Se desejar contribuir com melhorias, siga os passos:

1. Crie um fork do repositório
2. Crie um branch para suas mudanças: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m "Minha contribuição"`
4. Envie para o repositório remoto: `git push origin minha-feature`
5. Abra um Pull Request no GitHub
