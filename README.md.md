# 🛡️ Roadmap: Cibersegurança & DevSecOps

![Status: Em Progresso](https://img.shields.io/badge/Status-Em%20Progresso-blue)
![Curso: ADS](https://img.shields.io/badge/Curso-ADS-green)
![Instituição: IFPE Palmares](https://img.shields.io/badge/Institui%C3%A7%C3%A3o-IFPE%20Palmares-red)

> **Estudante:** [Eliabe Rafael Oliveira Silva] (Eliabits)
>
> **Formação:** Análise e Desenvolvimento de Sistemas (ADS) — IFPE Campus Palmares
>
> **Objetivo:** Documentar minha jornada de aprendizado, projetos práticos e evoluções na área de Segurança da Informação, Cibersegurança e Desenvolvimento de Software Seguro (DevSecOps).

---

## 📌 Índice de Progresso

- [ ] **Módulo 1:** Fundamentos de Redes, Linux e Segurança
- [ ] **Módulo 2:** Segurança no Desenvolvimento de Software (AppSec)
- [ ] **Módulo 3:** Offensive Security, Pentest e CTFs
- [ ] **Módulo 4:** DevSecOps e Segurança em Nuvem (Cloud Security)
- [ ] **Módulo 5:** Governança, LGPD e Defesa (Blue Team)

---

## 📚 Módulo 1: Fundamentos de Redes, Linux e Segurança
Para proteger um sistema, primeiro é preciso entender como ele se comunica e onde ele está hospedado. A base é essencial.

### 🎯 Objetivos de Estudo
- [ ] **Redes:** Modelo OSI e TCP/IP, Portas comuns (21, 22, 80, 443), DNS, DHCP, HTTP/HTTPS.
- [ ] **Sistemas Operacionais:** Proficiência na linha de comando Linux (Bash), gerenciamento de usuários, permissões (`chmod`, `chown`) e processos.
- [ ] **Segurança da Informação:** Tríade CIA (Confidencialidade, Integridade, Disponibilidade), Engenharia Social.
- [ ] **Criptografia Base:** Diferença entre Hash (MD5, SHA256), Criptografia Simétrica (AES) e Assimétrica (RSA).

### 🎓 Cursos Gratuitos Recomendados
- [Networking Basics (Cisco Skills for All)](https://skillsforall.com/) - Excelente base sobre como a internet funciona.
- [Introduction to Cybersecurity (Cisco Skills for All)](https://skillsforall.com/) - Conceitos primordiais de cibersegurança.
- [Guia Foca GNU/Linux](https://www.guiafoca.org/) - O melhor material gratuito em português para aprender Linux do zero ao avançado.
- [Fundação Bradesco: Segurança em Tecnologia da Informação](https://www.ev.org.br/) - Introdução conceitual muito boa e com certificado.

### 🛠️ Projetos & Práticas
- [ ] Configurar uma máquina virtual (VirtualBox/VMware) com Kali Linux ou Ubuntu Server.
- [ ] Interceptar o próprio tráfego de rede usando **Wireshark** para entender pacotes HTTP vs HTTPS.

---

## 💻 Módulo 2: Segurança no Desenvolvimento (AppSec)
O foco aqui é aprender como invasores quebram aplicações web e como escrever códigos em Java, Python ou Node.js (linguagens comuns em ADS) que sejam imunes a essas falhas.

### 🎯 Objetivos de Estudo
- [ ] **OWASP Top 10 (2021):** Dominar as vulnerabilidades mais comuns (Injection, Broken Access Control, XSS, CSRF, SSRF).
- [ ] **Autenticação:** Como implementar JWT (JSON Web Tokens) e OAuth2 de forma segura; armazenamento seguro de senhas (Argon2, bcrypt).
- [ ] **Validação e Sanitização:** Técnicas para não confiar no input do usuário e prevenir SQL Injection e XSS.
- [ ] **CORS e Headers de Segurança:** Configurar Content-Security-Policy (CSP), HSTS e X-Frame-Options.

### 🎓 Cursos Gratuitos Recomendados
- [PortSwigger Web Security Academy](https://portswigger.net/web-security) - **Obrigatório!** É o melhor treinamento gratuito de AppSec do mundo, criado pelos criadores do Burp Suite.
- [freeCodeCamp: Information Security Certification](https://www.freecodecamp.org/learn/information-security/) - Cobre AppSec, Helmets (Node.js) e tem projetos práticos em Python.
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) - Uma aplicação web moderna e intencionalmente vulnerável para você treinar.

### 🛠️ Projetos & Práticas
- [ ] Completar a trilha de *SQL Injection* e *XSS* na PortSwigger Academy.
- [ ] Desenvolver uma API REST (na linguagem que preferir) implementando autenticação JWT segura, rate limiting e proteção contra injeções.

---

## ⚔️ Módulo 3: Offensive Security, Pentest e CTFs
Entender as táticas dos cibercriminosos (Red Team) para saber como defender o código desenvolvido.

### 🎯 Objetivos de Estudo
- [ ] **Reconhecimento (Recon):** Coleta de informações com Nmap, subfinder, Google Dorks.
- [ ] **Análise de Vulnerabilidades:** Como usar scanners de rede e web.
- [ ] **Exploração Básica:** Uso de ferramentas como Metasploit, Burp Suite (Community) e OWASP ZAP.
- [ ] **Capture The Flag (CTF):** Resolução de desafios práticos para fixar o aprendizado em cenários gamificados.

### 🎓 Cursos Gratuitos e Plataformas
- [PicoCTF](https://picoctf.org/) - Melhor plataforma para iniciantes aprenderem segurança de forma gamificada (mantida pela Carnegie Mellon University).
- [TryHackMe (Plano Gratuito)](https://tryhackme.com/) - Salas introdutórias perfeitas (como *Complete Beginner* e *Web Fundamentals*).
- [Hack The Box (HTB)](https://www.hackthebox.com/) - Desafios e máquinas gratuitas (exige um pouco mais de conhecimento prévio).

### 🛠️ Projetos & Práticas
- [ ] Resolver as trilhas iniciais do PicoCTF (foco em Web Exploitation e Criptografia).
- [ ] Utilizar o OWASP ZAP para rodar um scan de vulnerabilidades automatizado contra uma aplicação de teste.

---

## 🚀 Módulo 4: DevSecOps e Segurança em Cloud
Como automatizar a segurança para que ela seja testada toda vez que você fizer um *commit* ou um *deploy*.

### 🎯 Objetivos de Estudo
- [ ] **Testes de Segurança:** Entender e aplicar SAST (Análise Estática), DAST (Análise Dinâmica) e SCA (Análise de Dependências).
- [ ] **CI/CD Seguro:** Integração de ferramentas de segurança no GitHub Actions ou GitLab CI.
- [ ] **Containers Seguros:** Boas práticas de Docker (distroless, rootless, scan de imagens).
- [ ] **Gerenciamento de Segredos:** Como não vazar chaves de API no GitHub e usar .env / Secret Managers.

### 🎓 Cursos Gratuitos Recomendados
- [GitLab: Intro to DevSecOps](https://about.gitlab.com/learn/) - O GitLab tem excelentes materiais gratuitos sobre integração de segurança.
- [AWS Skill Builder - Security Learning Plan](https://explore.skillbuilder.aws/learn) - Treinamentos gratuitos da AWS sobre segurança em nuvem.
- [Documentação Oficial do GitHub Actions](https://docs.github.com/pt/actions) - Melhor local para aprender automação CI/CD.

### 🛠️ Projetos & Práticas
- [ ] Configurar o **Dependabot** em um dos seus repositórios do GitHub.
- [ ] Criar uma pipeline no GitHub Actions que utiliza o **SonarCloud** (gratuito para repositórios públicos) ou **Semgrep** para buscar vulnerabilidades no código a cada Push.
- [ ] Escrever um `Dockerfile` otimizado e realizar o scan da imagem com a ferramenta [Trivy](https://github.com/aquasecurity/trivy).

---

## 📜 Módulo 5: Governança, LGPD e Defesa (Blue Team)
O mercado brasileiro exige profissionais que compreendam as leis de proteção de dados e saibam como reagir a incidentes.

### 🎯 Objetivos de Estudo
- [ ] **LGPD (Lei Geral de Proteção de Dados Pessoais):** Direitos dos titulares, bases legais, relatórios de impacto.
- [ ] **Privacy by Design:** Como arquitetar sistemas pensando na privacidade desde o início.
- [ ] **Resposta a Incidentes:** O que fazer quando um sistema é invadido (Identificação, Contenção, Erradicação, Recuperação, Lições Aprendidas).
- [ ] **Gestão de Logs e Monitoramento:** Importância de logs de auditoria seguros (SIEM).

### 🎓 Cursos Gratuitos Recomendados
- [Escola Virtual Gov (EV.G) - Introdução à LGPD](https://www.escolavirtual.gov.br/) - Excelente curso oficial do governo brasileiro, com certificado gratuito.
- [Escola Virtual Gov - Segurança da Informação](https://www.escolavirtual.gov.br/) - Outros cursos governamentais focados em proteção de dados e defesa cibernética.
- [Splunk Free Training](https://www.splunk.com/en_us/training/free-courses.html) - Cursos introdutórios sobre análise de logs e SIEM.

### 🛠️ Projetos & Práticas
- [ ] Implementar um sistema centralizado de logs (usando Stack ELK - Elasticsearch, Logstash, Kibana) em um projeto da faculdade.
- [ ] Mapear o fluxo de dados pessoais de uma aplicação do IFPE simulando um relatório de conformidade com a LGPD.

---
> 💡 *Dica:* Marque os checkboxes (`[x]`) à medida que for completando os cursos e projetos. O aprendizado em cibersegurança é contínuo!