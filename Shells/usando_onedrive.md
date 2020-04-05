By an4kein

https://www.arcserve.com/insights/office-365-exchange-reality-key-differentiators-udp-6-5-exchange-online-protection/

https://enigma0x3.net/2016/03/15/phishing-with-empire/

Requisitos:

Original Project: https://github.com/EmpireProject/Empire   (Version: 2.5)

Projeto with Fix: https://github.com/BC-SECURITY/Empire/releases (Version: 3.1.3)

Create account in OneDrive: https://products.office.com/en/onedrive/online-cloud-storage?rtc=1

https://www.bc-security.org/post/using-the-onedrive-listener-in-empire-3-1-3


To run the OneDrive listener, type 

`uselistener onedrive`

 and then

`info`

![run_onedrive_empire](https://raw.githubusercontent.com/an4kein/redteambrazil/master/Shells/images/run_module-empire.png?token=AJBHTVOQJXHFATEEP3WCA626RD6GY)

Acesse: https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationsListBlade

Registre um App:

ADICIONE UMA NOVA APLICACAO

![reg_app](https://raw.githubusercontent.com/an4kein/redteambrazil/master/Shells/images/run_application.png?token=AJBHTVLZMNVLV7G3B5OIEXC6RD6MW)

Add URL para redirecionamento:

https://login.live.com/oauth20_desktop.srf


Depois de registrado, copie seu CLIENTE ID

![CLIENTEID](https://raw.githubusercontent.com/an4kein/redteambrazil/master/Shells/images/copy-id.png?token=AJBHTVKF2R3ZWKXSYKJGF226RD67M)


O Segredo do Cliente é o próximo campo exigido pelo Empire. No entanto, ele não é gerado automaticamente, mas pode ser facilmente criado navegando até a guia Certificados e segredos. Uma vez nesta página, selecione Novo Segredo do Cliente para gerar o novo valor.

Novo cliente:

![add_new](https://raw.githubusercontent.com/an4kein/redteambrazil/master/Shells/images/cert_add.png?token=AJBHTVPO3G6Q3S375HH3JQC6RD7SW)

Get key:

![get_key](https://raw.githubusercontent.com/an4kein/redteambrazil/master/Shells/images/key.png?token=AJBHTVNDV3DQ37DCLNC4QA26RD7VW)
