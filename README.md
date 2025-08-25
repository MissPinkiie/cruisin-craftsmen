# ⚙️ Cruisin Craftsmen Mechanic – Berekentool

Deze tool is gemaakt voor **aankoop & recycling van materialen**.  
Het draait via **GitHub Pages** zodat iedereen hem eenvoudig kan gebruiken in de browser.

---

## 📂 Bestandsstructuur

- `index.html` → bevat **HTML + CSS + JavaScript** (alles-in-één bestand).  
- `logo.png` → logo dat in de header wordt getoond.  

---

## 🔧 Aanpassen van items & prijzen

### 1. Visuele rij toevoegen (HTML)
In de juiste `<div class="grid">`-sectie een nieuwe rij toevoegen:

```html
<div><label for="hout">Hout</label><div class="price">€15 / stuk</div></div>
<div><input id="hout" type="number" min="0" value="0"></div>
<div class="sub">€<span id="sub-hout">0</span></div>
