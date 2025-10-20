
# 🩺 Visão do Produto — ExameSUS  
**Versão 1.0**

---

## 📜 Histórico de Revisões

| Data       | Versão | Descrição do Documento | Autor(es) |
|-------------|--------|------------------------|------------|
| 14/10/2025  | 1.0    | Criação do documento   | Bruna Leidiana Nascimento Patricio, Joana Elise Araújo Lopes, Jonata Barbosa, Matheus Barbosa Firmino de Souza |

---

## Introdução

O Documento de Visão do Produto (DVP) descreve o sistema **ExameSUS**, um aplicativo voltado à modernização do serviço público de saúde.  
Ele define o problema a ser resolvido, as necessidades dos cidadãos e profissionais de saúde, as funcionalidades principais e as restrições do projeto.

---

## Propósito

Desenvolver um **aplicativo web e mobile** que permita ao cidadão acessar informações sobre seus exames realizados pelo SUS, incluindo notificações de agendamento, preparo e resultados, promovendo **inclusão digital e eficiência** no atendimento público.

---

## Definições e Abreviações

### Abreviações

| Termo | Definição |
|--------|------------|
| DVP | Documento de Visão do Produto |
| SUS | Sistema Único de Saúde |
| LGPD | Lei Geral de Proteção de Dados |
| CPF | Cadastro de Pessoa Física |
| CNS | Cartão Nacional de Saúde |
| API | Application Programming Interface |
| SMS | Secretaria Municipal de Saúde |

### Definições

| Termo | Definição |
|--------|------------|
| Cidadão | Usuário do SUS que acessará suas informações de exames pelo aplicativo. |
| Servidor Público | Profissional que atua nas unidades de saúde e alimenta o sistema com dados de exames. |
| Agendamento | Registro digital da data e local onde o exame será realizado. |
| Resultado de Exame | Documento digital emitido após o processamento dos exames realizados pelo SUS. |
| Notificação Automática | Alerta enviado pelo aplicativo para lembrar o cidadão sobre o agendamento e o preparo do exame. |

---

## Escopo do Produto

O **ExameSUS** tem como objetivo facilitar o acesso do cidadão às informações de saúde, permitindo acompanhar exames agendados e realizados pelo SUS, sem necessidade de deslocamento até a unidade.  
O sistema oferecerá **notificações automáticas**, **histórico de exames** e **acesso seguro via CPF e Cartão SUS**, contribuindo para a **transformação digital e modernização** dos serviços públicos municipais.

---

## Posicionamento

### Oportunidade de Negócios

A transformação digital da saúde pública é uma necessidade crescente.  
Muitas prefeituras ainda dependem de processos manuais para controle de exames, o que gera atrasos, perda de informações e desorganização.  

O **ExameSUS** surge como uma **solução municipal inovadora**, capaz de automatizar notificações, reduzir custos e melhorar a comunicação entre cidadão e sistema público de saúde.

---

## Descrição dos Benefícios e Problemas Resolvidos

| Benefícios | Problemas Resolvidos | Afetados |
|-------------|----------------------|-----------|
| Acesso rápido e seguro às informações de exames | Falta de comunicação sobre agendamentos e resultados | Cidadãos usuários do SUS |
| Redução de deslocamentos | Necessidade de ir presencialmente à unidade para obter informações | Pacientes e unidades de saúde |
| Aumento da eficiência no atendimento | Exames não realizados por esquecimento ou falta de notificação | Secretaria Municipal de Saúde |
| Inclusão digital | Dificuldade de acesso à informação para cidadãos com baixa familiaridade tecnológica | População em geral |
| Redução de custos operacionais | Desperdício de recursos com reagendamentos e exames perdidos | Gestores públicos |

---

## Descrição dos Stakeholders e Usuários

### Stakeholders

| Stakeholder | Descrição | Papel |
|--------------|------------|--------|
| Secretaria Municipal de Saúde (SMS) | Órgão responsável pela administração da saúde no município. | Parceira institucional e mantenedora do sistema. |
| Equipe de Desenvolvimento | Grupo de desenvolvedores e analistas responsáveis pelo ExameSUS. | Implementar e manter o sistema. |
| Servidores das Unidades de Saúde | Funcionários que inserem dados de agendamentos e resultados. | Usuários internos do sistema. |
| Cidadãos Usuários do SUS | População atendida pelas unidades de saúde do município. | Usuários finais do aplicativo. |
| Gestores Públicos | Autoridades responsáveis pela gestão de dados e relatórios. | Acompanhar métricas e resultados. |

### Usuários e Atores

| Usuário/Atores | Descrição | Responsabilidades | Stakeholders Relacionados |
|-----------------|------------|-------------------|----------------------------|
| Cidadão | Usuário que acessa o aplicativo para acompanhar exames. | Consultar histórico, receber notificações e resultados. | SMS, Equipe de Desenvolvimento |
| Servidor Público | Funcionário responsável por registrar informações de exames. | Inserir e atualizar dados de agendamento e resultados. | SMS |
| Administrador do Sistema | Responsável por gerenciar usuários e garantir o funcionamento do sistema. | Cadastrar, manter e supervisionar o ambiente do ExameSUS. | Equipe de Desenvolvimento, SMS |

---

## Descrição do Ambiente de Uso

### Ambiente de Uso

O sistema **ExameSUS** será utilizado em dois principais contextos:

- **Por cidadãos:** via aplicativo mobile ou navegador web simples.  
- **Por servidores de saúde:** via computadores nas unidades de saúde municipais.

### Ambiente físico
- Unidades básicas de saúde (UBS) e laboratórios conveniados ao SUS.  
- Residências dos cidadãos com acesso à internet.

### Dispositivos
- Smartphones, tablets ou computadores com acesso à internet.

### Sistema Operacional
- Android, iOS e navegadores web (Windows, Linux, macOS).

### Conectividade
- Compatível com redes de baixa velocidade (3G, Wi-Fi público ou instável).

### Qualidade esperada
- Interface simples e acessível.  
- Tempo de resposta rápido (até 10 segundos).  
- Disponibilidade mínima de 99%.

---

## Requisitos de Tecnologia

### Ambiente de Execução
- Aplicativo web e mobile (**PWA – Progressive Web App**).  
- Compatibilidade com navegadores leves (Chrome, Edge, Firefox).

### Infraestrutura
- Hospedagem em nuvem (AWS ou Azure).  
- Criptografia de dados e autenticação via CPF + Cartão SUS.  
- Backup automatizado e controle de acesso.

### Tecnologias sugeridas
- **Frontend:** React.js / Flutter  
- **Backend:** Node.js / Django  
- **Banco de Dados:** PostgreSQL ou Firebase  


---

## Visão Geral do Produto

O **ExameSUS** é uma solução digital voltada para o acompanhamento de exames realizados pelo SUS, permitindo que o cidadão visualize suas informações em tempo real.  
A proposta visa **modernizar o serviço público de saúde**, reduzindo deslocamentos, filas e falhas de comunicação, além de promover **inclusão digital**.

O sistema funcionará via web e mobile, com **interface acessível e design responsivo**, compatível com aparelhos simples e internet de baixa qualidade.

---

## Características e Funcionalidades de Alto Nível

- **Acesso Cidadão:** Login por CPF e Cartão SUS  
- **Consulta de Exames:** Histórico e resultados disponíveis em formato digital  
- **Notificações Automáticas:** Alertas de agendamento, preparo e resultado  
- **Integração com Unidades de Saúde:** Sincronização de dados com sistemas locais  
- **Acessibilidade:** Interface adaptada para idosos e pessoas com baixa alfabetização digital  
- **Painel Administrativo:** Controle de usuários e relatórios de desempenho  
- **Segurança:** Criptografia, autenticação e conformidade com a LGPD

---

## Restrições

| Tipo | Descrição |
|-------|------------|
| Orçamento | Projeto piloto sem orçamento |
| Tempo | Desenvolvimento em até 12 meses |
| Segurança | Conformidade com a LGPD obrigatória |
| Usabilidade | Interface otimizada para aparelhos simples |
| Interoperabilidade | Integração inicial apenas com o sistema local da Secretaria de Saúde |
| Escopo Geográfico | Fase inicial restrita ao município; expansão prevista após validação |

---
