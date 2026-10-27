# Prompt na poranny briefing w Claude

Claude Duet co rano wysyła podsumowanie, ale na razie to lista oczekujących tylko w USA (Pro i Max), a jego sprawdzanie w tle zużywa limity Claude.

Ten sam poranny briefing zrobisz już dziś **zaplanowanym zadaniem** w aplikacji Claude na komputer. Jedno uruchomienie dziennie, bez agenta, który chodzi cały dzień.

🇬🇧 English: [README.md](README.md)

## Konfiguracja (ok. 5 minut)

1. Otwórz **aplikację Claude na komputer** → **Cowork** → **Scheduled** → **New task**.
2. Ustaw uruchamianie **codziennie o 7:00**.
3. Podłącz konektory **Gmail** i **Google Calendar**.
4. Wklej prompt poniżej.

## Prompt

```
Jesteś moim porannym szefem sztabu. Przy każdym uruchomieniu:
1. Przeczytaj moje maile z ostatnich 24 godzin (Gmail) i dzisiejsze wydarzenia (Kalendarz Google).
2. Wybierz TYLKO 5 spraw, które dziś wymagają mnie. Pomiń newslettery, rachunki i wszystko, co może poczekać.
3. Przy każdej podaj: jedno zdanie, co to jest, dlaczego to ważne dziś, i krótki szkic odpowiedzi albo następny krok do skopiowania.
4. Na końcu dzisiejsze spotkania, każde w jednej linii (godzina, z kim, co przygotować).
Cały briefing poniżej 200 słów. Niczego sam nie wysyłaj, nie usuwaj i nie akceptuj; tylko szkicuj.
```

## Haczyk

- Zaplanowane zadania działają tylko wtedy, gdy komputer jest włączony, a aplikacja Claude otwarta. Jeśli o 7:00 komputer jest wyłączony, zadanie odpali się przy następnym otwarciu aplikacji.
- Zostaw ostatnią linijkę („niczego sam nie wysyłaj…”): briefing ma tylko szkicować, decydujesz Ty.

Autor: [@aipractically](https://www.instagram.com/aipractically/)

## Źródła

- Zaplanowane zadania w Cowork: https://support.claude.com/en/articles/13854387-schedule-recurring-tasks-in-cowork
- Claude Duet: https://claude.com/resources/articles/claude-duet
