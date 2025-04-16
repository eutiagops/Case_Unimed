> <h1>Case Unimed<h1>

## Estudo de Caso - Analista de Negócios

## 🎯 Objetivo:

- Avaliar as competências em análise de processos, entendimento de jornadas de usuários;
- Identificação de oportunidades de melhoria e a capacidade de propor soluções práticas e assertivas;
- Validar as habilidades na elaboração de documentações e histórias de usuários detalhadas.
<br>

## **Situação 1:** Ánalise de Jornada Atual (AS IS)


### 🧭**Mapa de jornada atual**


![Estudo de Caso](https://github.com/user-attachments/assets/fecee637-d4ba-4435-a1d1-1916a60bee80)


<br>


### **Oportunidades de melhoria identificadas na Jornada Atual**

 1. Sistemas desconectados sem integração
 2. Ausência de busca centralizada por especialidade, médico ou unidade
 3. Dependência de processos manuais (listas, planilhas, anotações)
 4. Falta de padronização no acompanhamento de pendências
 5. Múltiplos canais de atendimento sem rastreabilidade automatizada
<br>


## 📊**Diagnóstico**


| Diagnóstico do Processo de Agendamento |
|----------------------------------------|
| A análise do processo de agendamento evidencia falhas que afetam tanto o atendimento ao paciente quanto a eficiência da equipe. <br><br>Entre os principais problemas estão o uso de sistemas e cadastros sem integração, a ausência de uma busca centralizada por horários e especialidades, o uso excessivo de controles manuais e a existência de múltiplos canais sem rastreabilidade. <br><br>Estes pontos geram retrabalho, dificultam a organização e aumentam o risco de erros, comprometendo a operação como um todo. <br><br>Como consequência, a experiência do paciente é prejudicada, ocorre a perda na produtividade da equipe, e a gestão tem dificuldades para tomar decisões baseadas em dados. <br><br>Recomenda-se modernizar o processo com foco na unificação do sistema, automação de controles, centralização das informações e uso de canais rastreáveis. <br><br>Essas mudanças são fundamentais para garantir escalabilidade, qualidade no atendimento e maior eficiência operacional. |
<br>
<br>
<br>

## **Situação 2:** Definição de Melhorias e Proposição de Soluções

### 💡**Soluções de melhoria**

 1. Sistema Único de Gerenciamento de Agenda
 2. API de Integração de Sistemas Agenda x Cadastro
 3. Centralização dos dados de clínicas em uma base única e de fácil manutenção
 4. Segmentação da Agenda por Especialidade, Médico e Clínica
 5. Automatização e Integração das Ferramentas de Atendimento (Chatbots)
<br>

### 📋**Priorização do Backlog**


| **Tarefa** | **Atividades** | **Justificativa de Prioridades** | **Entrega de Valor** |
|-----------|----------------|----------------------------------|----------------------|
| 1. Levantamento e Requisitos para o Sistema Único de Agenda | - Mapear funcionalidades dos sistemas atuais e identificar lacunas<br>- Levantar requisitos funcionais e não funcionais com usuários<br>- Validar proposta com stakeholders | Base para eliminar duplicidade de sistemas e reduzir retrabalho e erros | 🥇Alta – fundamenta toda a integração e unificação de agendas |
| 2. Desenvolvimento da API de Integração Agenda x Cadastro | - Especificar endpoints e dados necessários<br>- Definir protocolos de segurança e autenticação<br>- Testar integração e ajustar conforme feedback | Garante sincronização automática entre agenda e cadastro, eliminando inserções manuais | 🥇Alta – assegura consistência e confiabilidade dos dados |
| 3. Centralização dos dados de clínicas em uma base única e de fácil manutenção | - Consolidar e migrar dados das clínicas para repositório central<br>- Implementar sincronização em tempo real<br>- Validar integridade dos dados | Facilita consulta e atualização de clínicas, reduzindo erros e agilizando identificação | 🥇Alta – melhora a eficiência operacional e a precisão das informações |
| 4. Definição e Implementação da Segmentação da Agenda | - Definir categorias por especialidade, médico e clínica<br>- Desenvolver modelo de visualização segmentada<br>- Testar e ajustar com a equipe | Agiliza a busca por horários e médicos, otimizando o tempo de atendimento | 🥈Média – impacta diretamente na agilidade de atendimento |
| 5. Desenvolvimento e Integração do Chat automatizado (chatbot) de Atendimento | - Mapear fluxos de atendimento para automação<br>- Desenvolver e configurar chatbot em WhatsApp/telefone<br>- Integrar chatbot com sistema de agenda | Reduz carga de trabalho manual e tempo de resposta, liberando atendentes para casos complexos | 🥈Média – melhora experiência do cliente e reduz custo operacional |
| 6. Testes de Usabilidade do Sistema Integrado | - Criar protótipos ou wireframes da solução<br>- Conduzir sessões de teste com atendentes<br>- Refinar interface e funcionalidades | Garante aceitação e usabilidade da solução, minimizando riscos de resistência | 🥈Média – assegura adoção eficaz e minimiza retrabalho pós-implantação |
| 7. Treinamento e Capacitação da Equipe | - Elaborar material de treinamento para novas ferramentas<br>- Conduzir workshops práticos<br>- Estabelecer canal de suporte pós-implementação | Assegura que a equipe saiba usar corretamente as novas ferramentas e processos | 🥈Média – maximiza retorno sobre o investimento e eficiência |
| 8. Monitoramento e Avaliação de Desempenho | - Definir KPIs (tempo, erros, satisfação)<br>- Configurar dashboards e relatórios<br>- Agendar reuniões periódicas de revisão | Permite medir resultados, detectar desvios e promover melhorias contínuas | 🥈Média – mantém ganhos a longo prazo e direciona próximas melhorias |
<br>


### ⚙️**Requisitos técnicos/funcionais iniciais**



| **Categoria** | **Requisitos Técnicos e Funcionais** |
|--------------|----------------------------------------|
| **1. Levantamento e Requisitos para o Sistema Único de Agenda** | **Requisito Funcional:** <br>  - Interface única para visualização e gestão de agendas por clínica, especialidade e médico. <br> **Requisito Técnico:** <br>  - Banco de dados centralizado (SQL/NoSQL) com alta disponibilidade e replicação. <br> **Procedimento:** <br>  - Migração incremental de dados dos sistemas legados para o novo sistema, garantindo rollback seguro.|
| **2. Desenvolvimento da API de Integração Agenda x Cadastro** | **Requisito Funcional:** <br>  - Endpoints RESTful para CRUD de agendamentos e sincronização de cadastros. <br> **Requisito Técnico:** <br>  - Autenticação via OAuth 2.0 e uso de padrões JSON Schema para validação de payloads. <br> **Automação:** <br>  - Jobs agendados (cron) para reconciliação periódica e tratamento de inconsistências. |
| **3. Centralização dos dados de clínicas em uma base única e de fácil manutenção** | Requisito Funcional: ** <br>  - Dashboard de administração de clínicas, com CRUD de unidades e especialidades. <br> Requisito Técnico: ** <br>  - Data warehouse ou data lake para consolidação de informações, com ETL em Python ou AWS Glue. <br> **Fluxo:** <br>  - Pipeline de ingestão em tempo real para atualização instantânea. (Kafka, AWS) |
| **4. Definição e Implementação da Segmentação da Agenda** | **Requisito Funcional:** <br>  -  Filtros dinâmicos na interface de agendamento (dropdowns, pesquisa incremental). <br> **Requisito Técnico:** <br>  -  Índices e vizualizações no banco para consultas. <br> **Procedimento:** <br>  -  Definição das listas de especialidades e mapeamento de médicos a categorias. |
| **5. Desenvolvimento e Integração do Chatbot de Atendimento** | **Requisito Funcional:** <br>  -   Fluxos de conversa pré-definidos para coleta de dados, sugestões de horários e confirmação. <br> **Requisito Técnico:** <br>  -  Plataforma de chatbot (ManyChat, Dialogflow ou similar) integrada à API de agenda. <br> **Automação:** <br>  -  Webhooks para notificações em tempo real e fallback para atendimento humano. |
<br>


## **Situação 3:** Documentação - Histórias de Usuário
<br>


### 🗣️**Histórias de usuário | Critérios de aceite | Requisitos Técnicos e Funcionais**
<br>

| **Solução** | **História de Usuário** | **Critérios de Aceite** | **Requisitos Técnicos/Funcionais** |
|------------|--------------------------|--------------------------|-------------------------------------|
| **1. Sistema Único de Gerenciamento de Agenda** | Como atendente, quero realizar o agendamento das consultas através de um único sistema integrado, para agilizar o atendimento, reduzir retrabalho e evitar erros decorrentes da troca de sistemas. | - O sistema permite realizar o agendamento em um único ambiente.<br>- A interface é intuitiva e de fácil navegação.<br>- A migração de dados dos sistemas legados é transparente para o usuário.<br>- Não há necessidade de alternar entre diferentes plataformas. | - Integração completa dos dados de agendamento.<br>- Single Sign-On (SSO).<br>- Interface web responsiva.<br>- Mecanismos de rollback para migração segura dos dados. |
| **2. API de Integração de Sistemas Agenda x Cadastro** | Como administrador de TI, quero que os sistemas de agenda e cadastro estejam integrados por meio de uma API robusta, para que os dados se sincronizem automaticamente, garantindo consistência e eliminando erros de inserções manuais. | - API com endpoints RESTful para CRUD.<br>- Autenticação via OAuth 2.0.<br>- Validação com JSON Schema.<br>- Atualizações em tempo real. | - Endpoints RESTful.<br>- Autenticação com tokens Bearer.<br>- JSON Schema para payloads.<br>- Mecanismos de reconciliação automática. |
| **3. Centralização da Gestão Clínica em uma Única Base** | Como gestor de operações, quero centralizar os dados de todas as clínicas em um único sistema, para facilitar a consulta e atualização das informações, garantindo que os dados estejam sempre corretos e disponíveis em tempo real. | - Informações consolidadas em dashboard central.<br>- Atualização dos dados em tempo real.<br>- Acesso e edição dinâmico.<br>- Integridade dos dados transferidos. | - Banco de dados centralizado.<br>- ETL para migração e sincronização.<br>- Integração via pipelines (Kafka, AWS Kinesis). |
| **4. Segmentação da Agenda por Especialidade, Médico e Clínica** | Como atendente, quero ter uma agenda segmentada por especialidade, médico e clínica, para localizar rapidamente horários disponíveis e oferecer um atendimento mais assertivo e rápido aos pacientes. | - Filtros dinâmicos na tela de consultas.<br>- Buscas rápidas e precisas.<br>- Resultados claros e organizados.<br>- Melhora no tempo de atendimento. | - [UI/UX otimizadas](https://github.com/user-attachments/assets/3342a6a6-131d-431a-96f0-55ffc19bd0e6). |
| **5. Automatização e Integração das Ferramentas de Atendimento (Chatbots)** | Como atendente, quero contar com um chatbot integrado ao sistema de agendamento, para que ele possa responder dúvidas frequentes e direcionar agendamentos automaticamente, reduzindo o volume de atendimentos manuais e permitindo que eu foque nos casos mais complexos. | - O chatbot responde perguntas frequentes de forma automatizada e assertiva.<br>- Integração com sistema de agenda e cadastro.<br>- O chatbot inicia e finaliza processos simples de agendamento.<br>- Os agendamentos realizados pelo chatbot são refletidos no sistema único de agenda.<br>- Casos não resolvidos são encaminhados para atendimento humano via notificação em tempo real. | - Plataforma de chatbot (Dialogflow, ManyChat).<br>- Fluxos customizáveis.<br>- Webhooks para integração em tempo real. |
<br>
<br>

## 📆**Execução Ágil**
<br>

### **Plano de Execução Ágil**

Como Agilista do projeto conduzirei de forma colaborativa e transparente, definindo os principais KPI´s de forma clara e tangível, definindo os papeis e responsaveis por cada parte do projeto. Realizando as cerimonias ágil no modelo de sprints quinzenais, planning ao inicio de cada sprint (2 a 4h), Review ao final de cada sprint com apresentação das soluções desenvolvidas e coleta de feedbacks (até 2h), Retro no dia após a review (até 1h), permitindo rapida adaptação e garantindo que cada etapa seja entregue com qualidade, visibilidade e dentro dos prazos estimados.  



