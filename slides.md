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

Autor: Jakub Surdej

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

Istniejące aplikacje.

<div class="text-left">
<ul>
  <li><a href="https://sematext.com/" target="_blank" rel="noopener">Sematext Synthetics</a></li>
  <li><a href="https://www.solarwinds.com/" target="_blank" rel="noopener">SolarWinds</a></li>
  <li><a href="https://www.datadoghq.com/" target="_blank" rel="noopener">Datadog</a></li>
  <li><a href="https://www.nagios.com/" target="_blank" rel="noopener">Nagios</a></li>
  <li><a href="https://ohdear.app/" target="_blank" rel="noopener">Oh Dear</a></li>
</ul>
</div>

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

# Analiza SWOT konkurencji

<p>
  <b>Mocne Strony:</b> Wiele z tych narzędzi oferuje kompleksowe monitorowanie z różnorodnymi opcjami powiadomień.
</p>
<p>
  <b>Słabe Strony:</b> Brak automatycznego wyszukiwania subdomen lub ograniczone opcje powiadomień w niektórych narzędziach.
</p>
<p>
  <b>Szanse:</b> Wprowadzenie zaawansowanego wyszukiwania subdomen i rozszerzonych opcji powiadomień może wyróżnić nasz projekt.
</p>
<p>
  <b>Zagrożenia:</b> Silna konkurencja i konieczność stałego aktualizowania funkcji w odpowiedzi na zmieniające się zagrożenia bezpieczeństwa.
</p>

---
class: px-10
transition: slide-left
---

# Unikalna Wartość

- Zaawansowane wyszukiwanie subdomen
- Elastyczne opcje powiadomień
- Łatwa integracja z infrastrukturą jako kod (IaC)
- Udostępnianie metryk zgodnych z OpenMetrics oraz Prometheus
- Otwartoźródłowy kod

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
