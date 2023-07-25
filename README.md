<h1>Web scraping na página de notícias do TRE-SP</h1>
Código para varredura de todas as notícias da página Comunicação do Tribunal Regional Eleitoral de São Paulo (TRE-SP) de acordo com o período selecionado pelo usuário entre os anos de 2021 e 2023. Futuramente iremos possibilitar a varredura dos outros tribunais da Justiça Eleitoral e anos anteriores a 2021.
</p>
<p>
Link com dados de 2022: https://docs.google.com/spreadsheets/d/1quID78A9Ni5LPzmOnYbOA5U29f0TJ6P_dfUSLcDJ8E0/edit?usp=sharing
</p>
<img src="https://img.shields.io/badge/status-em%20desenvolvimento-green"</>
</p>
<h2>Instalação</h2>

Para rodar este projeto, recomendo instalar a plataforma Anaconda, que facilita o gerenciamento de pacotes e uso de IDEs como o Jupyter Notebook - mas você pode usar a que preferir. Acesse https://www.anaconda.com/ para fazer a instalação. 

Em seguida, abra o prompt do Anaconda, crie um ambiente virtual e instale: 

```
pip install jupyter
pip install selenium
pip install pandas

```

<h2>Funcionamento</h2>

Ao executar o código, o usuário insere a sigla do TRE-SP, o ano e o mês do período do qual deseja extrair as notícias. São extraídas as seguintes informações, salvas em uma planilha ao final da execução:

1. Data e hora de publicação
2. Título e subtítulo (linha fina)
2. Tags utilizadas
4. Tempo de leitura preenchido automaticamente pelo Plone (em segundos)
5. Link 
6. Conteúdo da notícia



