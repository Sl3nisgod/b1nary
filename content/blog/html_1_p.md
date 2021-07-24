---
title: "lezione 1: Cos'è l'HTML"
date: 2021-06-29T10:07:47+06:00
draft: false

# post thumb
image: "img/html_1/1.jpg"

# meta description
description: "Vediamo cos'e l'HTML, la sua  storia, cosa sono tags e attributes e gli editor di testo"

# taxonomies
categories:
  - "HTML"
tags:
  - "HTML"
  - "Tech"

# post type
type: "post"
---
## Cos’e l’HTML?

Per poter cominciare a scrivere in HTML sicuramente vi sarà utile sapere da dove viene.

La maggior parte dei siti è scritta in HTML, esso è usato per creare pagine e farle funzionare.

Il codice che invece usiamo per farle diventare accattivanti si chiama `CSS` ma ci focalizzeremo su di lui più tardi, per ora impegniamoci a costruire una pagina più che farla bella.

## La storia del HTML

L’HTML è stato creato da Tim Berners-Lee, Robert Cailliau e altri nel 1989. L’acronimo HTML vine dalla frase “Hyper Text Markup Language”
* Hyper Text vuol dire che il documento contiene link che permettono al lettore di saltare da una parte all’altra della pagina.
* Markup Language è invece il modo in cui parla il computer e ci serve per controllare come il testo viene processato e presentato, per fare ciò usiamo: tag e attribute

## Cosa sono Tags e Attributes?

Sono la base dell’HTML, essi lavorano insieme ma performano diversi compiti.

-I tags sono usati per indicare l’inizio di un elemento HTML e sono solitamente rinchiusi in delle parentesi angolari `<>`. Ad esempio.
```html
<h1>
```
Loro però per funzionare necessitano sia di un tag di apertura che di uno di chiusura in modo da contenere le informazioni al loro interno. Ad esempio 
```html
<h1> Ciao </h1>
```
Notiamo che per chiudere un tag abbiamo bisogno che contenga il carattere `/`

-Gli attributes sono invece delle informazioni aggiuntive che diamo sono simili ad un tag di apertura ma non ne hanno uno di chiusura. Ad esempio: 
```html
<img src="mydog.jpg" alt="A photo of my dog.">
```
## Cosa sono gli editor?

Gli editor sono dei programmi che ci facilitano il lavoro suggerendoci la fine di un tag o chiudendo in automatico le parentesi, ma fate attenzione che non è assolutamente necessario un editor per programmare HTML, potenzialmente ci potremmo far bastare anche il blocco note di Windows dal momento che ci possiamo scrivere, per poi farlo diventare una pagina HTML ci basterà salvare il progetto con l'estensione `.html`

Esistono però vari editor che ci semplificano il lavoro, i più famosi sono:

* Visual Studio Code (consigliato)
* Sublime Text 3
* Brackets
* Atom

![image](../../img/html_1/2.jpg)

