# Roadmap: Engenharia de Inteligência Artificial / MLOps #
Este roadmap detalha o plano estratégico de 90 dias para a transição de carreira para a área de IA e MLOps, com foco em automação de pipelines, versionamento de modelos e infraestrutura escalável.

## Informações Gerais

### Carreira Escolhida: Engenharia de Inteligência Artificial / MLOps 


Horas Disponíveis: 20h por semana 


Nível de Experiência: Iniciante (nunca trabalhou em tech; fez cursos em 2001; usa Linux em tempo integral; escreve shell scripts) 


Objetivo: Conseguir o primeiro emprego (preferência por vagas remotas) 

🧩 Visão do Dia a Dia
Preparar, limpar e versionar conjuntos de dados para treino e validação.

Projetar, implementar e automatizar pipelines de treinamento e inferência.

Empacotar modelos (containerização) e automatizar deploys em ambientes de teste e produção.

Monitorar performance de modelos em produção, detectar deriva e configurar alertas.

Colaborar com times de dados e desenvolvimento para integrar modelos em aplicações e garantir confiabilidade.

### Mapa de Skills
Core Skills (Essenciais)
Python para ML (manipulação de dados, scripts, pacotes: pandas, numpy).

Conceitos de ML e modelagem (treino, validação, overfitting, métricas).

MLOps básico (pipelines, versionamento de modelos/dados, CI/CD para modelos).

Nice-to-Have (Complementares)
Docker e deploy de modelos (containers, imagens, registries).

Monitoramento e rastreamento de experimentos (MLflow, Evidently, Prometheus/Grafana).

Ferramentas e Tecnologias
Git / GitHub.

Linux / Bash.

Python / scikit-learn / PyTorch ou TensorFlow.

Docker.

MLflow.

Cloud (AWS/GCP/Azure) — escolha uma para foco.

## Roadmap de 90 Dias (20h/semana)
### Mês 1 - Fundamentos

Semana 1-2: Consolidar Python: listas, dicionários, funções, módulos, virtualenv/venv. Praticar manipulação de dados com pandas e visualização básica (matplotlib/seaborn).
+1


Semana 3-4: Estudar fundamentos de ML com scikit-learn: regressão, classificação, validação cruzada, métricas. Git/GitHub: fluxo de branches, commits, PRs, README e boas práticas de versionamento.
+1

Mês 2 - Prática

Semana 5-6: Implementar pipelines de treino simples: carregar dados, pré-processar, treinar, salvar modelo. Introdução a PyTorch ou TensorFlow: treinar um modelo simples e salvar checkpoints.


Semana 7-8: Docker: criar Dockerfile para ambiente de inferência; rodar modelo em container local. CI/CD básico com GitHub Actions: automatizar testes e build da imagem Docker ao push.
+1

Mês 3 - Portfólio e Preparação

Semana 9-10: MLflow: rastrear experimentos, registrar modelos e comparar runs. Deploy de modelo em ambiente de teste (container em VM ou serviço cloud gratuito); criar endpoint simples.
+1


Semana 11-12: Projeto final: integrar código, Docker, CI/CD e MLflow; escrever documentação e instruções de reprodução. Preparação para entrevistas: revisar conceitos, montar respostas STAR, publicar portfólio no GitHub.
+1

🚀 Projeto de Portfólio

Projeto: Sistema de inferência MLOps para classificação de texto (end-to-end).


O que fazer: Construir uma pipeline completa que coleta/usa um dataset de texto, treina um modelo de classificação, registra experimentos com MLflow, empacota o modelo em Docker, automatiza build com GitHub Actions e expõe um endpoint de inferência simples (ex.: Flask/FastAPI).

Entregáveis:

Repositório GitHub com código e histórico de commits.

GitHub Actions configurado para testes, build e push de imagem Docker.

Dockerfile e instruções para rodar localmente.

Experimentos e modelos registrados no MLflow.

README com arquitetura, instruções de deploy e exemplos de uso.

💬 Roteiro de Entrevistas

Projeto Técnico: Use o método STAR (Situação, Tarefa, Ação, Resultado).
+1


Versionamento: Explique versionamento de datasets, hashes e ferramentas como MLflow ou DVC.


Monitoramento: Liste métricas de drift de dados, performance e métricas de qualidade (accuracy, F1).


CI/CD para Modelos: Descreva etapas de testes unitários, treino automatizado e build de imagem.


Motivação: Conecte automação e escalabilidade com sua experiência prévia em Linux e scripts.

🎓 Trilha DIO Recomendada

Trilha: MLOps / Engenharia de Machine Learning.


Por que: Oferece módulos práticos de pipeline, deploy e monitoramento com projetos guiados.

Lembre-se: O mais importante é a constância, não a velocidade. Comece pela Semana 1 e vá no seu ritmo.
