# README - Personalização de Dados da Empresa

## Introdução
Este documento explica como modificar as informações da empresa na página HTML do site **Salgadinhos Delícia**.

## Onde Alterar os Dados

### 1. Nome da Empresa e Descrição
Arquivo: `index.html`

Altere o nome e a descrição no **header** da página:
```html
<h1>Salgadinhos Delícia</h1>
<p>Os melhores salgadinhos para sua festa</p>
```

### 2. Lista de Produtos
Arquivo: `index.html`

Edite os produtos dentro da seção **Nossos Salgadinhos**:
```html
<h3>Coxinha</h3>
<p>Deliciosa massa de batata recheada com frango desfiado temperado</p>
<p class="price">R$ 25,00</p>
```
Altere os nomes, descrições, preços e imagens conforme necessário.

### 3. Contato
Arquivo: `index.html`

Modifique os dados de contato na seção **Entre em Contato**:
```html
<span>(11) 99999-9999</span>
<span>Rua dos Salgados, 123 - São Paulo</span>
<span>Seg - Sáb: 9h às 18h</span>
<span>@salgadinhosdelicia</span>
```

### 4. WhatsApp
Arquivo: `index.html`

Altere o número do WhatsApp na função JavaScript:
```js
const message = encodeURIComponent("Olá! Gostaria de fazer um pedido dos melhores salgadinhos da cidade! 😋🎉");
window.open(`https://api.whatsapp.com/send?phone=5511999999999&text=${message}`, '_blank');
```
Substitua `5511999999999` pelo número correto da empresa.

## Conclusão
Com essas alterações, você pode personalizar o site com os dados reais da empresa. Caso precise de mais modificações, edite o arquivo `index.html` conforme necessário.

