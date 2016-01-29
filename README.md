# <img src=https://pbs.twimg.com/profile_images/438136190760284160/Q3LJPRGx.png width="30"> Crashlytics (Fabric)
[[Websidan för fabric ios]](https://get.fabric.io/ios?locale=en-us)

###Plus
+ Mycket enkel setup
+ Extra gratis information om mobilerna som krasherna inträffade på:
    * Orientation
    * Batteri %
    * Om den var rootad
    * Oanvänd RAM
    * Oanvänt minne
+ Lättanvänd [logging mekanism](http://support.crashlytics.com/knowledgebase/articles/120066-how-do-i-use-logging-)
+ När man loggar fångade exceptions med Crashlytics.logException ser man dem på samma sätt som crasher fast under en non-fatal kategori. 
+ Holler koll på hur ofta krasher händer. Prioriterar sedan och rapporterar viktigaste.
+ Kan förutse krasher?
+ Lätt för testare
   - Man behöver inte bry sig om UDIDer
+ En del av Fabric som ger enkel tillgång till [mycket annat bra](https://fabric.io/kits).

###Minus
- Känns lite småbuggigt
    + Macappen visade fel info om krashrapporter (kan vara åtgärdat med den senaste uppdateringen)
    + Webbapp för iPhone testare
    + En aning oresponsivt gränssnitt
- Nya krashgrupper blir nyhetsbrev i gmail (säkert temporärt)

###Annat
- Ägs av Twitter

# <img src=https://pbs.twimg.com/profile_images/378800000525330913/436e2f6e2e5b488a3ed636b6f37adb98.png width=30 /> HockeyApp

###Plus
+ Varierande åsikter om bäst crash reporitng, crash probe visar att HockeyApp ger bäst crash reporting [[Länk till crashprobe]](http://www.crashprobe.com/ios/)
+ Finns en bra mac för krashrapporter som man enkelt kan gå direkt till raden det krashade på i t.ex. Android Studio.

###Minus
- Mer manuellt arbete med setup och crash symbols
- Kostar

###Annat
- Ägs av Microsoft

# <img src=https://upload.wikimedia.org/wikipedia/en/thumb/e/ed/TestFlight_Icon.png/64px-TestFlight_Icon.png width=30 /> TestFlight

[[TestFlights websida]](https://developer.apple.com/testflight/)

###Plus
+ En del av iTunesConnect
+ Man behöver inte bry sig om UDIDs för testare. Man behöver bara deras Apple ID för att bjuda in dem.
+ Externa och interna testare

###Minus
- Inte Android
- Stödjer bara iOS8+
- Max 25 interna testare per app
- Interna byggen tar några timmar att ladda upp.
- Interna testare behöver access till samma iTunesConnect account
- För att appar skall finnas tillgängliga för externa testare måste dem gå igenom en beta review, vilket kan ta upp emot en dag.
- Den externa builden finns tillgänglig i 60 dagar, sen måste man ladda upp en ny build för review.
- Endast en pre-release version per platform kan vara aktiv för beta testing samtidigt, men interna och externa testare kan testa olika versioner.

###Annat
- Ägs av Apple


## Länkar:

Jämförelse mellan testverktyg - [http://savvyapps.com/blog/review-5-best-ios-crash-reporting-tools-infographic](http://savvyapps.com/blog/review-5-best-ios-crash-reporting-tools-infographic)

Crashlytics overview - [http://www.donnfelker.com/why-i-use-crashlytics-part-2/](http://www.donnfelker.com/why-i-use-crashlytics-part-2/)

Testflight overview - 
[https://developer.apple.com/library/ios/documentation/LanguagesUtilities/Conceptual/iTunesConnect_Guide/Chapters/BetaTestingTheApp.html#//apple_ref/doc/uid/TP40011225-CH35](https://developer.apple.com/library/ios/documentation/LanguagesUtilities/Conceptual/iTunesConnect_Guide/Chapters/BetaTestingTheApp.html#//apple_ref/doc/uid/TP40011225-CH35)

Uppdaterad iOS crash reporting tools overview - [https://blog.rollout.io/2015/12/ios-crash-reporting-tools-2016-update/](https://blog.rollout.io/2015/12/ios-crash-reporting-tools-2016-update/)