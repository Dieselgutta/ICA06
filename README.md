# ICA06

Link til pdf: https://fronter.com/uia/links/files.phtml/1530080210$980297832$/Innlevering_prcent_28G_prcent_29/Eksamen+-+mappeinnlevering+_prcent_28frist+fredag+19.+mai+2017+kl.+23_prcent_3A59_prcent_29/ICA-Mappe.pdf#page=37

Deltakere: Simen Fredriksen, Stian Blankenberg, Jone Manneråk, Kristian Hagberg, Tarjei Taxerås og Rasmus Sørby

Vi lagde ny repostory for ICAen fordi vi følte at den gamle repostorien var uryddig og uoversiktelig. Alle i gruppen har jobbet med oppgavene, men alle har ikke jobbet på egen PC. Av disse grunnene har ikke alle i gruppen commitet.


# Eksperiment 1

Ordet vi valgte å undersøke for lydfrekvenser var “elefant”. Dette ordet ga oss mulighet til å sammenligne to e-vokaler i forskjellig sammenheng, samt en a-vokalen. Det mest tydelige som kom fram her var uttalelsen til den første e-vokalen. Ved å sammenligne formantenes frekvenser opp mot en tabell for ulike vokaler, kunne vi fort se en sammenheng mellom dialekt og uttalelse av e. Mens en sørlending kom nærmere œ på tabellen, endte en østlending med en noe finere ɛ. Ellers var det større likhet ved den andre e-vokalen, samt a-vokalen hvor formant-frekvensene stemte overens med en ɑ.
Hvis vi skulle laget en språkgjennkjennelsesalgoritme hadde hovedfokuset nok ligget rundt formantenes tilknytning til hverandre. Ved hjelp av en kort setning burde det være mulig å “luke vekk” alle de språk-alternativene som ikke inneholder en tilsvarende oppbygging av formant-forhold. Identifisering av det som på engelsk heter “hisses and pops” ville nok vært til stor nytte her; dette er naturlige lyder som oppstår ved tale, og som kan være til hjelp for å skille språk fra hverandre.


# Eksperiment 2
I ekspriment 2 brukte vi eksempelet fra https://github.com/parente/espeakbox. Vi måtte laste ned docker på ubuntu, deretter kjørte vi programmet med denne kommandoen: sudo docker run --name espeakbox -d -p 8080:8080 parente/espeakbox

http://158.39.77.30:8080/speech?text=hei&voice=no&pitch=80&speed=170


# Eksperiment 3
Vi prøvde å bruke google sin speech API, slik som det er i dette eksempelet: https://www.google.com/intl/en/chrome/demos/speech.html, men fikk det ikke til. Vi slet med å få API nøkkelen til å fungere. Vi prøvde også med wit-engine, men slet med å forstå hvordan denne fungerte. 

