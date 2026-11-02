# TikTok svetainės pataisų paruošimas — 2026-11-02

## Patikra

Viešas /tiktok/, privacy.html ir terms.html grąžino HTTP 200. Pradinis puslapis buvo trumpas tekstinis pristatymas. HTML neturėjo img elemento ar aktyvaus favicon link; numatyto šablono favicon buvo tik komentaras. Bendros svetainės šaknis pristato Clipping YouTube, todėl TikTok paraiškai reikia naudoti /tiktok/ adresą.

Šaltinio tiktok/index.md patikra per GitHub: 7b78bc8f047358a4881fd757e24999e621187873.

## Paruošta vietoje

- Atskiras tiktok layout ir stilius, taikomas tik penkiems TikTok puslapiams.
- Bendra matoma ikona, favicon ir apple-touch-icon naudoja tą patį PNG.
- Šaltinis: C:\Users\gedvi\Downloads\clipping-app-icon-1024.png (1024×1024).
- SHA256: 047c4e3b98d7e9b77eb09b71773003621da84e0425733192479f024baba6532d.
- TikTok portale App icon reikia pasirinkti tą patį failą; tikslaus portalo failo baitų sutapimo dar nepatvirtinome.
- Išplėstas pagrindinis puslapis, pridėti realaus Desktop Inbox workflow naudojimo ir pagalbos puslapiai. Funkcijos patikrintos pagal vietinio TikTok repo desktop.py ir jo instrukcijas.
- Privacy ir Terms atnaujinta tik data, prieinamumo būsena bei išdėstymo metaduomenys. Teisinis turinys iš esmės nekeistas.
- Facebook ir YouTube puslapiai, URL patvirtinimo TXT nekeisti.

## Patikros ir ribos

Penkių Markdown puslapių vidinių nuorodų patikra ir ikonos baitų palyginimas praėjo. Vietinė HTML peržiūra sugeneruota su Python Markdown ir išdėstymas peržiūrėtas Chrome. Tai nėra tikras Jekyll build: Ruby/Bundler vietoje nerasti. GitHub Pages build ir galutiniai vieši URL turi būti patikrinti po publikavimo. git diff --check praėjo.

Pataisos paruoštos šakoje codex/tiktok-review-website. Push, Pages diegimas, TikTok portalo keitimas ir pakartotinis pateikimas dar neatlikti.

Vien papildomi puslapiai negarantuoja peržiūros patvirtinimo. Oficialios gairės taip pat riboja asmeninius / privačius bei dar testuojamus produktus. Esama faktinė būsena neslepiama; prieš pakartotinį pateikimą reikia įvertinti realaus produkto prieinamumą ir atitiktį, ne vien dizainą.

Šaltinis: https://developers.tiktok.com/docs/en/app-review-guidelines (patikrinta 2026-11-02).

## Toliau

Peržiūrėti vietinę svetainę, paskelbti pataisas ir patikrinti Pages build bei viešus puslapius. Tada portale suvienodinti App icon su tiktok/assets/app-icon.png ir Website URL su https://gedvidas.github.io/clipping-app-info/tiktok/. Paraiškos dar nelaikyti parengta vien dėl šių pakeitimų.
