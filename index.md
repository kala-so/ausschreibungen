---
layout: default
title: KaLa
---

<div class="intro">
  <h2>Mach mit beim KaLa 2028!</h2>
  <p> Für das Kantonslager 2028 suchen wir viele engagierte und motivierte Menschen, die Lust haben, bei
  der Vorbereitung und Umsetzung mitzuwirken.
  Die ersten Arbeiten starten ab sofort – und vielleicht bist du bald schon mit dabei!
  </p>
</div>

<h2>🔍 Offene Aufgaben – Wo kannst du mitanpacken?</h2>
<p>Hier findest du laufend neue Aufgaben in verschiedensten Bereichen.
Schau regelmässig vorbei, such dir eine passende Aufgabe aus und werde Teil des Teams!<br>
👉 Tipp: Schnapp dir deine liebsten Pfadi-Freund*innen und meldet euch gemeinsam – denn zusammen
macht die Vorbereitung noch mehr Spass und wird zu einem weiteren unvergesslichen Pfadi-Abenteuer.</p>

<h2>⭐ Das erwartet dich</h3>
Alle Mitarbeitenden profitieren von einem aktiven und lebendigen Planungsprozess:

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1em;margin-bottom:2em;">
  <div style="background:#eaf3e6;padding:1em;border-radius:0.7em;"> gemeinsame Co-Working-Tage</div>
  <div style="background:#eaf3e6;padding:1em;border-radius:0.7em;"> ein jährliches Planungsweekend</div>
  <div style="background:#eaf3e6;padding:1em;border-radius:0.7em;"> Austausch und Zusammenarbeit mit allen Teams</div>
  <div style="background:#eaf3e6;padding:1em;border-radius:0.7em;"> ein abwechslungsreiches FUN-Programm</div>
  <div style="background:#eaf3e6;padding:1em;border-radius:0.7em;"> gutes Essen</div>
  <div style="background:#eaf3e6;padding:1em;border-radius:0.7em;"> viele schöne Pfadi-Momente</div>
</div>

<p>Gemeinsam gestalten wir das KaLa 2028 – kreativ, bunt und unvergesslich.</p>

<h2>❓ Fragen?</h3>
<p>Bei Fragen zu den offenen Aufgaben oder zur Mitarbeit melde dich jederzeit bei der Ressortleitung.<br>
Wir freuen uns auf dich!</p>

<p>Klicke auf ein Ressort, um die Rollen anzuzeigen.</p>

<details>
<summary><b>📡 KOMMUNIKATION</b></summary>

<div class="content">
{% capture komm %}{% include 10_komm.md %}{% endcapture %}
{{ komm | markdownify }}
</div>
</details>

<details>

<summary><b>⛑️ SANITÄT & SICHERHEIT</b></summary>

<div class="content">
{% capture sansi %}{% include 20_sansi.md %}{% endcapture %}
{{ sansi | markdownify }}
</div>
</details>


<details>
<summary><b>🎯 PROGRAMM</b></summary>

<div class="content">
{% capture pro %}{% include 30_pro.md %}{% endcapture %}
{{ pro | markdownify }}
</div>
</details>


<details>
<summary><b>🚚 LOGISTIK</b></summary>

<div class="content">
{% capture log %}{% include 40_log.md %}{% endcapture %}
{{ log | markdownify }}
</div>
</details>


<details>
<summary><b>🌟 STAFF & EINHEITEN</b></summary>

<div class="content">
{% capture staein %}{% include 50_staein.md %}{% endcapture %}
{{ staein | markdownify }}
</div>
</details>


<details>
<summary><b>💰 FINANZEN</b></summary>


<div class="content">
{% capture fin %}{% include 60_fin.md %}{% endcapture %}
{{ fin | markdownify }}
</div>
</details>
