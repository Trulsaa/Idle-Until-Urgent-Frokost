# Idle Until Urgent

Repo: https://github.com/Trulsaa/Idle-Until-Urgent-Frokost

## Agenda

Brukerens opplevelse av vår frontend. Hva gjør at et brukergrensesnitt oppleves responsivt? Hvordan kan vi forbedre opplevelsen ved å velge riktig evalueringsstrategi?

* Hvordan påvirkes brukeropplevelsen av evalueringsstrategien?
* Diagnostisering
* 4 forskjellige strategier
* Hvordan og hvorfor bruke Idle Until Urgent?

## Hvem er jeg

* Navn: Truls Aagaard
* Født og oppvokst på Hamar
* Utdannet kokk, nano- ingeniør og industriell økonom
* Jobbet i Sopra Steria siden januar 2017
* Hobbyer: kode, matlaging og speedriding

## Prosjekt

* Kunde: Utenriksdepartementet
* Visjon: Gi alle brukerene på alle utenriksstasjonene et raskt og brukervennlig grensesnitt for å finne tilbake til og lese interne dokumenter
* Teknologier: React, MobX, TypeScript og Jest med venner
* Fokus: Brukeropplevelse

## Hvordan påvirkes brukeropplevelse av evalueringsstrategi?

![](https://paper-attachments.dropbox.com/s_D0987844BDAA7F0BD81C02B2CD9D58E80E4A006E7E533B73B62A8BBF0D95216E_1559545732314_rail-response-details.png)

## Diagnostisering

[Demo](http://sas.no)

## Strategier

* Eager evaluation
* Lazy evaluation
* Deferred evaluation
* Idle evaluation

Demo!

## Idle Until Urgent (av Philip Walton)

Sett oppgaven i kø for å bli evaluert ved neste idle periode, og gi oppgaven mulighet til å evalueres tidligere om nødvendig.

## Hvordan gå frem i egen kode

* Identifiser tung kode som kan brytes opp og som ikke trengs med en gang
* Ta en titt i konstruktørfunksjoner

## Browser support

https://caniuse.com/#search=requestIdleCallback

## Resurser

1.  [Idle Until Urgent](https://philipwalton.com/articles/idle-until-urgent/)
2.  [HTML5 event loop spec](https://www.w3.org/TR/html5/webappapis.html#event-loops)
3.  [Improving input responsiveness in Microsoft Edge](https://blogs.windows.com/msedgedev/2017/06/01/input-responsiveness-event-loop-microsoft-edge/#bP2ZdcQVvG3rRgh1.97)
4.  [Jake Archibald: In The Loop - JSConf.Asia 2018](https://youtu.be/cCOL7MC4Pl0)
5.  [Philip Roberts: What the heck is the event loop anyway?](https://2014.jsconf.eu/speakers/philip-roberts-what-the-heck-is-the-event-loop-anyway.html)
6.  [Visualize the event loop](http://latentflip.com/loupe/)
7.  [Measure Performance with the RAIL Model](https://developers.google.com/web/fundamentals/performance/rail)
8.  [Using-requestidlecallback](https://developers.google.com/web/updates/2015/08/using-requestidlecallback)
9.  [useIdleUntilUrgent](https://github.com/Trulsaa/useIdleUntilUrgent)
