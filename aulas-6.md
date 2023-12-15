
# Practical Cyber Threat Intelligence

Instrutor: Danilo Costa

## Dicas de livro

- *Visual Threat Intelligence, An Illustrated Guide for Threat Researches* - ROCCIA, Thomas
- *Building Cyber Threat Intelligence Capabilities for Organizations* - VIDAL, Robert
- *Find Bad, A Guide for Breaking into the Cyber Threat Intelligence Industry* - BAEZ, Miguel

## Ciclo de vida de CTI - Cyber Threat Intelligence

HUMINT / SOCMINT / OSINT - Metodologias mais famosas de intel.

### Fase de planejamento

- **Planejamento e direcionamento** - Coletar infos com o negócio, buscando entender o propósito do que se quer produzir. Para produzir uma boa intel é crucial entender bem o seu **consumidor**, qual o modelo de negócio, qual ramo que atua, quem são seus clientes, seus produtos, suas tecnologias e etc.

- **Threat Profile** - Entender o negócio/cliente para compreender quais as ameaças que podem afetar, de forma **oportuna** (fazer por que é possível/fácil), da **industria**, **próximas** e **ameaças diretas** (adversários conhecidos, com base no histórico de reposta a incidentes)

Entenda as **ameaças** e entenda seu **cliente** e sua **necessidade**!

### Fase de coleta de dados

- **Coleta de dados** - Onde buscar os dados para a necessidade do negócio? Busco em diferentes fontes dados para produzir intel. Aqui se sustenta a necessidade da intel, aqui, como em tudo em CTI, não existe bala de prata.

- **TIP** - Threat Intelligence Platform - Exemplos são: *Cyware*, *Anomali*, **Mandiant Advantage**, Kela, Silobreaker, *digital shadows*, *intel471*, *flashpoint*, *recorded future*...

- **Data Sources** - Exemplos - Pastebin, Grayhat Warfare, circl, abuse, social media, github, deep & dark web, surface web, crt.sh, urlscan.io, pulsedive, alien vault, dnslytics, censys, shodan, virustotal, intelligenceX, skopenow, pipl, domainTools - Novamente, cada fonte tem um propósito distinto, para atender a uma ou mais necessidades, mas nunca todas.

### Fase de análise e produção

- **Processamento e exploração das informações** - Modelar, tratar e cruzar os dados para armazenar. A fase mais crucial de um programa de inteligência.

- **Análise e produção de inteligência** - Enriquecimento e contextualização dos dados, além da intel humana aqui já se aplica IA e ML, aqui que é onde trabalha o analista de CTI, independente das ferramentas, ele é quem produz a intel acionável de fato. Importante aqui ter várias pessoas que formem um time **multidisciplinar**


### Fase de disseminação e integração

- **Divulgação** - Aqui a intel produzida é divulgada, importante ressaltar a diferença dessa comunicação conforme quem recebe a mensagem, tática, operacional ou estratégica. Podem ser alertas de ameaça, *reports* semanais e etc, novamente, a depender da realidade do negócio/time.

- **MISP** - Malware Information Sharing Platform - Projeto *Open-source* que auxilia no compartilhamento de informação de forma **padronizada**, facilitando a troca de informações ricas entre várias comunidades através do mundo. Também é possível integrar com outras fontes de segurança, como firewalls, enriquecimento de eventos e etc.

#### Integração com outras áreas de negócio

- Adversary Intelligence - Enriquecer alertas, contextualizar ataques
- Vulnerability Intelligence - Priorizar correção de vulnerabilidades
- Fraud intelligence - Fraude em produtos, modus
- Brand Intelligence - Falsos apps, websites, perfis

## CTI Analyst

Competências, habilidades e conhecimentos

- **Problem solving** - Pensamento crítico, pesquisa e análise, pensamento investigativo
- **Professional Effectiveness** - Comunicação, trabalho em equipe e inteligência emocional
- **Technical Literacy** - Redes corporativas, cybersecurity ecossistema, cybersecurity roles e responsabilidades
- **Cyber Threat Proficiency** - Parte ofensiva, conceitos de ameaças e frameworks, threat actors e TTPs

Tem mais guias no material, lembrar de baixar depois!

# Threat Hunting

Instrutor Wellington

**Threat hunting** é a técnica **proativa** voltada para a busca de indicadores de ataques e evidências deixadas no ambiente.

A palavra *proativa* é o mais forte da área, o Threat Hunting não espera por nenhum alerta.

É uma área que se destaca o conhecimento humano, justamente por essa abordagem de agir onde demais ferramentas não identificaram anomalias.

**Objetivo** é 
- Controles de segurança
- Defesa ativa
- Identificar o que não foi mapeado pelas demais ferramentas
- conter incidentes antecipadamente

## Pilares do Threat Hunting

- Ativos
- Ameaças
- Atores

## Modelos de Threat Hunting

- Baseado em inteligência - IOCs (indicadores de comprometimento)
- Baseado em hipóteses - analytics, inteligência, conhecimento situacional
- Baseado em IOAs (indicadores de ataque)