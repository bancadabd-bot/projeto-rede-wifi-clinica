# 🏥 Projeto de Rede Wi-Fi Corporativa para Clínica Médica

Projeto desenvolvido como Trabalho de Conclusão de Curso em Redes de Computadores.

O objetivo foi projetar, implementar e validar uma infraestrutura de rede
corporativa para uma clínica médica, utilizando segmentação por VLANs,
Wi-Fi 6, políticas de segurança, controle de acesso e gerenciamento
centralizado.

## 🛠 Tecnologias e equipamentos

- Cisco Catalyst 2960X
- TP-Link Omada ER605
- TP-Link EAP650 AX3000 Wi-Fi 6
- Omada Software Controller
- IEEE 802.1Q
- VLAN
- DHCP
- NAT
- Firewall / ACL
- Captive Portal
- QoS
- DPI
- Application Control
- Wireshark
- SPAN

## 🌐 Segmentação da rede

| VLAN | Finalidade |
|------|------------|
| 10 | Médicos |
| 20 | Funcionários |
| 30 | Pacientes |
| 40 | Impressoras |
| 99 | Gerenciamento |

## 🔐 Segurança

A rede foi segmentada de acordo com diferentes perfis de utilização.

A VLAN de pacientes foi isolada das redes corporativas e possui acesso
somente à Internet. Médicos e funcionários possuem acesso controlado
às impressoras, enquanto a VLAN de gerenciamento é utilizada para
administração da infraestrutura.

## 📡 Wi-Fi para pacientes

Foi implementado Captive Portal para controle de acesso dos pacientes
à rede sem fio.

## 📊 Monitoramento

Foram utilizados Omada Controller, DPI, Wireshark e SPAN para
monitoramento e análise do tráfego.

## 🧪 Validação

Foram realizados testes de:

- DHCP
- conectividade
- isolamento entre VLANs
- regras de firewall
- Captive Portal
- controle de largura de banda
- DPI
- controle de aplicações

## 📄 Trabalho completo

📘 **[Clique aqui para visualizar o artigo completo do TCC](docs/TCC-Projeto-Rede-WiFi-Clinica.pdf)**

O trabalho apresenta detalhadamente a arquitetura, implementação, configurações e testes realizados no ambiente da clínica.
Jonatan Luiz Frota de Carvalho  
Tecnólogo em Redes de Computadores
