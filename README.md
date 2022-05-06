# API para integração
Como adicionar um botão flutuante de chat para que o usuário consiga retirar boleto em seu site.




### **1º - Solicitar credenciais de acesso**

Solicitar à Sami as seguintes credenciais de acesso para integração(Username, KEY, AUTHENTICATION_KEY).


### **Utilizar**
```json
Content-Type: application/json
```

### **Cidade**

URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/cidades/

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true
}
```

### **Bairros**

URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/bairros/

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true,
    city": "Porto Alegre"
}
```

### **Tipo de imóvel**

URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/tiposimovel/

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true
}
```
