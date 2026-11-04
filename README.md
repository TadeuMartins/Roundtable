# TRANSFORM 2026 - Roundtable

Pagina de mediacao das quatro mesas-redondas, com temas, perguntas resumidas,
participantes, dois cronometros de 10 minutos por mesa e QR Code da plateia.

## Site

https://tadeumartins.github.io/Roundtable/

## Apresentacao

- Tema e dados dos participantes ficam alinhados a esquerda, com a parte principal do titulo em negrito. O rodape exibe a data e uma animacao compacta de cada tema, com pausa e suporte a movimento reduzido; "Beyond the Stage" aparece apenas no cabecalho.
- O botao de avancar inicia o bloco 1, depois o bloco 2 e depois abre o proximo evento do programa. Cada evento avanca com um clique; a mesa seguinte abre com os cronometros parados.
- Page Down e a seta direita executam o mesmo comando, inclusive com o menu de mesas aberto. O menu fecha ao avancar.
- A seta esquerda, Page Up e o botao de voltar percorrem a sequencia no sentido inverso, incluindo as rodadas e os eventos. Voltar preserva o tempo restante e deixa os cronometros pausados; no inicio, nao volta ao fim.
- Apenas o nome da roda atual aparece acima do titulo. O seletor compacto permite escolher outra mesa diretamente.
- Ao avancar, o cronometro anterior fica pausado; a proxima mesa abre sem iniciar a contagem.
- Entrar em uma mesa pelo menu ou pelo avanco prepara a primeira rodada, mesmo se a mesa ja foi usada. Tempos restantes sao preservados; uma rodada esgotada volta a 10 minutos quando iniciada pelo avanco.
- Depois da ultima mesa, aparece o evento final. O proximo comando encerra o programa, sem voltar ao inicio.
- Os controles individuais permitem pausar e reiniciar cada cronometro.
- Iniciar uma rodada pelo controle individual sincroniza o avanco com essa rodada e pausa a outra.
- Tempos e progresso ficam salvos apenas no navegador usado para a mediacao.
- O QR Code abre o formulario original de perguntas do evento. O formulario requer internet.

## Programa E Cores

Ordem e fundos seguem `Vinhetas Palco Paralelo.pptx`:

1. Mesa Tecnica 1 (verde #00D7A0).
2. TECH SESSION - TWRT (claro #F3F3F0).
3. TECH SESSION - Do SAP Clean ao SAP Inteligente (azul #000028).
4. Mesa Tecnica 2 (claro).
5. TECH SESSION - O novo paradigma: IA que constroi IA (azul).
6. Mesa Executiva 1 (claro).
7. EXEC SESSION - TWRT (claro).
8. EXEC SESSION - Do Discovery a Producao com IA (azul).
9. Mesa Executiva 2 (verde).
10. EXEC SESSION - Menos prazo. Menos custo. Mais valor. (azul).

As seis imagens em `Events` sao exportacoes integrais dos slides 2, 3, 5, 7, 8 e 10,
em 1920 x 1080. O enquadramento preserva o slide inteiro, sem cortes ou distorcao.
O menu permite selecionar tanto mesas quanto eventos. Recarregar preserva a tela atual.

## Arquivos E Publicacao

Site estatico, sem build e sem dependencias remotas de interface.
O GitHub Pages publica a raiz da branch `main`; `.nojekyll` desativa o processamento Jekyll.
Alteracoes enviadas a `main` sao publicadas automaticamente pelo GitHub Pages.

Para uso local e sem internet, abrir `index.html` mantendo os arquivos e as pastas `Lean`, `People` e `Events` juntos.
Nao e necessario servidor, instalacao ou acesso ao GitHub Pages. Apenas o formulario externo do QR Code depende de internet.
Nao estao incluidos roteiros internos, audios ou apresentacoes PowerPoint.
