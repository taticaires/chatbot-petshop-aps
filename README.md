# Chatbot PetShop: Atendimento e Gerenciamento de Agendamentos

Projeto acadêmico em grupo desenvolvido para a disciplina de **Atividades Práticas Supervisionadas (APS)**, com orientação da **Professora Rita Cassiano**.

O chatbot utiliza técnicas de Processamento de Linguagem Natural (NLP) e Machine Learning para classificar mensagens em categorias e selecionar respostas. Para solicitações de agendamento, consulta, alteração e cancelamento, utiliza um banco de dados SQLite.

## Integrantes
- Luciene Aparecida Oliveira
- Tatiane Avansi Caires
- Valdeyr Moreira Nicacio

## Funcionalidades
- Classificação de mensagens por categoria com `CountVectorizer` e `MultinomialNB`.
- Seleção de respostas cadastradas em arquivo JSON.
- Consulta de informações sobre serviços, horários, endereço e preços demonstrativos.
- Cadastro, consulta, alteração e cancelamento de agendamentos com SQLite.

## Tecnologias
Python, Pandas, Scikit-learn, JSON e SQLite.

## Arquivos
- `Chatbot_PetShop_APS.ipynb`: notebook principal.
- `treinamento_300_frases.csv`: frases e categorias utilizadas no treinamento.
- `respostas.json`: respostas associadas às categorias.
- `requirements.txt`: bibliotecas necessárias.

O banco `petshop.db` é criado automaticamente na primeira execução, com dados de demonstração. O processo evita inserir novamente os dados iniciais quando o banco já está preenchido.

## Como executar no Google Colab
1. Baixe este repositório ou abra o notebook no Google Colab.
2. Execute as células em ordem.
3. Se solicitado, envie `treinamento_300_frases.csv` e `respostas.json`.
4. Para iniciar a conversa interativa, execute `conversar()` na última seção.

## Observações
Este é um projeto acadêmico e demonstrativo. Nomes, telefones, endereço, preços e agendamentos utilizados nos exemplos são fictícios. O modelo classifica mensagens com base no conjunto de frases fornecido e pode não reconhecer solicitações fora das categorias treinadas.

O notebook foi organizado para facilitar a execução e a apresentação do trabalho. A proposta e os recursos descritos têm como base o projeto acadêmico original desenvolvido pelo grupo.
