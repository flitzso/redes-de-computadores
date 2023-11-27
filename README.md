# :globe_with_meridians:Redes-De-Computadores #

#### Simulador de Rede Cisco Packet Tracer ####
#### https://www.netacad.com/courses/packet-tracer ####

## :pushpin:Modelos de Redes: OSI e TCP/IP ##

![Figura-3-Modelo-OSI-e-TCP-IP](https://github.com/flitzso/redes-de-computadores/assets/106411702/deb3ec1f-64c9-472b-a166-c158f894435e)

### :round_pushpin:Modelo OSI (Open Systems Interconnection): ###
#### O Modelo OSI é um modelo de referência que descreve como as redes de computadores devem ser organizadas e como as diferentes camadas de software e hardware devem interagir. Ele é dividido em sete camadas, da camada física à camada de aplicação: ####
#### Camada Física: ####
##### Lida com a transmissão de bits brutos por meio de meios físicos, como cabos e sinais elétricos. ######
#### Camada de Enlace de Dados: ####
##### Gerencia a comunicação ponto a ponto entre dispositivos em uma rede, garantindo a integridade dos dados e corrigindo erros. ######
#### Camada de Rede: ####
##### Responsável pelo roteamento de pacotes entre diferentes redes, usando endereços IP. #####
#### Camada de Transporte: ####
##### Fornece serviços de transporte confiável e controle de fluxo, garantindo a entrega adequada de dados. #####
#### Camada de Sessão: ####
##### Estabelece, gerencia e encerra sessões de comunicação entre aplicativos em computadores diferentes. #####
#### Camada de Apresentação: ####
##### Lida com a tradução e formatação de dados para garantir que aplicativos em diferentes sistemas possam se comunicar efetivamente. #####
#### Camada de Aplicação: ####
##### Fornece interfaces para aplicativos de usuário final e serviços de rede, como HTTP, SMTP e FTP. #####
### :round_pushpin:Modelo TCP/IP (Transmission Control Protocol/Internet Protocol): ###
#### Camada de Interface de Rede: ####
##### Lida com a conectividade física e as especificidades da interface de rede. #####
#### Camada de Internet: ####
##### Responsável pelo roteamento de pacotes, usando endereços IP, e a comunicação entre redes. #####
#### Camada de Transporte: ####
##### Fornecer serviços de transporte confiável e controle de fluxo, semelhante à camada correspondente no Modelo OSI. #####
#### Camada de Aplicação: ####
##### Equivalente à camada de aplicação no Modelo OSI, fornece serviços de rede para aplicativos, como HTTP, SMTP e FTP. #####


## :pushpin:Protocolos e serviços de rede comuns ##

![star](https://github.com/flitzso/redes-de-computadores/assets/106411702/0e401592-f1e9-4519-86bb-8619f315ea55)

#### HTTP (Hypertext Transfer Protocol): ####
##### Usado para transferência de páginas da web e conteúdo. #####
#### HTTPS (HTTP Secure): ####
##### Uma versão segura do HTTP que criptografa os dados transmitidos. #####
#### FTP (File Transfer Protocol): ####
##### Utilizado para transferência de arquivos entre computadores em uma rede. #####
#### SMTP (Simple Mail Transfer Protocol): ####
##### Protocolo de envio de e-mails. #####
#### POP3 (Post Office Protocol, versão 3): ####
##### Protocolo de recebimento de e-mails. #####
#### IMAP (Internet Message Access Protocol): ####
##### Protocolo de acesso a e-mails mais avançado que permite gerenciar mensagens no servidor. #####
#### DNS (Domain Name System): ####
##### Converte nomes de domínio em endereços IP para roteamento na internet. #####
### :round_pushpin:Protocolos de Camada de Transporte: ###
#### TCP (Transmission Control Protocol): ####
##### Fornece comunicação confiável e orientada à conexão. #####
#### UDP (User Datagram Protocol): ####
##### Oferece comunicação não confiável e de baixa latência. #####
### :round_pushpin:Protocolos de Camada de Rede: ###
#### IPv4 (Internet Protocol version 4): ####
##### A versão mais amplamente usada do protocolo de internet. #####
#### IPv6 (Internet Protocol version 6): ####
##### Uma versão mais recente que oferece suporte a um número maior de endereços IP. #####
#### ICMP (Internet Control Message Protocol): ####
##### Usado para diagnóstico de problemas de rede e envio de mensagens de erro. #####
### :round_pushpin:Protocolos de Camada de Link de Dados: ###
#### Ethernet: ####
##### Protocolo amplamente utilizado para comunicação em redes locais (LANs). #####
#### Wi-Fi (802.11): ####
##### Padrão para redes sem fio. #####
### :round_pushpin:Serviços de Segurança: ###
#### SSL/TLS (Secure Sockets Layer/Transport Layer Security): ####
##### Usado para criptografar a comunicação na internet. #####
#### VPN (Virtual Private Network): ####
##### Permite a criação de redes privadas virtuais para comunicação segura pela internet. #####
### :round_pushpin:Serviços de Rede: ###
#### DHCP (Dynamic Host Configuration Protocol): ####
##### Usado para atribuir endereços IP automaticamente a dispositivos em uma rede. #####
#### NAT (Network Address Translation): ####
##### Redireciona o tráfego de rede entre redes públicas e privadas. #####
#### Proxy Server: ####
##### Intermediário entre os dispositivos da rede e a internet, usado para filtragem e caching de conteúdo. #####
#### Firewall: ####
##### Utilizado para proteger a rede controlando o tráfego de entrada e saída. #####

## :pushpin:Endereçamento IP (IPv4 e IPv6) ##
![0_t0D9HmtQBjS9sM4t](https://github.com/flitzso/redes-de-computadores/assets/106411702/d675a784-ecba-4087-aa89-bd48e0c624ec)

### :round_pushpin:IPv4 (Internet Protocol version 4): ###
#### Formato de Endereço: ####
##### O IPv4 usa endereços de 32 bits, representados em notação decimal pontuada (por exemplo, 192.168.1.1). #####
#### Espaço de Endereço: ####
##### O espaço de endereço IPv4 é limitado a aproximadamente 4,3 bilhões de endereços exclusivos. #####
#### Notação Decimal Pontuada: ####
##### Um endereço IPv4 é dividido em quatro octetos (ou bytes), separados por pontos. Cada octeto é representado em notação decimal, variando de 0 a 255 (por exemplo, 192.168.0.1). #####
#### Esgotamento de Endereços: ####
##### Devido ao rápido crescimento da Internet, o espaço de endereços IPv4 esgotou-se, o que levou à necessidade de uma nova versão. #####
### :round_pushpin:IPv6 (Internet Protocol version 6): ###
#### Formato de Endereço: ####
##### O IPv6 usa endereços de 128 bits, representados em notação hexadecimal (por exemplo, 2001:0db8:85a3:0000:0000:8a2e:0370:7334). #####
#### Espaço de Endereço: ####
##### O espaço de endereço IPv6 é vasto e fornece cerca de 340 undecilhões (ou 3,4 x 10^38) de endereços únicos. #####
#### Notação Hexadecimal: ####
##### Um endereço IPv6 é dividido em oito grupos de quatro dígitos hexadecimais, separados por dois pontos. Os grupos podem ser abreviados, por exemplo, "2001:0db8::8a2e:0370". #####
#### Resolução de Esgotamento: ####
##### O IPv6 foi desenvolvido para resolver o problema de esgotamento de endereços do IPv4 e oferecer suporte a um número muito maior de dispositivos e serviços conectados à Internet. #####

## :pushpin:Sub-redes e máscaras de sub-rede ##
![hqdefault](https://github.com/flitzso/redes-de-computadores/assets/106411702/d824cae1-af66-4643-adb7-162a40376326)

### :round_pushpin:Sub-Redes (Subnets): ###
#### O que é uma Sub-Rede: ####
##### Uma sub-rede é um segmento lógico de uma rede IP maior. Ela permite dividir uma rede em partes menores, o que é útil para organizar dispositivos, melhorar a segurança e otimizar o uso de endereços IP. #####
#### Vantagens de Usar Sub-Redes: ####
##### As sub-redes facilitam o gerenciamento de endereços IP, o isolamento de tráfego, o roteamento eficiente e a segmentação lógica de redes maiores. #####
#### Endereços IP em uma Sub-Rede: ####
##### Uma sub-rede é identificada por um endereço IP de rede e uma máscara de sub-rede. Os dispositivos na sub-rede compartilham os primeiros bits do endereço IP, enquanto os bits restantes são usados para identificar dispositivos individuais. #####

### :round_pushpin:Máscaras de Sub-Rede: ###
#### O que é uma Máscara de Sub-Rede: ####
##### Uma máscara de sub-rede é um valor binário que determina quais bits em um endereço IP são usados para identificar a rede e quais são usados para identificar dispositivos na sub-rede. #####
#### Notação da Máscara de Sub-Rede: ####
##### A máscara de sub-rede é representada por uma sequência de bits 1s seguidos por bits 0s. Por exemplo, uma máscara de sub-rede típica em notação decimal é "255.255.255.0," que é o mesmo que "/24" em notação CIDR (Classless Inter-Domain Routing). #####
#### Aplicação da Máscara de Sub-Rede: ####
##### Quando uma máscara de sub-rede é aplicada a um endereço IP, ela "mascara" (oculta) os bits usados para a identificação da sub-rede. Os bits que permanecem "1" na máscara identificam a rede, e os bits "0" identificam os dispositivos na sub-rede. #####
#### Exemplo de Máscara de Sub-Rede: ####
##### Para uma máscara de sub-rede "/24," os primeiros 24 bits identificam a rede, e os últimos 8 bits são usados para endereçar dispositivos. Por exemplo, 192.168.1.0/24 define uma rede com os endereços de 192.168.1.1 a 192.168.1.254. #####

## :pushpin:Componentes de rede: roteadores, switches, hubs, cabos ##
![asdasdsadsad](https://github.com/flitzso/redes-de-computadores/assets/106411702/4774b062-3a13-4e13-8451-f06cb2d2ab76)

### :round_pushpin:Roteadores: ###
#### Função: ####
##### Os roteadores são dispositivos de camada 3 (camada de rede) que encaminham o tráfego entre redes diferentes. Eles determinam o melhor caminho para o tráfego com base nos endereços IP de origem e destino. Os roteadores também podem realizar funções de NAT (Network Address Translation) para permitir que vários dispositivos compartilhem um único endereço IP público. #####
#### Utilização: ####
##### Os roteadores são usados para conectar redes locais (LANs) a redes mais amplas, como a Internet. Eles são essenciais para o encaminhamento de dados entre diferentes redes. #####

### :round_pushpin:Switches: ###
#### Função: ####
##### Os switches são dispositivos de camada 2 (camada de enlace de dados) que encaminham o tráfego dentro de uma rede local (LAN). Eles usam endereços MAC (Media Access Control) para determinar a qual porta encaminhar pacotes de dados. Isso melhora a eficiência da comunicação em uma rede. #####
#### Utilização: ####
##### Os switches são amplamente utilizados em redes locais para conectar dispositivos, como computadores, impressoras e outros dispositivos. Eles permitem a comunicação direta e eficiente entre os dispositivos na mesma rede. #####

### :round_pushpin:Hubs: ###
#### Função: ####
##### Os hubs são dispositivos de camada 1 (camada física) que simplesmente repetem os dados recebidos para todas as portas. Eles não tomam decisões de encaminhamento e não segmentam o tráfego. #####
#### Utilização: ####
##### Os hubs eram comuns em redes antigas, mas hoje em dia são pouco utilizados. Eles são inadequados para redes de alto desempenho devido à falta de eficiência no gerenciamento de tráfego. #####

### :round_pushpin:Cabos: ###
#### Função: ####
##### Os cabos são o meio físico que transporta os sinais elétricos ou ópticos entre os dispositivos de rede. Diferentes tipos de cabos são usados em redes, incluindo cabos de par trançado, cabos coaxiais, cabos de fibra óptica e cabos de par trançado blindado. #####
#### Utilização: ####
##### A escolha do tipo de cabo depende das necessidades da rede. Cabos de par trançado são comuns em redes Ethernet, enquanto cabos de fibra óptica são usados para redes de alta velocidade e longas distâncias. #####

## :pushpin:Topologias de rede: estrela, anel, barramento ##
![figura-22](https://github.com/flitzso/redes-de-computadores/assets/106411702/b9057015-c153-4b6f-851c-e9758a2aca07)

### :round_pushpin:Topologia de Estrela: ###

#### Descrição: ####
##### Na topologia de estrela, todos os dispositivos na rede são conectados a um único dispositivo central, como um switch ou um hub. Não há conexões diretas entre os dispositivos de ponta a ponta. #####
#### Vantagens: ####
##### * Facilidade de instalação e manutenção. #####
##### *falhas em um dispositivo não afetam diretamente os outros dispositivos na rede. #####
##### *Facilita a detecção de problemas e a resolução de falhas. #####
#### Desvantagens: ####
##### *Dependência do dispositivo central (hub ou switch); se ele falhar, a rede pode ficar inoperante. #####
##### *Custo adicional para a instalação de cabos até o dispositivo central. #####

### :round_pushpin:Topologia em Anel: ###
#### Descrição: ####
##### Na topologia em anel, cada dispositivo é conectado a dois outros dispositivos, formando um anel fechado. Os dados circulam pelo anel de dispositivo em dispositivo até atingir o destinatário pretendido. #####
#### Vantagens: ####
##### *Cada dispositivo tem acesso igual aos dados, sem gargalos. #####
##### *A topologia em anel é resistente a falhas, pois, se um dispositivo falhar, os dados podem seguir a outra direção no anel. #####
#### Desvantagens: ####
##### *Instalação e expansão mais complexas, pois a adição ou remoção de dispositivos pode interromper o anel. #####
##### *A falha do anel inteiro pode ocorrer se houver várias falhas em dispositivos consecutivos. #####
#### :round_pushpin:Topologia de Barramento: ####
#### Descrição: ####
#####  Na topologia de barramento, todos os dispositivos são conectados a um único cabo (barramento). Os dados são transmitidos ao longo do cabo e são acessíveis a todos os dispositivos na rede. #####
#### Vantagens: ####
##### *Simplicidade, pois é fácil de instalar e requer menos cabo. #####
##### *Custo reduzido, devido à simplicidade. #####
#### Desvantagens: ####
##### *Dificuldade em isolar problemas ou detectar falhas. #####
##### *À medida que mais dispositivos são adicionados, o desempenho pode degradar devido ao congestionamento do cabo. #####
##### *Não é uma escolha ideal para redes maiores ou de alta performance. #####

## :pushpin:Ethernet e protocolos de camada de enlace ##
![slide_1](https://github.com/flitzso/redes-de-computadores/assets/106411702/7b5c70bb-9528-4bd4-a1fa-71a542d62a98)

#### Ethernet: ####
##### O protocolo Ethernet é o padrão fundamental que governa a transmissão de quadros de dados em uma rede Ethernet. Ele define como os dispositivos na rede acessam o meio compartilhado e resolvem conflitos. Os quadros Ethernet contêm informações como endereços MAC de origem e destino e dados. #####
#### MAC (Media Access Control): ####
##### A camada MAC é a subcamada da camada de enlace de dados que controla o acesso ao meio físico da rede. Ela implementa técnicas como CSMA/CD (Carrier Sense Multiple Access with Collision Detection) para evitar colisões de dados em redes Ethernet com fio. No entanto, com a evolução da Ethernet, o CSMA/CD foi desativado em redes modernas de comutação. #####
#### IEEE 802.3: ####
##### O IEEE 802.3 é um padrão que especifica as características físicas e de camada de enlace da Ethernet. Ele inclui especificações para cabos, taxas de transmissão de dados, tipos de quadros e outras características técnicas. #####
#### IEEE 802.1Q (VLAN): ####
##### O IEEE 802.1Q é um padrão que introduz a funcionalidade de redes locais virtuais (VLANs) na Ethernet. Com VLANs, é possível segmentar uma única rede física em várias redes lógicas separadas, melhorando a segurança e o gerenciamento de tráfego. #####
#### Ethernet Gigabit e Ethernet 10 Gigabit: ####
##### Esses são padrões Ethernet que suportam taxas de transferência de dados mais altas, 1 Gbps (Gigabit Ethernet) e 10 Gbps (10 Gigabit Ethernet), respectivamente. Eles são usados em redes de alto desempenho e data centers. #####
#### Ethernet sobre Fibra Óptica: ####
##### A Ethernet também é usada em redes de fibra óptica para fornecer conectividade de alta velocidade em distâncias mais longas. Isso inclui padrões como 1000BASE-LX e 10GBASE-LR. #####

## :pushpin:Conectividade de rede e configuração de dispositivos ##
![artigo-05-12](https://github.com/flitzso/redes-de-computadores/assets/106411702/89cee814-99f0-40e2-b37c-e2c2abdeec9f)

#### Cabos e Conexões: ####
##### A escolha do tipo de cabo e das conexões corretas é fundamental para estabelecer uma conectividade física sólida em redes com fio. Cabos Ethernet de par trançado são comuns em redes locais (LANs), enquanto cabos de fibra óptica são usados para conexões de alta velocidade em distâncias maiores. #####
#### Dispositivos de Rede: ####
##### Roteadores, switches, hubs e access points são dispositivos-chave que facilitam a conectividade em uma rede. A configuração adequada desses dispositivos é essencial para direcionar o tráfego de forma eficiente e segura. #####
#### Configuração de Dispositivos: ####
##### Configurar dispositivos de rede, como roteadores e switches, envolve atribuir endereços IP, definir políticas de segurança, criar VLANs (se necessário) e estabelecer regras de encaminhamento. A interface de gerenciamento web ou a linha de comando podem ser usadas para fazer essas configurações. #####
#### Endereçamento IP: ####
##### Cada dispositivo em uma rede precisa ter um endereço IP único para se comunicar com outros dispositivos. A configuração de endereços IP pode ser feita manualmente (configuração estática) ou por meio de um servidor DHCP (Dynamic Host Configuration Protocol) para atribuição automática. #####
#### Protocolos e Serviços de Rede: ####
##### Ativar e configurar protocolos e serviços de rede é importante para definir como os dispositivos interagem. Isso inclui a ativação do DHCP, DNS (Domain Name System), NAT (Network Address Translation) e outros serviços de rede. #####
#### Segurança de Rede: ####
##### A segurança de rede desempenha um papel crucial. Configurar firewalls, políticas de acesso e autenticação ajuda a proteger a rede contra ameaças externas e internas. #####
#### Resolução de Problemas: ####
##### É importante ser capaz de diagnosticar e solucionar problemas de conectividade de rede. Isso pode incluir a verificação de cabos, a análise de logs de dispositivos de rede e o uso de ferramentas de diagnóstico de rede. #####
#### Monitoramento e Gerenciamento: ####
##### O monitoramento contínuo da rede é essencial para garantir o desempenho e a disponibilidade. Ferramentas de monitoramento, como SNMP (Simple Network Management Protocol), podem ser usadas para rastrear o status dos dispositivos e da rede. #####
#### Expansão e Manutenção: ####
##### À medida que a rede cresce, é importante planejar e implementar a expansão de dispositivos e infraestrutura. A manutenção regular, como atualizações de firmware e segurança, é crucial para manter a integridade da rede. #####

## :pushpin:Configuração básica de roteadores e switches ##
![rgc-configuration-guide-banner](https://github.com/flitzso/redes-de-computadores/assets/106411702/43df637e-4f1d-44cd-92da-581bc9bd52ed)

### :round_pushpin:Configuração Básica de Roteadores: ###
#### Conexão Física: ####
##### Conecte-se ao roteador usando um cabo de console ou uma interface de gerenciamento web, dependendo do modelo e das opções de gerenciamento disponíveis. #####
#### Login: ####
##### Faça o login no roteador com credenciais padrão ou as fornecidas pelo fabricante. Recomenda-se alterar as senhas padrão para melhorar a segurança. #####
#### Configuração de Interfaces: ####
##### Configure as interfaces de rede, como as portas Ethernet e as interfaces WAN. Atribua endereços IP e máscaras de sub-rede a essas interfaces. #####
#### Roteamento: ####
##### Defina as rotas de encaminhamento para direcionar o tráfego entre diferentes redes. Isso pode incluir rotas estáticas ou configurações de protocolos de roteamento, como OSPF ou RIP. #####
#### NAT (Network Address Translation): ####
##### Configure o NAT, se necessário, para permitir que vários dispositivos compartilhem um único endereço IP público. Isso é comum em redes domésticas e pequenas empresas. #####
#### DHCP (Dynamic Host Configuration Protocol): ####
##### Ative o servidor DHCP para atribuir automaticamente endereços IP a dispositivos na rede local. Configure os intervalos de endereços e outras opções, se necessário. #####
#### Firewall e Segurança: ####
##### Configure regras de firewall e políticas de segurança para proteger a rede contra ameaças externas. #####
#### Nome de Host e DNS: ####
##### Defina o nome de host do roteador e configure os servidores DNS para resolução de nomes de domínio. #####
#### Senhas e Contas de Usuário: ####
##### Crie contas de usuário com níveis de privilégio apropriados e defina senhas fortes para proteger o acesso ao roteador. #####
#### Salve a Configuração: ####
##### Após concluir as configurações, salve a configuração para que elas persistam após reinicializações. #####

### :round_pushpin:Configuração Básica de Switches: ###
#### Conexão Física: ####
##### Conecte-se ao switch usando um cabo de console ou uma interface de gerenciamento web, se disponível. #####
#### Login: ####
##### Faça o login no switch com as credenciais padrão ou altere as senhas padrão para melhorar a segurança. #####
#### Configuração de VLANs: ####
##### Configure as VLANs (Virtual LANs) para segmentar a rede em diferentes domínios de broadcast. Atribua portas a VLANs específicas. #####
#### STP (Spanning Tree Protocol): ####
##### Configure o STP para evitar loops de comutação na rede. O STP desativa portas redundantes, mantendo apenas uma porta ativa por VLAN. #####
#### Administração de Portas: ####
##### Configure características de porta, como velocidade e duplex, para corresponder às necessidades da rede. Ative portas conforme necessário. #####
#### Segurança de Porta: ####
##### Defina segurança de porta para evitar o acesso não autorizado. Isso pode incluir a configuração de MAC address filtering e port security. #####
#### Senha e Contas de Usuário: ####
##### Crie contas de usuário com privilégios adequados para gerenciar o switch. #####
#### Salve a Configuração: ####
##### Após fazer as configurações, salve a configuração para que elas sejam mantidas após reinicializações. #####

## :pushpin:Protocolos de roteamento: RIP, OSPF, BGP ##

#### :round_pushpin:RIP (Routing Information Protocol): ####
##### *RIP é um protocolo de vetor de distância usado em redes locais ou pequenas. #####
##### *Ele usa a métrica contagem de saltos (hops) para determinar as melhores rotas. #####
##### *RIP é adequado para redes menores, mas pode não ser escalável para redes maiores devido às suas limitações de contagem de saltos. #####
##### *Existem duas versões principais: RIP v1 e RIP v2. RIP v2 é mais avançado e suporta recursos adicionais, como autenticação e suporte a sub-redes VLSM. #####

#### :round_pushpin:OSPF (Open Shortest Path First): ####
##### *OSPF é um protocolo de roteamento de estado de link usado em redes IP, incluindo a Internet. #####
##### *Ele usa informações de estado de link para determinar as melhores rotas com base na topologia da rede. #####
##### *OSPF é altamente escalável e adequado para redes de médio a grande porte. #####
##### *Ele oferece suporte a áreas, autenticação e roteamento hierárquico. #####

#### :round_pushpin:BGP (Border Gateway Protocol): ####
##### *BGP é um protocolo de roteamento usado para roteamento entre sistemas autônomos (ASes), sendo fundamental para o funcionamento da Internet. #####
##### *Diferentemente de RIP e OSPF, que se concentram no roteamento interno, o BGP é usado para o roteamento entre redes autônomas distintas. #####
##### *BGP permite tomar decisões de roteamento com base em várias políticas, como preferência de caminho, atributos e filtros. #####
##### *É altamente configurável e oferece controle granular sobre o roteamento, mas é complexo e requer um planejamento cuidadoso. #####

## :pushpin:Configuração avançada de roteadores e switches. ##
![78031938](https://github.com/flitzso/redes-de-computadores/assets/106411702/77676e3f-636f-4f48-a3c5-5df9f32e9003)

### :round_pushpin:Configuração Avançada de Roteadores: ###

#### Roteamento Avançado: ####
##### Em redes maiores, você pode precisar configurar protocolos de roteamento dinâmico, como OSPF, BGP, ou EIGRP, para otimizar o roteamento de tráfego e garantir alta disponibilidade. #####
#### Redes Virtuais (VLANs): ####
##### O uso de VLANs permite segmentar uma rede em sub-redes virtuais, o que melhora a segurança e a eficiência do tráfego. #####
#### QoS (Quality of Service): ####
##### Configurar QoS permite priorizar o tráfego de acordo com a importância, garantindo que aplicativos críticos tenham largura de banda suficiente. #####
#### Redes VPN (Virtual Private Network): ####
##### Configurar VPNs permite conexões seguras entre redes remotas, protegendo a comunicação entre elas. #####
#### Configuração de Firewall: ####
##### Implementar regras de firewall para controlar o tráfego de entrada e saída, protegendo a rede contra ameaças externas. #####
#### Redirecionamento de Portas (Port Forwarding): ####
##### No caso de servidores ou serviços internos, é necessário redirecionar portas para que sejam acessíveis a partir da Internet. #####
#### Túneis IPv6 sobre IPv4: ####
##### À medida que o IPv6 se torna mais comum, você pode precisar configurar túneis para fornecer conectividade IPv6 em redes IPv4. #####

### :round_pushpin:Configuração Avançada de Switches: ###
#### STP (Spanning Tree Protocol): ####
##### Configurar STP ou RSTP é importante para evitar loops de rede em topologias complexas. #####
#### Redundância de Switches: ####
##### Usar técnicas de agregação de link (LACP) ou VRRP (Virtual Router Redundancy Protocol) para garantir alta disponibilidade e redundância. #####
#### Trunking e Port Channels: ####
##### Configurar trunks e port channels para acomodar o tráfego VLAN em redes maiores. #####
#### Listas de Controle de Acesso (ACLs): ####
##### Usar ACLs para controlar o tráfego em nível de switch com base em critérios como endereços IP, portas e protocolos. #####
#### VXLAN (Virtual eXtensible LAN): ####
##### Configurar VXLAN para criar redes virtuais escaláveis em ambientes de data center. #####
#### Monitoramento de Portas (Port Mirroring): ####
##### Monitorar o tráfego de uma porta ou VLAN específica para fins de solução de problemas e segurança. #####
#### Autenticação 802.1X: ####
##### Implementar autenticação de portas para melhorar a segurança e controlar o acesso a dispositivos na rede. #####

## :pushpin:VLANs (Virtual LANs) e segmentação de rede. ##
![vlans_01_thumb](https://github.com/flitzso/redes-de-computadores/assets/106411702/9a22caeb-5d7c-42b5-af3f-28ed64b97314)

### :round_pushpin:O que são VLANs (Virtual LANs): ###
##### *As VLANs são redes virtuais que permitem separar dispositivos em grupos lógicos, independentemente da localização física. #####
##### *Com as VLANs, você pode criar múltiplas redes lógicas em uma única rede física, isolando o tráfego entre elas. #####
##### *Isso é útil para melhorar a segurança, gerenciar o tráfego e organizar dispositivos em redes separadas com base em critérios como departamentos, funções ou requisitos de segurança. #####

### :round_pushpin:Benefícios da Segmentação de Rede com VLANs: ###
#### Segurança: ####
##### A segmentação permite isolar grupos de dispositivos, reduzindo a superfície de ataque e o risco de acesso não autorizado. #####
#### Gerenciamento de Tráfego: ####
##### VLANs ajudam a gerenciar e otimizar o tráfego de rede, permitindo a priorização de tráfego importante. #####
#### Organização e Flexibilidade: ####
##### Você pode organizar dispositivos com base em critérios específicos e reconfigurar facilmente a rede conforme necessário. #####
#### Escalabilidade: ####
##### VLANs facilitam a adição de novos dispositivos sem a necessidade de mudanças físicas na rede. #####


### :round_pushpin:Configuração de VLANs: ###
##### *A configuração de VLANs envolve configurar switches para atribuir portas a VLANs específicas. Isso é feito por meio da criação de VLANs virtuais e da associação de portas a essas VLANs. #####
##### *Os switches precisam suportar o protocolo 802.1Q (VLAN tagging) para que as VLANs funcionem corretamente. #####
##### *Roteadores também podem ser configurados para rotear o tráfego entre VLANs, permitindo a comunicação entre elas quando necessário. #####

### :round_pushpin:Exemplos de Aplicações de VLANs: ###
##### *Em um ambiente corporativo, você pode criar VLANs separadas para departamentos, como uma VLAN para o departamento de TI, outra para o departamento de contabilidade e assim por diante. #####
##### *Em data centers, as VLANs são usadas para isolar o tráfego de diferentes clientes ou aplicativos. #####
##### *Em redes de convidados, como hotéis ou escritórios, você pode criar uma VLAN separada para os dispositivos de visitantes para manter a rede principal segura. #####

### :round_pushpin:Segurança em VLANs: ###
##### *Para reforçar a segurança, as ACLs (Listas de Controle de Acesso) podem ser usadas para controlar o tráfego entre VLANs. #####
##### *Redes de convidados e redes de produção devem ser estritamente separadas para minimizar riscos de segurança. #####


## :pushpin:DHCP (Dynamic Host Configuration Protocol). ##
![DHCP](https://github.com/flitzso/redes-de-computadores/assets/106411702/d7763d89-7500-4266-adcc-6e5e7deb7d2c)

### :round_pushpin:Atribuição Dinâmica de Configurações: ###
##### *O DHCP permite que dispositivos em uma rede obtenham automaticamente informações de configuração, como endereço IP, máscara de sub-rede, gateway padrão, servidores DNS e outros parâmetros de rede. #####
##### *Isso elimina a necessidade de configurar manualmente cada dispositivo na rede, tornando a administração mais eficiente. #####

### :round_pushpin:Componentes do DHCP: ###
#### Servidor DHCP: ####
##### É um servidor que mantém um pool de endereços IP disponíveis e atribui esses endereços a dispositivos solicitantes. O servidor DHCP também fornece outras informações de configuração. #####
#### Cliente DHCP: ####
##### É um dispositivo que solicita configurações de rede ao servidor DHCP quando se conecta à rede. Os clientes DHCP podem ser computadores, telefones, impressoras, etc. #####
#### Âmbito (Scope): ####
##### É um intervalo de endereços IP que o servidor DHCP pode atribuir a dispositivos. Um servidor DHCP pode ter vários escopos para diferentes redes ou sub-redes. #####

### :round_pushpin:Processo de Atribuição: ###
##### *Quando um dispositivo se conecta à rede, ele envia uma solicitação DHCP ao servidor DHCP. #####
##### *O servidor DHCP responde com um pacote DHCP que contém o endereço IP e outras configurações de rede, que o dispositivo utilizará para se configurar automaticamente. #####
##### *O servidor DHCP mantém um registro do endereço IP atribuído, para evitar atribuir o mesmo endereço a mais de um dispositivo. #####


### :round_pushpin:Benefícios do DHCP: ###
#### Simplifica a Administração: ####
##### Elimina a necessidade de configurar manualmente cada dispositivo na rede. #####
#### Alocação Eficiente de Recursos: ####
##### Permite reutilizar endereços IP à medida que os dispositivos entram e saem da rede. #####
#### Facilita a Mobilidade: ####
##### Dispositivos podem obter configurações de rede automaticamente, mesmo quando se movem entre redes. #####
#### Evita Conflitos de IP: ####
##### Reduz o risco de conflitos de endereços IP, que podem ocorrer em redes com configurações manuais. #####

### :round_pushpin:Implementações do DHCP: ###
##### *O DHCP é comumente usado em redes locais (LANs), incluindo redes domésticas, empresas e data centers. #####
##### *Os roteadores e switches muitas vezes têm servidores DHCP embutidos, mas também é possível configurar servidores DHCP dedicados em redes maiores. #####

## :pushpin:DNS (Domain Name System) ##
![DNS-Explained](https://github.com/flitzso/redes-de-computadores/assets/106411702/eacd22e9-2c90-4839-8fa8-d1867fdc716c)

### :round_pushpin:Tradução de Nomes de Domínio em Endereços IP: ###
##### *O DNS traduz nomes de domínio (como www.exemplo.com) em endereços IP (como 192.0.2.1). Isso permite que os computadores localizem servidores e serviços na Internet usando nomes legíveis por humanos. #####

### :round_pushpin:Estrutura Hierárquica: ###
##### O DNS opera com uma estrutura hierárquica, com raiz, domínios de topo (TLDs) e domínios de segundo nível (SLDs). Por exemplo, "exemplo.com" é um domínio de segundo nível no domínio de topo "com". #####

### :round_pushpin:Servidores DNS: ###
##### *A infraestrutura do DNS é composta por servidores DNS em todo o mundo. Os servidores DNS armazenam informações de mapeamento entre nomes de domínio e endereços IP. #####
##### *Existem servidores DNS raiz, servidores de domínio de topo e servidores DNS autorizados para domínios específicos. #####

### :round_pushpin:Resolução DNS: ###
##### *Quando um usuário digita um nome de domínio em um navegador ou em outro aplicativo, o dispositivo envia uma consulta DNS para um servidor DNS. O servidor DNS realiza a resolução do nome de domínio, retornando o endereço IP correspondente. #####

### :round_pushpin:Cache DNS: ###
##### *Para otimizar o desempenho e reduzir a carga nos servidores DNS, os resultados das consultas DNS podem ser armazenados em cache em servidores DNS e dispositivos clientes. #####

### :round_pushpin:Registro DNS: ###
##### *Os registros DNS são tipos específicos de informações associadas a nomes de domínio. Exemplos de registros DNS incluem A (para mapeamento de nomes de domínio para endereços IPv4), AAAA (para mapeamento de nomes de domínio para endereços IPv6), MX (para mapeamento de nomes de domínio para servidores de e-mail) e CNAME (para criação de alias de nomes de domínio). #####

### :round_pushpin:Segurança DNS: ###
##### *O DNS pode ser vulnerável a ataques, como envenenamento de cache e sequestro de DNS. Para mitigar essas ameaças, foram desenvolvidos protocolos e técnicas de segurança, como DNSSEC (DNS Security Extensions). #####

### :round_pushpin:Uso do DNS em Redes Locais: ###
##### *Além de seu papel na Internet, o DNS também é usado em redes locais para mapear nomes de host em endereços IP dentro de uma rede. #####

![network-firewall-icon-illustration-vector-on-white-background](https://github.com/flitzso/redes-de-computadores/assets/106411702/26b82c6b-0092-4a79-a95b-4b623d3503ee)
## 📌Firewall: ##

Um firewall é um dispositivo ou software que atua como uma barreira entre uma rede privada e a Internet ou outras redes externas. Ele monitora e controla o tráfego de dados com   
 base em regras de segurança predefinidas. Existem dois tipos principais de firewalls: 

Firewalls de Hardware:

Dispositivos físicos dedicados para proteger uma rede.
Podem ser implementados como appliances ou roteadores com recursos de firewall.
Firewalls de Software:

Programas de software que são instalados em servidores ou dispositivos individuais.
Podem ser integrados ao sistema operacional ou fornecidos como aplicativos independentes.

## 📌Funcionamento do Firewall: ##
Filtragem de Pacotes: Examina cada pacote de dados e decide permitir ou bloquear com base em regras predefinidas.
Stateful Inspection: Avalia o estado da conexão para permitir ou bloquear o tráfego com base no contexto.
Proxy e Filtragem de Conteúdo: Controla o acesso a recursos da web e filtra conteúdo com base em políticas de segurança.

## 📌Segurança de Rede: ##
A segurança de rede envolve medidas adicionais para proteger dados, sistemas e recursos contra ameaças cibernéticas. Além do firewall, outras práticas comuns incluem:

Criptografia: Protege dados durante a transmissão, tornando difícil para terceiros não autorizados interpretar as informações.

Antivírus e Antimalware: Utiliza software para detectar, prevenir e remover software malicioso.

Atualizações e Patches: Mantém sistemas operacionais, aplicativos e dispositivos atualizados com as últimas correções de segurança.

Controle de Acesso: Limita o acesso a sistemas e dados apenas a usuários autorizados.

Monitoramento de Rede: Monitora o tráfego de rede em busca de atividades suspeitas e anomalias.

Políticas de Segurança: Define regras e diretrizes para garantir a conformidade e a segurança da informação.

Backup Regular: Mantém cópias de dados importantes para recuperação em caso de perda ou ataque.

![11506937-dados-protegidos-com-conceito-de-servico-vpn-banner-de-3d-com-espaco-de-copia-vetor](https://github.com/flitzso/redes-de-computadores/assets/106411702/be775716-21b7-4f03-b3a2-d4317e90724d)

### 📌VPN (Virtual Private Network): ###
Objetivo:

Estabelecer uma conexão segura entre um dispositivo ou uma rede e outro ponto na Internet ou em uma rede privada.
Funcionamento:

Utiliza técnicas de criptografia para proteger os dados transmitidos entre os pontos conectados.
Pode ser implementada de diversas maneiras, incluindo VPNs de acesso remoto, VPNs de site a site e VPNs de ponto a ponto.
Tipos de VPNs:

VPN de Acesso Remoto: Permite que usuários individuais se conectem a uma rede privada de forma segura a partir de locais remotos.
VPN de Site a Site: Conecta redes inteiras entre locais geograficamente distintos.
VPN de Ponto a Ponto: Estabelece uma conexão segura entre dois dispositivos específicos.
Túneis VPN:
Definição:

Em uma VPN, o termo "túnel" refere-se à passagem segura e criptografada através da qual os dados são transmitidos entre os pontos conectados.
Criptografia e Autenticação:

Os túneis VPN utilizam protocolos de segurança para criptografar e autenticar os dados transmitidos, garantindo que apenas as partes autorizadas possam acessar as informações.
Protocolos Comuns:

IPsec (Internet Protocol Security): Um conjunto de protocolos para garantir a segurança das comunicações na Internet.
SSL/TLS (Secure Sockets Layer/Transport Layer Security): Usado para conexões VPN baseadas na web.
L2TP/IPsec (Layer 2 Tunneling Protocol/IP Security): Combina o L2TP para criar o túnel e o IPsec para segurança.
Finalidade:

Os túneis VPN são cruciais para criar uma "via segura" na qual os dados podem ser transmitidos de forma protegida, mesmo através de redes não confiáveis, como a Internet pública.
VPN e Privacidade:

Além de oferecer segurança, as VPNs também ajudam a preservar a privacidade dos dados, mascarando o endereço IP real dos usuários.

