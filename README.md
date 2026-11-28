# WDA MultiPlay

**Atualização 1.6.55:** corrigida a declaração auxiliar de áudio e adaptada a consulta inicial de microfone do YouTube à WebView. Menu glass e animações preservados. [Notas e limites](docs/releases/1.6.55.md).

Canal oficial de downloads e atualizações do WDA MultiPlay para Android.

## Download

**[Baixar a versão mais recente](https://github.com/navygod/WDA-MultiPlay-Releases/releases/latest)**

Na página da versão, abra **Assets** e baixe o arquivo `WDA-MultiPlay-VERSAO.apk`. O arquivo `SHA256SUMS-VERSAO.txt` permite conferir a integridade do download.

Para instalar no Android, escolha o arquivo terminado em **.apk**. Os itens **Source code (zip)** e **Source code (tar.gz)** são arquivos gerados automaticamente pelo GitHub com o conteúdo deste repositório de distribuição, que contém o README.

Compatibilidade: **Android 8.0 ou superior, 64 bits (arm64-v8a ou x86_64)**.

## Atualizações

A partir da versão 1.6.17, abra **☰ → Configurações → Verificar atualizações**. Na **1.6.51**, a opção **Verificar ao abrir o app** consulta o GitHub a cada abertura ou retorno ao aplicativo, com intervalo mínimo de 60 segundos, e pode ser desativada. Ao reabrir antes disso, a busca aguarda o tempo restante com o app aberto. Uma versão nova mostra o selo **1** no menu e em Atualizações nas Configurações. O menu oferece **Atualizações · 1** como acesso direto. O selo permanece até instalar a versão ou uma consulta confirmar que não há novidade.

A partir da **1.6.19**, **Baixar atualização** mostra o progresso dentro do WDA. Depois, **Instalar atualização** abre a confirmação do Android. Na primeira vez, autorize **Permitir desta fonte** para o WDA quando solicitado. O app verifica o arquivo e recupera o download ao reabrir.

Na **1.6.34**, a opção é **Baixar atualizações automaticamente**: o WDA baixa e verifica o APK e mostra um aviso no **Início** sobre a nova versão, o andamento e o arquivo pronto. A instalação só começa ao tocar em **Instalar atualização**, com confirmação no Android. Não há instalação automática, mesmo com a opção ligada. A autorização **Permitir desta fonte** é solicitada somente no fluxo manual. A preferência anterior é preservada e o download pode usar dados móveis. Para obter a 1.6.34 a partir de uma edição anterior, use o fluxo manual atual uma vez. Não existe busca periódica com o app fechado.

Se você usa a **1.6.18 ou anterior**, instale manualmente o APK da 1.6.19 uma vez para obter o download integrado. As versões Release usam o mesmo pacote e certificado de produção para permitir a atualização da instalação existente, sem desinstalar o WDA.

## Integridade e privacidade

Cada release acompanha seu SHA-256. O certificado de assinatura de produção tem SHA-256:

`8f72599476eab9af30ec5ab630ae35759f8614e98899f1321efa8a80f8b3f7a8`

A consulta de atualização não envia conta Google, cookies, histórico ou arquivos ao GitHub. O serviço recebe os dados normais de uma conexão HTTP, incluindo endereço IP. Mais detalhes estão em **Sobre e privacidade**, dentro do aplicativo.

As verificações locais de integridade e assinatura não constituem aprovação pelo Play Protect.

## Sobre este repositório

Este repositório público distribui APKs, notas e checksums. O código-fonte do aplicativo é mantido em um repositório privado. Chaves de assinatura, senhas e arquivos locais não são distribuídos.

As licenças e os links dos componentes de terceiros estão disponíveis no aplicativo em **☰ → Baixar vídeo ou MP3 → Licenças dos componentes**. Entre eles estão [yt-dlp](https://github.com/yt-dlp/yt-dlp), [Chaquopy](https://github.com/chaquo/chaquopy), [Python](https://github.com/python/cpython), [certifi](https://github.com/certifi/python-certifi) e [LAME/lamejs](https://github.com/zhuker/lamejs).

Contato: [@web.devanalytics](https://www.instagram.com/web.devanalytics/).

Na **1.6.49**, a barra mostra apenas **Tema → ☰ → Somente áudio → ⌃**. Toque na **logo ou no nome WDA** para voltar ao Início. YouTube, Biblioteca, downloads, janela flutuante e chat ficam no menu. Modo teatro foi removido; a tela cheia do vídeo continua disponível.

Na **1.6.50**, Somente áudio preserva o volume efetivo do vídeo, incluindo atenuação e mudo. O nível é conferido novamente ao concluir a troca e permanece ao pausar, retomar e avançar na mesma sessão. Os botões físicos continuam controlando o volume de mídia do Android.

Na **1.6.52**, sair da tela cheia volta à vertical com os controles visíveis. As seleções do Mix ficam em duas colunas quando há espaço. Somente áudio ganha aleatório e repetição da música atual ou de toda a fila; o temporizador tem prioridade. Durante uma live, **Chat** aparece na barra superior para abrir ou fechar a conversa sem entrar no menu.

Na **1.6.53**, toque no microfone do YouTube e autorize o uso no WDA e no Android para pesquisar por voz. Se a permissão tiver sido bloqueada, permita em **Informações do app → Permissões → Microfone** no Android. O acesso fica restrito à origem oficial do YouTube aberta; a autorização de câmera do Google continua separada. A pesquisa depende do YouTube, da conexão e da WebView instalada. Nas lives, logo e controles ficam na mesma linha em telas de telefone; o nome WDA e o rótulo Somente áudio cedem espaço quando necessário, mantendo a logo e os botões acessíveis.

Na **1.6.54**, a autorização de microfone já concedida no Android é reutilizada sem repetir o aviso do WDA. A consulta ao serviço de reconhecimento de fala foi declarada para Android 11 ou superior. Após atualizar, feche a tela de voz que estava aguardando permissão e toque novamente no microfone. Nenhuma permissão nova foi adicionada; o serviço de reconhecimento compatível precisa estar instalado e habilitado no aparelho.

Na mesma **1.6.54**, o menu recebe acabamento de vidro nos temas claro e escuro, opções visualmente separadas e animações curtas. A lista mantém a ordem e as funções, abre sempre à esquerda e começa abaixo do botão ☰, inclusive com os controles recolhidos. O desfoque nativo depende do Android e do suporte ativo do aparelho; sem blur, o fundo fica mais opaco para preservar a leitura.

Biblioteca, players, chat e diálogos também recebem transições suaves, e os botões compartilhados ganham efeito de onda ao toque. A organização atual das telas e dos menus é preservada; as atualizações periódicas do player não repetem as animações.
