<h1>O objetivo deste projeto é estabelecer uma comunicação efetiva entre duas redes distintas (A e B) utilizando roteadores, switches e servidores.💻</h1>
  <h2>A configuração incluirá a implementação de DHCP para desktops e IP fixo para servidores em ambas as redes, bem como a comunicação entre um desktop na Rede A e um servidor web na Rede B.</h2>

<h3>Topologia de Rede:</h3>

<h4>Rede A (Alunos):

Subnet: 192.168.0.0/24
Gateway: 192.168.10.254
DHCP e DNS: 192.168.10.253
Máquinas na Rede A:

4 desktops com DHCP
1 servidor com IP fixo
Rede B (Alunos):

Subnet: 172.15.0.0/24
Gateway: 172.15.0.254
DHCP e DNS: 172.15.0.253
Servidor Web: 172.15.0.252
Máquinas na Rede B:

5 desktops com DHCP
1 servidor com IP fixo (Servidor Web)
Equipamentos:

1 Router 1841
3 Switches 2960 24TT
Configuração:

Router 1841:

Configurar interfaces para as redes A e B.
Habilitar roteamento para permitir o tráfego entre as sub-redes.
Configurar NAT (Network Address Translation) se necessário.
Switches 2960:

Configurar as portas dos switches associadas a cada sub-rede.
Garantir que a comunicação entre os switches seja possível.
Rede A (Alunos):

Configurar DHCP no servidor (192.168.10.253) para distribuir IPs dinamicamente para os desktops.
Configurar DNS para resolução de nomes na Rede A.
Rede B (Alunos):

Configurar DHCP no servidor (172.15.0.253) para distribuir IPs dinamicamente para os desktops.
Configurar DNS para resolução de nomes na Rede B.
Configurar o servidor web com IP fixo (172.15.0.252).
Teste de Comunicação:

Comunicação ICMP:

Verificar a comunicação ICMP entre desktops em cada rede.
Certificar-se de que o roteamento entre as redes está funcionando corretamente.
Acesso Web:

De um desktop na Rede A, tentar acessar o site hospedado no servidor web da Rede B (http://172.15.0.252).
Confirmar que a página web é carregada corretamente, validando a funcionalidade do roteamento, DNS e camada de aplicação.
Considerações Finais:
Este projeto visa criar uma infraestrutura de rede funcional, permitindo a comunicação eficiente entre duas redes distintas. 
Ao implementar configurações adequadas nos roteadores, switches, servidores DHCP, DNS e servidores web, espera-se alcançar um ambiente operacional onde os desktops de uma rede possam acessar serviços específicos hospedados em servidores na outra rede.
Certifique-se de monitorar a conectividade e ajustar as configurações conforme necessário para garantir um funcionamento contínuo.</h4>

<img src="/ada-projeto-redes.png">





