# Abordagem para responder às dinâmicas

## Padrão aprendido

As respostas de apoio devem seguir a organização do enunciado, separando a resposta por bloco e respondendo a cada pergunta de forma explícita. Escrever em português claro, em parágrafos objetivos, conectando a situação apresentada a:

- causa raiz e contexto técnico;
- governança, papéis e controles do processo;
- impactos para usuários, operação e negócio;
- ações preventivas, corretivas e de acompanhamento;
- equilíbrio entre segurança, agilidade e inovação.

Quando fizer sentido, fechar com uma conclusão curta que sintetize as lições da atividade. Para cenários de incidente, explicar não só como evitar a falha, mas também como conter e remediar seus efeitos. Para recomendações técnicas, dar exemplos concretos e explicar seus limites.

## Aplicação aos temas já trabalhados

- **Governança e cultura DevSecOps:** tratar segurança como responsabilidade compartilhada e integrada ao ciclo, evitando apresentá-la apenas como uma etapa final ou como tarefa exclusiva do time de segurança.
- **SCM, branches e revisão:** relacionar proteção da branch principal, Pull Requests, revisão independente, verificações automatizadas, permissões mínimas e rastreabilidade.
- **Segredos expostos:** não sugerir que apagar uma linha elimina o risco. Orientar revogação ou rotação imediata, investigação de uso, armazenamento seguro da nova credencial e limpeza do histórico quando apropriado.
- **SAST, DAST e SCA:** equilibrar cobertura e velocidade com análises incrementais e rápidas no fluxo de mudanças, verificações completas em momentos apropriados, triagem de alertas e critérios objetivos de bloqueio baseados em risco confirmado.
- **Falsos positivos:** explicar custos de triagem, atrasos e fadiga de alertas; recomendar calibração, justificativa rastreável para supressões e revisão periódica.
- **Testes de QA:** incluir cenários de abuso e validações de autorização, limites, duplicidade e exposição de dados nos testes funcionais, esclarecendo que eles complementam ferramentas especializadas.

## Fidelidade às fontes

Usar primeiro os enunciados e materiais oficiais da disciplina. Diferenciar com clareza o que está explicitamente nos materiais do que é recomendação de apoio. Não inventar critérios de avaliação, requisitos oficiais ou resultados de ferramentas. Se houver tabelas no enunciado, preencher os campos solicitados com políticas claras e coerentes com o cenário.

Os arquivos de respostas devem ser separados por dinâmica quando solicitado, com títulos próprios e conteúdo correspondente a cada atividade.
