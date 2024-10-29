﻿# Projeto PROXMOX Virtualization Solutions

## Descrição da Atividade:

Nesta atividade prática devemos, instalar e configurar e uma infraestrutura completa utilizando o PROXMOX como virtualizador.

## Descrição do Cenário:

-   **Windows (Virtualbox)**: Para hospedar a solução.
-   **Ubuntu Linux**: Distribuição linux para testes.
-   **Windows (Server)**: Sistema operacional server para testes .

## Tarefas:

**Remover a mensagem "no valid subscription"** : 
Edite o arquivo "proxmoxlib.js"
#nano /usr/share/javascript/proxmox-widget-toolkit/proxmoxlib.js
Localize a linha 563 onde tem " if (res === null || res === undefined || !res || res
                 564                .data.status.toLowerCase() !== 'active'){
                 565                Ext.Msg.show({ restante do código
Substitua por apenas if (false) {
                 564    Ext.Msg.show({ restante do código
Reinicie o servidor e pronto, a mensagem não aparecerá mais 

1. **Instalar e configurar a solução** : Iremos baixar, instalar e configurar a solução dentro do Virtualbox.

2. **Etapas pós instalação**:
    - Criar as redes .
    - Configurar o storage .
    - Criar os acessos .

3. **Criar as máquinas viruais**:
    - Windows Server como file server.
    - Ubuntu Server com um banco de dados.
    - Windows 10 como estação de trabalho .

## Referências Principais:

![Site da Solução]()
<br>https://www.proxmox.com/en/</br>

![Download da Solução]()
<br>https://www.proxmox.com/en/downloads)</br>

![Documentação da Solução]()
<br>https://www.proxmox.com/en/services/support#support-resources)</br>
