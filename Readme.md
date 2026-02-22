# IA Mentor de Carreira #
 
## Objetivo do Projeto ##
Este repositório documenta um desafio prático de mentoria de carreira utilizando Inteligência Artificial Generativa. O foco foi transformar prompts estruturados em agentes especializados para identificar perfis profissionais e traçar roteiros técnicos personalizados. Como prova de conceito, utilizei o fluxo para planejar minha transição para DevOps Engineer, aproveitando uma base sólida de mais de 20 anos em sistemas Linux e Shell Script.

#### Metodologia e Uso de Agentes ####
O projeto baseia-se em uma arquitetura de dois agentes principais:


__Agent 1 (Entrevistador de Carreira):__ Especializado em conduzir entrevistas estruturadas de 7 perguntas para extrair motivações e competências. Ele utiliza uma matriz de decisão interna para sugerir as 3 carreiras com maior afinidade.
+1


__Agent 2 (Planejador de Roadmaps):__ Especializado em criar planos de 90 dias, focando em core skills, ferramentas e projetos de portfólio. O planejamento é ajustado dinamicamente conforme a disponibilidade de horas semanais (neste caso, 20h) e nível de experiência.
+2

##### __Comparação e Análise de IAs (Benchmark)__ #####
Para garantir a melhor qualidade das respostas e evitar "alucinações", realizei um teste comparativo entre modelos:

__Microsoft Copilot & Google Gemini__: Submeti os mesmos prompts a ambas as plataformas para comparar a precisão técnica das sugestões e a profundidade dos roadmaps gerados.

*[Roadmap: Engenheira DevOps / SRE](https://url.comhttps://github.com/lcnjrj/ia-mentor-de-carreira/blob/main/roadmaps/roadmaps-Copilot/01.DevOps-Engineer-Junior/RoadmapEngenheiraDevOps.md)

*[Roadmap: Engenharia de Inteligência Artificial / MLOps](https://github.com/lcnjrj/ia-mentor-de-carreira/blob/main/roadmaps/roadmaps-Copilot/02.Engenharia-de-Intelig%C3%AAncia%20Artificial-MLOps/RoadmapEngenhariadeIntelig%C3%AAnciaArtificial.md)

*[Roadmap: Redatora Técnica / Technical Writer (Foco em Tecnologia)]([https://url.com](https://github.com/lcnjrj/ia-mentor-de-carreira/blob/main/roadmaps/roadmaps-Copilot/03.Technical-Writer/RoadmapTechnicalWriter.md))

*[Link Text](https://url.com)

*[Link Text](https://url.com)

*[Link Text](https://url.com)


__Exploração de Cenários__: Embora meu foco seja DevOps, executei o fluxo completo para as três sugestões de carreira fornecidas pelo Agent 1. Isso permitiu analisar a consistência da lógica da IA e a capacidade de personalização do Agent 2 para diferentes domínios tecnológicos.

__Vantagens de utilizar IA na Mentoria__
Hiper-personalização Reversa: O plano foca no preenchimento de gaps específicos. Em vez de repetir fundamentos de Linux/Bash que já domino, a IA direcionou o foco para Cloud, CI/CD e Observabilidade.


__Estruturação de Dados:__ Organização imediata de metas semanais e entregáveis de portfólio, reduzindo o tempo de planejamento de dias para minutos.

__Iteração Constante:__ Diferente de um PDF estático, o mentor de IA permite ajustes em tempo real conforme a evolução do aprendizado ou mudança de prioridades.
