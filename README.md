# Integrator Platform

Narzędzie do integracji platform marketplace dla sprzedawcy prowadzącego
jednoosobową działalność gospodarczą w Polsce.

## Cel aplikacji

Synchronizacja stanów magazynowych, ofert i zamówień między platformami sprzedażowymi:

- **Allegro** — zarządzanie ofertami, zamówieniami, etykietami wysyłki, zwrotami
- **EmpikPlace** (Mirakl) — synchronizacja stanów, obsługa zamówień, wystawianie ofert
- **OLX** — w planach

Aplikacja działa w trybie self-hosted na własnym serwerze VPS w Polsce.
Obsługuje wyłącznie konta operatora aplikacji — nie jest to usługa SaaS dla
wielu użytkowników.

## Technologia

- Python 3 / Flask
- SQLite
- Nginx + Gunicorn
- Ubuntu Server (VPS)

## Operator i kontakt

- **Operator**: Deal Center Kamil Barlak
- **Email kontaktowy**: dealcenter.biuro@gmail.com
- **Lokalizacja**: Polska

## Status

Aplikacja w użyciu produkcyjnym. Wersja: 1.0.0
