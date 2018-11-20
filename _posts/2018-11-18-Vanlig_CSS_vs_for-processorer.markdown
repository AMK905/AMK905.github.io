---
layout: post
title:  "CSS vs för-processad CSS"
date:   2018-11-18 10:40:00 -0600
categories: jekyll update
tags: uppgifter
comments: true
profile: true
---
När jag började på uppgiften med för-processad CSS i detta fall jekyll kändes det bara som att man komplicerar html och css för att man kan. Men när jag började förstå vad som var vad i koden och började arbeta med den hittade jag några fördelar. Såklart finns det även nackdelar men jag kan rekommendera er att man kan ha nytta av kunskaper kring för-processad CSS. Enligt flera källor på nätet ska jekyll ha används till Barack Obamas kampanj 2012. Jekyll är bra om man vill skapa en webbplats snabbt och har koll på läget. Man slipper bland annat att göra samma ändring på flera ställen i koden. Med hjälp av referenser och språket Liquid kan man få en ändring slå igenom på flera sidor. Om man har brottom har jekyll också mallar man kan utgå ifrån. 
Det kan dock vara jobbigt att tabba mellan olika dokument hela tiden och man får tänka en extra gång om man vill lägga till något på en sida. Eftersom en sida på webbplatsen är uppbyggd med flera olika html-dockument så är det inte alltid helt självklart vilket dokument man ska revidera. I vissa fall behöver man ändra i flera dokument för att få det som man vill. När jag skulle lägga till min profil på denna webbplatsen råkade jag ut för detta. För att få rätt placering fick jag lägga in koden redan i default.html som är högst upp om vi delar in layouts i en trädstruktur. Jag valde sedan att skapa ett eget html-dokument för profilen i mappen includes och hämta koden till default med Liquid. Problemet med att lägga profilen i default är dock att den hamnar på alla sidor som har default som layout om man inte lägger in någon logik för detta. Jag kan tänka mig att det kan vara bra med för-processad CSS när man är många som reviderar i koden eftesom vanlig html och css kan struktureras på så många olika sätt, då är det bättre att det finns en bestämd uppbyggnad att utgå ifrån. 
