# 🌐 Network_Lab_Exercises

## Descrição 📋

Este repositório contém uma série de casos de laboratório destinados a  desenvolver minhas habilidades em configuração e resolução de problemas de rede. Os exercícios focam em conceitos como configuração de IP estático, uso de ferramentas de diagnóstico como `ping`, e simulação de erros de rede usando ICMP.

## Casos de Laboratório 💻🔧

### 1. Configuração Básica de Rede 🛠️

**Objetivo:** Configurar uma rede básica e usar `ping` para verificar a conectividade.

**Atividade:** Configure duas máquinas virtuais (VMs) no mesmo segmento de rede com endereços IP estáticos. Use `ping` para verificar se ambas as VMs podem se comunicar entre si.

**Ferramentas:** VMs, comandos `ipconfig` e `ping` no Windows, `ifconfig` e `ping` no Linux.

#Na máquina Servidor foi feito o uso da seguinte configurações.

<img src="https://github.com/user-attachments/assets/dec325ab-47b4-4afb-8888-3e632cacc104" width="400">

- Adaptador 1: Placa em modo Bridge, conecta diretamente à rede local, recebendo seu próprio IP e funcionando como um dispositivo independente na rede.
  
<img src="https://github.com/user-attachments/assets/bdbd503d-75ec-4e3a-81c4-f70439e70d0f" width="400">

- Adaptador 2:Rede interna , para pode conectar com outra VM.

<img src="https://github.com/user-attachments/assets/9bb08950-38ec-4425-9a9b-8606511bca9d" width="400">
- Máquina cliente foi apenas usado uma rede interna.


![image](https://github.com/user-attachments/assets/7cbbf5e5-d68c-4f0d-b349-93733b3e6b49)
#Podemos ver o resultado final desse mini projeto, conectando duas maquinas virtuais uma como servidor e outra como cliente aonde apenas o servido tem acesso a internet
a maquina cliente somente tem acesso a rede interna.


---


### 2. Diagnóstico de Problemas de Conectividade 🕵️‍♂️

**Objetivo:** Identificar e resolver problemas de conectividade em uma rede.

**Atividade:** Em uma rede com três VMs (A, B e C), configure uma rota incorreta em uma das VMs. Use `ping` e `tracert` para identificar e corrigir a rota.

**Ferramentas:** VMs, comandos `ping`, `tracert` (Windows) e `traceroute` (Linux).

---

### 3. Uso de `ping` com Várias Flags 🎯

**Objetivo:** Usar diferentes opções de linha de comando com `ping` para diagnóstico avançado.

**Atividade:** Use `ping -t` no Windows para enviar solicitações de eco contínuas e `ping -c 5` no Linux para limitar a 5 pacotes. Analise os resultados.

**Ferramentas:** Sistemas Windows e Linux, comando `ping`.

---

### 4. Simulação de Erros de Rede com ICMP 🔍

**Objetivo:** Simular e analisar diferentes tipos de erros de rede usando ICMP.

**Atividade:** Use uma ferramenta de injeção de pacotes (como Scapy no Linux) para gerar mensagens ICMP de destino inacessível e TTL expirado. Capture e analise os pacotes com Wireshark.

**Ferramentas:** Scapy, Wireshark.

---

### 5. Configuração de Firewall e Teste de ICMP 🔒

**Objetivo:** Configurar regras de firewall para permitir ou bloquear tráfego ICMP.

**Atividade:** Em um sistema Windows ou Linux, configure regras de firewall para bloquear ICMP e teste o comportamento com `ping`. Depois, permita ICMP e teste novamente.

**Ferramentas:** Ferramentas de firewall do sistema operacional, comando `ping`.

---

## Licença 📜

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
