# Cronômetro para o OBS

Adiciona um cronômetro para contagem regressiva no OBS.

## Configuração

No OBS adiciona uma fonte `Navegador` na cena desejada, abrindo o arquivo `timer/timer.html` deste projeto.

Por padrão, a contagem será feita em relação ao próximo quarto de hora (15, 30, 45 minutos ou hora completa). Caso deseje informar alguma hora específica, o mesmo pode ser feito adicionado `?t=hh:mm` no final do caminho do arquivo, onde `hh:mm` deve ser substituido pela hora desejada. Exemplo: `timer/timer.html?t=17:00`.

## Personalização

A mensagem exibida ao finalizar a contagem pode ser personalizada no arquivo `timer/timer.html` dentro da tag `<div>` com a classe `msg`.

A fonte do cronômetro e da mensagem ao finalizâ-lo podem ser personalizadas no arquivo `timer/timer.css`.
