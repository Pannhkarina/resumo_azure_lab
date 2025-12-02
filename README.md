# resumo_azure_lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab de Microsoft Azure.

Durante meus estudos iniciais de computação em nuvem com Microsoft Azure, aprendi os principais conceitos fundamentais para começar a trabalhar com serviços de nuvem. Entre os pontos estudados estão:

> ## Criando uma conta gratuita no Azure

Aprendi a configurar uma conta gratuita na plataforma Azure, que oferece créditos iniciais e recursos limitados sem custo, permitindo praticar serviços como máquinas virtuais, armazenamento, bancos de dados e muito mais.

> ## O que é computação em nuvem

Entendi o conceito de computação em nuvem como o fornecimento de recursos de TI (servidores, redes, armazenamento, aplicativos) sob demanda, pela internet, com pagamento conforme o uso.
A nuvem oferece alta disponibilidade, escalabilidade e redução de custos.

> ## Domínio do Objetivo

Compreendi que o domínio do objetivo refere-se a entender o propósito de cada serviço de nuvem, escolhendo o recurso correto para resolver um problema específico — por exemplo: quando usar IaaS, PaaS ou SaaS, ou qual serviço do Azure atende melhor determinada necessidade.

> ## Modelos de Nuvem

Aprendi os três principais modelos:

* IaaS (Infrastructure as a Service) – infraestrutura como serviço; o usuário controla máquinas virtuais, redes e armazenamento.
* PaaS (Platform as a Service) – plataforma gerenciada; foco no desenvolvimento sem precisar administrar servidores.
* SaaS (Software as a Service) – aplicativos completos entregues pela nuvem.

Também estudei os tipos de implantação:

*  Nuvem Pública
* Nuvem Privada
* Nuvem Híbrida

 > ## CapEx x OpEx

Compreendi a diferença entre os modelos de custo:

* CapEx (Capital Expenditure) – investimento inicial em infraestrutura física, comum em datacenters tradicionais.

* OpEx (Operational Expenditure) – custos operacionais pagos conforme o uso, como acontece na nuvem.
A computação em nuvem reduz CapEx e aumenta a flexibilidade de OpEx.


# Benefícios da Computação em Nuvem

 > ##  Alta Disponibilidade

A nuvem oferece sistemas projetados para ficar disponíveis a maior parte do tempo, com SLAs que podem chegar a:

* 99% (até ~7h/mês de inatividade)
* 99,9% (até ~44 min/mês)
* 99,99% (até ~4 min/mês)
* 99,999% (até ~26 s/mês)

Quanto maior o SLA, maior a confiabilidade do serviço.

 > ## Escalabilidade e Elasticidade

* Escalabilidade: capacidade de aumentar ou diminuir recursos conforme a demanda (ex.: subir de uma VM pequena para uma maior).
* Elasticidade: ajuste automático dos recursos conforme o uso. A nuvem expande ou reduz a carga conforme necessário.

 > ## Confiabilidade

Serviços na nuvem são projetados para tolerar falhas, replicar dados e manter a continuidade de negócios.
Azure utiliza redundância regional e geográfica para manter sistemas operando mesmo diante de falhas.

 > ## Previsibilidade

A nuvem permite prever:

Desempenho (através de recursos configuráveis e monitoramento)
Custos (com modelos de cobrança baseados em uso e ferramentas de estimativa)

 > ## Segurança

Envolve proteção de dados, identidades e redes com ferramentas como:

* Criptografia
* Identidade e acesso (IAM)
* Monitoramento de ameaças
* Firewalls e políticas avançadas
* Segurança na nuvem segue o modelo de responsabilidade compartilhada entre cliente e provedor.

 > ## Governança

Conjunto de políticas e regras para padronizar recursos, controlar custos e garantir conformidade.
Ferramentas como Azure Policy, Blueprints e tags ajudam na organização e controle.

 > ## Gerenciabilidade

A nuvem permite gerenciar todos os recursos a partir de portais centralizados e APIs, garantindo:

* Monitoramento
* Automação
* Logging
* Alertas
* Gestão simplificada de recursos e ambientes

> ##  IaaS, PaaS e SaaS

### IaaS (Infrastructure as a Service):
Oferece infraestrutura básica de TI como máquinas virtuais, redes e armazenamento. O cliente gerencia o sistema operacional e aplicativos.

### PaaS (Platform as a Service):
Fornece uma plataforma completa para desenvolvimento, permitindo criar, testar e implantar aplicações sem gerenciar servidores.

### SaaS (Software as a Service):
Aplicativos completos fornecidos pela internet, já prontos para uso. O usuário apenas consome o serviço (ex.: Outlook, Teams, Salesforce).

> ##  Modelo de Responsabilidade Compartilhada

Na computação em nuvem, a segurança é dividida entre provedor e cliente:
### Azure é responsável por:

Segurança da nuvem (infraestrutura física, datacenters, hardware, rede, hypervisor).
Conformidade global e proteção estrutural de dados.

### O cliente é responsável por:
Segurança na nuvem (configurações de acesso, dados, identidades, políticas, senhas, firewalls).
Gerenciar aplicativos, usuários e configurações de segurança internas.
