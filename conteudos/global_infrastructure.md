# AWS Global Infrastructure

![AWS Global infrastructure](../imgs/AWS-Global-Infrastructure.png)

Para entendermos a estrutura global da AWS, temos que entender algumas divisões.

- AWS Regions (Regiões)
- AWS Availability Zones (Zonas de Disponibilidade)
- AWS Data Centers
- AWS Edge Locations (Pontos de presença)

## AWS Regions

- **O que é?** O conceito de região vem pela associação de um local físico onde os datacenters lógicos estão agrupados. Cada região é composta de pelo menos `3 AZs`, que ficam isoladas uma das outras. `A maioria dos serviços da AWS tem escopo regional.`

## AWS Availability Zones

- **O que é?** As zonas de disponibilidade (`AZ`), são um ou mais datacenters, com redundância em sua energia, rede e conectividade entre as outras AZs.

- Elas ficam separadas em um raio de 100 Km entre si, tendo um conexão física, para proporsionar alta disponibilidade, prevensão de desastres naturais. 

![AZs](../imgs/availability-zones.png)

## Referências

- https://aws.amazon.com/pt/about-aws/global-infrastructure/?p=ngi&loc=1