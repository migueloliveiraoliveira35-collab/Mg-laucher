# MG Launcher (Android)

Projeto inicial de launcher independente para Minecraft Bedrock no Android.

## O que tem
- Interface temática verde inspirada em blocos.
- Botão para abrir o Minecraft Bedrock oficial, se estiver instalado.
- Seletor de arquivos para localizar `.mcpack` e `.mcworld`.
- Atalho para as configurações do aplicativo.

## Gerar o APK sem computador
1. Baixe e extraia este ZIP.
2. Crie um repositório no GitHub e envie todos os arquivos extraídos.
3. Abra a aba **Actions** do repositório.
4. Execute **Build MG Launcher APK** (ou espere o build automático).
5. Abra a execução concluída e baixe o artefato **MG-Launcher-APK**.
6. Extraia o artefato para encontrar `app-debug.apk` e instale no Android.

## Observações
- O projeto não inclui Minecraft e não faz download de conteúdo pago.
- A importação de packs depende do Android e da versão do Minecraft; em alguns aparelhos será necessário abrir o arquivo pelo app Arquivos e selecionar Minecraft.
- O APK gerado pelo fluxo é uma versão de teste (`debug`), não uma versão publicada na Play Store.
