MAPA – Programação de Sistemas I: Sistema de Cadastro e Cobrança para Área Infantil em Shopping

Autor: Michael Ewerton Oliveira Disciplina: Programação de Sistemas I Instituição: UniCesumar

Descrição do Projeto

Este projeto consistiu na criação de um sistema em Java Swing para o controle de uma nova atração infantil em um shopping, simulando um cenário real de cadastro e cobrança por tempo de uso de brinquedos. A proposta exigiu o uso pleno da Programação Orientada a Objetos com foco em encapsulamento, validações e separação entre interface gráfica e lógica de negócio.

Funcionalidades Implementadas

Tela 1 – Cadastro do Responsável Campos: nome, CPF, telefone, e-mail, endereço e idade Validação: idade igual ou superior a 18

Tela 2 – Cadastro da Criança Campos: nome, idade, sexo e associação ao responsável Validação: idade igual ou inferior a 10

Tela 3 – Estadia e Cálculo da Cobrança Campos: tempo de estadia e exibição do resumo da cobrança Lógica de desconto aplicada automaticamente:

Até 20 min: R$1,50/min sem desconto

Acima de 20 min: 5%

Acima de 40 min: 10%

Acima de 60 min: 15%

Classes e Estrutura O.O.

Responsavel: atributos e métodos de validação da idade

Crianca: vinculação ao responsável + validação de idade

Estadia: cálculo de valor + aplicação de regras de desconto

Interface Gráfica (Java Swing)

Navegação sequencial entre telas

Campos e botões responsivos com validações de entrada

Transferência dos objetos entre janelas via parâmetros

Avaliação

Nota máxima (3,00/3,00) Feedback do professor: "Mais uma etapa do seu aprendizado em curso. O conhecimento é a chave para o mundo de oportunidade."
