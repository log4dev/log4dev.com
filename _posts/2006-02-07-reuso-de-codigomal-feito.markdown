---
theme:
  name: twitter
author: mgalves
comments: true
date: 2006-02-07 12:37:57
layout: post
slug: reuso-de-codigomal-feito
title: Reuso de código….mal feito
wordpress_id: 46
categories:
- Desenvolvimento
- Engenharia de Software
---

O vôo transcorria normalmente...o helicóptero de guerra parecia ser muito eficiente nas manobras....o piloto estava apreciando as paisagens australianas. De repente ao longe, o piloto observa uma manada de kangurus (é manada mesmo?). Resolve fazer um rasante para poder admirar de perto esses animais exóticos. Como esperado, os kangurus se assutam com o helicóptero, e correm (ou pulam) para detrás de um morro.Até aí, tudo normal.

De repente, um grupo de kangurus fortemente armados surge das montanhas e atiram um míssil contra o helicóptero, que explode !!!!!!!!!!!!!!!!!!!!!!!!

Ficção científica ? Não...erro de programação. Este episódio aconteceu durante uma apresentação de um simulador de vôo australiano para pilotos americanos. O erro: ao desenvolver o simulador, o programador utilizou a mesma biblioteca de geração de soldados virtuais para gerar os kangurus, mudando apenas o skin ! O único problema foi que o programador esqueceu de desabilitar a opção de artilharia e os reflexos de soldado.

A descrição deste fato pode ser lida [aqui](http://everything2.com/index.pl?node_id=783722)
