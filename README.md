# Moonbase Control: Route parameters

Zadanie z modułu Angular. Repozytorium zawiera kod startowy aplikacji Moonbase Control dla tej lekcji.

## Zadanie

Rozbuduj widok misji tak, aby użytkownik mógł przejść z listy do szczegółów wybranej misji.

Każda misja powinna posiadać własny adres wykorzystujący jej `id`, a widok szczegółów powinien pobierać i wyświetlać dane misji wskazanej w adresie.

- Utwórz komponent `MissionDetails` przeznaczony do wyświetlania pojedynczej misji.
- Dodaj ścieżkę `missions/:id` prowadzącą do nowego komponentu.
- Dodaj do elementów listy misji dynamiczny `routerLink`, wykorzystujący `id` konkretnej misji.
- Skonfiguruj Router tak, aby parametr `id` mógł zostać przekazany bezpośrednio do inputu komponentu.
- Dodaj w `MissionDetails` wymagany input `id`.
- Wykorzystaj istniejącą metodę `MissionsService` do pobrania misji wskazanej przez `id`.
- Wyświetl dane pobranej misji w `MissionDetails`.
- Dodaj stan ładowania widoczny podczas pobierania danych.
Rezultat: kliknięcie misji na liście prowadzi do adresu `/missions/:id`, a widok `MissionDetails` wyświetla dane misji odpowiadającej identyfikatorowi znajdującemu się w adresie.

## Jak zacząć

1. Zrób fork tego repozytorium na swoje konto GitHub.
2. Sklonuj swój fork na komputer.
3. Zainstaluj zależności: `npm install`.
4. Uruchom aplikację: `npm start`.
5. Jeśli zadanie korzysta z danych z API, uruchom w drugim terminalu mock API: `npm run api`.

## Jak oddać zadanie

1. Zapisz zmiany w commicie i wypchnij je do swojego forka.
2. Otwórz Pull Request z forka do repozytorium `mate-academy/angular_route-parameters`, do brancha `main`.
3. Platforma uruchomi review Twojego Pull Requesta.
