# SnapFrame

**Drop a PNG frame. Your players' cameras snap right in.**

A Foundry VTT module (v12 and v13) that places your players' webcams **behind the transparent areas of the scene's background image**. Each camera appears "inside" the frame drawn in your art. Works with any game system.

*Made by Ecos da Humanidade. Versão em português abaixo.*

## Installation

In Foundry: **Add-on Modules → Install Module**, and paste into the *Manifest URL* field:

```
https://raw.githubusercontent.com/angelomagnoBR/snapframe/main/module.json
```

## How to use

1. Create your art as a PNG, leaving the spots where cameras should appear **transparent**.
2. Set that art as the **scene background** (Configure Scene → Background).
3. With the scene open, as GM, click **Mesa de Câmeras: configurar esta cena** in the token controls, or go to **Settings → Mesa de Câmeras → Abrir editor**.
4. The module finds the transparent areas on its own, including each one's rotation.
5. For each area, choose which user sits there (the GM, a player, or nobody). To adjust by hand: drag to move, use the yellow square to resize, and the yellow dot on top or the degrees field to rotate.
6. Optional: in each area, use the **Imagem** button to choose what shows when that player's camera is off.
7. Check **Mesa ativa nesta cena** and save.

Each scene has its own setup. Scenes without one look normal.

GM shortcut to turn the table on or off in the current scene: **Shift + M**.

> The module's interface is still in Portuguese. English labels are coming in a future update.

## How it works

Cameras are drawn **inside** the Foundry canvas, right below the scene background. The transparent holes let the cameras show through, and everything Foundry draws (tokens, drawings, text, rulers) stays on top as usual. Cameras follow the scene when you zoom or pan.

Tip: set the scene **Darkness** to 0 and turn **Token Vision** off, or the cameras will be darkened too.

## For players

- Hover over **your** portrait to show the camera and microphone buttons.
- When your camera is off, an image shows in its place, in this order:
  1. the image **you** chose for this scene (🖼 button in your portrait controls);
  2. the image the **GM** chose for that spot in the editor;
  3. your linked character's image;
  4. your avatar.

## Settings

| Setting | What it does |
|---|---|
| Esconder o dock de câmeras padrão (Hide the default camera dock) | Hides Foundry's normal camera dock while the table is active; audio keeps working |
| Ocultar a mesa só para mim (Hide the table just for me) | Hides the table only on your computer |

## Support

SnapFrame is free. Premium features and a monthly frame pack are available to supporters on Patreon.

---

# SnapFrame (Português)

**Coloque uma moldura PNG. As câmeras dos jogadores encaixam sozinhas.**

Módulo para Foundry VTT (v12 e v13) que coloca as câmeras dos jogadores **atrás das áreas transparentes da imagem de fundo da cena**. Cada câmera aparece "dentro" da moldura desenhada na arte. Funciona com qualquer sistema.

## Instalação

No Foundry: **Add-on Modules → Install Module** e cole no campo *Manifest URL*:

```
https://raw.githubusercontent.com/angelomagnoBR/snapframe/main/module.json
```

## Como usar

1. Crie a arte em PNG deixando **transparentes** os lugares onde as câmeras devem aparecer.
2. Coloque essa arte como **imagem de fundo da cena** (Configurar Cena → Fundo).
3. Com a cena aberta, como GM, clique no botão **Mesa de Câmeras: configurar esta cena** (controles de token) ou vá em **Configurações → Mesa de Câmeras → Abrir editor**.
4. O módulo detecta as áreas transparentes do fundo sozinho, inclusive a inclinação de cada uma.
5. Em cada área, escolha qual usuário fica ali (pode ser o GM, ou deixar vazio). Para ajustar na mão: arraste para mover, quadrado amarelo para redimensionar, bolinha amarela no topo ou o campo de graus para girar.
6. Opcional: em cada área, use o botão **Imagem** para escolher o que aparece quando a câmera daquele jogador estiver desligada.
7. Marque **Mesa ativa nesta cena** e salve.

Cada cena tem a sua própria mesa. Em cenas sem mesa, tudo fica normal.

Atalho do GM para ligar/desligar a mesa da cena atual: **Shift + M**.

## Como funciona

As câmeras são desenhadas **dentro** do canvas do Foundry, logo abaixo da imagem de fundo da cena. Os buracos transparentes deixam as câmeras aparecerem e tudo o que o Foundry desenha (tokens, desenhos, textos, réguas) continua por cima, normalmente. As câmeras acompanham a cena se você der zoom ou arrastar.

Dica: deixe a **Escuridão** da cena em 0 e a **Visão de Token** desligada, senão as câmeras também ficam escuras.

## Para os jogadores

- Passe o mouse sobre a **sua** foto para aparecerem os botões de câmera e microfone.
- Com a câmera desligada, aparece uma imagem no lugar. A ordem é:
  1. a imagem que **você** escolheu para esta cena (botão 🖼 nos controles da sua foto);
  2. a imagem que o **GM** escolheu para a foto no editor;
  3. a imagem do seu personagem vinculado;
  4. o seu avatar.

## Configurações

| Configuração | O que faz |
|---|---|
| Esconder o dock de câmeras padrão | Some com o dock normal enquanto a mesa está ativa; o áudio continua |
| Ocultar a mesa só para mim | Esconde a mesa só no seu computador |
