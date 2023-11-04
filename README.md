# :globe_with_meridians: Redes-De-Computadores #

#### Xirrus Inspetor de Wi-Fi ####
#### https://xirrus-wi-fi-inspector.en.download.it/ ####

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
