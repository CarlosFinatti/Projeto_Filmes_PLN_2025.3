# Projeto_Filmes_PLN_2025.3
Projeto sobre processamento de linguagem natural, uso de LLMs e APIs.

O projeto consiste em receber uma sinopse do usuário, buscando um filme, usar técnicas de extração de palavras-chave e sumarização usando LangChain para fornecer uma sinopse filtrada para o LLM (gemini-2.0-flash-lite). Após isso, o LLM fornecerá, então, prováveis gêneros cinematográficos. Com esses gêneros, será aplicado uma transcrição baseado no padrão da API do TMDB (The Movie Database) que então será utilizado para filtrar filmes dos últimos 5 anos até a execução do código e gerar uma lista com esses filmes compartilhando esses gêneros.
