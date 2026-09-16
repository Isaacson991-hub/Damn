# 🎵 Meu Player Offline

Um player de música **100% offline** que roda no navegador.

## Como usar

1. Abra o arquivo `index.html` no navegador (Chrome, Edge, Firefox ou Safari).
2. Clique em **Adicionar músicas** ou arraste arquivos de áudio para a área indicada.
3. As músicas ficam salvas no seu navegador (IndexedDB) e você pode ouvir mesmo sem internet.
4. Para usar como app no celular/computador: no Chrome, clique em "Instalar app" ou "Adicionar à tela inicial".

## Recursos

- ✅ Upload de múltiplos arquivos (MP3, WAV, OGG, M4A, FLAC...)
- ✅ Arrastar e soltar
- ✅ Playlist persistente (fica salva mesmo depois de fechar o navegador)
- ✅ Play / Pause / Próxima / Anterior
- ✅ Modo aleatório e repetir
- ✅ Barra de progresso e controle de volume
- ✅ Funciona offline (PWA)
- ✅ Interface em português
- ✅ Responsivo (celular e desktop)

## Importante

- As músicas ficam **apenas no seu dispositivo**. Nada é enviado para a internet.
- Se limpar os dados do navegador, a biblioteca será apagada.
- Funciona melhor no Chrome e Edge.

## Arquivos

- `index.html` — o player completo
- `manifest.json` — configuração do app instalável
- `sw.js` — service worker para cache offline