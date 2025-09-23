# 🕵️  Resumo do Lab: Ferramentas de Monitoramento Microsoft Azure AZ-900
Este repositório reúne os principais aprendizados adquiridos durante o curso **Ferramentas de Monitoramento Azure** da plataforma [DIO.me](https://web.dio.me), Gerenciamento e Governança na Azure - Módulo 3.
O foco está nos benefícios e aplicações práticas da plataforma Microsoft Azure, explorando seus recursos e funcionalidades. O Bootcamp oferece uma base sólida em tecnologias de nuvem, abordando desde os conceitos fundamentais até os componentes essenciais da arquitetura Azure.
Entre os temas estudados estão: criação e gerenciamento de máquinas virtuais, configuração de bancos de dados e soluções de armazenamento, além de tópicos avançados como arquitetura em nuvem, governança, monitoramento e segurança de ambientes cloud.

---
## 📘Tópicos Abordados
As ferramentas de monitoramento do Azure são essenciais para gerenciar a performance, a disponibilidade e a segurança dos seus recursos na nuvem. A seguir, falaremos sobre essas três ferramentas que trabalhadas nos mostram uma visão completa e proativa da infraestrutura na nuvem. 
Enquanto o Domínio de Objetivo permite que se defina o que monitorar, o Azure Advisor ajuda a otimizar e melhorar os recursos, e o Azure Service Health o mantém informado sobre a saúde do próprio Azure.

---
## 🧭 Domínio de Objetivo (Targeting Scope)

O Domínio de Objetivo define quais recursos do Azure serão incluídos ou excluídos das análises e alertas.

### Exemplos de escopo:
- **Uma assinatura inteira**: visão geral de todos os recursos.
- **Um grupo de recursos específico**: ideal para ambientes como produção ou desenvolvimento.
- **Um recurso individual**: foco em VMs, bancos de dados ou apps web.

### Inclui:
- Ferramentas de diagnóstico e análise (Azure Monitor, Log Analytics)
- Alertas e métricas
- Monitoramento de integridade e disponibilidade

---

## 🖥️ Azure Monitor

Plataforma de observabilidade que coleta, analisa e responde a dados de telemetria de recursos no Azure, outras nuvens e ambientes locais.

### Benefícios:
- Detecta problemas rapidamente
- Visualiza desempenho de apps e infraestrutura
- Automatiza respostas a eventos críticos
- Gera alertas e relatórios personalizados

### 🔧 Componentes Principais:
- **Log Analytics**: análise de logs com linguagem de consulta poderosa
- **Application Insights**: monitora apps web e detecta falhas
- **Métricas**: dados numéricos em tempo real
- **Alertas**: notificações automáticas e ações
- **Dashboards**: painéis interativos

---

## 📊 Recursos Monitorados

- Máquinas Virtuais
- Aplicativos Web
- Bancos de Dados
- Recursos de Rede
- Clusters Kubernetes
- Ambientes híbridos e multinuvem

---

## ⚙️ Funcionalidades Avançadas

- **Rastreamento distribuído**: acompanha chamadas entre serviços
- **Exportação de dados**: integração com SIEMs, Power BI
- **Integração com terceiros**: Grafana, Prometheus etc.
- **Escalonamento automático**: aumenta recursos conforme a carga

---

## 💸 Custo

O custo depende de:
- Volume de dados ingeridos
- Tempo de retenção
- Funcionalidades extras (testes web, notificações)

💡 *Economize até 36% com reservas de capacidade.*

---

## 📌 Exemplos de Uso

- Equipe de TI detecta lentidão antes dos usuários
- Administrador configura alertas para reiniciar serviços
- Empresa acompanha KPIs em tempo real com dashboards

---

## 👩‍💻 Assistente do Azure (Azure Advisor)

Ferramenta inteligente que analisa telemetria e oferece recomendações personalizadas.

### Categorias de recomendação:
- **Confiabilidade**: backups, zonas de disponibilidade
- **Segurança**: identifica vulnerabilidades
- **Otimização de Custos**: redimensiona VMs, remove recursos não usados
- **Excelência Operacional**: automatiza tarefas, configura alertas
- **Otimização de Performance**: melhora velocidade e resposta

---

## ❤️‍🩹 Integridade do Serviço Azure (Azure Service Health)

Painel personalizado que mostra a saúde dos serviços do Azure usados.

### Diferença entre:
- **Azure Status**: visão global pública
- **Service Health**: visão personalizada por assinatura/região

### Informações fornecidas:
- **Problemas de Serviço**: interrupções atuais
- **Manutenção Planejada**: eventos que podem afetar desempenho
- **Avisos de Integridade**: alertas relevantes, mesmo que indiretos

💡 *Ideal para saber se o problema está no seu ambiente ou é global.*

---

## ✅ Conclusão
As ferramentas de monitoramento do Azure são a base para uma gestão de nuvem eficaz e proativa. O **Azure Advisor**, a **Integridade do Serviço do Azure** e o **Domínio de Objetivo** se complementam para formar um ecossistema robusto.
Juntas, essas ferramentas capacitam as equipes a sair de uma abordagem reativa e ir para uma abordagem mais estratégica, garantindo que suas cargas de trabalho na nuvem sejam confiáveis, seguras e eficientes em termos de custo.
As ferramentas de monitoramento do Azure — **Domínio de Objetivo**, **Azure Monitor**, **Azure Advisor** e **Azure Service Health** — formam um ecossistema robusto que permite uma gestão proativa, estratégica e eficiente da nuvem.

---
> Este conteúdo faz parte do projeto **Monitoramento Inteligente com o Azure - Laboratório** da plataforma [DIO.me](https://web.dio.me).

---
 
### 📚 Recursos Adicionais
- [O que é o Microsoft Entra?](https://learn.microsoft.com/pt-br/entra/fundamentals/what-is-entra)
- [Introdução ao Azure Advisor](https://learn.microsoft.com/pt-br/azure/advisor/advisor-overview)
- [Visão geral do Resource Health](https://learn.microsoft.com/pt-br/azure/service-health/resource-health-overview)
- [Log Analytics no Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/logs/log-analytics-overview?tabs=simple)
- [Agente do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/agents/azure-monitor-agent-manage?tabs=azure-portal)
- [Agente do Azure Monitor](https://learn.microsoft.com/pt-br/azure/azure-monitor/agents/azure-monitor-agent-overview?source=recommendations)
- [Azure Monitor](https://azure.microsoft.com/pt-br/products/monitor/?msockid=2f267db490ab678b012b6bc491bf6601)
- [Assistente do Azure](https://azure.microsoft.com/pt-br/products/advisor/?msockid=2f267db490ab678b012b6bc491bf6601)
- [Calculadora de Preços Azure](https://azure.microsoft.com/pt-br/pricing/calculator/?ef_id=_k_EAIaIQobChMI14z7o_fWjwMVc0FIAB3PYQApEAAYASACEgLE-fD_BwE_k_&OCID=AIDcmmzmnb0182_SEM__k_EAIaIQobChMI14z7o_fWjwMVc0FIAB3PYQApEAAYASACEgLE-fD_BwE_k_&gad_source=1&gad_campaignid=1635078708&gbraid=0AAAAADcJh_s0nlhmSLvv4COb6oAkGNm0s&gclid=EAIaIQobChMI14z7o_fWjwMVc0FIAB3PYQApEAAYASACEgLE-fD_BwE)
- [Assinatura do Azure](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/azure-subscription-service-limits)
  
📎 Link do curso: [Microsoft Azure AZ-900 - DIO.me](https://web.dio.me/track/microsoft-azure-az-900)
