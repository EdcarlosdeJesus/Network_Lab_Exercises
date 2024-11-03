# Network_Lab_Exercises
# Network_Lab_Exercises

## Descrição

Este repositório contém uma série de casos de laboratório destinados a ajudar jovens aprendizes e estagiários a desenvolver habilidades em configuração e resolução de problemas de rede. Os exercícios focam em conceitos como configuração de IP estático, uso de ferramentas de diagnóstico como `ping`, e simulação de erros de rede usando ICMP.

## Casos de Laboratório

### 1. Configuração Básica de Rede

**Objetivo:** Configurar uma rede básica e usar `ping` para verificar a conectividade.

**Atividade:** Configure duas máquinas virtuais (VMs) no mesmo segmento de rede com endereços IP estáticos. Use `ping` para verificar se ambas as VMs podem se comunicar entre si.

**Ferramentas:** VMs, comandos `ipconfig` e `ping` no Windows, `ifconfig` e `ping` no Linux.

### 2. Diagnóstico de Problemas de Conectividade

**Objetivo:** Identificar e resolver problemas de conectividade em uma rede.

**Atividade:** Em uma rede com três VMs (A, B e C), configure uma rota incorreta em uma das VMs. Use `ping` e `tracert` para identificar e corrigir a rota.

**Ferramentas:** VMs, comandos `ping`, `tracert` (Windows) e `traceroute` (Linux).

### 3. Uso de `ping` com Várias Flags

**Objetivo:** Usar diferentes opções de linha de comando com `ping` para diagnóstico avançado.

**Atividade:** Use `ping -t` no Windows para enviar solicitações de eco contínuas e `ping -c 5` no Linux para limitar a 5 pacotes. Analise os resultados.

**Ferramentas:** Sistemas Windows e Linux, comando `ping`.

### 4. Simulação de Erros de Rede com ICMP

**Objetivo:** Simular e analisar diferentes tipos de erros de rede usando ICMP.

**Atividade:** Use uma ferramenta de injeção de pacotes (como Scapy no Linux) para gerar mensagens ICMP de destino inacessível e TTL expirado. Capture e analise os pacotes com Wireshark.

**Ferramentas:** Scapy, Wireshark.

### 5. Configuração de Firewall e Teste de ICMP

**Objetivo:** Configurar regras de firewall para permitir ou bloquear tráfego ICMP.

**Atividade:** Em um sistema Windows ou Linux, configure regras de firewall para bloquear ICMP e teste o comportamento com `ping`. Depois, permita ICMP e teste novamente.

**Ferramentas:** Ferramentas de firewall do sistema operacional, comando `ping`.

## Contribuição

Sinta-se à vontade para abrir issues ou pull requests se encontrar algum problema ou quiser melhorar os laboratórios. Feedback é bem-vindo!

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
