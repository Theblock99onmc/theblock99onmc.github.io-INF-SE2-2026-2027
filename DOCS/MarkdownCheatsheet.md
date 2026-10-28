### Disclaimer: Gemaakt door gemini, 26 Okt 2026
# 📝 GitHub Markdown Cheatsheet

Een handig overzicht van alle veelgebruikte Markdown-syntax voor GitHub repositories, issues, pull requests en `README.md` bestanden.

---

## 📌 Inhoudsopgave
- [Koppen (Headers)](#koppen-headers)
- [Tekstopmaak](#tekstopmaak)
- [Lijsten](#lijsten)
- [Links en Afbeeldingen](#links-en-afbeeldingen)
- [Citations & Blockquotes](#citations--blockquotes)
- [Code & Syntax Highlighting](#code--syntax-highlighting)
- [Tabellen](#tabellen)
- [GitHub Callouts / Alerts](#github-callouts--alerts)
- [Uitklapbare Secties (Collapsible)](#uitklapbare-secties-collapsible)
- [Speciale GitHub Kenmerken](#speciale-github-kenmerken)

---

## Koppen (Headers)

```markdown
# H1 Kop (Hoofdtitel)
## H2 Kop
### H3 Kop
#### H4 Kop
##### H5 Kop
###### H6 Kop
```

---

## Tekstopmaak

| Effect | Syntax | Resultaat |
| :--- | :--- | :--- |
| **Vet** | `**vet gedrukt**` of `__vet gedrukt__` | **vet gedrukt** |
| *Cursief* | `*cursief*` of `_cursief_` | *cursief* |
| ~~Doorstrepen~~ | `~~doorstrepen~~` | ~~doorstrepen~~ |
| **_Vet & Cursief_** | `***vet & cursief***` | ***vet & cursief*** |
| `Inline code` | `` `code` `` | `code` |
| Subscript | `H~2~O` | H~2~O |
| Superscript | `X^2^` | X^2^ |

---

## Lijsten

### Ongeordende lijst
```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
* Alternatief met een sterretje
```

### Geordende lijst
```markdown
1. Eerste stap
2. Tweede stap
   1. Substap A
   2. Substap B
3. Derde stap
```

### Taaklijsten (Checkboxes)
```markdown
- [x] Taak afgerond
- [ ] Taak nog te doen
- [ ] Nog een taak
```

---

## Links en Afbeeldingen

```markdown
<!-- Hyperlink -->
[Bezoek GitHub](https://github.com)

<!-- Link met tooltip -->
[Bezoek GitHub](https://github.com "Ga naar GitHub")

<!-- Afbeelding -->
![Alt tekst voor afbeelding](https://via.placeholder.com/150)

<!-- Afbeelding met link -->
[![Alt tekst](https://via.placeholder.com/150)](https://github.com)
```

---

## Citaten & Blockquotes

```markdown
> Dit is een citaat of blockquote.
> Het kan meerdere regels beslaan.
>> Dit is een genest citaat.
```

---

## Code & Syntax Highlighting

### Inline Code
Gebruik enkele backticks: `const x = 10;`

### Codeblock met Syntax Highlighting
Gebruik drie backticks (\`\`\`) gevolgd door de taal:

````markdown
```javascript
function begroeting(naam) {
    console.log(`Hallo, ${naam}!`);
}
begroeting("Wereld");
```
````

````markdown
```python
def begroeting(naam):
    print(f"Hallo, {naam}!")
```
````

````markdown
```html
<div class="container">
    <h1>Hallo Wereld</h1>
</div>
```
````

---

## Tabellen

Gebruik streepjes (`-`) en kolommen (`|`). Met dubbele punten (`:`) kun je de uitlijning bepalen.

```markdown
| Links uitgelijnd | Gecentreerd | Rechts uitgelijnd |
| :--- | :---: | ---: |
| Cel 1 | Cel 2 | Cel 3 |
| Tekst | Tekst | € 10,00 |
```

---

## GitHub Callouts / Alerts

GitHub ondersteunt speciale accentvakken voor extra attentiewaarde:

```markdown
> [!NOTE]
> Handige informatie om rekening mee te houden.

> [!TIP]
> Een slimme tip voor efficiënter werken.

> [!IMPORTANT]
> Belangrijke informatie die de gebruiker moet weten.

> [!WARNING]
> Waarschuwing voor mogelijke problemen of fouten.

> [!CAUTION]
> Let op: risico op gegevensverlies of krachtige acties.
```

---

## Uitklapbare Secties (Collapsible)

Handig om lange stukken tekst of logs te verbergen:

```markdown
<details>
<summary>Klik hier om meer te lezen</summary>

Dit is de verborgen inhoud die pas zichtbaar wordt als je op het pijltje klikt.
Je kunt hier ook gewone **Markdown** in gebruiken!

</details>
```

---

## Speciale GitHub Kenmerken

| Functie | Syntax | Voorbeeld |
| :--- | :--- | :--- |
| **User Mentions** | `@gebruikersnaam` | @github |
| **Issue / PR Link** | `#nummer` | #42 |
| **Emojis** | `:emojinaam:` | :rocket: :sparkles: :bug: |
| **Voetnoten** | `Hier is tekst[^1]` + `[^1]: Uitleg` | Tekst met referentie |
| **SHA Commit Link** | Volledige of korte hash | `a1b2c3d` |

---
