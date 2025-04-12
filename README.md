# Sistema de Gestão de Construção Civil — Revisão da Formulação do Problema (Design Thinking)

Projeto: **Sistema de Gestão de Construção Civil para Empreendedor Individual**

---
## 1. Mapa de Atores

| Camada | Atores | Papel / Interesse | Relações‑chave |
|--------|--------|-------------------|----------------|
| **Primária** | Empreendedor individual (autogerenciador da obra) | Planeja, financia e gerencia a obra; usuário‑foco | Interage com todos os demais atores |
|  | Trabalhadores da obra (pedreiros, eletricistas, encanadores etc.) | Executam tarefas de campo | Recebem tarefas, horários e pagamentos do empreendedor |
| **Secundária** | Fornecedores de materiais | Vendem insumos e negociam prazos de entrega | Integração de pedidos e logística com o sistema |
|  | Profissionais técnicos (engenheiros, arquitetos, mestres de obra) | Fornecem suporte técnico e validam normas | Compartilham documentos e check‑lists com o empreendedor |
|  | Órgãos reguladores / prefeituras | Concedem licenças e fiscalizam | Recebem documentação e status via sistema |
| **Terciária** | Instituições financeiras | Financiamento e liberação de recursos | Integração para controle de fluxo de caixa |
|  | Clientes finais / compradores | Adquirem o imóvel após a obra | Influenciam requisitos de qualidade e prazo |
|  | Comunidade / vizinhança | Impactada por barulho, trânsito e resíduos | Requer comunicação e mitigação de impactos |

---
## 2. Mapa de Empatia — *Empreendedor Individual*

| Quadrante | Principais insights |
|-----------|--------------------|
| **O que *vê*** | • Aplicativos complexos voltados a engenheiros.<br>• Obras vizinhas com atrasos e desperdícios.<br>• Fornecedores pressionando por compras de última hora. |
| **O que *ouve*** | • Conselhos contraditórios de profissionais.<br>• Reclamações da equipe sobre pagamentos.<br>• Histórias de autoconstruções que estouraram o orçamento. |
| **O que *pensa & sente*** | • Ansiedade com custos imprevisíveis.<br>• Medo de fiscalizações e multas.<br>• Desejo de controlar tudo pelo celular. |
| **O que *diz & faz*** | • "Preciso terminar dentro do orçamento!"<br>• Usa planilhas improvisadas e grupos de WhatsApp.<br>• Compra material somente quando falta no canteiro. |
| **Dores (pains)** | • Falta de visibilidade de prazos.<br>• Dificuldade em priorizar tarefas.<br>• Pouco conhecimento técnico e burocrático. |
| **Ganhos (gains)** | • Obra dentro do prazo e do orçamento.<br>• Comunicação clara com equipe e fornecedores.<br>• Passo a passo simples para licenças e normas. |

---
## 3. Lista “O que é” e “O que não é”

| **É** | **Não é** |
|-------|-----------|
| Plataforma **mobile‑first** e web responsiva | Software pesado exclusivo para desktop |
| Focada em **usuários leigos** (pessoa física) | Destinada apenas a engenheiros experientes |
| Usa **check‑lists, lembretes e templates** simples | Requer conhecimento avançado de BIM/CAD |
| Integra **finanças, tarefas e documentação** em um só lugar | Ferramenta isolada para apenas uma área |
| Possui **assistente passo a passo** sobre licenças | Substitui completamente o engenheiro responsável |
| Oferece **relatórios visuais** de progresso | Gera relatórios técnicos complexos sem contexto |
| Adota **modelo SaaS freemium** | Venda única com alto custo inicial |

---
## 4. Brainwriting

### 4.1 Ideias brutas (6 participantes × 6 minutos)
1. Dashboard de orçamento em tempo real
2. Cronograma drag‑and‑drop com alertas
3. Marketplace de fornecedores integrados
4. Biblioteca de check‑lists por fase da obra
5. Assistente de licenças e normas (wizard)
6. Chat interno com histórico de decisões
7. Registro de horas da equipe via QR Code
8. Comparador de preços de materiais
9. Módulo de fotos georreferenciadas do progresso
10. Plano de contingência automática para clima
11. Notificações de vencimento de pagamentos
12. Exportação de relatórios para PDF/Excel
13. Módulo de sustentabilidade (resíduos e água)
14. Integração com bancos para fluxo de caixa
15. Gamificação de metas (pontos por etapa concluída)
16. Biblioteca de contratos e modelos jurídicos
17. Assistente de IA para dúvidas técnicas simples
18. Simulador de impacto de mudanças no escopo
19. Kanban simplificado para tarefas diárias
20. Botão de emergência para suporte especializado

### 4.2 Agrupamento de ideias por tema

| Tema | Ideias relacionadas |
|------|--------------------|
| **Planejamento & Cronograma** | 2, 10, 18, 19 |
| **Finanças & Orçamento** | 1, 8, 11, 14 |
| **Materiais & Fornecedores** | 3, 8 |
| **Execução & Acompanhamento** | 4, 7, 9, 12, 13 |
| **Compliance & Licenças** | 5, 16 |
| **Comunicação & Suporte** | 6, 17, 20 |
| **Motivação & Engajamento** | 15 |

### 4.3 Priorização (matriz Impacto × Esforço)

| Ideia agrupada | Impacto | Esforço | Prioridade |
|----------------|---------|---------|------------|
| Dashboard de orçamento + fluxo de caixa | Alto | Médio | **Alta (MVP)** |
| Cronograma drag‑and‑drop + Kanban | Alto | Médio | **Alta (MVP)** |
| Assistente de licenças & check‑lists | Médio | Alto | Média |
| Chat interno + histórico | Médio | Baixo | **Alta (MVP)** |
| Registro de horas via QR Code + fotos de progresso | Médio | Médio | Média |
| Marketplace de fornecedores | Alto | Alto | Baixa |
| Gamificação de metas | Baixo | Médio | Baixa |

> **MVP sugerido**: Dashboard financeiro, Cronograma visual, Chat interno e Check‑lists de etapas.

---
## 5. Rescrita do Desafio

> **Como podemos capacitar empreendedores pessoa física a planejar, executar e monitorar suas obras de construção civil de forma simples, dentro do prazo e do orçamento, garantindo conformidade legal sem exigir conhecimentos técnicos avançados?**

---
*Documento atualizado em 12 de abril de 2025 para a Atividade de Revisão da Parte 1 do Projeto de Engenharia de Sistemas.*

