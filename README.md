# resumo-do-lab
Resumo das aulas de Cloud - LAB DIO

##  Principais Tópicos Abordados

###  Disponibilidade na Nuvem
A disponibilidade de serviços em nuvem é garantida por Acordos de Nível de Serviço (**SLAs - Service Level Agreements**), que definem a porcentagem de tempo em que um serviço estará operacional. Esses SLAs variam de acordo com o provedor e o tipo de serviço contratado.

####  Comparação entre SLAs
Os provedores de nuvem oferecem diferentes níveis de disponibilidade, sendo os mais comuns:

- **99,9% ("Três Noves")** – Aproximadamente 8,76 horas de indisponibilidade por ano.
- **99,95% ("Três Noves e Meio")** – Aproximadamente 4,38 horas de indisponibilidade por ano.
- **99,99% ("Quatro Noves")** – Aproximadamente 52,6 minutos de indisponibilidade por ano.
- **99,999% ("Cinco Noves")** – Aproximadamente 5,26 minutos de indisponibilidade por ano.

A escolha do SLA adequado depende do nível de criticidade do serviço. Serviços de missão crítica, como aplicações bancárias ou sistemas hospitalares, geralmente exigem SLAs mais elevados para minimizar períodos de indisponibilidade.

###  Modelos de Redundância
Para garantir a continuidade dos serviços e minimizar riscos de perda de dados, diferentes estratégias de redundância são implementadas, incluindo:

- **LRS (Locally Redundant Storage):** Mantém múltiplas cópias dos dados dentro de um único datacenter na região primária. Protege contra falhas de hardware locais.
- **ZRS (Zone Redundant Storage):** Replica os dados de forma síncrona entre diferentes zonas dentro da mesma região, garantindo proteção contra falhas de zona.
- **GRS (Geo-Redundant Storage):** Replica os dados em uma região secundária distante da primária, garantindo proteção contra desastres de grande escala.
- **RA-GRS (Read-Access Geo-Redundant Storage):** Variante do GRS que permite leitura dos dados na região secundária para maior disponibilidade.

###  Conclusão
A compreensão dos SLAs e dos modelos de redundância permite uma melhor tomada de decisão ao adotar soluções em nuvem. Empresas devem considerar o nível de disponibilidade necessário para suas operações e escolher estratégias de redundância adequadas para garantir continuidade, segurança e escalabilidade.


