# Template — Matriz de Riscos de Portfólio

> Modelo para identificar, priorizar e acompanhar os riscos que ameaçam o portfólio como um todo — não os riscos internos de cada projeto, mas os que cruzam projetos ou afetam a entrega estratégica.

## Registro de riscos

| ID | Risco (se [evento], então [consequência]) | Categoria | Probabilidade | Impacto | Exposição | Resposta | Dono | Status |
|----|-------------------------------------------|-----------|---------------|---------|-----------|----------|------|--------|
| R1 | | | Baixa/Média/Alta | Baixo/Médio/Alto | | Mitigar/Evitar/Transferir/Aceitar | | Aberto/Monitorando/Fechado |

## Categorias de risco de portfólio

- **Recursos:** competição por pessoas-chave entre projetos.
- **Dependências:** projetos que se bloqueiam mutuamente.
- **Estratégico:** desalinhamento entre o que se faz e a direção da empresa.
- **Externo:** regulatório, fornecedores, mercado.
- **Capacidade:** portfólio maior do que a organização consegue executar.

## Exposição (probabilidade × impacto)

| | Impacto Baixo | Impacto Médio | Impacto Alto |
|--|---------------|---------------|--------------|
| **Prob. Alta** | 🟡 | 🔴 | 🔴 |
| **Prob. Média** | ⚪ | 🟡 | 🔴 |
| **Prob. Baixa** | ⚪ | ⚪ | 🟡 |

Concentre a atenção da governança nos riscos 🔴. Os ⚪ ficam monitorados, sem consumir tempo de reunião.

## Plano de resposta (para riscos de alta exposição)

| Campo | Conteúdo |
|-------|----------|
| **Risco** | |
| **Ações de mitigação** | (o que reduz probabilidade ou impacto desde já) |
| **Gatilho de contingência** | (o sinal observável de que o risco está se materializando) |
| **Plano de contingência** | (o que fazer se o gatilho disparar) |
| **Dono** | |

## Boas práticas

- O valor está nos gatilhos. Um plano de contingência sem gatilho observável nunca é acionado a tempo.
- Revise a matriz na cadência de governança. Risco que não é revisto vira surpresa.
- Distinga risco de portfólio (cruza projetos) de risco de projeto (interno). Este template é para o primeiro.
