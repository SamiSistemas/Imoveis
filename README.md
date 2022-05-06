# API para integração
Como adicionar um botão flutuante de chat para que o usuário consiga retirar boleto em seu site.


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

### **Fotos do imóvel**

URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/fotos/{id_imovel}

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true
}
```

### **Caracteristicas do imóvel**

URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/caracteristicas/{id_imovel}

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true
}
```


### **Caracteristicas do imóvel**

Todos Imóveis => URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/imovel/
Único imóvel => URL: https://wapi.samierp.com.br/AUTHENTICATION_KEY/locacao/imovel/{id_imovel}

### Exemplo:

```php
{
    "sigla": "KEY",
    "chamadaInterna": true,
    "properties_per_page": 50, #imóveis por página
    "current_page": 1, #pagina atual
    "city": 'Porto Alegre',
    "district": ['AUXILIADORA', 'CENTRO'],
    "types": ['Apto', 'Casa'],
    "bedrooms": 1, #Dormitórios
    "garages": 1, #Garagens
    "bathrooms": 1 #banheiros
    "suites": 1, #suítes
    "minimum_value": 50000, #Valor minímo
    "maximum_value": 150000, #Valor máximo
    "minimum_area": 30, #área minímo
    "maximum_area": 100, #área máximo
}
```
