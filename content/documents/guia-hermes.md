---
title: "Guia per crear pàgines amb Hermes"
description: "Regles editorials bàsiques perquè Hermes pugui preparar contingut per al web."
date: 2026-08-05
tags: ["hermes", "edicio"]
categories: ["Documents"]
authors: ["Benet Corner"]
featureimage: "/assets/benet-corner-3.jpg"
---

Hermes pot ajudar a preparar esborranys de pàgines, però no ha de publicar contingut sensible sense revisió humana.

## Format recomanat

Cada pàgina nova ha de tenir front matter:

```yaml
---
title: "Titol curt"
description: "Resum d'una frase"
date: 2026-08-05
tags: ["tema"]
categories: ["Documents"]
draft: true
---
```

## Regles

- Escriure en català clar i directe.
- Separar fets comprovats, propostes i preguntes obertes.
- Afegir data quan una dada pugui canviar.
- No incloure claus, contrasenyes, correus privats ni dades personals.
- Usar `draft: true` quan el text encara necessita revisió.
