# The Devs Department

Bem-vindo ao repositório oficial da The Devs Department! Este projeto está sendo desenvolvido como parte do trabalho do 2º Semestre de DSM na Fatec São José dos Campos, em parceria com a empresa Helpnei.**.

> **Projeto SCRUM**: Foco em proatividade, autonomia, colaboração e entrega de resultados.

📌 **Nosso [contato](#equipe)** está no final do README!  

## 📋 Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Objetivos](#objetivos)
- [Cronograma das Sprints](#cronograma-das-sprints)
- [Product Backlog](#product-backlog)
- [Sprint Backlog](#sprint-backlog)
- [Definition of Ready (DoR)](#definition-of-ready-dor)
- [Equipe](#equipe)

## 📝 Sobre o Projeto <a name="sobre-o-projeto"></a>
O projeto consiste no desenvolvimento de um Dashboard de Indicadores para a empresa Helpnei, com o objetivo de monitorar e exibir métricas importantes relacionadas a lojas, usuários e transações. O dashboard fornecerá uma visão clara e intuitiva do desempenho da plataforma, permitindo que administradores e patrocinadores tomem decisões informadas com base em dados.

## 🎯 Objetivos <a name="objetivos"></a>
O projeto integra conhecimentos aprendidos em sala, incluindo:

- Metodologia ágil **SCRUM**
- Análise de requisitos
- Desenvolvimento **Front-end** e **Back-end**
- Design de interfaces
- Integração de **APIs** e **Banco de Dados**

## 🗓️ Cronograma das Sprints <a name="cronograma-das-sprints"></a>
| Sprint       | Previsão      | Status           |
|--------------|---------------|------------------|
| **Kick Off** | 24/02/2025 a 28/02/2025   | ✅ Concluído     |
| **Sprint 1** | 10/03/2025 a 30/03/2025   | 🔄 Em andamento |
| **Sprint 2** | 07/04/2025 a 27/04/2025   | ⏳ A fazer       |
| **Sprint 3** | 05/05/2025 a 25/05/2025   | ⏳ A fazer       |
| **Feira de Soluções** | 29/05/2025       | ⏳ A fazer    |  


## 📊 Product Backlog  <a name="product-backlog"></a>
| Ranking | Prioridade | User Story | Estimativa (1-100) | Sprint | **Req. do Parceiro** |
|---------|------------|------------|------------|--------|----------------------|
| **1**   | **Alta**   | Como Administrador, quero acessar um painel de controle básico, onde posso visualizar os principais indicadores do sistema. | **40**  | Sprint 1 | RF-01 |
| **2**   | **Alta**   | Como administrador, quero que o sistema tenha um banco de dados estruturado para armazenar informações sobre usuários e lojas. | **60**   | Sprint 1 |RNF-02 |
| **3**   | **Alta**   | Como administrador, quero visualizar a distribuição geográfica das lojas e usuários para entender onde a plataforma tem maior impacto. | **40**   | Sprint 3 | RF-04 |
| **4**   | **Média**   | Como patrocinador, quero visualizar o número total de lojas criadas, para entender a abrangência da plataforma. | **40**   | Sprint 3 | RF-02 |
| **5**   | **Média**  | Como patrocinador, quero visualizar o número de usuários impactados para medir o alcance do projeto. | **40**   | Sprint 2 | RF-03 |
| **6**   | **Média**  | Como usuário, quero poder acessar um manual de uso do sistema para entender melhor suas funcionalidades. | **85**   | Sprint 2 | RNF-01 |
| **7**   | **Baixo**  | Como patrocinador, quero que a interface do dashboard seja intuitiva e com design melhorado, incluindo cores nos cards para facilitar a interpretação dos dados. | **45**   | Sprint 2 | RF-01 |





## 📂 Sprint Backlog <a name="sprint-backlog"></a>
### Sprint 1
- Criação de **mockup**.
- Desenvolvimento do **HTML/CSS responsivos**.
- Criação dos principais componentes visuais dos **Dashboards**.
- Modelagem do **Banco de Dados**.
- Conexão entre **Front-end** e **Backend**.

### Sprint 2
- Criação da **API Rest** para consulta de dados.
- Conexão entre **Front-End** e **Banco de Dados** via API.
- Criação de **gráficos básicos** para exibição de métricas.
- Testes da **API**.

### Sprint 3
- Refinamento do **Design**.
- Melhoria da **responsividade** em diferentes dispositivos.
- Criação do **Manual do Usuário**.
- Melhoria de **performance** e tempo de carregamento.
- **Ajustes finais**.

## ✅ Definition of Ready (DoR) <a name="definition-of-ready-dor"></a>

Para que uma tarefa esteja pronta para ser desenvolvida, os seguintes critérios devem ser atendidos:

### 1. Artefatos Necessários
- **Briefing Estruturado** – O contexto e os objetivos da API devem estar documentados.
- **User Story detalhada** – A funcionalidade deve estar descrita no formato correto:  
  *Como [usuário], quero [ação] para que [benefício].*
- **Critérios de Aceitação** – Definição clara do que deve ser entregue para que a User Story seja aceita.
- **Wireframes e Protótipos** – Se a funcionalidade envolver interação visual, os layouts devem estar definidos.
- **Modelos de Dados e Esquema do Banco** – As tabelas, relacionamentos e estrutura do banco de dados devem estar definidos e aprovados.
- **Regras de Negócio Documentadas** – Todas as regras de operação da funcionalidade devem estar descritas.

### 2. Regras Técnicas Definidas
- **Endpoint bem especificado**:
  - URL RESTful definida (ex: `GET /usuarios/{id}`).
  - Método HTTP correto (`GET`, `POST`, `PUT`, `DELETE`).
  - Formato da requisição e resposta **JSON** especificado.
- **Tratamento de Erros Definido** – Respostas esperadas para erros (`400 Bad Request`, `404 Not Found`, etc.).
- **Controle de Versionamento** – Definir versões da API (exemplo: `v1/usuarios`).
- **Performance e Eficiência** – Definir limites de requisição e evitar sobrecarga de dados.

### 3. Testes e Validação
- **Cenários de Teste Criados** – Casos normais e de exceção para validar a funcionalidade.
- **Dados para Testes Disponíveis** – Exemplo: usuários de teste cadastrados no banco de dados.
- **Plano de Testes de Integração** – Garantir que os endpoints funcionam bem com outros sistemas.

### 4. Aprovação e Alinhamento
- A equipe de desenvolvimento e o Product Owner revisaram e concordam que a funcionalidade pode ser desenvolvida.
- O item foi incluído no **Sprint Backlog** e tem estimativa de esforço definida.
- O desenvolvedor responsável compreendeu o escopo da tarefa e tirou dúvidas antes de iniciar.

## **👥 Equipe** <a name="equipe"></a>

| Função           | Nome                  | Links                                                                                                                                      |  
|-------------------|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------|  
| **Product Owner**      | Gustavo Almeida       | [LinkedIn](https://www.linkedin.com/in/gustavo-almeida-camargo/) • [GitHub](https://github.com/GustavoAC0802)                              |  
| **Scrum Master**      | Tatiane Oliveira      | [LinkedIn](https://www.linkedin.com/in/tatiane-oliveira-a66789296/) • [GitHub](https://github.com/TatianeOliveira8)                        |  
| **Dev Team**      | Pedro Alves           | [LinkedIn](https://www.linkedin.com/in/pedro-alves-579a93140/) • [GitHub](https://github.com/pphvaz)                                       |  
| **Dev Team**      | Nicoly Guedes         | [LinkedIn](https://www.linkedin.com/in/nicoly-guedes-dev/) • [GitHub](https://github.com/nicolygz)                                         |  
| **Dev Team**      | Guilherme Almeida     | [LinkedIn](https://www.linkedin.com/in/guilherme-almeida-profile/) • [GitHub](https://github.com/AlmdGuilherme)                            |  
| **Dev Team**      | Pedro Martins         | [LinkedIn](https://www.linkedin.com/in/pedro-henrique-martins-55a0752a4/) • [GitHub](https://github.com/pedro-h-martins)                   |  
| **Dev Team**      | Otávio Vianna         | [LinkedIn](https://www.linkedin.com/in/ot%C3%A1vio-vianna-lima-1b26a932a/) • [GitHub](https://github.com/tuzzooz)                         |  
| **Dev Team**      | Issami Umeoka         | [LinkedIn](https://www.linkedin.com/in/issami-umeoka-786716226/) • [GitHub](https://github.com/IssamiU)                                   |  
| **Dev Team**      | Tiago Freitas         | [LinkedIn](https://www.linkedin.com/in/tiago-freitas-74730b2a9/) • [GitHub](https://github.com/tiagow2)                                   |  

---

