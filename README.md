# 🔍 hosts_win.py – Consultas DNS em Python

Este projeto é uma **ferramenta interativa em Python** para realizar consultas de DNS utilizando o comando `nslookup`.  
O programa permite consultar diferentes tipos de registros DNS de um domínio específico, utilizando como servidor de resolução o **DNS público do Google (8.8.8.8)**.

---

## 🚀 Funcionalidades
- Consulta de registros DNS:  
  - **A** → Endereço IPv4 associado ao domínio.  
  - **NS** → Servidores de nomes responsáveis pelo domínio.  
  - **MX** → Servidores de e-mail do domínio.  
  - **TXT** → Registros de texto (SPF, DKIM, etc.).  
- Execução interativa em loop até o usuário decidir sair.  
- Resultados formatados diretamente no terminal.  

---

## 📦 Pré-requisitos
- **Sistema Operacional**: Windows (ou outro que possua `nslookup`).  
- **Python**: Versão 3.x.  
- **Bibliotecas**: Apenas módulos nativos do Python.  
  - `subprocess` (execução de comandos do SO).  

---

## ▶️ Como executar
1. Salve o código como `hosts_win.py`.  
2. No terminal ou prompt de comando, rode:  
   ```bash
   python hosts_win.py
