# Leandro de Araújo Teixeira

**Staff / Senior Red Team Operator & Adversary Emulation Specialist**  
**Offensive Security, Exploit Development, Firmware & Linux Kernel Driver Reverse Engineering**  
São Paulo, SP – Brasil  
📞 (11) 93001-8609 | ✉️ [leandro.tex@outlook.com](mailto:leandro.tex@outlook.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/leandrotex/) | 💻 [GitHub (latex)](https://github.com/latex)

---

## 🎯 Resumo Profissional

Especialista em Segurança Ofensiva (Red Team), Emulação de Adversários (Adversary Emulation) e Engenharia Reversa com mais de três décadas de sólida trajetória em tecnologia. Vivência profunda tanto em ataques de alta complexidade contra infraestruturas corporativas modernas (GCP, Azure, Kubernetes, Microsserviços e Inteligência Artificial) quanto em camadas de baixo nível: **engenharia reversa de firmware embarcado/IoT**, desmontagem de binários (ELF/PE) e **desenvolvimento/engenharia reversa de drivers de dispositivo no Kernel Linux**.

Ampla experiência na liderança e execução de campanhas de invasão ponta a ponta (MITRE ATT&CK), desenvolvimento de tooling ofensivo customizado (Python, Go, C, Rust e Bash), evasão de EDR/WAF/SIEM, pós-exploração, escalonamento de privilégios e movimentação lateral. Pioneiro em **AI Red Teaming**, testando proativamente vetores de ataque contra LLMs corporativos (Vertex AI / Gemini), incluindo Prompt Injection, Jailbreaking, quebra de guardrails e exfiltração de RAG.

Fundador do Garoa Hacker Clube e da Fundação HackerSpace, une o DNA hacker de pesquisa em hardware e software à capacidade estratégica de traduzir explorações complexas em planos de mitigação e elevação de postura para executivos e times de Blue Team (Purple Teaming).

---

## 🛠️ Arsenal Técnico & Competências Principais

- **Emulação de Adversários & Red Team Ops:** Simulação de APTs (MITRE ATT&CK), campanhas completas de invasão (Initial Access $\to$ Privilege Escalation $\to$ Lateral Movement $\to$ Exfiltration), EDR Evasion, C2 Infrastructure (Cobalt Strike, Sliver, Havoc, Empire, custom C2s).
- **Engenharia Reversa de Firmware & Hardware Hacking:** Extração de memória flash (SPI, NAND, EEPROM) via interfaces de hardware (JTAG, UART, I2C, SPI, Bus Pirate, analisadores lógicos), desempacotamento de imagens de firmware (SquashFS, CramFS, JFFS2 via Binwalk), busca de vulnerabilidades zero-day em sistemas embarcados/IoT, hardcoded credentials, buffer overflows e análise de protocolos proprietários.
- **Engenharia Reversa de Drivers & Kernel Linux:** Análise e desenvolvimento de Kernel Modules (C), depuração de kernel (GDB, KDB/KGDB, QEMU, tracepoints, eBPF), dissecação de tráfego de barramentos (USB, PCI, I2C), engenharia reversa de blobs binários proprietários para criação de drivers open-source nativos para Linux.
- **Análise de Binários & Exploit Development:** Ghidra, IDA Pro, Radare2/Cutter, GDB com GEF/Pwndbg, x64dbg, Binwalk, Pwntools, análise estática e dinâmica de binários x86/x64, ARM e MIPS, contorno de mitigações (DEP/NX, ASLR, Canaries).
- **AI Red Teaming & Segurança em LLMs:** Prompt Injection (direto e indireto), Jailbreaking avançado, vazamento de contexto (Prompt Leakage), contorno de Guardrails, data poisoning e exploração de vulnerabilidades no OWASP Top 10 for LLMs/GenAI (GCP Vertex AI, Model Garden, agentes autônomos).
- **Pentest em Infraestrutura, Cloud & APIs:** Google Cloud Platform (GCP), Microsoft Azure, AWS, Kubernetes (GKE/AKS/K8s Hardening), Active Directory / Entra ID attack paths (BloodHound, Mimikatz, Impacket, CrackMapExec), Burp Suite Professional, OWASP Top 10, GraphQL e REST APIs.
- **Desenvolvimento Ofensivo & Automação:** C, Rust, Python, Go, Bash, PowerShell, Assembly (x86/ARM), automação de payloads e integração de exploits em pipelines.

---

## 💼 Experiência Profissional

### **Jeitto (Fintech / Meios de Pagamento)** | *10/2024 – 10/2026 (2 anos)*  
**Staff / Senior Offensive Security Engineer & Red Team Lead**
- **Campanhas de Emulação de Adversários:** Planejou e executou operações contínuas de Red Teaming baseadas no framework MITRE ATT&CK contra ecossistemas críticos de pagamento, cartões de crédito e crédito digital no GCP e Azure.
- **Evasão de Detecção & C2:** Desenvolveu payloads evasivos customizados e esteiras de C2 que contornaram mecanismos de WAF (Cloud Armor) e EDRs corporativos, demonstrando caminhos de exploração antes de agentes maliciosos reais.
- **AI Red Teaming (Vertex AI):** Conduziu baterias de testes ofensivos contra produtos baseados em Large Language Models (LLMs) integrados ao core financeiro, forçando quebras de guardrails, injeção de prompts e extração de dados confidenciais via RAG, resultando na criação de uma camada ativa de blindagem defensiva.
- **Auditoria Ofensiva de APIs Financeiras:** Identificou vulnerabilidades de Broken Object Level Authorization (BOLA/IDOR) e quebras de regras de negócio em microsserviços de pagamento, prevenindo fraudes financeiras de alto impacto financeiro e regulatório.
- **Purple Teaming & Elevação do SOC:** Conduziu debriefings pós-operação com o time de Blue Team / SOC, transformando cada TTP de ataque bem-sucedido em regras de correlação e detecção em SIEM, elevando a cobertura de defesa em 88%.

---

### **Clinicorp (Healthtech / SaaS Odontologia & Financeiro)** | *10/2022 – 09/2024 (2 anos)*  
**Senior Red Team Specialist & Penetration Tester**
- **Simulação de Ameaças & Compromisso de Dados:** Liderou campanhas ofensivas orientadas a demonstrar o impacto de vazamento de dados altamente sensíveis (prontuários e transações financeiras em conformidade com a LGPD e HIPAA).
- **Exploração de Identidade & Movimentação Lateral:** Mapeou vetores de ataque em arquiteturas híbridas e provedores de identidade (IAM/SSO), explorando permissões excessivas, chaves de API expostas e caminhos de escalonamento de privilégio no GCP e Azure.
- **Pentest em Aplicações Web e Mobile:** Executou testes de intrusão em profundidade (Black/Gray Box) contra aplicações web (React/Node) e aplicativos móveis (Android/iOS), descobrindo falhas críticas de autenticação, bypass de controles criptográficos e injeções de código.
- **Revisão Ofensiva de Código & Container Escape:** Conduziu testes de quebra de isolamento em clusters Kubernetes (GKE), testando técnicas de container breakout e adulteração de pipelines CI/CD, garantindo a correção de 92% das brechas antes da liberação em produção.

---

### **Locaweb SA** | *05/2019 – 09/2022 (3 anos e 5 meses)*  
**Senior Offensive Security Engineer / Threat Emulation**
- **Operações Red Team em Escala Massiva:** Executou testes de invasão e campanhas de emulação de adversários em infraestrutura massiva de data centers, nuvem pública e privada, atendendo a centenas de milhares de clientes.
- **Mapeamento de Domínio com BloodHound:** Mapeou grafos de ataque em florestas complexas de Active Directory, identificando e explorando caminhos não documentados para Domain Admin e acesso a storage arrays corporativos.
- **Análise Ofensiva de Hypervisors & Redes:** Conduziu auditorias de segurança ofensiva em tecnologias de virtualização (KVM, OpenStack) e redes corporativas, identificando vulnerabilidades de segmentação de VLANs e bypass de firewalls perimetrais.
- **Engenharia Reversa de Softwares Proprietários:** Desmontou e analisou binários de serviços legados e componentes compilados internos com Ghidra e Radare2, descobrindo falhas de corrupção de memória e chamadas inseguras de sistema.

---

### **PagSeguro SA** | *05/2017 – 04/2019 (2 anos)*  
**Offensive Security Engineer & DevOps Security**
- Executou testes de intrusão e simulações de ataque em gateways de pagamento, APIs de checkout transparente e terminais POS/SmartPOS.
- Avaliou a integridade de dispositivos de pagamento físicos, testando segurança de bootloader, interfaces de debug e resistência a adulterações locais.
- Criou exploits controlados para validar vulnerabilidades em esteiras de CI/CD e infraestruturas na AWS, provando a necessidade de controles de menor privilégio.

---

### **TCIBPO LTDA** | *05/2016 – 04/2017 (1 ano)*  
**Penetration Tester & Security Automation Engineer**
- Conduziu testes de intrusão de rede e infraestrutura em ambientes corporativos de grande porte em nuvens AWS e Azure.
- Desenvolveu scripts e ferramentas de automação em Python e Bash para acelerar enumeração, varredura de portas e verificação de configurações vulneráveis.

---

### **HCFMUSP (Hospital das Clínicas da FMUSP)** | *01/2014 – 04/2016 (2 anos e 4 meses)*  
**Senior Security Analyst & Researcher (P&D)**
- Atuou na divisão de P&D conduzindo testes de segurança ofensiva e análise de protocolos em equipamentos médicos conectados (IoMT - Internet of Medical Things) e sistemas de prontuário eletrônico.
- Analisou fluxos de comunicação de rede e dispositivos proprietários, identificando pontos críticos de interceptação de tráfego, criptografia fraca e falhas de controle de acesso.

---

### **Conectiva Linux** | *Analista de Sistemas / Kernel & Driver Researcher*  
**Engenharia Reversa de Hardware, Firmware & Desenvolvimento de Drivers Linux**
- **Desenvolvimento e Engenharia Reversa de Drivers:** Desenvolveu e adaptou drivers de dispositivo para o Kernel Linux em linguagem C. Atuou na engenharia reversa de chips e periféricos sem especificações públicas ou suporte nativo para Linux, monitorando tráfego de barramento e decompilando binários de drivers proprietários.
- **Análise de Binários ELF & Kernel Internals:** Pesquisa e depuração profunda de chamadas de sistema, estruturas internas do kernel Linux, empacotamento seguro e hardening de distribuições.

---

## 🔬 Especialização em Firmware & Hardware Reverse Engineering (Destaque Prático)

- **Extração Física e Lógica de Firmware:** Domínio de técnicas de aquisição de código executável diretamente de chips de memória (dump de flash SPI/I2C via clipes SOIC e solda direta) utilizando Bus Pirate, Raspberry Pi e gravadores dedicados.
- **Desempacotamento e Triage:** Reconstrução de árvores de diretórios a partir de dumps binários brutos com Binwalk, extração de sistemas de arquivos compactados e análise de cabeçalhos de bootloaders (U-Boot).
- **Caça a Falhas em Binários Embarcados:** Descompilação e análise de binários compilados para arquiteturas RISC/ARM/MIPS com **Ghidra, IDA Pro e Radare2**, identificando backdoors de depuração não removidos, credenciais codificadas e estouros de pilha.
- **Drivers Open-Source Nativos:** Histórico prático na criação de drivers Linux para dispositivos proprietários (como o projeto `canvasbio-cb2000-linux-driver`), revertendo protocolos de comunicação USB e viabilizando suporte 100% funcional no sistema operacional.

---

## 🎓 Formação Acadêmica

- **Bacharelado em Engenharia da Computação** – Universidade Presbiteriana Mackenzie
- **Pós-Graduação / Especialização em Data Science** – Johns Hopkins University *(Cursando)*
- **Técnico em Mecatrônica** – SENAI-SP *(Fundamentos sólidos de circuitos digitais, microcontroladores, barramentos de comunicação e eletrônica aplicada)*

---

## 📜 Certificações, Treinamentos & Credenciais

- **Ofensivo & Red Team:** Metodologias baseadas em OSCP / CRTO, Treinamento Avançado em Exploração de Redes e Sistemas, Evasão de Defesas.
- **Cloud & Arquitetura:** Treinamentos em Google Cloud Platform (GCP) Security & Architecture, Microsoft Azure Security Technologies.
- **Linux & Kernel:** Linux Conectiva, LPIC-1, LPIC-2, UTHA Linux Center (Criptografia, Firewalls e Segurança Avançada).
- **Redes & Telecom:** Cisco/Cyclades (Router, Switch & Network Administration).

---

## 🌐 Comunidade Hacker, Liderança & Inovação

- **Garoa Hacker Clube:** Membro fundador e participante pioneiro da cultura de hackerspaces no Brasil, liderando oficinas de hardware hacking, segurança ofensiva, software livre e engenharia reversa.
- **Fundação HackerSpace:** Co-Fundador e evangelizador de educação tecnológica colaborativa (2008 – Presente), promovendo inclusão digital, laboratórios de pesquisa em segurança e projetos open-source.
- **Campus Party Brasil:** Palestrante oficial em diversas edições (2010, 2012, 2013 e CP 10), ministrando palestras magnas e workshops técnicos sobre Linux, segurança ofensiva e exploração de sistemas.
- **Grupo de Usuários Linux Gentoo SP:** Ex-Presidente, liderando encontros técnicos sobre compilação de kernel, otimização de baixo nível e segurança de sistemas operacionais.
- **Mentor Técnico em Hackathons:** Mentor em mais de 20 hackathons de inovação, instruindo equipes em arquitetura resiliente, segurança de APIs e desenvolvimento seguro.
