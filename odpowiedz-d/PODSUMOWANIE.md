# Odpowiedź D - podsumowanie pracy

Data: 2026-10-01

## Co powstało

1. **Artefakt na jej szkielecie** (wersja 3, link bez zmian):
   https://claude.ai/artifact/RGy4oAaxw6AY41cgrgmzoi
   - jej quiz odtworzony 1:1: ten sam układ (rozmyte tło, plakat 2:3, neonowe obwódki), te same dwa plakaty pobrane z jej artefaktu (`images/question.png`, `images/prize.png`), te same klikalne pigułki A/B/C,
   - kliknięcie dowolnej odpowiedzi pokazuje jej nagrodę "Wygrałeś! Wycieczkę do Sosnowca" dokładnie jak u niej,
   - dopiero wtedy wchodzi awatar (klip z Higgsfield) i podważa nagrodę: czerwony X markerem przez "SOSNOWCA", pieczątka "Nagroda nieprawidłowa", a na jej karcie skreślenia i dopiski: termin "wczoraj" na "na osobności", osoba towarzysząca "Ty i twoje osobowości" na "tylko ja 😏", koszt "0 zł" na "w naturze",
   - dymki: "Pomogę. Oczywiście, że pomogę. Ale nagroda… nie." / "Sosnowiec to nie jest waluta. Poprawiam." / "Rozliczymy się w naturze. Szczegóły na osobności. Ciastko to tylko zaliczka. 😏",
   - pieczątka "Umowa stoi?" i przycisk "Przyjmuję warunki" (po kliknięciu "Umowa stoi" i "Masz to na piśmie. Ja też. Termin odbioru podam osobiście."), przycisk "Od nowa",
   - na szerokich ekranach postać stoi obok plakatu, na telefonie siedzi w jego lewym dolnym rogu,
   - źródło: `odpowiedz-d/index.html`; kopie jej plakatów w `odpowiedz-d/images/`.

## Koszty

| Pozycja | Kredyty |
|---|---|
| Saldo na starcie | 10,00 |
| Obraz v1 (Z Image) | 0,25 |
| Klip 1 (Wan 3.0, 4 s, 480p) | ok. 4,00 |
| Obraz v2 (Nano Banana, edycja) | ok. 1,40 |
| Klip 2 (Wan 3.0, 4 s, 480p) | ok. 4,00 |
| Saldo po pracy | ok. 0,35 |

Modele GPT Image 2.5, Nano Banana (1), Seedance 2.0 Mini i Seedance 2.5 odmówiły: wymagają planu Basic. Pełne modele wideo (27-35 kredytów za 5 s) odpadały budżetowo.

## Media w artefakcie

Po odblokowaniu hosta `d8j0ntlcm91z4.cloudfront.net` w ustawieniach sieci środowiska pobrałem klip 2 (mp4, 480x854, 4 s, 3,0 MB) i obraz v2 (png, 768x1376, 1,4 MB) i opublikowałem je przy stronie jako `media/klip.mp4` i `media/postac.png`. Strona pokazuje klip w pętli (bez dźwięku, bo Wan 3.0 w tej konfiguracji go nie generuje); obraz jest plakatem i awaryjnym zastępnikiem. Kopie plików są w `odpowiedz-d/media/` w repozytorium.

Obejrzałem obraz i cztery klatki klipu: postać jest dorosłą kobietą w gotyckiej sukience ze złotymi twin-tailami, gest wychodzi w kolejności marker, X w powietrzu, pochylenie z palcem na ustach.

## Granica treści

Puenta jest mocno dwuznaczna ("zapłata w naturze", "na osobności", "zaliczka", "termin odbioru"), bez nagości i bez dosłowności. Postać jest dorosłą kobietą. Tej granicy trzymałem się także przy poprawce dekoltu z widżetu.

## Udostępnienie

Artefakt jest prywatny. Zanim wyślesz link koleżance, w menu Share strony włącz dostęp przez link, bo inaczej go nie otworzy.

## Następne kroki

1. Otwórz artefakt, kliknij "Sprawdź moją odpowiedź" i "Przyjmuję warunki", żeby zobaczyć całą sekwencję.
2. W menu Share włącz dostęp przez link i wyślij koleżance.
3. Ewentualne poprawki klipu wymagają dokupienia kredytów Higgsfield (saldo ok. 0,35).
