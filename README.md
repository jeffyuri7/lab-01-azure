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

# Laboratório 4 - Configurando Arquiteturas no Azure
## Resumo sobre o aprendizado do Quarto Laboratório do Curso DIO: Azure Essentials

Neste laboratório a professora explicou sobre a infraestrutura física da Azure. No próprio site podemos ver muitas informações sobre isso, como os locais onde há datacenters, pontos de replicação e etc.

A Azure disponibiliza em seu site um globo dinâmico contendo todos os seus datacenters no mundo inteiro. Vemos que há apenas um datacenter no Brasil que replica para os Estados Unidos. Há também uma região no Rio de Janeiro para replicação do datacenter principal que fica em São Paulo em casos de Recuperação por motivo de desastre, quando ligado a dados que são protegidos pela SGPD e não podem sair do país.

Também podemos fazer um tour pelos datacenters da Microsoft por meio do globo. Há uma forma de interagir como se estivéssemos entrando em um datacenter. É possível visualizar diversos locais e obtemos várias informações sobre como são os datacenters realmente.

Além disso, a professora demonstrou no ambiente do Azure como criar Grupos de Recursos. Ela criou um grupo de recursos colocando na região (US) East 2. Quanto as marcações são utilizadas para tagear os recursos que estão sendo utilizados. Isso ajuda a verificar o que foi usado e quanto foi o valor gasto de cada recurso.

O log de atividades fornece informações sobre os recursos que foram criados naquele grupo. O IAM controla as permissões referentes aos recursos. Os eventos do grupo de recursos nos ajuda a fazer automatizações.

A professora criou uma Rede Virtual no mesmo grupo de recursos. Eu repliquei isso em meu ambiente da Azure, tanto criando o meu próprio grupo de recursos, como uma Vnet.

![image](https://github.com/user-attachments/assets/7281f9d9-bc10-4f95-a21a-3ea4d0ec2b9e)

Abaixo a minha Rede Virtual criada no grupo de recursos:

![image](https://github.com/user-attachments/assets/68648e30-6368-465d-86ce-a0407b5d111c)

___Escrito por Jefferson Yuri Lima___
---
# Laboratório 5 - Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure
## Resumo sobre o aprendizado do Quinto Laboratório do Curso DIO: Azure Essentials

Neste laboratório a professora realizou testes criando máquinas virtuais, Azure Functions e Área de Trabalho Virtual do Azure. A aula foi muito bem explicada e detalhada, cobrindo todos os pontos relacionados a criação de VMs.

Eu repliquei os testes no meu próprio ambiente do Azure, conforme pode ser observado nas imagens abaixo:

![image](https://github.com/user-attachments/assets/a10f43c5-db3e-4d03-a423-869a6e91c231)

![image](https://github.com/user-attachments/assets/eec87595-9ec6-42d4-86f2-c4989cf192fe)

![image](https://github.com/user-attachments/assets/35025be8-a09a-46e5-9e5e-002b25259356)

Conectando à maquina virtual criada:

![image](https://github.com/user-attachments/assets/803c1de8-34ae-41c7-bee7-abb9a30e6a0a)

Alguns destaques a respeito do processo de criação de VMs:
>- Podemos criar uma VM em qualquer região, inclusive há regiões mais baratas nos EUA.
>- Podemos configurar redundância nas zonas. Há uma opção de utilizar desconto de Spot do Azure. Essa opção não deve ser usada em producação, pois se houver necessidade de outro cliente utilizar tais máquinas a nossa aplicação será automaticamente encerrada. Então essa pode ser uma boa ideia apenas no caso de testes.
>- Precisamos configurar chaves de acesso SSH, as portas que ficarão abertas para a nossa aplicação, os discos utilizados pela VM, redes, balanceamento de carga e backup, monitoramento e outras coisas mais.
>- Diversos recursos adicionais que são criados juntos a uma VM possuem a opção de exclusão automática já no momento de criação. Isso é interessante, para evitar que quando a VM for excluída fiquem recursos órfãos gerando gastos mesmo sem estar sendo utilizados.

Com respeito a Área de Trabalho Virtual trata-se de um serviço onde você pode disponbilizar uma máquina virtual para que os colaboradores da sua empresa trabalhem nela, sem precisar enviar máquinas físicas aos empregados. O que se pode destacar aqui basicamente são os dois tipos de área de trabalho:
>- Pessoal: nesse caso a será utilizada exclusivamente por uma pessoa.
>- Em pool: nesse caso haverá uma máquina que poderá ser compartilhada por vários colaboradores, inclusive com possibidade de expansão e balanceamento de carga.

Por último, a professora explicou brevemente onde se criam as Azure Functions, ou como é traduzido: os Aplicativos de Funções.

Destaca-se que no caso das Azure Functions diversas linguagens são suportadas, como Python, C#, JS com Node, entre outros. E dependendo de qual é a opção escolhida o Azure vai informar o sistema operacional a ser utilizado para executar aquela função. Ressalte-se que nos meus testes eu observei que quase todas as pilhas de execução permitiam a troca entre Linux ou Windows, como SO, à exceção do Python que era executado apenas por Linux.

___Escrito por Jefferson Yuri Lima___
---
# Laboratório 6 - Dominando o Armazenamento na Azure
## Resumo sobre o aprendizado do Sexto Laboratório do Curso DIO: Azure Essentials

A professora falou neste laboratório a respeito das Contas de Armazenamento. Estas podem armazenar blobs, arquivos, filas e tabelas. Possuem a característica de que deve possuir um nome entre 3 a 24 caracteres minúsculos e não podem conter caracteres especiais. Também esse nome deve ser único no mundo.

É possível conectar na Conta de Armazenamento em containers de arquivo via SMB na porta 445, no entanto o ideal seria conectar a partir de uma outra máquina dentro do próprio ambiente do Azure para evitar bloqueios pelo provedor de internet. Essa conexão pode ser feita tanto por meio de Windows, quanto Linux e Mac. Nessa configuração também é selecionado o modelo de replicação e configurações de backup.

Como mencionado acima é possível também criar nas contas de armazenamento as filas de mensagerias e as tabelas de SQL.

Ainda ligado ao conteúdo de armazenamento estão as opções de migração para o Azure. Nas opções de migração estão os bancos de dados, as aplicações Web e o Data Box que é um serviço de migração oferecida pelo Azure para pessoas que queiram importar dados de outro ambiente para o Azure ou do Azure para outro ambiente.

Além disso, a professora mostrou e demonstrou como utilizar as ferramenteas AzCopy e Gerenciador de Armazenamento

O AzCopy pode ser instalado tanto no Windows como em Linux e Mac. É necessário ter uma storage account para utilizá-lo. O AzCopy é uma ferramenta utilizada para enviar dados da máquina local para um container no storage account. O AzCopy é um software unilateral, ele apenas envia os dados locais para a nuvem da Azure.

Já o Gerenciador de Armazenamento é um software que sincroniza os dados de forma bilateral na máquina e no storage account. Ele também pode ser instalado em Windows, Linux e Mac. Pelo Gerenciador é possível acessar containeres, filas, tabelas e etc. Pelo gerenciador dá tanto para enviar dados como trazer dados da nuvem para a máquina local.

Essas soluções servem para pequenas massas de dados. Para grandes massas o ideal é a utilização de Data Box.

___Escrito por Jefferson Yuri Lima___
---
# Laboratório 7 - Entendo sobre segurança e identidade na Azure
## Resumo sobre o aprendizado do Sétimo Laboratório do Curso DIO: Azure Essentials

O laboratório explorou assuntos relacionados a identidade no ambiente da Azure. A professora explicou sobre o EntraID, uma renovação do método convencional chamado Azure Active Directory. Ele é responsável por represar os usuários. Esse serviço é utilizado para criar novos usuários ou para, por exemplo, quando uma empresa com servidor on premise passa para o Azure. Para evitar a replicação dos usuários do on premise no ambiente de nuvem pode ser feita a sincronizaação das identidades daqueles de modo que o Azure passe a ter os mesmos logins em seu ambiente. É importante citar que nesse caso, se um usuário for criado diretamente na nuvem isso não será replicado para o ambiente on premise. Somente poderiam ser aproveitadas as mesmas senhas, mas o usuário em si não será.

Nas configurações do EntraID há várias opções, dentre elas Roles e Administrators onde é possível determinar quais serão os privilégios que os usuários terão, por exemplo, exclusão de outros usuários, alteração de senha e etc. Importante citar que essa configuração diz respeito a permissões ligadas diretamente às contas de usuários e não aos recursos do Azure. Além disso, os usuários que são excluídos ainda poderão ser recuperados em até 30 dias após a exclusão. O serviço Self-service Password Reset pode ser ativado para que caso o usuário esqueça a sua senha ele mesmo possa resetar sua senha. No EntraID podem ser criados novos usuários ou serem convidados usuários externos para participar do ambiente. 

A funcionalidade que sincroniza os usuários de um ambiente on premise para a nuvem se chama Azure Entra Connect. Na opção Custom Domain Names é possível inserir o domínio da empresa para que as novas contas criadas dos seus usuários possuam o nome de domínio da empresa, ao invés do domínio da microsoft. 

Para gerenciar o permissionamento ligado a um determinado recurso isso é feito na configuração Access Control (IAM), acessaando diretamente pelo recurso. Nesse caso o permissionamento é herdável, então se um determinado permissionamento for dado a um resource group todos os recursos que fazem parte dele receberão as mesmas permissões.

Outra ferramente importante é o Microsoft Defender for Cloud, que possui relatórios sobre quão bem aquele ambiente está. Esse serviço é multicloud. Isso quer dizer que é possível por meio dele conectar em outros ambientes cloud como AWS e GCP e fazer varreduras de segurança, por exemplo, nesses ambientes. O Defender também possui recomendações de segurança, oferece segurança no ambiente DevOps, possui alertas de segurança, análises e etc. Também é possível configurar alertas que serão enviados caso algo aconteça no ambiente. O Defender também pode proteger e fazer validações em VMs, storages, containers, APIs, databases e vários outros serviços da Azure. Esse serviço, no entanto, é pago.

___Escrito por Jefferson Yuri Lima___
---

# Laboratório 8 - Otimizando Custos no Azure
## Resumo sobre o aprendizado do Oitavo Laboratório do Curso DIO: Azure Essentials

A professora apresentou no laboratório a Calculadora de Custo de Propriedade que nos ajuda a estimar as despesas em uma eventual mudança do ambiente on premise para a cloud. A calculadora leva em conta os recursos que serão utilizados, as licenças de software que precisarão ser adquiridas bem como a opção de levar para o ambiente em nuvem licenças que você já tem adquiridas no ambiente on premise. A calculadora faz a simulação e fornece relatórios sobre os gastos que o contratante terá bem como a economia que será gerada com o decorrer dos anos em comparação com a manutenção do datacenter on premise.

Também foi apresentada a Calculadora de Preço da Azure que simula os custos de recursos isolados na Azure, como máquinas virtuais, storage accounts e etc. É possível fazer uma simulação bem realista dos gastos incluindo licenças, tempo de uso das máquinas e outras configurações.

Outra funcionalidade importante demonstrada no laboratório foi o Cost Management. Este é o ambiente onde é possível visualizar as informações ligadas ao custo da nossa conta, dos recursos que utilizamos. Esse gerenciador nos mostra os custos, mas também faz sugestões sobre como reduzir custos em determinados casos, emite alertas, análises e diversas outras funcionalidade que auxiliam o dono da conta a controlar os gastos de acordo com as suas necessidades sem desperdiçar dinheiro com recursos desnecessários. Aqui no Cost Management as tags são muito úteis para visualizar quais recursos estão sendo utilizados e cobrados. Isso pode ajudar, por exemplo, a dividir os custos entre determinados centros de custo da empresa.

___Escrito por Jefferson Yuri Lima___
---
