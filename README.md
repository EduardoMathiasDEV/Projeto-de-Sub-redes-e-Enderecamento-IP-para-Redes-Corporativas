# Projeto-de-Sub-redes-e-Enderecamento-IP-para-Redes-Corporativas

# Projeto de Sub-redes e Endereçamento IP para Redes Corporativas

📡 **Disciplina:** Redes de Computadores  
👨‍🏫 **Professor:** Mozart Hasse  

---

## 🎯 Objetivo

Este projeto teve como propósito aplicar na prática conceitos fundamentais de redes de computadores, em especial:

- Manipulação de endereços IP.  
- Alocação de endereços IP para diferentes sub-redes.  
- Uso do utilitário **ipcalc** para cálculo e dimensionamento de redes.  
- Aplicação de procedimentos básicos de segurança em redes locais.  

---

## 🛠️ Estrutura do Projeto

O repositório contém:

- **`Projeto_de_Sub-redes_e_Enderecamento_IP_para_Redes_Corporativas.pdf`**  
  Documento principal com:  
  - Identificação da equipe.  
  - Três propostas diferentes de endereçamento de rede (iniciando em 192, 172 e 10).  
  - Cálculos de sub-redes usando notação CIDR.  
  - Definição de máscaras decimais, endereços de rede e broadcast.  
  - Tabelas de IPs atribuídos a servidores (DB, BI, ERP, Proxy, DNS, DHCP, LDAP, etc.).  
  - Estimativa de hosts disponíveis em cada sub-rede.

- **`Saidas_ipcalc/`**  
  Pasta com os arquivos `.txt` gerados a partir dos comandos `ipcalc`, demonstrando os cálculos de cada sub-rede.

---

## 🌐 Cenário de Rede Proposto

A rede corporativa foi planejada para atender:  

- **Setor Administrativo (B)**: até 100 + BB estações + servidores dedicados.  
- **Chão de Fábrica (C)**: até 70 + CC estações + servidores internos.  
- **Setor de Produção Reduzida (D)**: até 5 + DD estações + servidores básicos.  
- **Rede WiFi (W)**: sub-rede dedicada para dispositivos móveis e notebooks, com o máximo possível de endereços disponíveis.  

Cada sub-rede foi isolada em termos de segurança (não há comunicação direta entre elas sem passar pelo gateway/firewall).  

---

## 💻 Tecnologias e Ferramentas

- **Linux/Ubuntu** (máquina virtual ou Docker).  
- **ipcalc** – para cálculo de sub-redes.  
- **CIDR Notation** – para representação de endereços IP.  
- **Diagramas/Tabelas** – para organização dos resultados.  


