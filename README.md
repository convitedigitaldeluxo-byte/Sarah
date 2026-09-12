# Convite — Sarah 15 anos

Site do convite animado, com os dois ícones do vídeo clicáveis.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | A página |
| `convite-sarah.mp4` | O vídeo convertido para H.264 (toca em qualquer navegador) |
| `poster.jpg` | Primeira imagem, exibida enquanto o vídeo carrega |
| `preview.jpg` | Miniatura que aparece ao compartilhar o link no WhatsApp |

Os quatro precisam ficar na **mesma pasta**, na raiz do repositório.

## Publicar no GitHub Pages

1. Crie um repositório e envie os quatro arquivos.
2. No repositório: **Settings → Pages**.
3. Em *Source*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
4. Em um ou dois minutos o link fica no ar: `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## O que os ícones fazem

- **Confirmar presença** → abre o WhatsApp para `+55 85 98793-4758` com a mensagem já escrita: *Confirmo minha presença no aniversário da Sarah.*
- **Localização** → abre o Google Maps em Rua Dr. João de Deus, 627 — Bairro de Fátima, Fortaleza/CE.

Os mesmos dois atalhos aparecem como botões abaixo do vídeo, para quem não perceber que os ícones são clicáveis.

## Como alterar

Abra o `index.html` e procure:

- **Telefone e mensagem:** os links `https://wa.me/5585987934758?text=...` (aparecem duas vezes). O número vai sem sinais: código do país + DDD + número.
- **Endereço:** os links do Google Maps (duas vezes) e o texto no fim da página.
- **Posição dos ícones clicáveis:** as regras `.toque--presenca` e `.toque--local` no CSS, em porcentagem do vídeo. Só mexa nisso se trocar o vídeo.
