# Análise de Banco de Dados de Livros com SQL

## 📄 Descrição
Este projeto utiliza SQL para realizar uma análise aprofundada em um banco de dados de uma plataforma de livros. O objetivo é extrair insights acionáveis sobre livros, autores, editoras e o comportamento de avaliação dos usuários.

---

## 🎯 Objetivos da Análise
1.  Contar o número de livros lançados após o ano 2000.
2.  Calcular o número de avaliações e a classificação média para cada livro.
3.  Identificar a editora com o maior número de livros com mais de 50 páginas.
4.  Encontrar o autor com a maior média de classificação, considerando apenas livros com 50 ou mais avaliações.
5.  Calcular a média de avaliações de usuários que avaliaram mais de 50 livros.

---

## 🛠️ Tecnologias Utilizadas
- **SQL (PostgreSQL):** Linguagem principal para todas as consultas e extração de dados.
- **Python:** Utilizado como ambiente para executar as queries.
- **Pandas:** Para executar as consultas via SQLAlchemy e exibir os resultados de forma organizada.
- **SQLAlchemy:** Para criar a conexão com o banco de dados PostgreSQL.

---

## 🔬 Estrutura da Análise
A análise foi conduzida através de uma série de consultas SQL, cada uma projetada para responder a um dos objetivos listados. As técnicas incluem:
- `COUNT` e `AVG` com `GROUP BY`
- `JOIN` entre múltiplas tabelas (`books`, `authors`, `publishers`, `ratings`)
- `WHERE` e `HAVING` para filtragem de dados
- `ORDER BY` e `LIMIT` para ranqueamento
- Subqueries e CTEs (`WITH`) para consultas complexas

---

## 📊 Principais Insights
- **Tendência de Publicação:** 819 livros no banco de dados foram publicados após 01/01/2000.
- **Editora de Destaque:** A `Penguin Books` é a editora com mais livros de conteúdo substancial (mais de 50 páginas).
- **Autor Mais Bem Avaliado:** Entre os autores com obras populares, `J.K. Rowling/Mary GrandPré` se destaca com a maior média de avaliação.
