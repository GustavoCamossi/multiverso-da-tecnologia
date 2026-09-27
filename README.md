# Multiverso da Tecnologia

Jogo interativo do estande de Inteligência Artificial da **Unimar Aberta**.

O visitante é recebido pelo Mestre dos Portais, abre quatro portais desenhando um círculo, enfrenta um desafio diferente em cada mundo, conquista artefatos, funde-os num cristal, descobre seu perfil tecnológico e conhece o curso de Inteligência Artificial da Unimar.

| Portal | Desafio | O que a IA faz |
|---|---|---|
| Agro | Pilotar um drone e escanear pragas escondidas | Visão computacional |
| Saúde | Tocar no ritmo dos batimentos | Monitoramento em tempo real |
| Empreendedorismo | Arrastar mensagens de clientes para o setor certo | Treinamento por exemplos (classificação) |
| Tecnologia | Memorizar e repetir a sequência do firewall | Reconhecimento de padrões em segurança |

A narração usa áudios gerados com voz neural (Piper, voz pt_BR "faber"), embutidos no próprio arquivo.

## Como usar no estande

1. Abra `index.html` no Google Chrome (funciona sem internet) ou acesse o endereço do GitHub Pages.
2. Clique em **Tela cheia** na barra inferior.
3. Use fone ou caixa de som: o jogo tem trilha, efeitos e narração.

Controles: mouse ou toque; no teclado, números/letras escolhem, **Enter** avança, **Esc** recomeça. Sem interação por 60 s, o jogo volta ao início.

## Como editar

Os textos, portais, artefatos, perfis, cursos e o link do QR Code estão no começo do script, na seção `CONTEÚDO DO JOGO`.

Tecnologias: HTML, CSS e JavaScript puros, sem dependências externas (a geração do QR Code usa a biblioteca `qrcode-generator`, MIT, embutida no arquivo).
