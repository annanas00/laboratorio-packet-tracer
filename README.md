# Configuração de DHCP em um Roteador Wireless

## Descrição

Esta atividade foi desenvolvida no Cisco Packet Tracer com o objetivo de configurar um roteador wireless para distribuir endereços IP automaticamente utilizando o protocolo DHCP (Dynamic Host Configuration Protocol).

## Objetivos

- Conectar 3 computadores a um roteador wireless.
- Configurar o serviço DHCP no roteador.
- Alterar a faixa de endereços IP distribuída pelo DHCP.
- Configurar os computadores para obter endereço IP automaticamente.
- Testar a conectividade da rede.

## Topologia da Rede

A rede é composta por:

- 1 Roteador Wireless
- 3 PCs
- Cabos Ethernet (Copper Straight-Through)

## Configurações Realizadas

### Configuração DHCP

- Endereço IP do roteador: 192.168.5.1
- DHCP: Habilitado
- Endereço inicial DHCP: 192.168.5.126
- Número máximo de usuários: 75

### Configuração dos Clientes

Todos os computadores foram configurados para obter endereço IP automaticamente através do DHCP.

## Verificações Realizadas

### Verificação do Endereço IP

Foi utilizado o comando:

```bash
ipconfig
```

Para verificar os endereços IP atribuídos aos computadores.

### Teste de Conectividade

Foi utilizado o comando:

```bash
ping
```

Para verificar a comunicação entre os dispositivos da rede.

## Resultados

Os computadores receberam endereços IP automaticamente através do DHCP e a comunicação entre os dispositivos foi realizada com sucesso.

## Ferramenta Utilizada

- Cisco Packet Tracer

## Conceitos Aplicados

- DHCP (Dynamic Host Configuration Protocol)
- Endereçamento IPv4
- Gateway Padrão
- Redes Locais (LAN)
- Roteadores Wireless
- Testes de Conectividade com Ping

## Topologia

![Topologia da Rede](topologia.png)
<img width="1034" height="496" alt="TOPOLOGIA" src="https://github.com/user-attachments/assets/8ebb07ac-7a49-4fd4-91eb-22774b12bbf1" />

