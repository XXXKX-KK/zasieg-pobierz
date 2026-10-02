# Zasięg — pobierz aplikację

Zasięg pokazuje na pasku statusu aktualną prędkość internetu, a w powiadomieniu
kolorem jakość połączenia: zielony dobry, pomarańczowy średni, czerwony słaby.
Działa na Androidzie i nie ma jej w Sklepie Play — instalujesz ją z pliku, stąd.

## Pobierz

**[→ Najnowsza wersja](https://github.com/XXXKX-KK/zasieg-pobierz/releases/latest)**

Na tej stronie, w sekcji **Assets**, tapnij plik **`zasieg.apk`**.

## Instalacja krok po kroku

1. **Tapnij `zasieg.apk`** na stronie wydania. Przeglądarka pobierze plik.
2. Android zapyta, czy zezwolić tej przeglądarce na instalowanie aplikacji.
   Tapnij **Ustawienia** → włącz **Zezwalaj z tego źródła** → wróć przyciskiem
   wstecz. To pytanie pojawia się tylko raz.
3. W powiadomieniu o pobraniu (albo w **Pliki → Pobrane**) tapnij
   **`zasieg.apk`** → **Zainstaluj**.
4. Otwórz Zasięg i zezwól na powiadomienia — bez tego liczba nie pojawi się na pasku.
5. W aplikacji: **Ustawienia → Wyłącz optymalizację baterii**. Samsung inaczej
   usypia monitor w tle.

## „Zablokowano przez Play Protect"

To normalne ostrzeżenie dla każdej aplikacji spoza Sklepu Play. Tapnij
**Więcej szczegółów** → **Zainstaluj mimo to**.

## Aktualizacje

**Nie musisz tu wracać.** Apka raz na dobę sprawdza, czy jest nowsza wersja, i
pokazuje powiadomienie „Nowa wersja Zasięgu”. Tapnij je, pobierz, zainstaluj.
Ręcznie: **Ustawienia → Sprawdź aktualizacje**.

Aktualizacja nie kasuje ustawień ani historii.

## Prywatność

- **Bez konta i bez zgody wszystko zostaje w telefonie.** Pomiary, trasy i mapa są zapisywane
  tylko lokalnie.
- **Konto** (Google, kod na e-mail albo „Pomiń” – konto anonimowe) służy wyłącznie do wspólnej
  mapy i kopii tras. Nie wyświetlamy reklam i nie sprzedajemy danych.
- **Wspólna mapa** (tylko po włączeniu „Dołącz do wspólnej mapy”): wysyłamy wyłącznie kwadrat
  ok. 150 m, operatora, rodzaj sieci (LTE/5G…), **dzień** i liczbę pomiarów każdej jakości. Bez
  godzin, tras, numeru telefonu i nazw sieci Wi-Fi; pomiary na Wi-Fi nigdy nie są wysyłane. Inni
  widzą kwadrat dopiero, gdy mierzyło go kilka osób albo jedna osoba w kilka różnych dni – i nigdy
  nie widzą, kto ani ile osób.
- **Kopia tras** (tylko po włączeniu „Kopia moich tras w chmurze”): trasy widzi wyłącznie
  właściciel konta; służą do przywrócenia danych na nowym telefonie.
- **Strefy prywatne:** okolica domu (wykrywana w telefonie z pomiarów nocnych) i miejsca wskazane
  przez Ciebie nie trafiają do wspólnej mapy, a trasy są w nich ucinane.
- **Usunięcie:** Ustawienia → Wspólna mapa → „Usuń moje dane z serwera” albo Ustawienia → Konto →
  „Usuń konto i wszystkie dane” – usuwa konto i wszystko na serwerze od razu.
- Dane leżą w Supabase (UE, Irlandia). Pytania i prośby o usunięcie danych: zakładka **Issues** w tym repozytorium.

## Czego tu nie ma

W tym repozytorium nie ma kodu — tylko ta instrukcja i pliki instalacyjne.
