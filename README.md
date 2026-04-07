🗂️ Fluxo App — Wireframe de Média Fidelidade

Desafio prático do curso de UX/UI Design · DIO
Criação de wireframe One Page com aplicação dos princípios de usabilidade de Nielsen e Bastien

---


📌 Sobre o Projeto
O Fluxo é um aplicativo de gestão de tarefas e produtividade, desenvolvido como objeto de estudo para a criação de um wireframe de média fidelidade no formato One Page.
O objetivo não é apenas desenhar telas, mas tomar decisões conscientes de interface com base na psicologia do design e nas leis de usabilidade, documentando cada escolha com referência ao princípio que a fundamenta.

---

🎯 Objetivos de Aprendizagem Alcançados

 Criação de wireframe de média fidelidade para produto digital
 Aplicação das 10 Heurísticas de Nielsen em decisões de interface
 Aplicação dos critérios ergonômicos de Bastien e Scapin
 Documentação estruturada de decisões de design
 Uso de princípios de psicologia perceptiva (Gestalt) na composição visual

 ---


🖥️ O Produto: Fluxo App
AtributoDetalheTipoAplicativo web de gestão de tarefasFormatoOne Page (dashboard único)Público-alvoTimes de trabalho e profissionais que gerenciam múltiplos projetosProblema resolvidoVisibilidade do progresso de tarefas e projetos em um único painel, sem necessidade de navegar entre páginas

---


🗺️ Estrutura da One Page
O wireframe é composto por 7 seções organizadas verticalmente, cada uma com função e justificativa de usabilidade.

```
┌─────────────────────────────────────────┐
│  1. NAVBAR GLOBAL (sticky)              │
├─────────────────────────────────────────┤
│  2. HERO / CABEÇALHO DO DASHBOARD       │
├─────────────────────────────────────────┤
│  3. FILTROS, BUSCA E ORDENAÇÃO          │
├─────────────────────────────────────────┤
│  4. VIEW PRINCIPAL — KANBAN             │  ← Conteúdo primário
├─────────────────────────────────────────┤
│  5. DRAWER LATERAL (detalhe de tarefa)  │
├─────────────────────────────────────────┤
│  6. ANÁLISE E RELATÓRIOS                │
├─────────────────────────────────────────┤
│  7. RODAPÉ                              │
└─────────────────────────────────────────┘
```
---
🧠 Princípios de Usabilidade Aplicados
Heurísticas de Nielsen
#HeurísticaOnde aplicadaComo#1Visibilidade do status do sistemaHero, Kanban, AnáliseProgress bars nas métricas-chave; cor de coluna indica estado atual#2Correspondência com o mundo realDrawer de tarefaCheckbox de subtarefa espelha lista de papel; linguagem "A fazer / Em andamento / Concluído"#3Controle e liberdade do usuárioFiltrosTags de filtro ativo com botão de remoção individual (✕) e opção "Limpar filtros"#4Consistência e padrõesNavbarLogo sempre à esquerda; ícones padrão (notificação, ajuda, avatar); menu em posição esperada#5Prevenção de errosKanbanTarefas concluídas com opacidade reduzida, dificultando edição acidental#6Reconhecimento em vez de memorizaçãoKanban, FiltrosCor da coluna comunica status sem necessidade de leitura; tags de filtro ativo visíveis#7Flexibilidade e eficiênciaKanbanSuporte a drag-and-drop entre colunas; atalho "+ Adicionar tarefa" visível em cada coluna
Critérios Ergonômicos de Bastien e Scapin
CritérioOnde aplicadaComoCompatibilidadeNavbarOrdem do menu reflete fluxo mental: visão geral → projetos → tarefasCarga de trabalhoDrawerCampos mais importantes agrupados no topo; informações complementares abaixo, reduzindo esforço cognitivoFeedback imediatoFiltros, KanbanView ativo em destaque (Kanban vs. Lista); filtros aplicados visíveis como tagsAgrupamentoAnáliseGráficos agrupados por tipo de leitura: tendência temporal (barras), distribuição (donut), síntese (stat cards)Significância dos códigosKanbanCódigo de cor consistente: cinza = a fazer, roxo = em andamento, amarelo = revisão, verde = concluído
Psicologia Perceptiva (Gestalt)
LeiAplicaçãoProximidadeCards de tarefa agrupados dentro de colunas; métricas em grid 3×1SemelhançaTodos os cards com mesmo visual → mesma hierarquia de informaçãoFigura e fundoDrawer com overlay no fundo cria separação clara do conteúdo ativoContinuidadeProgress bars guiam o olhar da esquerda para direita, comunicando progresso

---

📐 Decisões de Design
Hierarquia visual
A hierarquia segue três níveis:

Nível 1 — Orientação: Navbar + Hero (onde estou? quais são meus números?)
Nível 2 — Ação: Filtros + Kanban (o que preciso fazer agora?)
Nível 3 — Análise: Relatórios (como está meu desempenho?)

Codificação por cor
As cores não foram escolhidas arbitrariamente. Cada cor do Kanban segue convenções mentais já estabelecidas:

Cinza → neutro, pendente, sem urgência
Roxo/Azul → ativo, em progresso (cor de destaque do produto)
Amarelo/Âmbar → atenção, revisão necessária
Verde → sucesso, concluído

Drawer em vez de página separada
A abertura do detalhe da tarefa em um painel lateral (drawer) — e não em uma nova página — foi uma decisão deliberada, fundamentada na heurística #3 de Nielsen (controle e liberdade). O usuário mantém o contexto do Kanban visível ao fundo, podendo fechar o drawer a qualquer momento sem perder sua posição.
CTA primário único
Na seção Hero, existe apenas um botão primário ("+ Nova Tarefa"). O botão secundário ("Ver Projetos") é visualmente subordinado. Isso aplica a Lei de Fitts e o princípio de hierarquia de ações, evitando que o usuário precise decidir entre duas ações de igual peso.

---

🛠️ Ferramentas e Tecnologias
FerramentaUsoHTML/CSSPrototipagem do wireframe em códigoClaude AIGeração e refinamento do wireframe interativoGitHubVersionamento e apresentação do projetoMarkdownDocumentação (este arquivo)

Nota: O wireframe foi desenvolvido em HTML/CSS como artefato interativo, o que permite visualização direta no navegador sem necessidade de ferramentas externas como Figma ou Sketch.

```

📁 Estrutura do Repositório
/
├── README.md               ← Este arquivo (documentação completa)
├── wireframe.html          ← Wireframe interativo em HTML
└── images/
    ├── preview-navbar.png
    ├── preview-hero.png
    ├── preview-kanban.png
    ├── preview-drawer.png
    └── preview-analytics.png

````

🚀 Como Visualizar
Opção 1 — Diretamente no navegador:
bash# Clone o repositório
git clone https://github.com/woody-m/ux-wireframe-fluxo-app.git

# Abra o arquivo no navegador
open wireframe.html
Opção 2 — GitHub Pages:
Acesse a versão publicada em: https://github.com/woody-m/ux-wireframe-fluxo-app.git

---

📖 Referências

NIELSEN, J. 10 Usability Heuristics for User Interface Design. Nielsen Norman Group, 1994. Disponível em: https://www.nngroup.com/articles/ten-usability-heuristics/
BASTIEN, J. M. C.; SCAPIN, D. L. Ergonomic Criteria for Evaluating the Ergonomic Quality of Interactive Systems. International Journal of Human-Computer Studies, 1993.
NORMAN, D. The Design of Everyday Things. Basic Books, 2013.
DIO. Formação UX/UI Design — Material do curso.

---


👤 Autor
Bruna Woodymila Siqueira Lopes Ivánek 

Desenvolvido como parte do desafio prático da Formação UX/UI Design na DIO.

"Design is not just what it looks like and feels like. Design is how it works." — Steve Jobs
