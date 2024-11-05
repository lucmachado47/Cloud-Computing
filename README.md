# Cloud-Computing

## O que é a computação em nuvem?

Computação em nuvem é a virtualização dos serviços de computação, fornecendo esses serviços via internet. Com a computação em nuvem, é possível acessar recursos de computação de forma escalável e pagar apenas pelo que se usa, promovendo inovações rápidas, flexibilidade nos recursos e economia de escala.

## Benefícios da Computação em Nuvem
- Escalabilidade: permite aumentar ou diminuir os recursos de acordo com a demanda.
- Acessibilidade: usuários podem acessar os serviços de qualquer local com conexão à internet.
- Redução de Custos: elimina a necessidade de investimento inicial em infraestrutura física.
- Backup e Recuperação de Desastres: facilita a recuperação de dados e a continuidade dos negócios.
- Segurança: grandes provedores de nuvem oferecem proteção contra ameaças e conformidade com regulamentações.

## Modelos de Nuvem

### A computação em nuvem pode ser dividida em quatro modelos principais:
- `Nuvem privada:`
  - Ambientes em nuvem no próprio datacenter.
  - As organizações são responsáveis por operar os serviços que fornecem.
  - Não fornece acesso aos usuários fora da organização.
- `Nuvem pública:`
  -  São pertencentes a provedores de hosting.
  -  Forneceem recursos a várias organizações e usuários.
  -  Acessada via conexão de rede segura.
- `Nuvem híbrida:`
  - Combina os dois modelos de nuvens anteriores para permitir que os aplicativos sejam executados no local mais adequado.
- `Multicloud:`
  - Combinam serviços de nuvem de pelo menos duas nuvens diferentes.

## Despesas `CapEx` e `Opex`
As despesas relacionadas à infraestrutura de TI são divididas entre CapEx (Capital Expenditure) e OpEx (Operational Expenditure):

### Capex (despesa de capitais)
- São despesas relacionadas à aquisição de infraestrutura de TI, como datacenters, servidores, mobiliário e refrigeração.
- Esse custo inicial tende a diminuir com o tempo, pois o investimento é feito uma vez, enquanto os custos contínuos para manter a infraestrutura são pagos posteriormente.
  
### Opex (despesas operacionais)
- São despesas contínuas para operar e manter a infraestrutura, como consumo de energia, internet, manutenção e atualizações de software.

## Modelo de Consumo
Os provedores de serviços em nuvem adotam um modelo de pagamento conforme o uso, ou pay-as-you-go. Isso significa que os recursos podem ser aumentados ou reduzidos de acordo com a demanda, e os custos são cobrados com base no uso efetivo.

# Principais Fornecedores de Nuvem

### Alguns dos principais provedores de computação em nuvem incluem:
- Amazon Web Services (AWS): conhecida pela variedade de serviços e presença global.
- Microsoft Azure: integrada com o ecossistema Microsoft, popular em ambientes corporativos.
- Google Cloud Platform (GCP): forte em soluções de análise de dados e aprendizado de máquina.

## Principais benefícios da computação em nuvem

- `Alta disponibilidade:` Refere-se aos serviços entregáveis. Se concentra em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer.
- `Escabilidade:` Refere-se à capacidade de ajustar recursos para atender as demandas.
- `Elasticidade:` Refere-se à capacidade de expandir os recursos atráves de um salto repentino acentuado na demanda, da mesma forma em que podem ser reduzidos nas quedas de demanda.
- `Confiabilidade:` Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente.
- `Previsibilidade:` Permite que você avance com confiança, seja no desempenho ou no custo.
- `Segurança:` A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes, mas a implementação de muitas são feitas pelo próprio usuário.
- `Governança:` A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora da conformidade com seus padrões corporativos e fornece estratégias de mitigação.
- `Gerenciabilidade:` Um dos principais benefícios da Cloud Computing são as opções de capacidade de gerenciamento dos recursos na nuvem.

## Service Level Agreement (SLA)
É um documento que pretende gerir as expectativas do fornecedor de serviços e do cliente, relativamente à qualidade do serviço entregue, medindo e validando se os parâmetros previamente acordados são cumpridos.

## Tempo Estimado de Não Conformidade com a Disponibilidade Esperada

| Objetivo | Não Conformidade por Semana | Não Conformidade por Mês | Não Conformidade por Ano |
|----------|-----------------------------|---------------------------|---------------------------|
| 99%      | 1,68 horas                  | 7,20 horas               | 3,65 dias                 |
| 99,90%   | 10,10 minutos               | 43,20 minutos            | 8,76 horas                |
| 99,95%   | 5 minutos                   | 21,60 minutos            | 4,38 horas                |
| 99,99%   | 1,01 minuto                 | 4,32 minutos             | 52,56 minutos             |
| 99,999%  | 6 segundos                  | 25,90 segundos           | 5,26 minutos              |

# Serviços de Nuvem: IaaS, PaaS e SaaS

## Tipos de Serviço de Nuvem

A computação em nuvem oferece diferentes tipos de serviços para atender às necessidades de usuários e empresas. Eles incluem:

### 1. IaaS (Infrastructure as a Service)
   - **Descrição**: Fornece infraestrutura de TI virtualizada pela internet, incluindo máquinas virtuais, armazenamento e redes.
   - **Exemplos**: Microsoft Azure, Amazon Web Services (AWS), Google Compute Engine.
   - **Uso Comum**: Permite a criação de servidores virtuais e configuração de redes com controle total do sistema operacional e armazenamento, ideal para empresas que querem gerenciar sua própria infraestrutura.

### 2. PaaS (Platform as a Service)
   - **Descrição**: Fornece uma plataforma completa que inclui infraestrutura, middleware e ferramentas para desenvolvimento e execução de aplicações.
   - **Exemplos**: Azure App Service, Google App Engine, Heroku.
   - **Uso Comum**: Ideal para desenvolvedores que querem criar, testar e implantar aplicativos rapidamente sem gerenciar infraestrutura subjacente.

### 3. SaaS (Software as a Service)
   - **Descrição**: Oferece software acessível via navegador, gerenciado pelo provedor e utilizado diretamente pelo usuário.
   - **Exemplos**: Microsoft 365, Google Workspace, Salesforce.
   - **Uso Comum**: Aplicativos prontos para uso, onde o provedor cuida de tudo, como manutenção, segurança e atualizações.

## Modelo de Responsabilidade Compartilhada

O modelo de responsabilidade compartilhada define as responsabilidades do provedor de nuvem e do cliente para garantir segurança e gerenciamento de dados. 

- **Provedor de Nuvem**: Responsável pela segurança da infraestrutura subjacente, incluindo hardware, redes e centros de dados.
- **Cliente**: Responsável pela segurança dos dados, configuração de rede e gerenciamento de contas de usuário dentro do ambiente contratado.

O grau de responsabilidade varia de acordo com o tipo de serviço:
- **IaaS**: O cliente tem maior responsabilidade, incluindo o gerenciamento de sistemas operacionais e dados.
- **PaaS**: O cliente é responsável pelos dados e pela gestão das aplicações, enquanto o provedor cuida do ambiente de execução.
- **SaaS**: O provedor gerencia a maior parte do serviço, enquanto o cliente foca no gerenciamento de acesso e nos dados utilizados.

Esse modelo garante uma divisão clara para que tanto o provedor quanto o cliente saibam quais partes são de sua responsabilidade, promovendo maior segurança e eficiência na gestão de dados e infraestrutura.


