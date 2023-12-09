
# Inteligência de ameaças e Hunting

Rever conteúdo - estava na estrada no começo

Professor - Vagner Florindo, perdi a introdução dele

# Definição de inteligência de ameaças

Sun Tzu - Conhecer o inimigo **e** a si mesmo.

Alan Turing - Quebra do código da máquina alemã *enigma*

**Inteligência de ameaças** - Cyber Threat Intelligence - reune e analisa as ameaças e as correlaciona com a org. e o ambiente

**Informação acionável** - Infos que podem levar a etapas que terão impacto na seg. do seu público alvo
Ao receber uma informação acionável devemos entender imediatamente como fazer o **melhor uso possível**

**CSIRT** - Computer Security Incident Response Team, coleta dados de rede, threat intelligence, ativos, infra, dados históricos vs atuai, passivo / reativo x proativo

# Fontes de inteligência de ameaças

Fontes automatizadas são mais baratas, geram mais dados, mas geram muitos dados que não são tão relevantes.
As manuais são muito mais caras (pelo custo de pessoal capacitado) mas geram muito menos dados, porém de forma mais precisa.

Também temos que fontes internas são mais confiáveis que as externas.

Outro ponto é se a fonte já é conhecida, é importante reavaliar a confiança desta, mas são mais confiáveis que fontes desconhecidas.

É importante manter a **heterogeneidade** dos dados coletados de diferentes fontes, isso é a **normalização**. Não existe solução universal.

A **agregação** é o desafio seguinte, unificando dados que resultam o mesmo.

Seguindo com o **enriquecimento** buscando melhorar a integridade dos dados, melhorando também a precisão dos dados. Filtre, elimine, aproveite e ajuste.

Lembrando que a **automação** é um processo crucial em todas as etapas.

Mesmo após todas as etapas aplicadas, os **dados brutos não perdem sua importância e precisam ser armazenados**, podendo ser úteis nas análises finais.

Após a etapa de preparação, vem o **armazenamento**
O primeiro desafio é o tempo de retenção desse dados, conforme requerimentos legais e limitações técnicas.
Tendo o dado armazenado, a gestão é crucial, comum entre conjuntos, metadados e etc.

# Análise de ameaças 

## Hunting 

**Hunting** se refere a análise exploratória - pesquisando proativamente as atividades maliciosas, descobrindo anomalias e ameaças. **Não é Pentest!** O objetivo é identificar ações indevidas que estão ocorrendo na rede da empresa, se o *hunting* identificou, é uma ameaça real na sua empresa, que esta sendo executada ou aconteceu. Exemplos são:
- Identificar campanhas de fraude
- Detectar anomalias de netflow
- Redes de sensores - análise de tráfego
- Monitorando infraestrutura e ferramentas maliciosas
- Cluster de malware
- Agreg. de vulnerabilidade, relatórios de incidentes (Taranis)

## Consciência situacional

Fundamental, é uma visão ampla da situação atual, entendo o contexto e se preparando para possíveis ataques.
Aqui automação e a inteligência humana atuam em conjunto
Quando ocorre um ataque é crucial entender o que aquilo significa.

## Suporte à análise através da visualização 

- Gráficos de links -> Indicando a origem e abrindo por níveis.
- Baseada em tempo -> Histograma
- Gráficos de dispersão

# Indicação de livros


Michael Bazzell - Vários livros na área, o pai da área