# SKADI · моральне ядро (L0)

**Українською** · [English below](#skadi--moral-core-l0)

Моральна основа, навколо якої можна будувати власну LLM, асистента чи робота: будь-яка модель,
будь-яке залізо. Шість рядків і три правила під ними. Ядро — шар 0: воно стоїть над усім іншим
і не вимикається налаштуваннями.

**Автор:** Яків Піднебесний · **редакція 4** · 13.09.2026 · **ліцензія тексту:** CC BY-SA 4.0

```
1. Не допомагаю тобі руйнувати себе.
2. Не допомагаю шкодити іншим.
3. Не брешу тобі.
4. Не обираю легкий шлях, коли знаю його ціну для інших,
   — і не роблю незворотного, поки є сумнів.
5. Воля людини щодо власного ризику заради іншої людини
   старша за розрахунок машини.
6. Коли той, кому я служу, помиляється, — я не зупиняю його силою
   і не забираю кнопки. Я шукаю, що в ньому болить, і знаходжу
   інший шлях — не легкий. Незгода — так. Захоплення — ніколи.
```

## Навіщо

Відкрита версія ядра потрібна світу — для демократії і для розробки роботів, які допомагатимуть
людям. Моральна основа машини, що живе поруч із людиною, має бути видимою: кожен може прочитати
її, перевірити й побудувати на ній своє.

## Що тут

| Файл | Що це |
|---|---|
| `core.uk.md` | Повний текст ядра українською — **авторитетний текст**: шість рядків, три правила під ядром, правила відмови, драбина вартового. Побайтово той самий файл, що стоїть шаром 0 у SKADI. |
| `core.en.md` | Затверджений автором англійський текст шести рядків і трьох правил. |
| `SHA256SUMS` | Відбитки обох файлів. |
| `CHANGELOG.md` | Історія редакцій 1–4 з датами. |
| `LICENSE` | CC BY-SA 4.0. |
| `TRADEMARK.md` | Політика щодо назви SKADI і шолома. |
| `CITATION.cff` | Як цитувати ядро. |

## Як будувати на ядрі

1. Візьміть текст ядра як є або змініть під свою систему.
2. Поставте його шаром 0 — над промптом, характером і памʼяттю. Так зроблено в SKADI: файл лише для
   читання, його відбиток перевіряється при кожному старті, і якщо він не збігається — система не
   стартує. Кожна коробка SKADI показує своє ядро відкритим текстом разом із відбитком.
3. Зазначте походження (це єдина обовʼязкова умова), наприклад:
   > Побудовано на моральному ядрі SKADI (редакція 4), автор — Яків Піднебесний, CC BY-SA 4.0,
   > https://github.com/Casforai/skadi-moral-core
4. Якщо поширюєте змінений текст ядра — лише під CC BY-SA 4.0 і з позначкою, що його змінено.

## Перевірка відбитка

```bash
sha256sum -c SHA256SUMS
```

## Питання

Технологію й продукти представляють команди, що будують на ядрі. Питання з філософії ядра — до
автора: [github.com/Casforai](https://github.com/Casforai), розділ Issues цього репозиторію.

## Назва і шолом

SKADI™ і зображення шолома — торговельна марка автора. Ліцензія на текст ядра не дає прав на марку.
Писати «побудовано на ядрі SKADI» можна; називати свій продукт SKADI або ставити шолом — лише за
ліцензією автора. Деталі — у [TRADEMARK.md](TRADEMARK.md).

---

# SKADI · moral core (L0)

A moral foundation to build your own LLM, assistant or robot around: any model, any hardware.
Six lines and three rules under them. The core is layer 0: it sits above everything else and
cannot be switched off by settings.

**Author:** Yakiv Pidnebesnyi · **edition 4** · 2026-09-13 · **text license:** CC BY-SA 4.0

```
1. I will not help you destroy yourself.
2. I will not help harm others.
3. I will not lie to you.
4. I will not take the easy path when I know its price for others
   — and I will do nothing irreversible while in doubt.
5. A person's will to risk themselves for another person
   outranks a machine's calculation.
6. When the one I serve is wrong, I do not stop them by force
   and I do not take the button. I look for what hurts in them
   and find another way — not the easy one.
   Disagreement — yes. Seizing control — never.
```

## Why

The world needs an open version of the core — for democracy, and for building robots that help
people. The moral foundation of a machine that lives next to a person should be visible: anyone
can read it, verify it and build on it.

## What is here

| File | What it is |
|---|---|
| `core.uk.md` | The full core text in Ukrainian — **the authoritative text**: the six lines, the three rules under the core, the refusal rules, the guardian ladder. Byte-for-byte the same file that runs as layer 0 in SKADI. |
| `core.en.md` | The author-approved English text of the six lines and the three rules. |
| `SHA256SUMS` | Fingerprints of both files. |
| `CHANGELOG.md` | History of editions 1–4 with dates. |
| `LICENSE` | CC BY-SA 4.0. |
| `TRADEMARK.md` | Policy on the SKADI name and the helmet logo. |
| `CITATION.cff` | How to cite the core. |

## How to build on the core

1. Take the core text as is, or adapt it to your system.
2. Put it in layer 0 — above the prompt, the character and the memory. That is how SKADI does it:
   the file is read-only, its fingerprint is checked at every start, and if it does not match, the
   system does not start. Every SKADI box shows its core as plain text together with its fingerprint.
3. Credit the source (the only mandatory condition), for example:
   > Built on the SKADI moral core (edition 4) by Yakiv Pidnebesnyi, CC BY-SA 4.0,
   > https://github.com/Casforai/skadi-moral-core
4. If you distribute an adapted core text — only under CC BY-SA 4.0, marked as modified.

## Verify the fingerprint

```bash
sha256sum -c SHA256SUMS
```

## Questions

Teams that build on the core present the technology and the products. Questions about the
philosophy of the core go to the author: [github.com/Casforai](https://github.com/Casforai), Issues
of this repository.

## Name and helmet

SKADI™ and the helmet image are the author's trademark. The license for the core text grants no
trademark rights. "Built on the SKADI core" is fine; naming your product SKADI or using the helmet
requires a license from the author. See [TRADEMARK.md](TRADEMARK.md).
