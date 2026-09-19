**Materia**: Fundamentos de redes -- ENE0274

**Professor:** Laerte Peotta de Melo, Dr.

**Aluno**: lucas de souza viegas


1)  Codifique as credenciais com Base64

![](./assets/atividade_05/4c3a9e4709d8e4a9e8d54491e585fbe634996508.png){width="6.260416666666667in"
height="1.1875in"}

2)  Conexão com o smtp do google

![](./assets/atividade_05/e7ea191b883a6e31a419f1a27e4653f6e28f53fc.png){width="6.260416666666667in"
height="4.489583333333333in"}

![](./assets/atividade_05/a134182570737088b0b2546cdf7c2f41f0970079.png){width="6.260416666666667in"
height="4.489583333333333in"}

![](./assets/atividade_05/9258dcf1a1d496019d865ec64b99fc93d98ea89b.png){width="6.260416666666667in"
height="4.489583333333333in"}

-   **openssl s_client**: cria uma conexão segura usando TLS/SSL.

-   **-starttls smtp**: inicia a negociação TLS sobre o protocolo SMTP.

-   **-connect smtp.gmail.com:587**: conecta à porta SMTP do Gmail
    (587).

-   O terminal mostra o **certificado digital** do servidor, confirmando
    que a comunicação é autenticada e segura.

3)  Handshake com SMTP + AUTH LOGIN

![](./assets/atividade_05/e4f07068d3fe8790268d37ac2c1a833f36002951.png){width="6.260416666666667in"
height="1.1979166666666667in"}

4)  Envio da mensagem

![](./assets/atividade_05/4d7222043142b4c13690ee6644e98d58e424c534.png){width="6.260416666666667in"
height="4.302083333333333in"}

![](./assets/atividade_05/e8d28cb938649c09dda1600e6e170cc213f7a883.png){width="6.260416666666667in"
height="2.71875in"}

![](./assets/atividade_05/a7e39a957d88361cf9eac98dcb14f3d6028a3f98.png){width="6.260416666666667in"
height="1.1354166666666667in"}

> ![](./assets/atividade_05/3f91fa2dd6a4acb111ba67fc98fedd903ba7d1bb.png){width="6.260416666666667in"
> height="1.40625in"}

5)  Eu me conectei de forma correta ao **SMTP do Gmail** com
    **STARTTLS** (conexão segura).

-   As credenciais foram autenticadas.

-   O e-mail foi enviado e confirmado pelo servidor (250 2.0.0 OK).

-   O encerramento da conexão foi normal.
