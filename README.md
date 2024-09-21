# Laboratório 1 - Localizando Serviços por Categoria

## Resumo sobre o aprendizado do Primeiro Laboratório do Curso DIO: Azure Essentials

A computação em nuvem é o fornecimento de serviços de computação pela Internet. Empresas como Microsoft, Amazon e Google oferecem tais serviços. A ideia de poder ter o melhor do que um datacenter pode oferecer sem precisar arcar com enormes investimentos com equipamentos fazem da computação em nuvem um excelente serviço.

Entre os benefícios da computação em nuvem podemos citar: rapidez para colocar seu projeto no ar, possibilidade de escalabilidade vertical ou horizontal de forma imediata e de acordo com a demanda, maior facilidade de gerenciar sua infraestrutura e economia de escala.

Existem basicamente três tipos de nuvem:

- Nuvem Privada: é o modelo mais antigo de infraestrutura, no qual cada empresa possui sua própria estrutura de datacenters. Nesse modelo a empresa tem controle total sobre sua infraestrutura. No entanto, o custo e a responsabilidade pela manutenção ficará completamente a cargo da própria empresa. Esse modelo demanda um demasiado investimento inicial.
- Nuvem Pública: esse modelo é caracterizado pelo que comumente chamamos de ambiente em nuvem de forma genérica. Trata-se da prestação dos serviços de computação a quaisquer empresas que se interessem em utilizar a infraestrutura de outras grandes empresas que possuem enormes datacenters e diversas zonas de disponibilidade. Aqui se enquadram serviços como Azure, AWS e GCP.
- Nuvem Híbrida: o melhor dos dois mundos. Esse modelo combina os benefícios da nuvem privada com os da nuvem pública. Ao utilizar esse modelo unem-se a estrutura própria de algumas empresas com serviços de nuvem pública, oferecendo controle em parte da operação,visto que a empresa possui seus próprios datacenters, com alguns dos benefícios da nuvem pública como escalabilidade em momentos de pico ou mesmo apenas serviços pontuais como o gerenciamento de backups.

É importante citar que existe uma ampla gama de serviços de computação em nuvem para as mais diversas finalidades. Esse leque de oportunidades distribuídos entre serviços do tipo IaaS, PaaS e SaaS tornam possível que cada um, desde desenvolvedores independentes a grandes corporações possam encontrar uma solução que me melhor se adeque ao seu projeto, com preços acessíveis e que tornam o seu negócio viável, visto que o modelo de cobrança é baseado no consumo.

Isso quer dizer que você paga apenas pelos recursos que utilizar e durante o tempo que utilizar. Esse modelo de cobrança permite que a estrutura e os gastos de um negócio possam crescer proporcionalmente de acordo com a demanda do projeto, escalando conforme a necessidade.

No entanto, apesar de todos os benefícios que a computação em nuvem oferece, faz-se necessário que o arquiteto das soluções Devops de uma determinada compania tenha conhecimentos sobre o devido funcionamento dos recursos disponíveis no ambiente de cloud escolhido, para evitar cobranças indevidas e gastos desnecessários. É nessa esteira que os treinamentos como esse realizado pela Digital Inovation One (DIO) e as certificações como a AZ-900 ajudam a preparar o profissional de mercado para projetar e encontrar a melhor solução para cada caso.

___Escrito por Jefferson Yuri Lima___

---

# Laboratório 2 - Criando Máquinas Virtuais no Azure
## Resumo sobre o aprendizado do Segundo Laboratório do Curso DIO: Azure Essentials

O segundo laboratório do curso Azure, apesar do tema "Criando Máquinas Virtuais no Azure", explorou as características do SLA. Trata-se do Acordo de Nível de Serviço, na sua tradução para o português, que diz respeito principalmente às características de disponibilidade dos recursos da nuvem contratados. O SLA prevê determinados tempos aceitáveis de indisponibilidade do recurso contratado abordando os períodos de uma semana, um mês e um ano. Quanto maior a porcentagem do SLA menor é o tempo de insdiponibilidade que aquele recurso poderá ficar.

É importante citar que o SLA não se trata de uma previsão exata de indisponibilidade do recurso. A Microsoft não está afirmando que aquele item ficará indisponível por aquele tempo durante os períodos acordados. O que se busca aqui é acordar um tempo razoável em que o recurso poderá ficar indisponível para fins de manutenção ou outros serviços que impactem a utilização do recurso.

Caso o recurso venha a ficar indisponível por mais tempo do que o previsto no SLA a Microsoft irá disponibilizar créditos para o cliente utilizar no ambiente da Azure. 

O SLA é muito importante para a estratégia da empresa e do negócio. Visto que estão envolvidos a disponibilidade do servidor e os custos associados é importante que o arquiteto do sistema tenha ciência das necessidades do projeto e dos gastos envolvidos para assim adequar ambos ao SLA mais apropriado. Por isso, em casos como testes de aplicativo pode-se optar por utilizar um recurso que possua um SLA com tempo de indisponibilidade maior do que um recurso que está em ambiente de produção.


___Escrito por Jefferson Yuri Lima___

---

# Laboratório 3 - Configurando uma instância de Banco de Dados na Azure
## Resumo sobre o aprendizado do Terceiro Laboratório do Curso DIO: Azure Essentials

Neste laboratório vemos algumas configurações referentes à criação de Máquinas Virtuais bem como de Banco de Dados no Azure. 

Conforme a imagem abaixo, vemos que é necessário realizar várias configurações relacionadas à criação de uma máquina virtual. Essas configurações definirão o tipo de máquina escolhido, a sua capacidade processamento e de armazenamento, se ela estará visível na internet ou não, entre outras.

![image](https://github.com/user-attachments/assets/867c52de-9beb-4dca-b172-2130e22f96ec)

É importante citar que o preço, a disponibilidade e a capacidade de processamento de tais máquinas será completamente influenciado pelo que for configurado. Por isso deve-se ter conhecimento sobre as regras de negócio e as necessidades ligadas àquele recurso.

Além do laboratório mostrar máquinas virtuais vemos brevemente algumas configurações referentes a Banco de Dados.

Conforme vemos na imagem abaixo, também extraída do meu ambiente no Azure, vemos que o banco de dados também necessita de diversas configurações, entre elas a criação de um servidor de dados, que é demonstrado pela professora no Laboratório. 

![image](https://github.com/user-attachments/assets/8596bc4e-0eb7-4424-bf8a-25761ffdb4c3)

Outra característica importante a citar referente ao Banco de Dados é a configuração de redundância. Esse é um dos principais itens que impactará diretamente na disponibilidade do seu sistema mesmo diante de problemas e impactará também no SLA.

Por último, mas não menos importante, não podemos deixar de citar a importância de configurar a segurança destes recursos visto que geralmente estes ficarão disponíveis na internet e por isso podem ser alvo de ataques. Sendo assim, é imprescindível a realização de configurações de segurança.


___Escrito por Jefferson Yuri Lima___
---
