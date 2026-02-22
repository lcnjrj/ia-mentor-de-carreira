 IA Mentor de Carreira 
 
Objetivo do Projeto
Este repositório documenta um desafio prático de mentoria de carreira utilizando Inteligência Artificial Generativa. O foco foi transformar prompts estruturados em agentes especializados para identificar perfis profissionais e traçar roteiros técnicos personalizados. Como prova de conceito, utilizei o fluxo para planejar minha transição para DevOps Engineer, aproveitando uma base sólida de mais de 20 anos em sistemas Linux e Shell Script.

Metodologia e Uso de Agentes
O projeto baseia-se em uma arquitetura de dois agentes principais:


Agent 1 (Entrevistador de Carreira): Especializado em conduzir entrevistas estruturadas de 7 perguntas para extrair motivações e competências. Ele utiliza uma matriz de decisão interna para sugerir as 3 carreiras com maior afinidade.
+1


Agent 2 (Planejador de Roadmaps): Especializado em criar planos de 90 dias, focando em core skills, ferramentas e projetos de portfólio. O planejamento é ajustado dinamicamente conforme a disponibilidade de horas semanais (neste caso, 20h) e nível de experiência.
+2

Comparação e Análise de IAs (Benchmark)
Para garantir a melhor qualidade das respostas e evitar "alucinações", realizei um teste comparativo entre modelos:

Google Gemini & Microsoft Copilot: Submeti os mesmos prompts a ambas as plataformas para comparar a precisão técnica das sugestões e a profundidade dos roadmaps gerados.

Exploração de Cenários: Embora meu foco seja DevOps, executei o fluxo completo para as três sugestões de carreira fornecidas pelo Agent 1. Isso permitiu analisar a consistência da lógica da IA e a capacidade de personalização do Agent 2 para diferentes domínios tecnológicos.

Vantagens de utilizar IA na Mentoria
Hiper-personalização Reversa: O plano foca no preenchimento de gaps específicos. Em vez de repetir fundamentos de Linux/Bash que já domino, a IA direcionou o foco para Cloud, CI/CD e Observabilidade.


Estruturação de Dados: Organização imediata de metas semanais e entregáveis de portfólio, reduzindo o tempo de planejamento de dias para minutos.

Iteração Constante: Diferente de um PDF estático, o mentor de IA permite ajustes em tempo real conforme a evolução do aprendizado ou mudança de prioridades.
