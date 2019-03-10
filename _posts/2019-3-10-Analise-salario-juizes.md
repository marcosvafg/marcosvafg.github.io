---
layout: post
title: Analisando o salários dos juízes brasileiros
---
Conforme determinação do Conselho Nacional de Justiça - CNJ ([Portaria n. 63, de 17 de agosto de 2017](http://www.cnj.jus.br/busca-atos-adm?documento=3352)) todos os 90 tribunais brasileiros devem disponibilizar as informações de remuneração dos seus magistrados, em cumprimento à lei de Acesso à Informação. Para padronizar a divulgação desses dados o CNJ criou uma planilha Excel padrão, que deve ser preenchida pelos tribunais, e passou a disponibilizar todas as planilhas em seu site ([Remuneraçao dos Magistrados](http://www.cnj.jus.br/transparencia/remuneracao-dos-magistrados)).

Como todas as planilhas são, supostamente, iguais, criei um conjunto de instruções Python para abrir e importar uma planilha, e analisar os dados contidos nela. Todo o código está disponível em um **Jupyter Notebook** que também serve como um tutorial introdutório ao uso da biblioteca **pandas** e à análise de dados com Python. Como exemplo usei os dados disponibilizados pelo Tribunal de Justiça do Distrito Federal e Territórios - TJDFT, com base na planilha baixada do site do CNJ no dia 07/12/2017.

Usando o notebook como exemplo e a planilha de outro tibunal, qualquer pessoa deve conseguir realizar as mesmas análises, ou até mesmo expandir o trabalho realizado aqui. Obviamente algum tribunal específico pode descumprir a determinação do CNJ e acabar por disponibilizar seus dados em um formato diferente da planilha padrão. Se isso acontecer, mudanças deverão ser realizadas no código, principalmente na parte intitulada **Importando os dados**. Mas nada que seja impossível de fazer.

Te convido a estudar, entender, usar e modificar o código disponibilizado.

[Salários dos Juízes do TJDFT - 12/2017](https://github.com/marcosvafg/salario_juizes/blob/master/Salarios_Juizes_TJDFT_122017.ipynb)

**Bons códigos!**
   
