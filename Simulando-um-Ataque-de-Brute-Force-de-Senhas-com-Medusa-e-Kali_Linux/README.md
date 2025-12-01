# 🚀 Projeto de Simulação: Auditoria de Segurança com Kali Linux e Medusa

## 📌 Entendendo o Desafio
Este projeto faz parte de um desafio educacional da DIO, com o objetivo de **documentar e compartilhar** uma experiência prática de auditoria de segurança em ambientes simulados.  
O foco é **aprender conceitos de força bruta e mitigação de vulnerabilidades**, sem comprometer dados reais ou sistemas de produção.

---

## 🎯 Descrição do Desafio
- Configurar ambiente simulado com duas VMs:
  - **Kali Linux** (máquina de auditoria)
  - **Metasploitable 2 / DVWA** (máquina vulnerável)
- Executar **cenários simulados**:
  - Força bruta em FTP
  - Automação de tentativas em formulário web (DVWA)
  - Password spraying em SMB com enumeração de usuários
- Documentar:
  - Wordlists fictícias
  - Exemplos de comandos simulados
  - Recomendações de mitigação

> ⚠️ **Aviso Importante:**  
> Este projeto é **apenas uma simulação acadêmica**. Nenhum ataque real foi realizado.  
> Todos os exemplos são fictícios e servem apenas para fins de estudo.

---

## 🛠️ Objetivos de Aprendizagem
- Compreender ataques de força bruta em diferentes serviços (FTP, Web, SMB).
- Utilizar Kali Linux e Medusa em ambiente **controlado**.
- Documentar processos técnicos de forma clara e estruturada.
- Reconhecer vulnerabilidades comuns e propor medidas de mitigação.
- Utilizar o GitHub como portfólio técnico.

---

## 📂 Estrutura do Repositório




---

## 🔐 Exemplos de Simulação
### Cenário FTP
Usuário fictício: `user_demo`  
Senha fictícia: `password123`

Comando simulado:
```bash
medusa -h 127.0.0.1 -u user_demo -P wordlists/demo.txt -M ftp

Cenário Web (DVWA)

medusa -h 127.0.0.1 -u admin -P wordlists/demo.txt -M http -m FORM

Cenário SMB

medusa -h 127.0.0.1 -u demo_user -P wordlists/demo.txt -M smb


✅ Conclusão
Este projeto é uma simulação acadêmica que demonstra como documentar cenários de auditoria de segurança sem comprometer dados reais. O foco está em aprender, refletir e compartilhar conhecimento de forma responsável.