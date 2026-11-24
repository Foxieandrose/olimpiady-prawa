# Kurs z prawa – OWoP i OWoPiP (2026/27)

Nieoficjalny kurs przygotowawczy do dwóch olimpiad: Ogólnopolskiej Olimpiady Wiedzy o Prawie (OWoP) i Ogólnopolskiej Olimpiady Wiedzy o Państwie i Prawie (OWoPiP).

Co jest w środku:
- **Lekcje** – nauka krok po kroku: ściąga, tabele, krótkie quizy po każdej części, oznaczone fakty, o które pytano na olimpiadach.
- **Nauka (fiszki)** – powtórki w odstępach jak w Anki, osobno dla etapu szkolnego, okręgowego i finału.
- **Testy** – osobno OWoP i OWoPiP: testy archiwalne w oryginalnej kolejności, testy próbne (także w nowym formacie testu szkolnego OWoP z 2026 r.), ćwiczenia zadań otwartych, prawda/fałsz i przyporządkowania, egzamin pisemny, pytania problemowe.
- **Archiwum** – wszystkie testy do wydruku (PDF) z kluczami.

## Jak zacząć
Otwórz stronę w przeglądarce (komputer albo telefon). Na telefonie: „Udostępnij → Do ekranu początkowego” – kurs otwiera się wtedy jak aplikacja.

## Zapisywanie postępu
- Postęp zapisuje się **automatycznie w tej przeglądarce** na tym urządzeniu (nie trzeba się logować).
- Żeby przenieść postęp na inne urządzenie albo zrobić kopię: **Opcje → Zapisz kopię do pliku**, a na drugim urządzeniu **Opcje → Wczytaj kopię z pliku** (albo „Utwórz i skopiuj kod” / „Wczytaj kod z pola”).
- Wyczyszczenie danych przeglądarki usuwa postęp – warto co jakiś czas zapisać kopię do pliku.
- (Opcjonalnie) synchronizacja między urządzeniami przez konto Google: wymaga własnego projektu Firebase i wklejenia konfiguracji do `firebase-config.js` (`window.FIREBASE_CONFIG = {...}` z Ustawień projektu → Twoje aplikacje → aplikacja webowa; w Authentication włącz logowanie Google, w Firestore utwórz bazę). Bez tego strona działa z zapisem lokalnym.

Funkcje oceny odpowiedzi przez Claude i dyktowania działają tylko w wersji kursu w Claude; tutaj ocenia się samodzielnie według wzorca.

## Źródła
Testy archiwalne: organizatorzy olimpiad – OWoP: Komitet Główny OWoP, https://olimpiada.slo2.pl; OWoPiP: WSPiA Rzeszowska Szkoła Wyższa, https://olimpiada.wspia.eu. Przepisy: teksty ujednolicone z ISAP / ELI Sejmu (stan XI 2026). Klucze zweryfikowane ze stanem prawnym; różnice z kluczem organizatora są opisane przy pytaniach.

Pliki generuje projekt kursu (build/export_web.py, build/make_site.py, build/make_archive.py) – nie edytuj `cards.json` ani `lekcje.json` ręcznie.
