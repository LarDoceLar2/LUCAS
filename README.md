aqui esta a base se prisisar:

```html
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vaquinha Solidária</title>
    <style>
        /* Estilos básicos para o site */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        .cta-button {
            display: block;
            width: 100%;
            padding: 15px;
            margin-top: 20px;
            text-align: center;
            background-color: #28a745;
            color: white;
            font-size: 18px;
            text-decoration: none;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #218838;
        }

        .social-share {
            text-align: center;
            margin-top: 20px;
        }

        .social-share button {
            padding: 10px 15px;
            margin: 5px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            color: white;
        }

        .facebook {
            background-color: #3b5998;
        }

        .whatsapp {
            background-color: #25d366;
        }

        .twitter {
            background-color: #1da1f2;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Título da página -->
        <h1>Ajude na Vaquinha Solidária!</h1>
        
        <!-- Descrição da vaquinha -->
        <p>
            Estamos arrecadando fundos para uma causa muito importante e sua ajuda pode fazer toda a diferença!
            Clique no botão abaixo para acessar a vaquinha e contribuir com o que puder.
        </p>
        
        <!-- Botão de chamada para ação -->
        <a href="https://www.vakinha.com.br/meu-link" class="cta-button">Contribua Agora!</a>
        
        <!-- Seção para compartilhar nas redes sociais -->
        <div class="social-share">
            <p>Compartilhe com seus amigos:</p>
            <!-- Botões para compartilhar -->
            <button class="facebook" onclick="shareFacebook()">Facebook</button>
            <button class="whatsapp" onclick="shareWhatsApp()">WhatsApp</button>
            <button class="twitter" onclick="shareTwitter()">Twitter</button>
        </div>
    </div>

    <script>
        // Função para compartilhar no Facebook
        function shareFacebook() {
            const url = encodeURIComponent('https://www.vakinha.com.br/meu-link');
            const facebookShareUrl = `https://www.facebook.com/sharer/sharer.php?u=${url}`;
            window.open(facebookShareUrl, '_blank');
        }

        // Função para compartilhar no WhatsApp
        function shareWhatsApp() {
            const text = encodeURIComponent('Ajude nessa vaquinha solidária! Contribua com o que puder: https://www.vakinha.com.br/meu-link');
            const whatsappShareUrl = `https://wa.me/?text=${text}`;
            window.open(whatsappShareUrl, '_blank');
        }

        // Função para compartilhar no Twitter
        function shareTwitter() {
            const text = encodeURIComponent('Ajude nessa vaquinha solidária! Contribua com o que puder: https://www.vakinha.com.br/meu-link');
            const twitterShareUrl = `https://twitter.com/intent/tweet?text=${text}`;
            window.open(twitterShareUrl, '_blank');
        }
    </script>

</body>
</html>
```

### Explicação do código:

1. **HTML**: 
   - Estrutura da página, título, parágrafos e botão de doação.
   - Há uma seção para compartilhamento nas redes sociais com botões para Facebook, WhatsApp e Twitter.

2. **CSS**: 
   - Estilização básica da página: centraliza os textos, define cores e estilos dos botões e da página.

3. **JavaScript**: 
   - Funções para compartilhar o link da vaquinha diretamente no Facebook, WhatsApp e Twitter.
   - Abre uma nova aba para cada rede social com o link para a vaquinha.

### O que você precisa alterar:
- Substitua `"https://www.vakinha.com.br/meu-link"` pelo link da sua vaquinha.

Assim, terá um site pronto para divulgar sua campanha e permitir que as pessoas compartilhem nas redes sociais! 

Se precisar de ajustes ou mais alguma ajuda, avise-me.

Para mais informações, visite [GPTOnline](https://gptonline.ai/pt/).

voce tera que ajustar o botao "contribua agora"
