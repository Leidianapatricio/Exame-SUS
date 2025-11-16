# Requisitos de Software  
## ExameSUS  
<small>Versão 1.0</small>  

---

### Histórico de Revisões  
| Data       | Versão | Descrição             | Autores                                |
|-------------|---------|-----------------------|----------------------------------------|
| 20/10/2025  | 1.0     | Criação do documento  | Anderson Sousa, Bruna Priscila, Felipe Cartaxo, Leidiana Nascimento e Mathes Barbosa |

---

## Introdução  
Este documento descreve os requisitos do sistema **ExameSUS**, uma aplicação voltada à gestão e acompanhamento de exames médicos realizados por usuários do **Sistema Único de Saúde (SUS)**.  

O sistema tem como objetivo **facilitar o acesso às informações de saúde**, **reduzir deslocamentos desnecessários** e **aumentar a eficiência no agendamento e acompanhamento de exames**, contribuindo para a **inclusão digital e modernização dos serviços públicos**.  

---

## Definições, Acrônimos e Abreviações  
- **RF** — Requisito Funcional  
- **RNF** — Requisito Não Funcional  

Exemplo: RF001, RNF001.  

---

## Usuários Identificados  
- **Usuário Cidadão:** Pessoa cadastrada no SUS que acessa o sistema para visualizar e acompanhar exames.  
- **Profissional de Saúde:** Funcionário autorizado da unidade de saúde responsável por registrar e atualizar informações sobre exames.  
- **Administrador do Sistema:** Responsável por gerenciar cadastros, permissões e configurações gerais da aplicação.  

---

## Requisitos Funcionais  

### Módulo 1 — Cadastro e Acesso  

**[RF001]** — Como cidadão, quero realizar login no sistema utilizando **CPF** ou **número do cartão SUS**, para acessar minhas informações de exames com segurança.  

**[RF002]** — Como cidadão, quero poder realizar meu próprio cadastramento no sistema, informando CPF, número do Cartão SUS e dados de contato, para obter acesso independente ao aplicativo.  

**[RF003]** — Como profissional de saúde, quero poder cadastrar novos usuários vinculados ao SUS, garantindo que todos os cidadãos tenham acesso ao sistema. 

**[RF004]** — Como administrador, quero poder gerenciar permissões de acesso, definindo quais usuários podem inserir, editar ou visualizar exames.  


---

### Módulo 2 — Gerenciamento de Exames  

**[RF006]** — Como cidadão, quero visualizar a lista de exames agendados e realizados, com informações sobre data, tipo de exame, local e status.  

**[RF007]** — Como cidadão, quero receber notificações automáticas sobre o agendamento e o preparo necessário para os exames, evitando perda de prazos.  

**[RF008]** — Como profissional de saúde, quero registrar novos exames no sistema com dados como tipo, unidade de realização, data e profissional responsável.  

**[RF009]** — Como profissional de saúde, quero atualizar o status dos exames (agendado, em andamento, concluído, cancelado) para manter o histórico atualizado.  

**[RF010]** — Como cidadão, quero consultar os resultados dos exames diretamente no aplicativo, com opção de visualizar o laudo em formato PDF.  

**[RF011]** — Como cidadão, quero baixar o resultado do exame em meu dispositivo, para ter acesso mesmo sem internet.  

**[RF012]** — Como cidadão, quero poder pesquisar exames por nome, tipo ou data, para localizar informações específicas rapidamente.  

---

### Módulo 3 — Histórico e Acompanhamento  

**[RF013]** — Como cidadão, quero visualizar um histórico completo dos meus exames, incluindo resultados anteriores e comparações de dados.  

**[RF014]** — Como profissional de saúde, quero acessar o histórico de exames de um paciente, para auxiliar em diagnósticos e decisões clínicas.  

**[RF015]** — Como cidadão, quero receber lembretes de acompanhamento quando um novo exame de controle for recomendado, promovendo continuidade do tratamento.  

**[RF016]** — Como profissional de saúde, quero gerar relatórios de exames realizados por período ou tipo, para apoiar a gestão da unidade.  

---

### Módulo 4 — Administração e Configurações  

**[RF017]** — Como administrador, quero configurar unidades de saúde (nome, endereço, contato), vinculando-as aos exames registrados.  

**[RF018]** — Como administrador, quero gerenciar cadastros de profissionais de saúde, incluindo cargo, CPF e unidade de trabalho.  

**[RF019]** — Como administrador, quero emitir relatórios gerenciais com estatísticas sobre exames realizados, cancelados ou pendentes, para apoiar decisões da gestão pública.  

**[RF020]** — Como administrador, quero configurar mensagens automáticas de lembrete e confirmação enviadas ao cidadão.  

**[RF021]** — Como administrador, quero visualizar logs de acesso e ações do sistema, garantindo segurança e rastreabilidade.  

---

## Requisitos Não Funcionais  

### Usabilidade  
**[RNF001]** — O sistema deve ter interface simples e intuitiva, compatível com usuários com pouca experiência digital.  
**[RNF002]** — O aplicativo deve ser acessível em dispositivos móveis e desktop, mantendo a mesma clareza visual.  
**[RNF003]** — O sistema deve emitir alertas visuais e sonoros para notificações de exames.  

### Confiabilidade  
**[RNF004]** — O sistema deve manter cópias de segurança automáticas dos dados a cada 24 horas.  
**[RNF005]** — O sistema deve garantir integridade dos dados durante atualizações ou quedas de conexão.  
**[RNF006]** — O histórico de exames deve ser mantido por tempo indeterminado, sem perda de dados.  

### Desempenho  
**[RNF007]** — O sistema deve carregar páginas em até 2 segundos em conexões de baixa velocidade.  
**[RNF008]** — O aplicativo deve ser leve, funcionando corretamente em aparelhos com hardware básico e conexões 3G.  
**[RNF009]** — O envio de notificações deve ocorrer em tempo real após atualização de status do exame.  

### Segurança e Privacidade  
**[RNF010]** — Todas as comunicações devem ser criptografadas (HTTPS).  
**[RNF011]** — O acesso deve exigir autenticação com CPF e senha, com opção de autenticação em dois fatores para profissionais e administradores.  
**[RNF012]** — O sistema deve estar em conformidade com a **LGPD (Lei nº 13.709/2018)**, garantindo o tratamento ético dos dados pessoais.  

### Suportabilidade  
**[RNF013]** — O sistema deve ser compatível com os principais navegadores (Chrome, Firefox, Edge) e sistemas Android e iOS.  
**[RNF014]** — O sistema deve permitir sincronização offline, possibilitando o uso temporário sem internet.  
