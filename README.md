# API para integração
Como adicionar um botão flutuante de chat para que o usuário consiga retirar boleto em seu site.




### **1º - Solicitar credenciais de acesso**

Solicitar à Sami as seguintes credenciais de acesso para integração.


### **Cidade**

Inserir, antes do fechamento da tag BODY do site, a chamada para as configurações.
URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/cidades/

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true
}
```
