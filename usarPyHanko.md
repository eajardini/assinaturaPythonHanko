Biblioteca python pyhanko

Download de pfx de testes em https://asecuritysite.com/encryption/digitalcert2

1ª assinatura
pyhanko sign addsig --field 2/50,50,200,150/Name pkcs12 20231130_Ata.pdf output.pdf fred_pass_apples.pfx

2ª assinatura
pyhanko sign addsig --field 2/210,50,350,200/cpf pkcs12 output.pdf output2.pdf bill01_pass_orange.pfx 
