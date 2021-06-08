# Implementando um Classificador de Spam com Naive Bayes

A partir do Capítulo 16, iniciaremos uma série de Mini-Projetos com um PDF com a Definição do Problema e Scripts para Execução e Compreensão da solução do problema:

O objetivo deste projeto é construir um classificador de Spam usando o
algoritmo de classificação Naive Bayes. Construiremos esse algoritmo a partir do
zero sem usar bibliotecas, o que será muito útil para construção de aplicações
analíticas.
O modelo de documento que usaremos aqui é um modelo de saco de
palavras (bag of words). Usaremos dois tipos de modelo bag of words:

<ul>
  <li>Com base na presença de palavra (se uma palavra aparece no
documento ou não, o que tornará os atributos de entrada binários)</li>
  <li>Com base na frequência de palavras (frequência de ocorrência de palavra
no documento, o que tornará os atributos de entrada contínuos)</li>
</ul>