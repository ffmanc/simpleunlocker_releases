# SimpleUnlocker

Free Windows utility for managing the Lineage II client instance mutex limit.
Supports the recognized Live, Essence and Classic mutex patterns.

Download only from the [official releases](https://github.com/ffmanc/simpleunlocker_releases/releases).
Windows 10/11 x64, .NET Framework 4.8 and administrator permission are required.
Extract the ZIP to a dedicated local folder and launch `SimpleUnlocker.exe`.
The **EN / PT** switch changes the language immediately and saves your preference.

## Updates

Builds with the updater check for newer releases in the background and validate
RSA-signed metadata, the executable SHA-256, size and identity before installation.
Automatic updates are enabled by default. A downloaded update installs on the
next launch, or through **Update now**. Disable **Automatic updates** to control
installation manually; **Check for updates** remains available. If a new version
fails its startup check, the previous executable is restored.

Older builds without the updater require one manual installation first. The
application version changes only with an explicitly versioned release.
The current executable has no Authenticode code-signing certificate; Windows may
show an unknown-publisher warning. Signed update metadata does not replace Windows
code signing. Verify `SHA256SUMS.txt` against a downloaded asset if needed.

Update requests contact GitHub to retrieve public metadata and release assets.
The app sends no game account data, language settings or handle logs. Ordinary
HTTP connection information, including the client IP and app user-agent, reaches
the service. No GitHub credentials are required by the application.

This repository contains distribution documentation and signed update metadata.
Application source and private signing material are maintained separately. GitHub's
automatic source archives contain this repository's documentation, not the app source.

## Português

Utilitário gratuito para Windows que gerencia o limite de instâncias dos clientes
Lineage II, com os padrões reconhecidos de Live, Essence e Classic.

Baixe somente nas [releases oficiais](https://github.com/ffmanc/simpleunlocker_releases/releases).
Requer Windows 10/11 x64, .NET Framework 4.8 e execução como administrador.
Extraia o ZIP em uma pasta local exclusiva e abra `SimpleUnlocker.exe`.
Altere o idioma usando **EN / PT**; a preferência é salva automaticamente.

As atualizações são verificadas em segundo plano. O aplicativo valida a assinatura
dos metadados, o SHA-256, o tamanho e a identidade do executável. Uma versão nova
baixada será instalada na próxima abertura, ou pelo link **Atualizar agora**.
Desmarque **Atualizações automáticas** para controlar a instalação manualmente;
**Verificar atualizações** continua disponível. Se a nova versão falhar ao iniciar,
o executável anterior será restaurado.

Versões antigas sem o atualizador precisam de uma substituição manual inicial.
O executável ainda não possui certificado Authenticode; o Windows pode mostrar
um aviso de editor desconhecido. A assinatura dos metadados protege o canal de
atualização e não substitui a assinatura de código do Windows.

O aplicativo consulta o GitHub para obter metadados e arquivos públicos. Não envia
dados da conta do jogo, preferências de idioma ou logs de handles. As informações
normais da conexão HTTP, incluindo IP e identificação do aplicativo, chegam ao
serviço. O aplicativo não precisa de credenciais do GitHub.

Developed by / Desenvolvido por [Fabricio Mancuzo](mailto:fabricio.mancuzo@gmail.com).
The app's PayPal and Pix donations support continued development.
