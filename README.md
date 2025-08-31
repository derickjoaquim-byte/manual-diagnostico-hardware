# manual-diagnostico-hardware
# Guia Prático: Otimizando a Gestão de Chamados com GLPI

## 🎯 Objetivo do Projeto

Este repositório serve como um guia centralizado de boas práticas para a gestão de um Service Desk utilizando a ferramenta GLPI. O objetivo é documentar processos que visam reduzir o tempo de resolução, aumentar a satisfação do usuário e fornecer dados estratégicos para a gestão de TI. Este não é um projeto de código, mas um **projeto de documentação e processos**.

---

## 🛠️ Ferramentas e Metodologias Abordadas

*   **Ferramenta Principal:** GLPI (Gestionnaire Libre de Parc Informatique)
*   **Metodologia:** Conceitos baseados no framework ITIL
*   **Foco:** Gestão de Incidentes, Requisições e Base de Conhecimento

---

## 📖 O Guia

### 1. Estruturação de Categorias de Chamados
*   **Problema:** Chamados genéricos que dificultam a triagem.
*   **Solução Proposta:** Criar uma árvore de categorias detalhada (ex: Hardware > Notebook > Tela; Software > ERP > Módulo Fiscal).
*   **Benefício:** Atribuição automática para a equipe correta e geração de relatórios mais precisos.

### 2. Definição de SLAs (Service Level Agreements)
*   **Problema:** Falta de clareza sobre os prazos de atendimento.
*   **Solução Proposta:** Configurar SLAs baseados na Urgência e no Impacto do chamado.
    *   **Crítico (Sistema parado):** SLA de 2 horas para primeira resposta.
    *   **Alto (Funcionalidade importante afetada):** SLA de 4 horas.
    *   **Médio/Baixo:** SLA de 8 a 24 horas.

### 3. Utilização da Base de Conhecimento
*   **Problema:** Respostas inconsistentes para problemas recorrentes.
*   **Solução Proposta:** Documentar a solução de cada chamado relevante e publicá-la na Base de Conhecimento interna do GLPI, criando artigos que a própria equipe e os usuários possam consultar.
*   **Benefício:** Reduz o volume de chamados repetidos e capacita os usuários a resolverem problemas simples sozinhos.

---

## 🧠 O que eu aprendi com este projeto

*   **Visão Estratégica:** Aprendi que a forma como os dados são inseridos no GLPI impacta diretamente a capacidade da gestão de tomar decisões informadas. Um sistema bem configurado transforma o Service Desk de reativo para proativo.
*   **Importância da Padronização:** A criação de padrões claros para registro e resolução de chamados é o segredo para escalar uma operação de suporte sem perder a qualidade.
*   **Comunicação:** A documentação clara e acessível é tão importante quanto a solução técnica em si. Ela garante que o conhecimento não fique centralizado em uma única pessoa.
