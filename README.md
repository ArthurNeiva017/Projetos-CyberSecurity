# 🛡️ Projetos CyberSecurity

<p align="center">
  <strong>🔐 Coleção de projetos práticos desenvolvidos para aprendizado em Cybersecurity.</strong>
</p>

<p align="center">
  Pequenas ferramentas de segurança desenvolvidas principalmente com Python 🐍
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Cybersecurity-Projects-red?style=for-the-badge&logo=hackthebox&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge">
</p>

---

# 📌 Sobre o Repositório

Bem-vindo ao **Projetos CyberSecurity**! 🛡️

Este repositório foi criado para reunir pequenos projetos e ferramentas desenvolvidos durante meus estudos em **Cybersecurity e Segurança da Informação**.

A proposta é desenvolver aplicações relativamente simples que permitam colocar em prática conceitos de:

* 🐍 Python
* 🔐 Segurança da Informação
* 🌐 APIs
* 🗄️ Banco de Dados
* 🔎 Indicadores de Comprometimento
* 🌍 URLs, domínios e endereços IP
* 🌳 Git e GitHub

Cada projeto possui um objetivo específico e poderá receber novas funcionalidades conforme meus conhecimentos forem evoluindo.

---

# 🚀 Projetos

| Projeto                                | Descrição                                                   | Status                |
| -------------------------------------- | ----------------------------------------------------------- | --------------------- |
| 🔐 **Gerenciador de Senhas**           | Armazena e permite consultar credenciais localmente         | 🚧 Em desenvolvimento |
| 🔎 **Extrator de IOC**              | Verifica indicadores como IP, domínio, URL e hash           | 🔜 Planejado          |
| 🎲 **Gerador de Senhas**               | Gera senhas aleatórias seguindo critérios de segurança      | 🔜 Planejado          |

---

# [🔐 01 — Gerenciador de Senhas](https://github.com/ArthurNeiva017/Gerenciador-de-Senhas)

Aplicação desenvolvida em **Python + SQLite** para armazenar e consultar credenciais localmente.

### Funcionalidades

* 🔑 Criação de senha mestre
* 🔐 Autenticação
* ➕ Cadastro de credenciais
* 📋 Listagem de serviços
* 🔍 Recuperação de credenciais
* 🗄️ Banco de dados SQLite
* #️⃣ Hash da senha mestre
* 🙈 Entrada de senha oculta no terminal
* 🛡️ Consultas SQL parametrizadas
* 📦 Código modularizado

### Tecnologias

```text
Python
SQLite
Hashlib
Getpass
```

### Status

```text
🚧 Em desenvolvimento
```
---

# 🎲 03 — Gerador de Senhas

Ferramenta simples para gerar senhas aleatórias e fortes.

O usuário poderá definir:

```text
Tamanho da senha
Letras maiúsculas
Letras minúsculas
Números
Caracteres especiais
```

Exemplo:

```text
================================
       🔐 PASSWORD GENERATOR
================================

Tamanho da senha: 16

Incluir números? S
Incluir caracteres especiais? S

Senha gerada:

G7@mK!2qP#9xL4$z
```

### Funcionalidades planejadas

* 🎲 Geração aleatória
* 🔢 Escolha do tamanho
* 🔠 Letras maiúsculas e minúsculas
* 🔢 Números
* 🔣 Caracteres especiais

### Status

```text
🔜 Planejado
```
---

# 🔎 09 — Extrator de IOC

Ferramenta capaz de receber um texto e identificar automaticamente possíveis **Indicadores de Comprometimento**.

Por exemplo:

```text
Foi identificada comunicação com
192.168.10.50 e acesso ao domínio
malicious-example.com.
```

Resultado:

```text
======= IOCs ENCONTRADOS =======

IPv4:
192.168.10.50

Domínios:
malicious-example.com
```

Futuramente poderá identificar:

* 🌐 IPv4
* 🌐 IPv6
* 🌍 Domínios
* 🔗 URLs
* #️⃣ MD5
* #️⃣ SHA-1
* #️⃣ SHA-256
* 📧 Endereços de e-mail

### Status

```text
🔜 Planejado
```

---


# 🛠️ Tecnologias

<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">

</p>

Dependendo do projeto, também poderão ser utilizadas:

```text
Requests
APIs REST
JSON
Regex
Hashlib
Cryptography
```

---

# 📈 Níveis dos Projetos

Os projetos serão desenvolvidos aumentando gradualmente a dificuldade.

| Nível            | Projeto                       |
| ---------------- | ----------------------------- |
| 🟢 Básico        | Gerador de Senhas             |
| 🟡 Intermediário | Gerenciador de Senhas         |
| 🟡 Intermediário | Extrator de IOC            |

---

# 🗺️ Roadmap

* [x] 🔐 Gerenciador de Senhas
* [ ] 🔎 Extrator de IOC
* [ ] 🎲 Gerador de Senhas
* [ ] 🔐 Verificador de Força de Senha



---

# 🎯 Objetivo

O objetivo deste repositório é desenvolver projetos pequenos e práticos para aplicar conhecimentos de **Python e Cybersecurity**.

A proposta é começar com ferramentas simples e aumentar gradualmente a complexidade:

```text
🐍 Python
    │
    ▼
🔐 Fundamentos de Segurança
    │
    ▼
🔎 Indicadores de Comprometimento
    │
    ▼
🛡️ APIs de Cybersecurity
```

---

# ⚠️ Uso Responsável

Todos os projetos presentes neste repositório possuem finalidade **educacional e de aprendizado em Segurança da Informação**.

As ferramentas devem ser utilizadas somente em ambientes próprios, autorizados ou para análise de informações públicas.

---

# 👨‍💻 Autor

Desenvolvido por **Arthur Neiva**

🐙 GitHub: `ArthurNeiva017`

---

<p align="center">
  <strong>🛡️ Projetos CyberSecurity 🛡️</strong>
</p>

<p align="center">
  🔐 Segurança • 🐍 Python • 🔎 IOC 
</p>

<p align="center">
  <i>Aprendendo Cybersecurity através da prática.</i>
</p>

<p align="center">
  ⭐ Novos projetos serão adicionados conforme a evolução dos estudos!
</p>
