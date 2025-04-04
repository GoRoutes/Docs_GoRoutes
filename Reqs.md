

## 📜 Requisitos Funcionais (RF)

- **Dashboard Administrativo**
- **CRUD para:**
  - Alunos (dados pessoais, endereço, responsáveis).
  - Rotas (origem, destino, paradas, horários).
  - Motoristas (dados cadastrais, histórico de rotas).
  - Veículos (dados como placa, modelo, capacidade).
  - Responsáveis (vinculação e permissões).
  - Registro de logs (histórico de ações: edições, exclusões).
- **Gestão de Rotas Inteligentes**
  - Recomendação automática da melhor rota ao cadastrar um novo aluno.
  - Recálculo automático de rotas após atualizações nos cadastros (opcional).
  - Definição de rotas de backup para contingência.
- **Controle em Tempo Real**
  - Rastreamento via GPS dos veículos (opcional).
  - Exibição de previsão de chegada (ETA) para alunos e responsáveis.
- **Interação com Alunos e Responsáveis**
  - Registro de presença e solicitação de retorno antecipado.
  - Solicitação de desembarque alternativo com autorização dos responsáveis.
  - Notificações automáticas para mudanças de rota, atrasos ou emergências.
- **Monitoramento e Dados**
  - Registro completo do histórico de rotas e eventos.
  - Exibição de foto e número do veículo para identificação.
  - Restrição para edições realizadas por motoristas.

---

## 🔧 Requisitos Não Funcionais (RNF)

- **Backup e Resiliência**
  - Armazenamento seguro do histórico de rotas para auditoria.
  - Redundância de dados para prevenir falhas de conexão.
- **Usabilidade e Interface**
  - Interface amigável e intuitiva.
  - Mapa interativo com sobreposição das rotas.
- **Integração e Tecnologia**
  - Integração com APIs de geolocalização (Google Maps, Mapbox).
  - Sistema de notificações via app, e-mail e SMS.
  - Uso de banco de dados relacional robusto (PostgreSQL ou MySQL).
- **Desempenho e Disponibilidade**
  - Atualização em tempo real dos dados.
  - Escalabilidade para suportar aumento da base de usuários.
- **Plataforma Móvel**
  - Desenvolvimento de aplicativo móvel nativo ou PWA.

---

## 📌 Regras de Negócio (RN)

- **Gestão Integrada do Transporte Escolar**
  - Atender de forma centralizada administradores, motoristas, alunos e responsáveis.
- **Otimização Operacional**
  - Automatizar processos e gerenciar rotas de forma inteligente.
- **Segurança e Confiabilidade**
  - Assegurar a segurança dos usuários e conformidade com as regras estabelecidas.
- **Escalabilidade e Auditoria**
  - Permitir crescimento do sistema e auditoria detalhada das operações.

---
