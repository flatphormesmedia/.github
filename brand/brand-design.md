# flatphormesmedia.de — Brand Design Guide

> **Version:** 1.0 · **Stand:** 2026-11-06 · **Status:** Brand-Basis / Living Document
>
> **Leitidee:** *Less bla. More code. ❤️ Dresden.*

## 1. Zweck und Geltungsbereich

Dieses Dokument ist die zentrale gestalterische Referenz für **flatphormesmedia.de**. Es gilt für Websites, Apps, GitHub-Profile und -READMEs, Präsentationen, Dokumentationen, Social Media, Icons, Merchandise und sonstige digitale oder gedruckte Markenmaterialien.

**Priorität:** Wiedererkennbarkeit, Lesbarkeit, technische Klarheit und ein sympathischer, eigenständiger Charakter. Die Regeln beschreiben den Standard, nicht eine Einschränkung jeder kreativen Idee. Abweichungen sind bewusst zu dokumentieren.

## 2. Markenidentität

- **Name / Schreibweise:** `flatphormesmedia.de` (durchgehend klein, einschließlich `.de`).
- **Herkunft:** Dresden, Deutschland.
- **Positionierung:** Software und digitale Ideen mit Leidenschaft, Neugier und Liebe zum Detail.
- **Persönlichkeit:** modern, reduziert, clever, zugänglich, leicht frech; niemals steril oder überladen.
- **Markenwerte:** Einfachheit, Qualität, Kreativität, Pragmatismus, Herzblut.
- **Tonalität:** direkt, kurz, menschlich; Fachbegriffe nur dort, wo sie helfen. Humor sparsam und natürlich.

### Copy und Claims

**Empfohlener kurzer Claim:** `Less bla. More code. ❤️ Dresden.`

**Weitere Optionen:**
- `Code mit Herz. Made in Dresden.`
- `Made in Dresden. Built with ❤️ & ☕. Powered by Code.`
- `Keep it simple. Make it awesome.`

Diese Claims sind Vorschläge, keine Pflichttexte. Aussagen über konkrete Leistungen oder Referenzen müssen vor Veröffentlichung überprüft werden.

## 3. Logo und Markenzeichen

### Bestandteile

1. **Symbol:** ein gleichmäßig proportioniertes, massives, isometrisches 3D-Plus, nach hinten gekippt; harte, dunkle Außenkanten, graue teiltransparente Flächen und sichtbare innere Kanten. Keine Leuchteffekte.
2. **Wortmarke:** `flatphormesmedia.de` in fließender, handschriftlich wirkender Schrift.
3. **Signaturpunkt:** der Punkt vor `de` wird in **Signature Red** hervorgehoben.
4. **Sekundärmotiv:** eine organische, Yin-Yang-artige Trennlinie zwischen hellen und dunklen Flächen, inspiriert vom bisherigen Profilbild/Banner.

### Varianten

| Variante | Verwendung |
|---|---|
| Horizontales Logo (Plus links, Schrift rechts) | Website-Header, README-Banner, Signaturen |
| Gestapeltes Logo (Plus über Schrift) | Profilbilder, quadratische Social-Media-Flächen |
| Symbol allein | Favicons, kleine App-Icons, sehr kleine Avatare |
| Hell-/Dunkel-Komposition | Hero-Banner, Cover und Branding-Flächen |

**Regeln:** Seitenverhältnis des Plus und gleich breite Arme beibehalten; Schriftzug nicht umformulieren oder strecken; Signaturpunkt als einziges kräftiges Farbsignal bevorzugen. Ausreichend Freiraum um Logo und Wortmarke lassen. Keine Glow-, Neon-, 3D-Chrom- oder übermäßigen Schatteneffekte hinzufügen.

**Wichtig:** Die im Chat entwickelten Bilder sind visuelle Referenzen, keine nachweislich vorhandenen Vektormaster. Vor Produktion sind finale SVG-/PNG-Masterdateien zu erstellen und auf echte Transparenz zu prüfen. Ein Schachbrettmuster in einer Vorschau beweist keine Alpha-Transparenz.

## 4. Farbpalette

### Kernfarben

| Token | Name | Hex | Rolle |
|---|---|---|---|
| `--brand-ink` | Obsidian | `#111318` | Primärer dunkler Hintergrund, Text auf hell |
| `--brand-charcoal` | Charcoal | `#252A31` | Dunkle Cards, sekundäre Flächen |
| `--brand-white` | Pure White | `#FFFFFF` | Helle Cards, Text auf dunkel |
| `--brand-soft-white` | Soft White | `#F5F6F7` | Heller Seitenhintergrund |
| `--brand-glass` | Glass Gray | `#C9CDD2` | Plus-Symbol, neutrale Akzente |
| `--brand-red` | Signature Red | `#FF2855` | Logo-Punkt, gezielte Highlights |
| `--brand-red-accessible` | Deep Signature Red | `#C9003D` | Kleinere Texte und Buttons auf hellen Flächen |
| `--brand-muted` | Muted Gray | `#626873` | Sekundärtext auf hell |

**Farbnutzung als Orientierung:** ca. 80 % neutrale Basis, 15 % Grautöne/Glas, 5 % Akzentrot. Keine starre mathematische Quote.

**Zusatzfarben:** Statusfarben für Erfolg, Warnung und Fehler dürfen funktional verwendet werden, gehören aber nicht zur primären Markenidentität. Violett ist **keine** verbindliche Zweit-Markenfarbe.

### Kontrast

- Fließtext nach Möglichkeit mit WCAG-AA-Kontrast gestalten (mindestens 4,5:1); große Schrift und UI-Grafik mindestens 3:1.
- `#FF2855` eignet sich besonders als Akzentpunkt, Linie und große dekorative Fläche, aber nicht automatisch für kleine weiße Button-Beschriftung.
- Für weiße Schrift auf rotem Button oder roten Text auf weißer Fläche die dunklere Variante `#C9003D` bevorzugen und im konkreten Kontext testen.
- Glasgraue Transparenzen dürfen nie die Lesbarkeit von Text beeinträchtigen.

## 5. Dark und Light Mode

| UI-Element | Dark Mode | Light Mode |
|---|---|---|
| Seitenhintergrund | `#111318` | `#F5F6F7` |
| Card / Surface | `#252A31` | `#FFFFFF` |
| Primärtext | `#FFFFFF` | `#111318` |
| Sekundärtext | `#C9CDD2` | `#626873` |
| Akzent / dekorativer Punkt | `#FF2855` | `#FF2855` |
| Textlink / primärer Button | Kontrastgeprüfte Variante | `#C9003D` |

- Beide Modi sind gleichwertige Ausprägungen derselben Marke.
- Systempräferenz als Standard; manueller Wechsel, wenn das Produkt ihn anbietet.
- Keine reinen Schwarz-Weiß-Umkehrungen von Logos ohne Prüfung der Konturen und der Lesbarkeit.
- Yin-Yang-artige Flächen können hell und dunkel verbinden; sie sollen den Inhalt nicht überlagern.

## 6. Typografie

**Prinzip:** Eine klare, moderne Sans-Serif-Schrift für UI und Fließtext; die Handschrift bleibt vor allem der Wortmarke und gelegentlichen kurzen Highlights vorbehalten.

- **UI / Text:** bevorzugt `Inter`, Alternativen `Manrope`, `system-ui`, `Arial`, `sans-serif`.
- **Logo:** vorhandene handschriftliche Wortmarke als Grafikmaster verwenden; nicht mit einer beliebigen Script-Schrift nachbauen.
- **Hierarchie:** prägnante Headlines, kurze Absätze, deutliche Abstufung zwischen Titel, Fließtext und Metadaten.
- **Schriftschnitt:** überwiegend Regular, Medium und Semibold; kein exzessiver Einsatz von Extra-Bold.
- **Schreibweise:** klare Satzschreibung; bewusst kurze englische Claims sind willkommen.

## 7. Layout und UI-Sprache

- Großzügiger Weißraum und eine ruhige, klare Rasterstruktur.
- Wenige, sinnvoll gruppierte Elemente statt dekorativer Überladung.
- Cards mit subtilen Rundungen; Schatten zurückhaltend und nur bei echtem Tiefenbedarf.
- Buttons und Links klar unterscheidbar, Fokuszustände sichtbar und per Tastatur bedienbar.
- Animationen kurz, dezent und funktional; `prefers-reduced-motion` respektieren.
- Iconografie: einfache Linien- oder geometrische Icons mit konsistenter Strichstärke.
- Keine beliebigen Gradients, grellen Farbflächen oder austauschbare Stock-Tech-Bildwelten.

### Beispielhafte Design Tokens (CSS)

```css
:root {
  --brand-ink: #111318;
  --brand-charcoal: #252A31;
  --brand-white: #ffffff;
  --brand-soft-white: #f5f6f7;
  --brand-glass: #c9cdd2;
  --brand-red: #ff2855;
  --brand-red-accessible: #c9003d;
  --brand-muted: #626873;

  --page-bg: var(--brand-soft-white);
  --surface-bg: var(--brand-white);
  --text-primary: var(--brand-ink);
  --text-secondary: var(--brand-muted);
  --action-bg: var(--brand-red-accessible);
  --action-text: var(--brand-white);
  --radius-card: 14px;
  --radius-control: 9px;
  --font-body: Inter, system-ui, Arial, sans-serif;
}

[data-theme="dark"] {
  --page-bg: var(--brand-ink);
  --surface-bg: var(--brand-charcoal);
  --text-primary: var(--brand-white);
  --text-secondary: var(--brand-glass);
  --action-bg: var(--brand-red-accessible);
  --action-text: var(--brand-white);
}
```

## 8. Bildsprache und Grafiken

- Bevorzugt grafische Kompositionen, echte Projekte und glaubwürdige visuelle Details.
- 3D-Plus: geometrisch sauber, symmetrische Arme, dezente Grautransparenz, klare schwarze Kanten.
- Schwarz-Weiß-Wellenmotiv: organisch, hochwertig und zurückhaltend, keine harte Clipart-Yin-Yang-Kopie.
- Signature Red nur als kleiner Blickfang, z. B. Punkt, Cursor, Linie oder ausgewähltes UI-Detail.
- Bildbearbeitung: klare Konturen, keine überzogenen Glow-/HDR-/Neon-Effekte.

## 9. Anwendungen

### Website und Web-Apps
- Horizontalen Logo-Lockup im Header nutzen.
- Dark/Light über semantische Tokens umsetzen.
- CTAs sparsam, aber gut sichtbar; Kontrast und Tastaturbedienung prüfen.
- Den Markencharakter über Typografie, Freiraum, Plus-Symbol und kleine rote Details vermitteln.

### GitHub-Organisation und Repositories
- Profilbild: quadratische oder kreisgeeignete Komposition mit gut erkennbarem Plus; Schriftzug nur, wenn in kleiner Größe lesbar.
- Organisations-README: Banner, kurzer Claim, zwei bis drei Sätze und Link.
- Empfohlener Claim: **Less bla. More code. ❤️ Dresden.**
- Beispielpfad: `.github/profile/README.md`, Banner unter `.github/profile/assets/banner.png`.

### Social Media und Präsentationen
- Wiederkehrende Verwendung von Plus, Wortmarke, Signature Red und Schwarz-Weiß-Welle.
- Textmenge gering halten; Lesbarkeit bei kleinen Bildschirmgrößen prüfen.
- Je Plattform passende Ausschnitte statt verzerrter Mastergrafiken verwenden.

### Druck und Merchandise
- Vereinfachte Einfarb-Version des Plus vorsehen.
- Linienbreiten und Transparenzen für das konkrete Druckverfahren testen.
- Schriftzug und Symbol nicht zu klein setzen.

## 10. Tonalität und Textregeln

**Do:** kurz, pointiert, freundlich, technisch kompetent und menschlich.

**Don't:** leere Superlative, Marketingfloskeln, übertriebene Coolness oder unbelegte Versprechen.

Beispiel:

> We build software with passion, curiosity, and a little bit of magic.  
> Made with ❤️ & ☕ in Dresden.

Englische Kurzclaims dürfen neben deutscher Beschreibung stehen. Für längere Texte die Sprache der Zielgruppe konsequent beibehalten.

## 11. Regeln für Designer und Coding-Agenten

Bei jeder neuen Erstellung für **flatphormesmedia.de**:

1. Dieses Dokument als gestalterische Ausgangsbasis verwenden.
2. Vorhandene Logo-Master und Design-Tokens wiederverwenden, statt Varianten frei zu rekonstruieren.
3. In erster Linie mit neutralen Farben gestalten; Signature Red nur gezielt einsetzen.
4. Dark und Light Mode mitdenken, sofern das Medium beide unterstützt.
5. Lesbarkeit, Kontrast, Responsivität und Zugänglichkeit prüfen.
6. Handschrift nicht als allgemeine UI-Schrift verwenden.
7. Gestalterische Abweichungen bewusst begründen und gegebenenfalls hier nachtragen.
8. Keine nicht belegten Leistungs-, Kunden- oder Produktbehauptungen hinzufügen.

### Prompt-Baustein für neue Aufgaben

> Erstelle [Artefakt] für **flatphormesmedia.de**. Halte dich an `brand-design.md`: reduzierter, hochwertiger Schwarz-Weiß-/Anthrazit-Look, geometrisches grautransparentes 3D-Plus mit dunklen Kanten, handschriftliche Wortmarke, Signature Red `#FF2855` als sparsamer Akzent und bei Bedarf eine organische Hell-Dunkel-Welle. Berücksichtige Kontrast, Lesbarkeit, Einsatzkontext und Dark/Light Mode. Nutze vorhandene Master-Assets statt sie neu zu erfinden.

## 12. Assets, Pflege und offene Entscheidungen

**Empfohlene Struktur:**

```text
brand/
├── brand-design.md
├── assets/
│   ├── logo-horizontal-light.png
│   ├── logo-horizontal-dark.png
│   ├── logo-stacked.png
│   ├── symbol-only.png
│   ├── github-avatar.png
│   └── banner-yinyang.png
└── README.md
```

Die Dateinamen sind Vorschläge, keine Behauptung bereits vorhandener Dateien.

**Noch festzulegen:** finale Vektormaster, exakte Logotyp-Schrift bzw. Pfade, minimale Logogröße, verbindlicher Schutzraum, freigegebene Avatar-Version, druckfähige Farbwerte und rechtliche Markennutzung.

**Änderungsprinzip:** Farbwerte, Logo-Proportionen und andere identitätsstiftende Entscheidungen nur bewusst und versionsgeführt ändern. Neue Anwendungen dürfen ergänzt werden, ohne die Kernidentität zu verwässern.
