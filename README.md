# Scraper & Crawler — Books to Scrape

Trabalho de Sistemas de Informação (FEMA): coleta de dados com **Selenium** e **BeautifulSoup** no site
[books.toscrape.com](https://books.toscrape.com), tratamento com **pandas** e análise com **matplotlib**.

| Nome | RA |
|---|---|
| Gabriela Viana Cunha | 2411550012 |
| Kaique Alexandre Souza Kubota | 2411550841 |
| Maria Vitória Alvim Nardotto | 2411550024 |

## Arquivos

| Arquivo | Conteúdo |
|---|---|
| `Projeto_Books_Scraper.ipynb` | Notebook: coleta com paginação, crawling, tratamento, gráficos e conclusões |
| `Projeto_Books_Scraper.html` | Notebook exportado em HTML |
| `livros.csv` | 200 livros coletados e tratados |
| `requirements.txt` | Pacotes Python |

## Como rodar

Requer Python 3.10+ e Google Chrome (o Selenium baixa o driver sozinho).

```bash
pip install -r requirements.txt
```

```bash
jupyter lab
```

Abra o notebook e execute todas as células (cerca de 3 minutos). `HEADLESS = True` roda sem abrir o navegador.
