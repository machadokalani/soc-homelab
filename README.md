# Security Operation Center - Homelab

## NO-AI POLICY
### Este repositório não utiliza IA generativa para fazer textos. Todo o conteúdo foi escrito e documentado de maneira orgânica. O escopo de utilização de IA se limita a ferramentas de pesquisa, nunca substituíndo a tomada de decisões humanas, ou produzindo conteúdo. Essa política foi adotada porque o presente repositório tem finalidade educacional e formativa, onde a autonomia como analista é a prioridade.


## OBJETIVO
### A ideia central é desenvolver um laboratório de estudos, simulando um SOC (Security Operation Center), e consolidar habilidades de um analista N1. Irei configurar uma arquitetura de máquinas virtuais, incluso um Windows-10 (alvo) e o Wazuh-Manager (dashboard) que irá monitorar ataques simulados do Atomic Red Team.


## STACK E ARQUITETURA
### Host: Acer Nitro V15 - Ubuntu 26.04
### Virtualização: KVM + QEMU + LIBVIRT, sendo gerenciados com virsh e virt-install. Para mais detalhes sobre a escolha de software de virtualização será feito uma página dedicada explicando decisões de configurações.
### Rede: Configurei uma rede virtual "soclab" com libvirt em NAT (10.10.10.0/24), onde o DHCP e DNS são fornecidos pelo dnsmasq do libvirt, com IP fixo para cada máquina virtual.
### SIEM/XDR: Wazuh 4.14.8 em uma máquina virtual Ubuntu Server 24.04.5.
### Endpoint monitorado: Virtual Machine com Windows 10 Pro 22H2 com Sysmon, com agente configurado de forma centralizada pelo agent.conf do grupo default.

## DETECÇÕES E PLAYBOOKS

## SIMULAÇÕES DE ATAQUE

## ROADMAP

## ESTRUTURA DO REPOSITÓRIO

## CONTATO
