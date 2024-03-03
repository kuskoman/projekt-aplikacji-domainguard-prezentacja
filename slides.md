---
theme: dracula
class: text-center
highlighter: shiki
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: DomainGuard - aplikacja do monitorowania ważności domen i certyfikatów SSL
monaco: true
---

# DomainGuard

## Aplikacja do monitorowania ważności domen i certyfikatów SSL

<style>
h1 {
  color: #4EC5D4;
}
</style>

---
class: px-10
transition: fade
---

# Czym jest DomainGuard?

<p class="description">Projekt ma na celu stworzenie zaawansowanej aplikacji do monitoringu domen i certyfikatów SSL, która automatycznie wyszukuje subdomeny dla dodanych domen i monitoruje status ich certyfikatów SSL. Aplikacja ma na celu zminimalizowanie ryzyka wygaśnięcia certyfikatów i zwiększenie bezpieczeństwa online dla firm i indywidualnych użytkowników.</p>

<style>
.description {
  font-size: 1.2rem;
  line-height: 1.8rem;
  margin-top: 1rem;
  color: #A9B8C3;
}
</style>

---
class: px-10
transition: slide-right
---

# Kluczowe Funkcjonalności

- Automatyczne wyszukiwanie subdomen
- Monitoring statusu certyfikatów SSL
- Powiadomienia o zbliżającym się wygaśnięciu certyfikatów
- Dashboard użytkownika z przeglądem statusu

---
class: px-10
transition: slide-up
---

# Dla Kogo Jest DomainGuard?

- Administratorzy stron internetowych
- Firmy hostingowe
- Przedsiębiorstwa z obecnością online

---
class: px-10
transition: fade-in
---

# Badanie Rynku

Istniejące aplikacje i ich krótki opis.

---
class: px-10
transition: fade-in
---

# Analiza Konkurencji: Sematext Synthetics

Sematext Synthetics to kompleksowe narzędzie do monitorowania certyfikatów SSL i wydajności stron internetowych. Oferuje automatyczne testy i powiadomienia, ale skupia się głównie na monitorowaniu wydajności, co może być ograniczeniem dla użytkowników zainteresowanych głębszą analizą bezpieczeństwa SSL.

---
class: px-10
transition: fade-in
---

# Analiza Konkurencji: Datadog

Datadog oferuje szeroką gamę funkcji monitorowania, w tym SSL, z zaawansowaną analizą danych. Jednak wysokie koszty mogą stanowić barierę dla mniejszych firm oraz indywidualnych użytkowników, co otwiera przestrzeń dla bardziej dostępnych rozwiązań, takich jak DomainGuard.

---
class: px-10
transition: slide-left
---

# Unikalna Wartość

- Zaawansowane wyszukiwanie subdomen
- Elastyczne opcje powiadomień
- Łatwa integracja z infrastrukturą jako kod (IaC)

---
class: px-10
transition: fade-out
---

# Plan Rozwoju

1. Prototyp i testy MVP
2. Rozwój funkcjonalności i integracji
3. Stworzenie stabilnego API
4. Wydanie interfejsu CLI, oraz SDK dla narzędzia Terraform
5. Współpraca z społecznością open-source
