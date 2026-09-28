# Multiverso da Tecnologia

Jogo interativo do estande de Inteligência Artificial da **Unimar Aberta**.

O visitante é recebido pelo Mestre dos Portais, abre quatro portais desenhando um círculo, enfrenta um desafio diferente em cada mundo, conquista artefatos, funde-os num cristal, descobre seu perfil tecnológico e conhece o curso de Inteligência Artificial da Unimar.

| Portal | Desafio | O que a IA faz |
|---|---|---|
| Agro | Pilotar um drone e escanear pragas escondidas | Visão computacional |
| Saúde | Tocar no ritmo dos batimentos | Monitoramento em tempo real |
| Empreendedorismo | Arrastar mensagens de clientes para o setor certo | Treinamento por exemplos (classificação) |
| Tecnologia | Memorizar e repetir a sequência do firewall | Reconhecimento de padrões em segurança |

A narração do Mestre dos Portais usa áudios gerados com voz neural (Kokoro, voz pt-BR "pm_alex", com tratamento de voz de mago), embutidos no próprio arquivo.

## Como usar no estande

1. Abra `index.html` no Google Chrome (funciona sem internet) ou acesse o endereço do GitHub Pages.
2. Clique em **Tela cheia** na barra inferior.
3. Use fone ou caixa de som: o jogo tem trilha, efeitos e narração.

Controles: mouse ou toque; no teclado, números/letras escolhem, **Enter** avança, **Esc** recomeça. Sem interação por 60 s, o jogo volta ao início.

## Vídeos

Os vídeos do mundo real ficam na pasta `videos/` (um `.mp4` e um `.webm` por portal, com o mesmo nome). Mantenha a pasta junto do `index.html`: assim o vídeo toca direto no jogo, inclusive sem internet.

Fontes dos vídeos (uso educativo no evento):

| Portal | Vídeo | Fonte |
|---|---|---|
| Agro | Arbus 4000 JAV, pulverização autônoma | Jacto |
| Saúde | IA detecta e perfila câncer de mama (A.C. Camargo) | Veja Saúde |
| Empreendedorismo | Amazon Go, a loja sem caixa | Amazon |
| Tecnologia | IA em gastronomia, edição, jornalismo e medicina (trecho editado) | TecMundo |

## Como editar

Os textos, portais, artefatos, perfis, cursos e o link do QR Code estão no começo do script, na seção `CONTEÚDO DO JOGO`.

Tecnologias: HTML, CSS e JavaScript puros, sem dependências externas (a geração do QR Code usa a biblioteca `qrcode-generator`, MIT, embutida no arquivo).
