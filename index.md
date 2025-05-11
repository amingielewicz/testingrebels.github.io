---
layout: home
title: TestingRebels - Testowanie bez kagańca
---

# TestingRebels - Testowanie bez kagańca

**Przestrzeń dla testerów z charakterem. Instruktaże, API, automatyzacja i bunt.**

## 💥 Co tu znajdziesz?

**TestingRebels** to przestrzeń dla testerów z charakterem. Strona to przede wszystkim **instruktaże** – techniczne, konkretne i z życia wzięte. Pojawią się tu także luźniejsze treści:
- przemyślenia o testowaniu,
- recenzje narzędzi,
- automatyzacja,
- API,
- a także trochę punku i buntu.

> „Rebelia to akt myślenia samodzielnie.” — Albert Camus

Nie wszystko musi być perfekcyjne i zamknięte w procesie. Strona rozwija się razem ze mną – testerem, który ciągle się uczy i nie boi się podążać własną drogą.

📚 Jeśli jesteś jednym z tych, którzy pytają „dlaczego?”, a nie tylko „gdzie kliknąć” – rozgość się.

---

## 📚 Rozpocznij przygodę z TestingRebels

1. **Instruktaże i poradniki** – zaczynając od podstaw do bardziej zaawansowanych tematów.
2. **Automatyzacja testów** – ułatwiaj sobie pracę i oszczędzaj czas.
3. **Testowanie API** – wszystko, co musisz wiedzieć o testach API.
4. **Recenzje narzędzi** – sprawdzam i dzielę się opiniami na temat narzędzi, które warto znać.
5. **Myślenie poza schematami** – bo testowanie to nie tylko klikanie, ale zrozumienie.

---

## 🌐 Nawigacja

{% for item in site.data.navigation.main %}
  - [{{ item.title }}]({{ item.url }})
{% endfor %}
