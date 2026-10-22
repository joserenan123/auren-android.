# AUREN — projeto Android inicial

Este projeto empacota o HTML AUREN fornecido em um aplicativo Android usando WebView. A identidade visual original foi mantida.

## Como gerar o APK
1. Instale o Android Studio em um computador.
2. Abra a pasta `AUREN_Android_Project` no Android Studio.
3. Aguarde a sincronização do Gradle e instale o Android SDK 35 se solicitado.
4. Para testar: **Run > Run 'app'** com um celular Android conectado ou emulador.
5. Para gerar o APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Importante sobre a loja completa
O HTML recebido é uma página de conceito visual e declara que as imagens não representam produtos disponíveis para compra. Este projeto é a base Android e **ainda não implementa** autenticação real, catálogo comercial, estoque, pagamentos ou processamento de pedidos. Para uma loja real, precisamos cadastrar produtos e ligar o app a um backend seguro (autenticação, banco de dados, estoque e pedidos) e a um provedor de pagamento. Não coloque senhas, chaves secretas ou dados de cartão no HTML/app.

O projeto inclui a permissão de internet para a futura integração com o backend, mas não depende de conexão para abrir a página atual.
