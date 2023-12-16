---
título: 'Visão geral dos exemplos'
description: 'Um conjunto de exemplos para características comuns do Electron'
lesma: exemplos
ocultar_título: falso
---

# Visão geral dos exemplos

Nesta seção, coletamos um conjunto de guias para recursos comuns
que você pode querer implementar em seu aplicativo Electron. Cada guia
contém um exemplo prático em um aplicativo de exemplo mínimo e independente.
A maneira mais fácil de executar esses exemplos é baixando [Electron Fiddle][fiddle].

Depois que o Fiddle estiver instalado, você pode pressionar o botão "Abrir no Fiddle" que você
encontrará abaixo exemplos de código como o seguinte:

```fiddle docs/fiddles/quick-start

```

Se ainda houver algo que você não sabe fazer, dê uma olhada na [API][app]
pois há uma chance de que esteja documentado ali (e também abra um problema solicitando o
guia!).

<!-- guia-início da tabela -->

| Guia | Descrição |
| :-------------------- | -------------------------------------------------- -------------------------------------------------- --------------- |
| [Portas de mensagem][] | Este guia fornece alguns exemplos de como você pode usar MessagePorts em seu aplicativo para comunicar diferentes processos. |
| [Acesso ao dispositivo][] | Aprenda como acessar o hardware do dispositivo (Bluetooth, USB, Serial). |
| [Atalhos de teclado][] | Configure atalhos de teclado locais e globais para seu aplicativo Electron. |
| [Multithreading][] | Com Web Workers, é possível executar JavaScript em threads no nível do sistema operacional |
| [Renderização fora da tela][] | A renderização fora da tela permite obter o conteúdo de um BrowserWindow em um bitmap, para que possa ser renderizado em qualquer lugar. |
| [Verificador ortográfico][] | Aprenda como usar o corretor ortográfico integrado, definir idiomas, etc. |
| [Incorporações na Web][] | Descubra as diferentes maneiras de incorporar conteúdo da web de terceiros em seu aplicativo. |

<!-- guide-table-end -->

## Como...?

Você pode encontrar a lista completa de "Como fazer?" na barra lateral. Se houver
algo que você gostaria de fazer e que não está documentado, por favor junte-se
nosso [servidor Discord][discord] e conte-nos!

[aplicativo]: ../api/app.md
[discordância]: https://discord.gg/electronjs
[violino]: https://www.electronjs.org/fiddle
[Portas de mensagem]: ./message-ports.md
[Acesso ao dispositivo]: ./devices.md
[Atalhos de teclado]: ./keyboard-shortcuts.md
[Multithreading]: ./multithreading.md
[Renderização fora da tela]: ./offscreen-rendering.md
[Verificador ortográfico]: ./spellchecker.md
[Incorporações na Web]: ./web-embeds.md
