## Desafio de projeto
Neste desafio, foi realizado um ataque de phishing com o auxílio da ferramenta setoolkit do Kali Linux. A ideia era criar uma réplica da página de login do Facebook para obter as credenciais de acesso da vítima.

### Ferramentas

- Kali Linux
- setoolkit

### 

### Configurando o Phishing no Kali Linux

- Acesso root: `sudo su`

![Untitled](img1.png)

- Iniciando o setoolkit: `setoolkit`

![Untitled](img2.png)

- Tipo de ataque: `Social-Engineering Attacks`

![Untitled](img3.png)

- Vetor de ataque: `Web Site Attack Vectors`

![Untitled](img4.png)

- Método de ataque: `Credential Harvester Attack Method`

![Untitled](img5.png)

- Método de ataque: `Site Cloner`

![Untitled](img6.png)

- Obtendo o endereço da máquina: `ifconfig`

![Untitled](img7.png)

- URL para clone: [http://www.facebook.com](http://www.facebook.com/)

![Untitled](img8.png)

### Resutados

![Untitled](img9.png)

![https://github.com/cassiano-dio/cibersecurity-desafio-phishing/raw/master/passwd.png](passwd.png)
