# TRANSFORM 2026 - Roundtable

Pagina de mediacao das quatro mesas-redondas, com temas, perguntas resumidas,
dois cronometros de 10 minutos por mesa, animacoes e QR Code da plateia.

## Site

https://tadeumartins.github.io/Roundtable/

## Apresentacao

- O botao de avancar inicia o bloco 1, depois o bloco 2 e depois abre a proxima mesa.
- Page Down e a seta direita executam o mesmo comando, inclusive com o menu de mesas aberto. O menu fecha ao avancar.
- Apenas o nome da roda atual aparece acima do titulo. O seletor compacto permite escolher outra mesa diretamente.
- Ao avancar, o cronometro anterior fica pausado; a proxima mesa abre sem iniciar a contagem.
- Entrar em uma mesa pelo menu ou pelo avanco prepara a primeira rodada, mesmo se a mesa ja foi usada. Tempos restantes sao preservados; uma rodada esgotada volta a 10 minutos quando iniciada pelo avanco.
- Na ultima mesa, o comando encerra a sequencia, sem voltar ao inicio.
- Os controles individuais permitem pausar e reiniciar cada cronometro.
- Iniciar uma rodada pelo controle individual sincroniza o avanco com essa rodada e pausa a outra.
- Tempos e progresso ficam salvos apenas no navegador usado para a mediacao.
- O QR Code abre o formulario original de perguntas do evento. O formulario requer internet.

## Arquivos E Publicacao

Site estatico, sem build e sem dependencias remotas de interface.
O GitHub Pages publica a raiz da branch `main`; `.nojekyll` desativa o processamento Jekyll.
Alteracoes enviadas a `main` sao publicadas automaticamente pelo GitHub Pages.

Para uso local, abrir `index.html` mantendo os arquivos e a pasta `Lean` juntos.
Nao estao incluidos roteiros internos, audios ou apresentacoes PowerPoint.