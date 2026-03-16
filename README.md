# Estudo de Metodologia: Cascata (Waterfall)

Este repositório contém a análise técnica e documentação sobre a **Metodologia Cascata**, desenvolvida como parte das atividades da Unidade Curricular de Desenvolvimento de Sistemas.

---

## O que é a Metodologia Cascata?

A metodologia **Cascata (Waterfall)** é um modelo de desenvolvimento de sistemas sequencial e linear. Ela recebe esse nome porque o progresso flui logicamente de uma fase para outra, como uma queda d'água, onde uma etapa só começa quando a anterior está 100% concluída.

### Definição
Formalizada por Winston Royce em 1970, esta abordagem prioriza o planejamento detalhado e a documentação rigorosa antes de qualquer linha de código ser escrita. É um dos modelos mais tradicionais da Engenharia de Software.

---

### Curiosidade Histórica
Apesar de ser o "pai" do modelo Cascata, no seu artigo original de 1970, Winston Royce na verdade propôs um modelo que incluía retornos (feedbacks) entre as fases, alertando que uma abordagem estritamente linear seria arriscada e propensa a falhas. Ironicamente, a indústria adotou apenas a interpretação estritamente sequencial do seu diagrama, que acabou se popularizando como o modelo Cascata tradicional que conhecemos hoje.
## Características Principais

* **Fluxo Sequencial:** O projeto é dividido em fases distintas (Requisitos, Design, Implementação, Testes, Implantação e Manutenção).
* **Documentação Robusta:** Cada fase gera um documento formal que serve de base para a próxima etapa.
* **Rigidez de Escopo:** Os requisitos são definidos e fixados no início. Mudanças durante o processo são evitadas devido ao alto custo de retrabalho.
* **Divisão Clara de Etapas:** Facilita o gerenciamento de cronograma, pois os marcos (milestones) são bem definidos.
* **Aprovação por Fases:** O cliente geralmente revisa e aprova o progresso ao final de cada grande etapa, e não de forma contínua.

---

## Fases do Modelo

1.  **Requisitos:** Coleta detalhada de todas as necessidades do cliente.
2.  **Análise/Design:** Planejamento da arquitetura do software e interface.
3.  **Implementação:** Desenvolvimento real do código baseado no design.
4.  **Testes (QA):** Verificação de erros e validação se o sistema atende aos requisitos iniciais.
5.  **Implantação:** Entrega do produto final ao usuário/cliente.
6.  **Manutenção:** Correções de bugs e atualizações necessárias após o lançamento.

---

## Papéis e Responsabilidades na Equipe

Devido à natureza fragmentada do modelo Cascata, as equipes geralmente são altamente especializadas e trabalham de forma isolada em suas respectivas fases:

* **Analista de Requisitos:** Focado quase exclusivamente na primeira fase, sendo a ponte entre o cliente e a equipe técnica para gerar o Documento de Especificação de Requisitos.
* **Arquiteto de Software/Designer:** Traduz os requisitos em diagramas (UML, MER) e define a infraestrutura tecnológica.
* **Desenvolvedor/Programador:** Fica responsável apenas por codificar o que foi estritamente definido nos documentos de design, geralmente sem contato direto com o cliente.
* **Engenheiro de Qualidade (QA):** Entra em ação na fase de Testes, criando e executando cenários baseados nos requisitos iniciais para validar o sistema.
* **Gerente de Projetos:** Papel vital para garantir que o cronograma rígido e as entregas (milestones) de cada fase sejam cumpridos antes de autorizar o início da próxima.

## Tecnologias e Ferramentas Relacionadas
Para gerenciar projetos neste modelo, utilizam-se ferramentas de cronograma rígido:
* **Gráficos de Gantt** (Visualização do cronograma sequencial)
* **Microsoft Project** ou **GanttProject**
* **Enterprise Architect** (Modelagem UML)

---

## Projetos Recomendados

A Metodologia Cascata é indicada para cenários onde a previsibilidade é mais importante que a velocidade. Os principais tipos de projetos são:

* **Sistemas Críticos:** Softwares médicos, aeroespaciais e de segurança, onde a documentação e os testes rigorosos são vitais.
* **Projetos de Escopo Fechado:** Quando o cliente sabe exatamente o que precisa e os requisitos não sofrerão alterações.
* **Sistemas Governamentais:** Projetos que exigem conformidade com leis e auditorias rigorosas.
* **Hardware/Embarcados:** Softwares que operam integrados a componentes físicos e exigem alta estabilidade inicial.

---

### Exemplo Prático: Sistema de Controle de Voo (Aviônica)
Imagine o desenvolvimento do software que controla os freios ou a navegação de um avião comercial. Neste cenário, não é possível usar uma abordagem de tentativa e erro (como em metodologias ágeis). Todos os requisitos de segurança, limites de velocidade, tempo de resposta do hardware e protocolos de emergência precisam ser 100% mapeados, documentados e testados antes de o avião sair do chão. Mudanças de escopo de última hora são inaceitáveis devido ao risco de vida envolvido. Este é o cenário perfeito para a Metodologia Cascata.

##  Vantagens e Desvantagens

###  Vantagens
* **Estrutura Clara:** Facilidade em definir marcos e prazos.
* **Documentação Robusta:** Essencial para sistemas que exigem auditoria e histórico.
* **Foco no Planeamento:** Reduz ambiguidades antes da fase de código.

###  Desvantagens
* **Dificuldade em Mudanças:** Alterar requisitos no meio do processo gera alto custo.
* **Feedback Tardio:** O cliente só interage com o produto final, aumentando o risco de insatisfação.
* **Testes Tardios:** Erros de design só são encontrados na fase final de QA.
---

## Comparativo Rápido: Cascata vs. Ágil

Para fins de contexto de mercado atual, é comum comparar o modelo Cascata com as metodologias Ágeis (como Scrum):

| Característica | Metodologia Cascata | Metodologias Ágeis |
| :--- | :--- | :--- |
| **Abordagem** | Preditiva (Planejamento total inicial) | Adaptativa (Planejamento contínuo) |
| **Escopo** | Fixo e rígido | Flexível e aberto a mudanças |
| **Entregas** | Uma única entrega no final do projeto | Entregas pequenas, contínuas e iterativas |
| **Participação do Cliente**| Alta no início (Requisitos) e no fim (Entrega) | Contínua durante todo o desenvolvimento |
| **Foco Principal** | Processos, cronogramas e documentação | Software funcionando e colaboração |

---


## 👥 Integrantes do Grupo (Alunos)
* **Lucas Aquino Guedes**
* **Erick Silva Fernandes de Araujo**
