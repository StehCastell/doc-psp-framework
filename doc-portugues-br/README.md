# 📚 doc-psp-framework

> Um **manual vivo de engenharia de software pessoal** baseado no **PSP (Personal Software Process)** — estágios PSP0 a PSP3, em 4 fases. Cada pasta é **autossuficiente**.

Serve como **guia de estudo**, **modelo de disciplina pessoal** e **referência profissional** de processo individual.

## 🧭 Organização
Por **área de processo** (disciplina); dentro de cada área, a documentação **evolui por estágio do PSP**. Os estágios não duplicam a estrutura — só definem a maturidade pessoal e as capacidades adicionadas.

```
doc-portugues-br/
├── README.md
├── estagios-psp/      ← definição de cada estágio (PSP0 a PSP3)
├── areas-processo/    ← as 9 disciplinas, cada uma autossuficiente
│   └── <área>/  README.md + estagio-PSPx.md
├── artefatos/         ← 1 exemplo real de cada arquivo (inclui .xlsx)
├── templates-base/    ← templates genéricos
└── exemplos/          ← projetos de referência por fase
```

## 🎚️ Estágios do PSP

| Estágio | Nome | Fase |
|---|---|---|
| [PSP0](estagios-psp/estagio-PSP0.md) | Linha de Base | Fase 1 — Medição Pessoal |
| [PSP0.1](estagios-psp/estagio-PSP0.1.md) | Padrão e Tamanho | Fase 1 — Medição Pessoal |
| [PSP1](estagios-psp/estagio-PSP1.md) | Planejamento Pessoal | Fase 2 — Planejamento Pessoal |
| [PSP1.1](estagios-psp/estagio-PSP1.1.md) | Cronograma e Valor Agregado | Fase 2 — Planejamento Pessoal |
| [PSP2](estagios-psp/estagio-PSP2.md) | Qualidade Pessoal | Fase 3 — Qualidade Pessoal |
| [PSP2.1](estagios-psp/estagio-PSP2.1.md) | Projeto e Verificação | Fase 3 — Qualidade Pessoal |
| [PSP3](estagios-psp/estagio-PSP3.md) | Processo Cíclico | Fase 4 — Processo Cíclico Pessoal |

## 🗂️ Áreas de processo

| Área | Disciplina | Disponível |
|---|---|---|
| 🧭 [`processo-pessoal`](areas-processo/processo-pessoal/README.md) | Processo Pessoal | a partir de PSP0.1 |
| 📊 [`medicao`](areas-processo/medicao/README.md) | Medição | a partir de PSP0 |
| 📁 [`projeto`](areas-processo/projeto/README.md) | Projeto | a partir de PSP0 |
| 📄 [`relatorios`](areas-processo/relatorios/README.md) | Relatórios | a partir de PSP0 |
| 📅 [`planejamento`](areas-processo/planejamento/README.md) | Planejamento | a partir de PSP1 |
| 🔬 [`analise`](areas-processo/analise/README.md) | Análise | a partir de PSP1.1 |
| ✅ [`qualidade`](areas-processo/qualidade/README.md) | Qualidade | a partir de PSP2 |
| 🗂️ [`configuracao`](areas-processo/configuracao/README.md) | Configuração | a partir de PSP0.1 |
| 🔁 [`iteracoes`](areas-processo/iteracoes/README.md) | Iterações | a partir de PSP3 |

## 🚦 Por onde começar
1. Leia os [estágios do PSP](estagios-psp/estagio-PSP0.md).
2. Escolha uma [área](areas-processo/medicao/README.md) e leia o README.
3. Siga a evolução `PSP0 → PSP3` dentro da área.
4. Use os [templates-base](templates-base/estimativa.md) e veja [exemplos reais](artefatos/README.md).

## 🧱 Princípios
- **Autossuficiência** · **Zero duplicação** · **Por disciplina** · **Estágios como evolução** · **Self-contained**.
