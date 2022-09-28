# Formacao-Front-end-Regex

Regular expressions

- Extrair seções específicas de um arquivo de texto.
- Validação de formatação de, por exemplo, e-mail ou telefone.
- Análise de arquivos de texto e extração de dados para, por exemplo, gravar no banco de dados.
- Substituindo os valores de um texto para limpar, reformatar ou alterar o conteúdo.

Existem quantifiers que definem quantas vezes um caractere deve aparecer:
- {1} é um quantifier que significa uma vez.
- * é um quantifier que significa zero, uma ou mais vezes
- . é um meta-char que significa qualquer char.
- Com \ podemos escapar meta-chars, por exemplo \.
- [.-]?- ponto ou hífen zero ou uma vez.

O símbolo + é um outro atalho para definir a quantidade:
- ? -> zero ou uma vez.
- * -> zero ou mais vezes.
- + -> uma ou mais vezes.
- {n} -> exatamente n vezes.
- {n,} -> no mínimo n vezes.
- {n,m} -> no mínimo n vezes, no máximo m vezes.
