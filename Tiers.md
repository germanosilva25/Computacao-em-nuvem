### Tiers de Infraestrutura de Data Centers

Os diferentes "tiers" de infraestrutura de data centers são definidos pelo Uptime Institute e representam uma maneira de classificar a confiabilidade e a redundância de um data center. Cada tier tem critérios específicos que um data center deve atender para se qualificar para essa classificação. Eles são classificados do Tier I ao Tier IV, com cada nível representando um aumento na disponibilidade e na redundância.

### Tier I: Basic Capacity

**Descrição:**
- O Tier I representa a infraestrutura básica de um data center. Este nível fornece capacidade de energia e resfriamento, mas sem redundância para componentes críticos.

**Características:**
- **Disponibilidade:** 99,671% (equivalente a aproximadamente 28,8 horas de inatividade por ano).
- **Componentes:** Sistemas de energia e resfriamento não redundantes.
- **Redundância:** Nenhuma (N).
- **Manutenção:** Requer downtime para manutenção.
- **Uso Típico:** Pequenas empresas ou ambientes de teste e desenvolvimento.

### Tier II: Redundant Capacity Components

**Descrição:**
- O Tier II melhora a infraestrutura básica adicionando componentes redundantes para aumentar a disponibilidade. Isso inclui redundância para sistemas de energia e resfriamento.

**Características:**
- **Disponibilidade:** 99,741% (equivalente a aproximadamente 22 horas de inatividade por ano).
- **Componentes:** Sistemas de energia e resfriamento redundantes.
- **Redundância:** Parcial (N+1), com componentes redundantes para fornecer backup.
- **Manutenção:** Alguma manutenção pode ser feita sem causar downtime.
- **Uso Típico:** Empresas de médio porte ou departamentos críticos de TI em organizações maiores.

### Tier III: Concurrently Maintainable

**Descrição:**
- O Tier III permite que os sistemas de energia e resfriamento sejam mantidos sem causar interrupções. Isso é alcançado por meio de redundância e caminhos múltiplos para distribuição de energia e resfriamento.

**Características:**
- **Disponibilidade:** 99,982% (equivalente a aproximadamente 1,6 horas de inatividade por ano).
- **Componentes:** Sistemas de energia e resfriamento redundantes e caminhos múltiplos.
- **Redundância:** Total (N+1) para todos os componentes críticos.
- **Manutenção:** Manutenção pode ser realizada sem downtime.
- **Uso Típico:** Grandes empresas ou organizações que exigem alta disponibilidade para suas operações.

### Tier IV: Fault Tolerant

**Descrição:**
- O Tier IV é o nível mais alto de classificação e oferece tolerância a falhas. Isso significa que qualquer falha em um componente crítico não afetará a operação do data center.

**Características:**
- **Disponibilidade:** 99,995% (equivalente a aproximadamente 26,3 minutos de inatividade por ano).
- **Componentes:** Sistemas de energia e resfriamento redundantes, caminhos múltiplos e isolamento de falhas.
- **Redundância:** Total (2N+1) para garantir tolerância a falhas.
- **Manutenção:** Qualquer manutenção ou substituição pode ser realizada sem downtime.
- **Uso Típico:** Organizações que não podem tolerar downtime, como bancos, hospitais e grandes corporações com operações críticas.

### Comparação dos Tiers

| **Tier** | **Disponibilidade** | **Inatividade Anual** | **Redundância** | **Uso Típico** |
|----------|---------------------|-----------------------|-----------------|----------------|
| **Tier I** | 99,671% | 28,8 horas | Nenhuma (N) | Pequenas empresas, ambientes de teste |
| **Tier II** | 99,741% | 22 horas | Parcial (N+1) | Empresas de médio porte, departamentos de TI |
| **Tier III** | 99,982% | 1,6 horas | Total (N+1) | Grandes empresas, ambientes críticos |
| **Tier IV** | 99,995% | 26,3 minutos | Tolerância a falhas (2N+1) | Bancos, hospitais, grandes corporações |

### Conclusão

Os tiers de infraestrutura fornecem um padrão para avaliar e classificar data centers com base em sua confiabilidade e redundância. Cada nível atende diferentes necessidades de disponibilidade e orçamento, permitindo que as organizações escolham a infraestrutura que melhor atenda às suas necessidades de negócio. A compreensão desses tiers ajuda as empresas a tomar decisões informadas sobre onde hospedar suas operações de TI e garantir a continuidade do negócio.

