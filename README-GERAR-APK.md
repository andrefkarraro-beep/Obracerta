# Como gerar o arquivo .APK no Android Studio

Este pacote contém o projeto Android completo (Kotlin + WebView com aplicativo embutido offline em app/src/main/assets).

## Passo a passo no Android Studio

1. Extraia este arquivo `.zip` para uma pasta no seu computador (ex.: `C:\Projetos\ObraCerta-Android-APK`).
2. Abra o **Android Studio** e clique em **Open** (Abrir).
3. Selecione a pasta extraída `ObraCerta-Android-APK` e clique em **OK**.
4. Aguarde o Gradle sincronizar as dependências (barra inferior direita). Se aparecer um aviso sobre Gradle Wrapper, clique em **OK / Use Gradle Wrapper**.
5. No menu superior do Android Studio, clique em:
   **Build > Build Bundle(s) / APK(s) > Build APK(s)**
6. Quando terminar, clique em **locate** na notificação — o arquivo `app-debug.apk` estará em:
   `app/build/outputs/apk/debug/app-debug.apk`
7. Envie esse `app-debug.apk` para o celular Android e toque nele para instalar.
