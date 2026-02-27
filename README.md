# shakers-semana-3-dados-avancados

Este projeto faz parte do Desafio da Semana 3, com foco em Metafields e Metaobjetos que culminava em uma section com Slider Dinâmico.

---

## O que foi implementado
Metafields: Permite armazenar dados personalizados no Shopify, estendendo informações de produtos, coleções, pedidos, etc. (Utilizado no desafio para armazenar uma lista de metaobjetos)
Metaobjetos: São estruturas de dados reutilizáveis, ideiais para representar entidades personalizadas. (Utilizadas no projeto para relacionar um produto e uma imagem)

- Criação e estruturação de Metafields
- Criação e manipulação de Metaobjetos
- Consumo de Metafields e Metaobjetos via Liquid
- Construção de uma section dinâmica com slider.

Para criar um metafield e um metaobjeto é necessário ir em Configurações na sua loja Shopify e cadastrar no campo de "Metacampo e Metaobjetos" e foi preciso relacionar dentro das confugurações de um produto já existente o metafield com duas entradas de um metaobjeto.

---
## Teste

- Para rodar o projeto localmente, é necessário utilizar a Shopify CLI.

---
## Pull Request
- [Ver Pull Request](https://github.com/SamanthaChuta/shakers-semana-3-dados-avancados/pull/1)

- [Vídeo](https://drive.google.com/drive/folders/1A8_ntRlIzkR018XyDTCP13gUZcpzxY7m?usp=drive_link)


---

## Estrutura do projeto

```bash
shakers-semana-3-dados-avancados/
-section/metaobject-slider.liquid
-assets/metaobject-slider.css
-assets/metaobject-slider.js
