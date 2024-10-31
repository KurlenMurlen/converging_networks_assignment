# converging_networks_assignment
REQUIREMENTS || REQUERIMENTOS

[PTBR]
Neste Projeto 2, sua equipe deverá estender o cenário apresentado no Projeto 1. 

No caso, o objetivo é a adição de uma rede WIFI  em cada um dos andares por meio da inclusão de um Access Point em cada andar, sendo gerenciado por um Controlador WLAN.
Um servidor DHCP será usado para alocar endereços IPs e configurações DNS/GW default para os dispositivos móveis com interface WIFI para que possam usar a rede.
Cada dispositivo móvel deverá ter acesso normalmente aos servidores do data center, bem como à Internet. 
Haverá duas redes wifi instaladas e cada uma deverá ser uma VLAN separada.
Os endereços IP destas VLANs deverão ser 172.29.EQ.0/24 e 172.30.EQ.0/24, sendo EQ o número atribuído à sua equipe na sequência defesa.
Serão consideradas as mesmas equipes do Projeto 1 (caso haja mudança, comunicar o professor). A nota é composta pela nota comum da equipe, referente ao projeto e relatório, mais a nota individual de cada membro pela participação durante a defesa.

Sua equipe deverá entregar e defender o cenário funcionando com:

1) WLAN controller inserido e configurado na rede.

2) No controlador, usando a interface WEB de gerenciamento, criar uma WLAN com as  seguintes configs (Exemplo ANDAR1):

WLAN SSID: ANDAR1

L2 Security: WPA+WPA2    com WPA2 Policy , AES e PSK

Chave PSK: Redes2024

3) Servidor DHCP inserido e configurado na rede atribuindo endereçamento IP e outras informações para os clientes conforme abaixo:

Número máximo de clientes: 50

DNS server: o server do respectivo site

 4) Adicionar dispos itivos wifi e testar se estão pegando IP e acessando servidor WEB depois, EXATAMENTE COMO OS TESTES DE ACESSO DOS PCs das VLANs da rede cabeada.
 
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
[ENG]
In this Project 2, your team will need to extend the scenario presented in Project 1.

In this case, the goal is to add a WIFI network on each floor by including an Access Point on each floor, managed by a WLAN Controller.
A DHCP server will be used to allocate IP addresses and default DNS/GW configurations to mobile devices with WIFI interfaces so they can use the network.
Each mobile device should have regular access to data center servers as well as the Internet.
There will be two WIFI networks installed, and each should be a separate VLAN.
The IP addresses for these VLANs should be 172.29.EQ.0/24 and 172.30.EQ.0/24, with EQ being the number assigned to your team in the defense sequence.
The same teams from Project 1 will be considered (if there are changes, notify the professor). The grade is composed of the team’s common grade, referring to the project and report, plus each member’s individual grade based on participation during the defense.

Your team must deliver and defend the scenario in working order with:

	1.	WLAN controller installed and configured on the network.
	2.	On the controller, using the WEB management interface, create a WLAN with the following settings (Example FLOOR1):

WLAN SSID: FLOOR1

L2 Security: WPA+WPA2 with WPA2 Policy, AES, and PSK

PSK Key: Networks2024

	3.	DHCP server installed and configured on the network, assigning IP addresses and other information to clients as follows:

Maximum number of clients: 50

DNS server: the server of the respective site

	4.	Add WIFI devices and test if they are obtaining IPs and accessing the WEB server afterward, EXACTLY LIKE THE ACCESS TESTS FOR THE PCs in the wired VLAN network.
