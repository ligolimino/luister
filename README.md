# Letterlab — luisteren

Auditieve oefeningen zonder afbeelding, zodat de cursist echt naar het
woord luistert. Na een juist antwoord verschijnt het woord, met de klank
in het roze: zo leg je de link tussen klank en teken. De tool rekent zelf
uit wat juist is.

Stappenplan technisch lezen: stap 2, 5, 8 en 11 (A, C, F en G).

## Soorten

| Link | Vraag | Antwoordknoppen |
|---|---|---|
| `soort=zelfde&woorden=raam/raam,raam/ram` | Hoor je hetzelfde? | = en ≠ |
| `soort=hoor&klank=r&woorden=jas,raam,deur` | Hoor je de klank? | ✓ en ✗ |
| `soort=plaats&klank=r&woorden=raam,deur,arm` | Waar hoor je de klank? | blanco strook met vakjes |
| `soort=welke&keuzes=a,aa&woorden=dak,zaak` | Welke klank hoor je? | de keuzes |
| `soort=tel&woorden=vaas,lees,map` | Hoeveel klanken hoor je? | bolletjes (1 tot 6) |

Een woord dat niet past (bv. bij `welke` geen of twee keuzes, bij `plaats`
zonder de klank), valt weg.

## Andere mogelijkheden

| In de link | Betekenis |
|---|---|
| `mix=ja` | Elke keer een andere volgorde. |
| `toon=nee` | Het woord niet tonen na het antwoord. |
| `b-a-nk` | Streepjes in een woord bepalen zelf de klanken. |

## Wat de cursist ziet

- Bolletjes bovenaan: groen = meteen juist, oranje = na een nieuwe poging.
- Het woord klinkt vanzelf. De grote knop speelt het opnieuw.
- Fout: het antwoord kleurt rood en schudt. De cursist probeert opnieuw.
- Juist: vinkje, het woord met de klank in het roze, en nog eens het geluid.
- Op het einde: hoeveel er meteen juist waren, en **Opnieuw**.

Toetsen voor de lesgever: spatie of L = opnieuw luisteren, Enter = volgende.

## Geluid

Woorden uit `assets/audio/woorden/<eerste letter>/` of `nonsens/`
(centrale repository), daarna de mappen van het klik-klakboekje, anders de
browserstem. Voeg ontbrekende opnames toe via de createpagina.

## Publiceren (eenmalig)

1. Maak bij **ligolimino** een openbare repository `luister`.
2. Kies **uploading an existing file** en sleep de **inhoud** van deze map
   erin (niet de map zelf). Kies **Commit changes**.
3. **Settings → Pages**: branch `main`, map `/ (root)`, **Save**.
4. Na enkele minuten: `https://ligolimino.github.io/luister/`.

Open je die link zonder iets erachter, dan zie je een uitlegpagina met een
formulier om zelf een link te maken.

## Zelfstandig en onderhoudsvrij

- Alleen gewone bestanden: geen installatie, geen bouwstap, geen databank.
- Het lettertype Andika staat in de repository zelf.
- De volledige oefening staat in de link. Een link blijft werken zolang de
  repository online staat.
- In Genially is de achtergrond doorzichtig, zodat de dia zichtbaar blijft.

## Na een wijziging

Telefoons kunnen een oude versie bewaren. Wacht even of herlaad de pagina.

## Licentie lettertype

Andika valt onder de SIL Open Font License, zie
`assets/fonts/OFL-LICENSE.txt`.
