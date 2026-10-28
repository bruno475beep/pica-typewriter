# Pica Typewriter

Uma máquina de escrever no navegador: fonte de datilografia, fita gasta, som de teclas, carro que anda, páginas A4/Carta e exportação para .txt, .md, imagem e PDF.

**Use agora:** https://bruno475beep.github.io/pica-typewriter/

Fitas *Worn ribbon*, *Very worn ribbon* e *Clean*, e duas opções que se combinam com qualquer fita: *Aged paper* (pequenas marcas de desgaste espalhadas pela folha) e *Coffee* (uma única marca de xícara, *Single spot*, ou marcas aleatórias, *Random rings*; o botão ↻ sorteia outras).

Cabeçalho e rodapé: botão *Header & footer*, até duas linhas centralizadas em cada um, repetidas em todas as folhas; `{page}` e `{pages}` viram a numeração.

**Notas de rodapé**: digite `^[` (o colchete fecha sozinho), use Ctrl+Alt+N ou o botão *Footnote* e escreva a nota; a seta → volta ao texto. A nota é datilografada no pé da mesma folha, sob um traço; no Word vira nota de rodapé de verdade, no Markdown fica `^[nota]` e no texto simples vai para o fim.

**Documents ▾**: os 5 documentos mais recentes ficam guardados neste navegador, com tudo (formatação, notas, cabeçalho e rodapé, papel e tinta); ☆ fixa um documento para ele nunca sair. *New document* guarda o atual na lista. Para uma cópia sua, que sobrevive a limpar o navegador e vai para outro computador, use *Save ▾ Pica document (.pica)* e abra-o depois com *Open…*.

**Save ▾**: um só botão para salvar em PDF, Word (.docx), Markdown ou texto; antes de salvar, uma caixa pede o nome do arquivo. **New document** começa uma folha em branco (o Undo traz o texto de volta) e **Ctrl+Enter** abre uma folha nova.

**Word, formatted (.docx)**: padrão de documentos jurídicos — Georgia 11, justificado, entrelinhas 1,2, A4 com margens de 2,5/3 cm, número de página a partir da 2ª. Números digitados no começo da linha (`1.`, `1.1`, `1.1.1`, `1.1.1.1`, `(a)`, `(1)`, `(i)`, `(A)`) viram numeração automática do Word; títulos de 1º nível saem em negrito e caixa alta; citações em parágrafo próprio, recuadas e em itálico; `[•]` e `[comentários]` em amarelo; termos definidos, como (“Fundo”), em negrito.

**Word, unformatted (.docx)**: um documento do Word para continuar trabalhando — texto, negrito, itálico, sublinhado, quebras de página, cabeçalho e rodapé (com numeração automática), papel e margens, na fonte Special Elite embutida no arquivo (ou Courier Prime, no modo *Clean*). Sai sem desgaste de fita, papel envelhecido ou café.

Tudo roda num único arquivo `index.html`, sem servidor e sem instalação — pode baixá-lo e abrir offline. O texto fica guardado só no seu navegador.

Atalhos: Ctrl+B negrito · Ctrl+I itálico · Ctrl+U sublinhado · Ctrl+Alt+N nota de rodapé · Ctrl+Enter nova folha · Ctrl+Z desfazer.

Versões anteriores: [v1](https://bruno475beep.github.io/pica-typewriter/v1/) (a primeira), [v2](https://bruno475beep.github.io/pica-typewriter/v2/) (com os efeitos, sem cabeçalho e rodapé) e [v3](https://bruno475beep.github.io/pica-typewriter/v3/) (com papel envelhecido mais forte).
