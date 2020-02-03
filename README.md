### <p align="center"><img width="150px" height="150px" src="icon.png"></p>

# [PWA](#)

## INSTALAÇÃO

1. Clone este repositório

  ```bash
  git clone https://github.com/KevinStoneTech/pwa
  ```


## HTML

1. A maneira de começar a usar o PWA é adicionando a uma tag de script

  ```html
  <link rel="manifest" href="./manifest.json" />
  <script src="./pwa.dev.min.js"></script>
  <script> if (navigator.serviceWorker) { navigator.serviceWorker.register ('./sw.js') } </script>
  ```