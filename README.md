CorujaLab [![Build Status](https://travis-ci.org/CorujaLab/corujalab.github.io.svg?branch=master)](https://travis-ci.org/CorujaLab/corujalab.github.io)
=========

Site da CorujaLab, baseado no [Freelancer bootstrap theme ](http://startbootstrap.com/templates/freelancer/)

## Como alterar um item do Portfolio
 - Coloque a imagem em `/img/portoflio/`
 - Crie um post para cada um dos projetos. Você pode usar o exemplo abaixo como
   base:

```txt
---
layout: default
modal-id: 1
date: 2015-07-13
img: safe.png
alt: image-alt
title: Antecipador
project-date: Julho de 2015
category: Desenvolvimento
description: O Antecipador ajuda no gerenciamento de micro e pequenas empresas, identificando antecipadamente as necessidades de seus clientes e disponibilizando informações precisas sobre o seu potencial de mercado.

---
```

## Como trocar o endereço de email do formulário de contato
- Altere o email no arquivo `_includes/contact_static.html`. Para mais detalhes,
acesse o site do [formspree](http://formspree.io/).
