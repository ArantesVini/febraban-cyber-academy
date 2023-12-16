
# Operações e resposta a Incidentes

Tanto no Brasil como no mundo todo, **incidentes ocorrem todo o tempo**, em empresas dos mais diversos portes, segmentos e níveis de tecnologia.

**Incidente Cibernético** É uma questão de *QUANDO*, e não *SE*, o comprometimento ou violação de segurança de sua empresa vai acontecer.

- Incidente de segurança, de acordo com o NIST, é uma violação ou ameaça iminente de violação das políticas/práticas de segurança estabelecidas.

Incidentes não é só um ataque, um incidente pode ocorrer dentro do ambiente da empresa, sendo praticado por pessoas autorizadas, mas indo contra políticas e práticas estabelecidas.

## Ciclo de vida de resposta a incidentes

### Preparação

- Time multidisciplinar
- Recursos eficazes de reporte
- Acesso a repositório e logs
- SPOC
- kit de inciação ao incident handling
### Análise e detecção 

- meio de detecção
- Compartilhamento de conh. e info.
- Threat intelligence com reconhecimento de contexto
- Segmentação e arquit.
- Boa compreensão / visibilidade da rede

### Contenção, erradicação e recuperação

### Pós incidente

## Atuação do analista de resposta a incidentes

### Atividades diárias
- Entender como um invasor tentou/conseguiu entrar no sistema
- Impedir, detectar e responder tentativas

### Conhecimento sobre o atacante

- técnicas
- táticas
- procedimentos
- Cyber kill chain

### Ação sobre ataques

- antecipar ataques
- propor medidas defensivas

## Monitoramento de eventos de segurança

**Eventos** -> Qualquer ocorrência observável em um sistema ou rede de computadores.

**Nem todo eventos é de interessa de segurança**, apenas os eventos **adversos**!

## Análise de logs e investigação de incidentes

"If there's no LOGs, there's no crime."

### Níveis de rede

- Perímetro de rede -> Firewalls, sistemas de internet e etc
- Perímetro de Host ->Dados que um host recebe e envia pra rede
- Nível de Host -> Dados que residem no host
- Nível de aplicação -> Operações do usuário e momento de execução

## Identificação e resposta a incidentes de segurança

- **Contenção** -> Impedir que um incidente fique pior
- **Erradicação** -> Eliminar artefatos do invasor, entender a causa raiz, vetores de ataque e TTPs em geral
- **Recuperação** -> Restaurar e monitorar a fim de garantir que nada escapou à detecção

Também classificamos um incidente com base no **tipo**, **impacto** e **extensão**.

## Análise forense

**Forense** -> Relativo ao judiciário, materiais e evidências que permitem serem admitidas no judiciário para provar um fato.
**Forense digital** -> No meio computacional, buscando defender inocentes e compreendes as motivações do incidente.

### Tudo é evidência?

- Vestígios -> Qualquer marca, fato, sinal
- Indícios -> A circunstância conhecida e provada em que pode concluir-se a existência de outras circunstâncias
- **Evidencias** -> Após análise pelos peritos, se mostram diretamente relacionado ao caso
- Provas -> Meio utilizado pelas partes

### Investigação digital

Aquisição -> Identificação -> Análise -> Apresentação
Apresentação->Análise->Aquisição->Identificação


#### Aquisição
Obtenção ou preservação, física ou remota, da posse do computador ou mídia objeto da investig., mapeamento da rede e dispositivos de armazen. físicos externos

#### Identificação
Quais dados podem ser recuperados, através de técnicas e ferramentas forense.

#### Análise
Avaliação dos dados de informações recuperados para determinar como e se bem eles podem ser usados de formar a evidenciar o evento que se procura esclarecer, bem como sua autoria

#### Apresentação
Apresentação das provas descobertas de forma que sejam compreendidas pelo objeto da investig.

## Técnicas de aquisição de computadores

O que coletar primeiro? Com base na ordem da volatilidade, priorizando CPU, cache e etc
Registros -> Cachê do CPU -> RAM -> HDD -> Dispositivos externos ou secundários