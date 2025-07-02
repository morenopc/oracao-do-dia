# Oração do Dia

Este projeto exibe automaticamente uma imagem diária de oração, baseada na data atual, em uma página web simples.

## Como funciona

- O arquivo `index.html` calcula o dia e mês atuais.
- Ele monta o nome da imagem no formato `DIA-DIASNOMES.png`, por exemplo, `2-30.png`.
- A imagem é carregada do diretório remoto:  
  `https://temploiniciatico.wordpress.com/wp-content/uploads/2025/06/`
- A imagem correspondente ao dia é exibida na página.

## Como usar

1. Abra o arquivo `index.html` em seu navegador.
2. A imagem do dia será exibida automaticamente.

## Personalização

- Para alterar o diretório das imagens, edite a variável `urlBase` no script do `index.html`.
- As imagens devem estar nomeadas conforme o padrão: `DIAMES.png`, por exemplo, `230.png` para o dia 2 do mês 30.
