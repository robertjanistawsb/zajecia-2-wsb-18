# Tytuł projektu:
Aplikacja do planowania nauki dla studentów

# Cel projektu:
Ułatwić studentom organizację nauki poprzez tworzenie strukturalnych planów, harmonogramów i monitorowanie postępów. Rozwiązuje problem braku struktury nauki, rozproszenia zadań i niskiej motywacji.

# Opis problemu:
Studenci często nie mają jasnego planu nauki, co prowadzi do odkładania zadań, chaotycznej nauki przed egzaminami i niskiej efektywności. Brakuje narzędzia, które łatwo wygeneruje realistyczny plan dostosowany do indywidualnych celów i dostępnego czasu.

## Główne funkcje:
- Generator planu nauki na podstawie celów, terminów i dostępnych godzin.
- Harmonogram (kalendarz tygodniowy/dzienny) z przypomnieniami.
- Podział materiału na jednostki (lekcje, tematy, zadania) z priorytetami.
- Timer Pomodoro i tryb skupienia.
- Śledzenie postępów, statystyki (czas nauki, zrealizowane zadania).
- Integracja z kalendarzem studenta (opcja importu terminów).
- Możliwość tworzenia listy materiałów i notatek.

## Grupa docelowa:
Studenci uczelni wyższych oraz licealiści przygotowujący się do egzaminów.

## Wartość biznesowa i użytkowa:
- Wyższa efektywność nauki i lepsze wyniki egzaminów.
- Mniejsze odczucie przytłoczenia i lepsze zarządzanie czasem.
- Narzędzie o niskim progu wejścia, dostępne na urządzeniach mobilnych i desktopie.

### Technologie (proponowane):
- Frontend: React / Vue (responsywny UI)
- Backend: Node.js + Express lub Python Flask
- Baza danych: SQLite / PostgreSQL
- Powiadomienia: lokalne / push
- Opcjonalnie: aplikacja mobilna React Native / Flutter

### MVP (minimum funkcjonalne):
1. Rejestracja użytkownika i tworzenie profilu.
2. Dodawanie kursów/tematów i terminów.
3. Generowanie tygodniowego planu.
4. Podstawowy timer i śledzenie zadań.
5. Zapisywanie i przeglądanie historii postępów.
---
**Kryteria akceptacji:**
- Użytkownik potrafi wprowadzić cele i terminy oraz otrzymać gotowy plan.
- System zapisuje postępy i wyświetla podstawowe statystyki.
- Powiadomienia przypominają o zaplanowanych sesjach.
---
**Kamienie milowe:**
1. Analiza wymagań i projekt UX.
2. Implementacja backendu i modelu danych.
3. Prosty frontend do tworzenia planów.
4. Timer i śledzenie postępów.
5. Testy użytkowników i iteracje.

Ryzyka i założenia:
- Różnorodność metod nauki -> plan powinien być konfigurowalny.
- Założenie, że użytkownik poświęci kilka minut na konfigurację.
- Prywatność danych i zabezpieczenie kont użytkowników.
---
Krótka konkluzja:
Projekt dostarczy praktyczne narzędzie zwiększające strukturę i efektywność nauki poprzez automatyzację planowania, przypomnienia i monitorowanie postępów.
