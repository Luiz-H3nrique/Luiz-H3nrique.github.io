---
title: Formação SRE - Alura
author: Luiz Henrique
date: 2023-06-19 14:10:00 +0800
categories: [SRE]
tags: [SRE]
--- 

Durante a minha formação como SRE na Alura, tive a oportunidade de desenvolver um projeto prático que envolveu a implementação de logs e tracer em uma API desenvolvida em Spring Boot. Neste post, vou compartilhar os detalhes desse projeto e como essas ferramentas foram aplicadas para melhorar a observabilidade e o monitoramento da nossa aplicação.

## Contexto do Projeto
Para o projeto, foi Disponibilizado uma API  desenvolvida  ultilizando o framework Spring Boot. O objetivo era implematr a  observabilidade e obter o desempenho e os possíveis gargalos do sistema.


![Desktop View](/assets/img/post/Arquitetura-forma%C3%A7%C3%A3o-SRE.png ){: .normal }

## Prometheus
Para a coleta de Metricas foi ulilizado o  Prometheus que  é um sistema de monitoramento de código aberto que permite a coleta e a visualização de métricas de serviços em tempo real. Ele é altamente escalável e possui uma arquitetura flexível que permite a integração com outras ferramentas.

## Grafana
Para a visualização das metricas coletada foi ultilizado grafana que permite a criação de painéis interativos e personalizados para monitorar e analisar métricas. Ele é altamente configurável e pode ser integrado com diversas fontes de dados, incluindo o Prometheus.
![Desktop View](/assets/img/post/grafana.jpeg){: .normal }
## Grafana Loki 
O Grafana Loki é uma ferramenta de log que permite a coleta, a indexação e a pesquisa de logs em escala. Ele é altamente escalável e pode ser integrado com outros sistemas de monitoramento, como o Prometheus.

### Jaeger 

O Jaeger é uma ferramenta de rastreamento distribuído que permite a visualização e a análise dos fluxos de operações em sistemas distribuídos.
![Desktop View](/assets/img/post/jaeger.jpeg){: .normal }
Essas ferramentas são apenas algumas das muitas que os SREs utilizam para monitorar, gerenciar e otimizar serviços digitais. Cada uma delas tem sua própria finalidade e pode ser combinada com outras para criar soluções personalizadas de acordo com as necessidades de cada projeto.

Durante a Formação SRE da Alura, pude adquirir conhecimentos práticos e aplicar essas ferramentas em projetos reais, o que fortaleceu minha habilidade como profissional de SRE. Estou entusiasmado para continuar explorando e aprimorando meu conhecimento nessas tecnologias, a fim de oferecer soluções eficientes e confiáveis para os serviços digitais que gerencio.