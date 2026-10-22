# Gerar o APK usando apenas o celular Android

Este projeto tem um workflow de GitHub Actions que compila o APK na nuvem. Você não precisa instalar Android Studio no celular.

## Passos
1. Entre em https://github.com pelo navegador e crie uma conta ou faça login.
2. Crie um repositório novo, por exemplo `auren-android`. Deixe-o **Private** se preferir manter o código privado.
3. Extraia este ZIP no celular usando o gerenciador de arquivos. Abra a pasta `AUREN_Android_Project`.
4. Envie o **conteúdo** dessa pasta para o repositório (não envie somente o ZIP). A pasta `.github/workflows` é importante; se não aparecer, ative a opção de mostrar arquivos ocultos no gerenciador.
5. No GitHub, abra a aba **Actions**. Se aparecer uma tela de confirmação, habilite workflows.
6. Selecione **Build AUREN APK** e toque em **Run workflow**. Aguarde o trabalho terminar com marca verde.
7. Abra a execução concluída e, em **Artifacts**, baixe `AUREN-debug-APK`. Extraia o ZIP baixado; dentro estará `app-debug.apk`.
8. Toque em `app-debug.apk` para instalar. Se o Android bloquear, autorize a instalação dessa fonte nas configurações exibidas pelo próprio sistema e tente novamente.

Se a opção de enviar pasta inteira não estiver disponível no navegador do celular, este método pode ficar difícil; não envie apenas o ZIP do projeto, pois o workflow não o extrai automaticamente.

## Importante
Este APK é uma versão de teste que abre o HTML local da AUREN. Ele não contém ainda login real, catálogo conectado a estoque, carrinho persistente, checkout, pagamentos nem gestão de pedidos. Não é uma loja pronta para vender.
