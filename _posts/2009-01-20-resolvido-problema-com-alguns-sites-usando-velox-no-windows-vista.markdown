--- 
layout: post
status: publish
published: true
title: "[Resolvido] Problema com alguns sites usando Velox no Windows Vista"
author: Rafael Lima
author_login: admin
author_email: contato@rafael.adm.br
author_url: http://rafael.lima.myopenid.com/
wordpress_id: 272
wordpress_url: http://rafael.adm.br/?p=272
date: 2009-01-20 11:00:09 -02:00
categories: 
- Posts
tags: 
- windows
- dicas
- velox
- vista
---
Estava com um problema s&eacute;rio para colocar o Velox pra funcionar direito via conex&atilde;o direta no Windows Vista Business na BielSystems. Depois de ler um bocado solucionei rodando a seguinte linha no command prompt como administrador:

<span style="color: #ff0000;">netsh interface ipv4 set subinterface "Velox" mtu=1300 store=persistent</span>

&Eacute; isso!
