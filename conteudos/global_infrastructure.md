# AWS Global Infrastructure

![AWS Global infrastructure](../imgs/AWS-Global-Infrastructure.png)

Para entendermos a estrutura global da AWS, temos que entender algumas divisões.

- AWS Regions (Regiões)
- AWS Availability Zones (Zonas de Disponibilidade)
- AWS Data Centers
- AWS Edge Locations (Pontos de presença)

## AWS Regions

- **O que é?** O conceito de região vem pela associação de um local físico onde os datacenters lógicos estão agrupados. Cada região é composta de pelo menos `3 AZs`, que ficam isoladas uma das outras. `A maioria dos serviços da AWS tem escopo regional.`