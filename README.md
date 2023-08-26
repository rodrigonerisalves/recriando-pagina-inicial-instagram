# Desafio Recriando a Página Inicial do Instagram

O código abaixo é uma estrutura básica de uma página HTML que representa uma tela de login do Instagram. Aqui está uma divisão por partes do código e como foi feito:

**Declaração Inicial**

```html
<!DOCTYPE html>
<html lang="en">
```
- Define o tipo de documento como HTML5.

**Cabeçalho**

```html
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Instagram</title>
</head>
```
- Define o conjunto de caracteres como UTF-8.
- Configura a exibição responsiva para dispositivos móveis.
- Importa um arquivo de estilo CSS externo chamado "style.css".
- Define o título da página como "Instagram".

**Corpo do Documento**

```html
<body>
    <div class="instagram-wrapper">
        <div class="instagram-phone">
            <img src="img/cel-instagram.png" alt="celular">
        </div>
        <div class="instagram-continue">
            <div class="group">
                <img src="img/instagram-logo-4.png" class="instagram-logo" alt="instagram logo">
                <div class="profile-photo">
                    <img src="https://i.stack.imgur.com/14h3t.png" alt="foto de perfil">
                </div>
                <a href="https://www.instagram.com/rodrigonerisoficial/" class="instagram-login">Continue como rodrigonerisoficial</a>
                <a href="https://www.instagram.com/" class="instagram-logout">Remover conta</a>
            </div>
            <div class="group">
                <p class="not-account">Não é rodrigonerisoficial </p>
                <p class="not-account">
                    <span class="link-blue">Alternar contas</span>
                    ou
                    <span class="link-blue">Inscreva-se</span>
                </p>
            </div>
            <div class="get-the-app">
                <p class="get-app">Baixe o aplicativo</p>
                <div class="download">
                    <a href="https://l.instagram.com/?u=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dcom.instagram.android%26referrer%3Dig_mid%253DA3C24CA1-C6B8-4A12-88D5-EF1E0D856202%2526utm_campaign%253DloginPage%2526utm_content%253Dlo%2526utm_source%253Dinstagramweb%2526utm_medium%253Dbadge&e=AT2eWdfGd88oh6iI4RxGALoZtsZ1cj9v6nQD-_XwJ3ccOmg7QPAKCtQeEx3rMF3Q9D9Oi97lPqKOfep8zQLi-H43AEHK8n86MQ0MPWoTCMH7zQslb_jQv-C5GBuNQqU4D24f-93NB26RuG6bO6CUnQ" class="app-download"></a>
                    <a href="ms-windows-store://pdp/?productid=9nblggh5l9xt&referrer=appbadge&source=www.instagram.com&mode=mini&pos=0%2C0%2C1366%2C738" class="app-download"></a>
                </div>
            </div>
        </div>
    </div>
</body>
```
- Contém o conteúdo principal da página, envolvido por uma div com a classe "instagram-wrapper".
- A div "instagram-phone" contém uma imagem do celular do Instagram.
- A div "instagram-continue" contém o formulário de login e outras informações do Instagram.
- A div "group" agrupa elementos como o logo do Instagram, foto de perfil, links "Continue como rodrigonerisoficial" e "Remover conta".
- A div "group" também agrupa os parágrafos com informações adicionais e os links "Alternar contas" e "Inscreva-se".
- A div "get-the-app" contém informações sobre o aplicativo e os links para download.
- A div "download" contém os links para download do aplicativo nas respectivas lojas.

**Fechamento da Página**

```html
</html>
```
- Fecha a tag HTML.

Este código HTML cria uma página com a interface básica de login do Instagram, incluindo o logo do Instagram, um formulário de login, links para entrar com uma conta existente ou criar uma nova conta e links para baixar o aplicativo Instagram nas lojas de aplicativos. É importante notar que algumas imagens e links externos foram utilizados neste exemplo, portanto, para visualizar a página corretamente, é necessário ter acesso a esses recursos.

## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Visual Studio Code](https://code.visualstudio.com/download) - Code Editing


## ✒️ Autor

* **Rodrigo Neris** -  [*Trabalho Inicial*](https://github.com/rodrigonerisalves)
---
⌨️ com ❤️ por [Rodrigo Neris](www.linkedin.com/in/rodrigo-neris) 😊