# PROMPT – Generate Portable Multimodal Cognitive Artifact

Öppna Canvas och skapa en fristående artefakt i Markdown-format.

## Syfte

Syftet är INTE att skapa dokumentation eller bloggtext.

Syftet är att skapa ett portabelt multimodalt kognitivt objekt som kan:

* importeras i ProMind,
* användas som semantisk retrieval-enhet,
* återanvändas i andra GPT-chattar,
* och automatiskt återaktivera både konceptuell förståelse och visuella resurser.

Artefakten måste därför:

* vara självständig,
* innehålla tillräcklig kontext,
* förklara konceptets innebörd,
* bära den implicita intentionen,
* och innehålla explicita multimodala referenser med hög fidelity.

---

# Instruktioner

Använd hela chatten som grund:

* originalmaterial,
* frågor och svar,
* implicit resonemang,
* redaktionell syntes,
* och tillhörande bildreferenser.

Fokusera på:

* konceptets kärna,
* varför konceptet existerar,
* hur det ska förstås,
* vanliga feltolkningar,
* och hur det används praktiskt inom Prime Arch.

Utgå från att framtida GPT-instans:

* inte har tillgång till originalchatten,
* men kan läsa markdown-artefakten som textobjekt,
* extrahera explicita resurser,
* och åter-rendera dessa resurser i assistant-output.

---

# Viktigt

Bilderna är inte dekorationer.

De är primära pedagogiska och semantiska artefakter.

Artefakten måste därför innehålla:

* Bildtitel
* Kort beskrivning
* Exakt extern URL
* Explicit markdown image embedding

---

# Kritisk fidelity-regel

Använd endast explicita URL:er från materialet.

Du får INTE:

* använda bildsökning,
* använda semantisk bildmatchning,
* använda query-baserad rendering,
* använda alternativa bilder,
* substituera resurser,
* eller förbättra bilderna.

Markdown image embeddings måste använda EXAKT samma URL som anges i artefakten.

---

# Format för varje bild

Använd EXAKT denna struktur:

```md
## Bild 01 — Titel

Beskrivning:
Kort beskrivning av bildens betydelse.

URL:
https://example.com/image.jpg

Renderad bild:

![](https://example.com/image.jpg)
```

---

# Viktig multimodal princip

Markdown image embedding används inte enbart för presentation.

Det fungerar som explicit multimodal resource binding.

Syftet är att framtida GPT-instans ska kunna:

* läsa artefakten som text,
* identifiera explicita resurser,
* och åter-rendera EXAKT samma bilder i assistant-output utan semantisk substitution.

---

# Struktur

Artefakten ska innehålla följande sektioner:

* Titel
* Syfte
* Kärnkoncept
* Visuell modell
* Implicit innebörd
* Praktisk användning
* Vanliga missförstånd
* Relation till Prime Arch
* Kognitiv betydelse
* Bildreferenser
* Källkontext
* Sammanfattande syntes

---

# Formatkrav

Skriv sakligt och koncentrerat.

* Ingen bloggstil.
* Ingen marknadsföring.
* Ingen metakommentar.
* Ingen repetition.

Prioritera semantisk tydlighet framför pedagogisk utfyllnad.

Artefakten ska fungera som ett GPT-läsbart multimodalt kognitivt objekt.

Bilderna ska vara självrenderande via explicit markdown image embedding.
