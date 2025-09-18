# 📚 Raspador de Livros


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

 ▶️ Como rodar o projeto
1. Clone o repositório
git clone https://github.com/seu-usuario/Raspagem-de-site--WebScraping.git
cd Raspagem-de-site--WebScraping

1. Instale as dependências
pip install requests beautifulsoup4 pandas tk pyinstaller

2. Rode direto pelo Python
python app.py

3. (Opcional) Gerar um .exe

Para entregar o programa sem precisar instalar Python:

python -m PyInstaller --onefile --noconsole app.py


O executável será criado na pasta:

dist/app.exe

📂 Saída

O programa gera automaticamente um arquivo:

Tabela_de_livros.csv
