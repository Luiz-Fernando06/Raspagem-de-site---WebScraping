# Raspagem de site - WebScraping
📚 Raspador de Livros

Este projeto é um web scraper que coleta informações de livros no site Books to Scrape
 e gera uma tabela em CSV com:

📖 Título do livro

💲 Preço

✅ Disponibilidade

O programa foi feito em Python, com uma interface gráfica simples em Tkinter, para que qualquer pessoa consiga rodar com apenas um clique.

⚙️ Como funciona

Faz o rastreamento das 50 páginas do site.

Extrai título, preço e disponibilidade de cada livro.

Armazena tudo em uma planilha .csv chamada Tabela_de_livros.csv.

Mostra uma mensagem de sucesso indicando onde o arquivo foi salvo.

📦 Tecnologias usadas

Requests
 → Requisições HTTP

BeautifulSoup
 → Extração de dados do HTML

Pandas
 → Manipulação de dados e geração de CSV

Tkinter
 → Interface gráfica

 🎯 Objetivo

Projeto feito para treino de raspagem de dados (web scraping) e entrega em formato executável para cliente.

PyInstaller
 → Transformar o script em .exe
