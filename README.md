# Santander Bootcamp Ciberseguranca
---
# 📒 Configurando o Phishing no Kali Linux

- Acesso root: sudo su
- Iniciando o setoolkit: setoolkit
- Tipo de ataque: Social-Engineering Attacks
- Vetor de ataque: Web Site Attack Vectors
- Método de ataque: Credential Harvester Attack Method
- Método de ataque: Site Cloner
- Obtendo o endereço da máquina: ifconfig
- Criação de uma URK clone
---
1️⃣ Acesso root
bash
sudo su
Eleva os privilégios para root, permitindo a execução de comandos administrativos no sistema.

2️⃣ Iniciando o SET (Social-Engineer Toolkit)
bash
setoolkit
O SET é uma ferramenta usada para simular ataques de engenharia social, incluindo Phishing, criação de payloads e envio de e-mails maliciosos.

3️⃣ Escolhendo o tipo de ataque
Social-Engineering Attacks
Opção dentro do SET que contém diversos métodos de ataque relacionados à engenharia social.

4️⃣ Escolhendo o vetor de ataque
Web Site Attack Vectors
Permite criar ataques baseados na clonagem de páginas web.

5️⃣ Escolhendo o método de ataque
Credential Harvester Attack Method
Este método coleta credenciais (usuário/senha) digitadas pela vítima ao acessar a página falsa.

6️⃣ Escolhendo o template do site
Web Templates
Aqui, pode-se escolher entre diferentes modelos de sites para clonar ou inserir um URL específico.

7️⃣ Obtendo o endereço IP da máquina
ifconfig
Mostra o endereço IP local da máquina. Esse IP será usado para hospedar o site falso e direcionar vítimas para ele.

8️⃣ Definindo a URL para clonar
http://www.google.com
O site do Google será clonado, e todas as credenciais inseridas na página falsa serão capturadas.

Resultado esperado
Quando um usuário acessar o link da página falsa gerada pelo SET e tentar fazer login, suas credenciais serão registradas no Kali Linux.


![image](https://github.com/user-attachments/assets/703622f7-6fad-431f-bc87-ed93618f2d1d)


== Referências ==
* [DIO Bootcamp](https://www.dio.me/)
* https://www.kali.org/docs/introduction/what-is-kali-linux/
