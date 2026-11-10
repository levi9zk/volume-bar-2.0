# Volume Bar

Painel de volume para Android no estilo do iPhone: uma linha fina na lateral da tela que vira uma barra grande quando você arrasta. Tudo configurável dentro do app.

> Versão atual: **1.2.0** · Testado em um Motorola Moto G41 com Android 11

## O que ele faz

- **Linha fina** que aparece ao apertar os botões de volume, com animação de deslizar pra dentro e pra fora da tela.
- **Barra grande** (estilo iPhone): encoste na linha e arraste pra cima ou pra baixo pra ajustar o volume com o dedo.
- **Segurar o botão** de volume sobe ou desce o volume sozinho.
- **Tocar em qualquer lugar da tela** faz a barra sumir.
- **Esconde em apps escolhidos**: o Instagram já vem marcado. Nesses apps o volume volta a ser controlado pelo Android.
- **Aparência configurável**, com prévia ao vivo:
  - modelo: as duas versões, só a linha ou só a barra grande;
  - lado da tela (esquerda ou direita), tamanho e posição;
  - cor e espessura da linha;
  - cor do fundo, opacidade e cor do preenchimento da barra grande;
  - tempo que a barra fica na tela.
- **Idioma:** Português e English.

## Como instalar

1. Baixe o APK mais recente (veja "Como compilar" abaixo) e instale. O Android vai pedir pra permitir a instalação de fontes desconhecidas.
2. Abra o app **Volume Bar**.
3. Na tela inicial, toque em **Permissões** e ative o serviço **Volume Bar** em Acessibilidade.
4. Recomendado: toque em **Manter a barra funcionando** e tire a restrição de bateria, pra o Android não encerrar o serviço.
5. Aperte os botões de volume. A barra aparece.

Para ajustar o visual, use a aba **Aparência**. O idioma e os créditos ficam na bolinha com o lápis, no topo da tela.

## Permissões e privacidade

| Permissão | Para que serve |
|---|---|
| Serviço de acessibilidade | Capturar os botões de volume, desenhar a barra por cima de outros apps e saber qual app está aberto (pra esconder a barra no Instagram etc.). |
| Ignorar otimização de bateria | Opcional. Evita que o Android feche o serviço. |

O app **não tem permissão de internet** e não coleta nem envia nenhum dado. As configurações ficam salvas só no aparelho.

## Limitações

- O app controla o volume de **mídia** (e o de chamada, durante ligações). O volume do toque e o modo silencioso não passam por ele.
- Enquanto o serviço está ativo, o atalho de print pelos botões (ligar + volume baixo) pode parar de funcionar, porque o app captura os botões de volume.
- A barra some no **app inteiro** escolhido (por exemplo, no Instagram todo), e não só nos stories: o Android não permite saber em qual tela de dentro do app você está.
- Em alguns aparelhos o sistema pode encerrar o serviço em segundo plano. Se acontecer, tire a restrição de bateria.
