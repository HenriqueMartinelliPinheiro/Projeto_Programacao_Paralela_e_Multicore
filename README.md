# Projeto_Programacao_Paralela_e_Multicore
Projeto para a disciplina de Programação Paralela e Multicore do Curso de Bacharelado em Ciência da Computação do IFC Videira

## Problema Proposto
Desenvolver uma aplicação paralela que gerencie a compra de ingressos para grandes eventos internacionais, como shows de artistas famosos ou finais de campeonatos esportivos, onde a demanda é extremamente alta e as filas virtuais se formam rapidamente. A aplicação precisa lidar com milhares de usuários tentando acessar simultaneamente o sistema, implementar filas virtuais eficientes, e distribuir os ingressos de forma justa e rápida, minimizando o tempo de espera e evitando travamentos do sistema.

### Requisitos

**1ª versão:**
 - Solução simples (prova de conceito) utilizando apenas threads
 - Requisitos mínimos:
   - Proposta em formato de relatório contendo um resumo da abordagem e um diagrama exemplificando a solução;
   - Implementação da PoC em uma linguagem de interesse da equipe;
   - Desempenho no uso em larga escala
   - Implementar tanto o produtor quanto o consumidor
   - Avaliar se a solução proposta no PoC atende as necessidades

**2ª versão:**
- Solução utilizando os conceitos de sincronização (cooperação e/ou competição) como tratamento de condição de corrida (race condition) e seção crítica
- Requisitos mínimos:
   - Empacotar os dados no formato JSON;
   - Usar filas para controlar os fluxo de entrada e saída dos dados;
   - Implementar sincronização (cooperação e/ou competição);
   - Tratar condição de corrida e identificar e controlar a seção crítica.

**3ª versão:**
- Solução completa utilizando toda a teoria vista na disciplina, além de ferramentas e bibliotecas
  - Requisitos mínimos:
   - Prever escalabilidade
   - Usar message broker (RabbitMq, Apache Kafka)
   - Usar containers docker. OBS: a orquestração pode ser realizada com docker compose

**Desafios:**
  - Implementar observabilidade (Ex: grafana, logic Monitor)
  - Implementar a solução em Go Lang
