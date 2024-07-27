# JOGO VELHA EM APK
👨‍🏫JOGO DA VELHA FEITO NO ANDROID STUDIO EM KOTLIN.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este é um jogo da velha (tic-tac-toe) para Android com as seguintes funcionalidades:

- **Jogadores Alternados**: Dois jogadores alternam turnos para marcar as células do tabuleiro.
- **Interface Gráfica**: O tabuleiro é composto por uma grade 3x3 de células (ImageView).
- **Marcação das Células**: Cada jogador marca uma célula vazia com um círculo ou X.
- **Detecção de Vencedor**: Verifica automaticamente se um jogador completou uma linha, coluna ou diagonal com suas marcas, declarando-o vencedor.
- **Verificação de Empate**: Detecta quando todas as células estão preenchidas sem um vencedor, declarando empate.
- **Reinício do Jogo**: Um botão de reiniciar permite limpar o tabuleiro e começar uma nova partida.
- **Feedback ao Jogador**: Mostra mensagens indicando vitória ou empate.

## EXECUTANDO O PROJETO
### INSTALANDO O APK:
   - **Download do APK**: Acesse a pasta `./APK/` e encontre o arquivo `NomeDoApp.apk`.
   - **Transferência para o dispositivo**: Transfira o arquivo APK para o seu dispositivo Android. Isso pode ser feito via cabo USB, Google Drive, email ou qualquer outro método de transferência de arquivos.
   - **Instalação**:
     1. No dispositivo Android, vá para `Configurações` > `Segurança` e habilite a opção `Fontes desconhecidas` (Isso permite a instalação de aplicativos fora da Google Play Store).
     2. Navegue até o local onde o APK foi salvo (usando um gerenciador de arquivos).
     3. Toque no arquivo `NomeDoApp.apk` para iniciar a instalação.
     4. Siga as instruções na tela para concluir a instalação.
   - **Execução**: Após a instalação, você pode abrir o aplicativo diretamente da tela de instalação ou encontrá-lo na gaveta de aplicativos do seu dispositivo.

### ANDROID STUDIO:
#### ABRINDO O PROJETO:
   - **Preparação do ambiente**:
     1. Certifique-se de que você tenha o [Android Studio](https://developer.android.com/studio) instalado em sua máquina.
     2. Instale as dependências necessárias (SDKs, emuladores, etc.) conforme indicado pela documentação do Android Studio.

   - **Abrindo o projeto no Android Studio**:
     1. Abra o Android Studio.
     2. Na tela de boas-vindas, selecione `Open an existing project`.
     3. Navegue até o diretório `./CODIGO` onde o projeto foi clonado e selecione-o.
     4. Aguarde enquanto o Android Studio indexa o projeto e baixa as dependências necessárias.

   - **Executando o projeto**:
     1. Conecte um dispositivo Android via USB ou configure um emulador de dispositivo Android no Android Studio.
     2. Certifique-se de que o dispositivo/emulador está selecionado na barra de dispositivos do Android Studio.
     3. Clique no botão `Run` (ícone de play) para compilar e executar o aplicativo.

   - **Depuração**:
     - Para iniciar a depuração, clique no botão `Debug` (ícone de inseto) e siga as instruções do Android Studio para definir pontos de interrupção e inspecionar variáveis.

#### GERANDO O APK:
   Depois de melhorar o projeto, você pode gerar o APK novamente. Siga os passos abaixo para gerar o APK usando o Android Studio:

   1. **Abrir o Projeto**:
      - Abra o Android Studio.
      - Vá para `File` > `Open...` e selecione o diretório `./CODIGO` do seu projeto.

   2. **Construir o Projeto**:
      - Certifique-se de que todas as dependências estejam atualizadas e que o projeto esteja compilando corretamente.
      - Vá para `Build` > `Clean Project` para limpar o projeto.
      - Depois, vá para `Build` > `Rebuild Project` para reconstruir o projeto.

   3. **Gerar o APK**:
      - Vá para `Build` > `Build Bundle(s) / APK(s)` > `Build APK(s)`.
      - O Android Studio começará a compilar o projeto e a gerar o APK.
      - Após a conclusão, uma notificação aparecerá no canto inferior direito da tela com a mensagem `APK(s) generated successfully.`
      - Clique na notificação ou vá para `locate` para encontrar o APK gerado, que geralmente está localizado em `./app/build/outputs/apk/release/`.

   4. **Testar o APK**:
      - Transfira o APK gerado para o seu dispositivo Android e instale-o conforme as instruções na seção **EXECUTANDO O PROJETO** > **APK** acima.

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens e tecnologias, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE ANDROID STUDIO EM KOTLIN](https://github.com/VILHALVA/CURSO-DE-ANDROID-STUDIO-EM-KOTLIN)
* [CURSO DE KOTLIN](https://github.com/VILHALVA/CURSO-DE-KOTLIN)
* [CURSO DE XML](https://github.com/VILHALVA/CURSO-DE-XML)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO "thiagosilva2004"](https://github.com/thiagosilva2004/android-jogo-da-velha)
- [PROJETO EDITADO PELO VILHALVA](https://github.com/VILHALVA)



