<p align="right">
  <img src="https://github.com/ThalitaFelima/DesafioGithub/blob/main/Imagem%201%20-%20Readme.jpg" alt="foto de perfil" width="200">
</p>

<h3 align="center">Thalita Ferreira Lima de Paula</h3>
<p align="center">Aspirante a Dev – Alpha EdTech</p>


<hr>

![texto alternativo](https://t2.tudocdn.net/558755?w=824&h=494)

# **Trila I- Introdução à Redes e à Internet**

# **Professor Kenji Taniguchi**





#### 🗂️ Aula 01 – Conceitos Fundamentais de Redes



Data: 10/11/25, 08:00



Rede como conjunto de dispositivos interligados para troca de informações.



Tipos de redes: LAN, WAN, MAN, PAN.



Modelo OSI (7 camadas) e TCP/IP (4 camadas).



Conceitos de protocolos, encapsulamento, switches e roteadores.



Para devs: entenda como dados descem pelas camadas e como cada nível pode afetar latência, MTU, pacotes fragmentados e erros de transporte.



&nbsp;-----------------------------------------------------------------------------------------------



#### 🔗 Aula 02 – Protocolos de Comunicação



Data: 11/11/25, 08:00



TCP: confiável, orientado à conexão.



UDP: rápido, sem garantia de entrega.



HTTP/HTTPS, SMTP, DNS, FTP.



Para devs: teste serviços considerando TCP e UDP; valide portas e firewall; verifique timeouts e retransmissões.



------------------------------------------------------------------------------------------------



#### 🌐 Aula 03 – IP, Sub-redes e Portas



Data: 12/11/25, 08:00



IPv4 e IPv6; representação e máscara.



Subnetting e CIDR.



Portas lógicas para diferenciação de serviços.



NAT e roteamento.



Para devs: entenda impacto de NAT em APIs, VPN e logs. Sempre confirme faixa de IP e firewall na integração.



------------------------------------------------------------------------------------------------

#### 

#### 🧭 Aula 04 – Serviços e Aplicações na Internet



Data: 13/11/25, 08:00



Modelos cliente-servidor e P2P.



Web, e-mail, streaming.



CDN e balanceamento.



Para devs: use cache, compressão, CDN e técnicas de otimização para reduzir latência.



------------------------------------------------------------------------------------------------



#### 🏷️ Aula 05 – DNS (Domain Name System)



Data: 14/11/25, 08:00



Resolve nomes para endereços IP.



Registros: A, AAAA, CNAME, MX, TXT.



DNS recursivo, autoritativo e caching.



Para devs: erros de DNS podem parecer falhas de API; teste resolução, TTL e propagação.



------------------------------------------------------------------------------------------------





#### 🌍 Aula 06 – Arquitetura da Internet



Data: 17/11/25, 08:00



Estrutura hierárquica, ISPs, BGP.



Autonomia dos sistemas e roteamento global.



Para devs: entenda que latência internacional é estrutural; monitore rotas e comportamento da rede.



------------------------------------------------------------------------------------------------



#### 🖧 Aula 07 – Redes de Computadores



Data: 18/11/25, 08:00



Switching e VLANs.



Wi-Fi, interferência e padrões IEEE.



QoS e priorização.



Para devs: redes instáveis afetam apps em tempo real; implemente reconexão, retry e tolerância a falhas.



------------------------------------------------------------------------------------------------



#### 🔐 Aula 08 – Segurança de Redes



Data: 19/11/25, 08:00



Firewalls, IDS/IPS, VPN, TLS.



Malware: vírus, worms, trojans, ransomware, spyware.



Ataques: MITM, DDoS, spoofing, sniffing.



Para devs: priorize atualização, logs, criptografia, autenticação forte, políticas de privilégios mínimos.



------------------------------------------------------------------------------------------------



#### 🛡️ Aula 09 – Segurança na Web



Data: 24/11/25, 08:00



HTTPS, certificados SSL/TLS.



Handshake, chave simétrica e assimétrica.



Vulnerabilidades HTTP: falta de criptografia, interceptação, manipulação de conteúdo.



Conteúdos das CDNs e mitigação de ataques.



Para devs: implemente HSTS, sanitize inputs, use HTTPS obrigatório, verifique expiração de certificados.



------------------------------------------------------------------------------------------------

#### 

#### 🚀 Aula 10 – Tendências Modernas



Data: 25/11/25, 08:00



IoT e protocolos leves (MQTT, CoAP, Zigbee, BLE).



SDN e separação entre plano de controle e plano de dados.



Blockchain, consenso e imutabilidade.



Nuvem, Zero Trust, ZTNA, SASE.



Para devs: compreenda impacto de VPN, IAM, políticas de rede na nuvem, automação e infraestrutura como código.



------------------------------------------------------------------------------------------------



#### 💡 Dicas Gerais para Devs 



* Teste aplicações em redes reais (Wi-Fi ruim, VPN, 4G).
* Conheça basics: DNS, portas, IP, rotas, firewall.
* Trate erros de rede como parte do fluxo normal da aplicação.
* Evite suposições sobre IP do usuário, especialmente com VPN.
* Garanta criptografia, rotacionamento de chaves e certificados.
* Em nuvem: privilegie IAM, roles, segmentação e automação.
* Use logs estruturados para rastrear problemas entre camadas.
* Lembre-se que a maior brecha moderna é configuração incorreta.



------------------------------------------------------------------------------------------------


![texto alternativo](https://hermes.dio.me/articles/cover/d2489f96-d56f-4b82-bc7f-84fbc9fb1368.jpg)




# **Trila II- Controle de Versão** 

# **Professor Paulo Marcotti**



#### 🗂️ Aula 01 – Git, VSCode e GitLens



26/11/2025 – 08:00



📌 Conceitos de Controle de Versão



* O que é um sistema de controle de versão.
* O que é Git.
* Repositório, commit e como o Git armazena histórico.



🛠️ Instalação



* Git no Windows, Linux, macOS.
* Uso no Windows nativo e via WSL.



⚙️ Configuração Inicial



* Nome e email.
* Editor de texto.
* Configurações globais e locais.



📁 Fluxo Básico



* Criar pasta do projeto.
* git init e a pasta .git.
* Working Tree, Index e Commit.
* git status, git add, git commit.



📜 Histórico



* git log e hash de commit.
* Commits armazenam somente deltas.



💡 Dicas para devs



* Commitar cedo e commit pequeno facilita rollback.
* Descrever commits com clareza ajuda na manutenção.
* Revisar git status antes de qualquer ação evita erros.
* Entender Working Tree e Index reduz confusão com arquivos não rastreados.



------------------------------------------------------------------------------------------------



#### 🌿 Aula 02 – Branches e Merge



27/11/2025 – 08:00



🌱 Branches



* O que é uma branch e como usá-las.
* git branch e a referência HEAD.
* git checkout (mesmo commit e commits diferentes).



🔀 Merge



* Merge fast-forward.
* Merge three-way.
* Quando ocorre cada um.
* Conflitos de merge e resolução.



🗑️ Gerenciamento de Branches



Deletando branches.



🆘 Resolução de Problemas Comuns



* Working Tree modificada: git stash.
* Cancelando merge com conflito: git merge --abort.
* Desfazendo merge: git reset --hard.
* Commit feito na branch errada: git reset --hard.
* Desfazer commit mantendo conteúdo: git reset --mixed.



💡 Dicas para devs



* Criar uma branch por feature evita confusão.
* Prefira merges frequentes para evitar conflitos grandes.
* Leia conflitos com calma: Git marca exatamente onde resolver.
* Não faça git reset --hard sem ter certeza: ele destrói conteúdo local.



------------------------------------------------------------------------------------------------



#### 🌐 Aula 03 – Repositório Remoto



28/11/2025 – 08:00



📡 Conceitos



* O que é um repositório remoto.
* Remoto como backup.
* Remotos não atualizam automaticamente.



🏛️ GitHub



* Criar conta.
* Criar par de chaves SSH.
* Criar repositório remoto.



📤 Envio do Projeto



* git remote add.
* git push e upstream.
* Remote-tracking branch.



👥 Colaboração



* git clone.
* Adicionar colaboradores.
* Mudanças locais e git push.



🔄 Integração de Mudanças



* git fetch, git merge, git pull.
* Atualizar branch main no local e no remoto.
* Deletar branch remota.



⚠️ Problemas Comuns



* Push falhou (non-fast-forward).
* Divergência entre branch local e remota.
* Conflitos ao dar pull.



💡 Dicas para devs



* Nunca dê git push -f sem motivo — sobrescreve histórico.
* Sempre faça git pull antes de iniciar uma feature.
* Use SSH, não HTTPS, para evitar pedir senha.
* Mantenha sua main estável e funcional.



------------------------------------------------------------------------------------------------

#### 

#### 🔁 Aula 04 – Pull Request



01/12/2025 – 08:00



🌟 Conceito de Pull Request



* PR é uma solicitação para integrar alterações de uma branch em outra.
* Usado em colaboração, revisão de código e versionamento organizado.



📝 Processo



* Criar branch de feature.
* Enviar para o remoto via git push.
* Abrir PR no GitHub.
* Revisar comentários, ajustar commits e atualizar PR.
* Merge do PR na branch principal.



🔍 Revisão de Código



* Comentários, sugestões e aprovação.
* Histórico detalhado das mudanças.



💡 Dicas para devs



* PR pequeno = revisão rápida.
* Explique o propósito do PR com clareza
* Nomeie bem suas branches.
* Evite PRs gigantes: dificultam testes e revisões.
* Sempre atualize a branch antes de abrir o PR.



