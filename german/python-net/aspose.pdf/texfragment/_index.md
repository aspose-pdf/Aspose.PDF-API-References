---
title: "TeXFragment"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein TeX-Fragment dar."
type: docs
weight: 1510
url: /de/python-net/aspose.pdf/texfragment/
---

## TeXFragment class

Stellt ein TeX-Fragment dar.

Der TeXFragment-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| TeXFragment(text) | Initialisiert eine neue Instanz der TeXFragment-Klasse |
| TeXFragment(text, remove_indents) | Initialisiert eine neue Instanz der TeXFragment-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| vertical_alignment | Liest oder setzt die vertikale Ausrichtung eines Absatzes |
| horizontal_alignment | Liest oder setzt die horizontale Ausrichtung eines Absatzes |
| Rand | Liest oder setzt einen äußeren Rand für den Absatz (für die PDF-Erstellung) |
| is_first_paragraph_in_column | Liest oder setzt einen Bool-Wert, der angibt, ob dieser Absatz in die nächste Spalte gesetzt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_kept_with_next | Liest oder setzt einen Bool-Wert, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_new_page | Liest oder setzt einen Bool-Wert, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird.<br/>            Standard ist false. (für die PDF-Erstellung) |
| is_in_line_paragraph | Liest oder setzt, ob ein Absatz inline ist.<br/>            Standard ist false. (für die PDF-Erstellung) |
| Hyperlink | Liest oder setzt den Fragment-Hyperlink (für den PDF-Generator). |
| z_index | Liest oder setzt einen int‑Wert, der die Z‑Reihenfolge des Diagramms angibt. Ein Diagramm mit größerem ZIndex <br/>            wird über dem Diagramm mit kleinerem ZIndex platziert. ZIndex kann negativ sein. Ein Diagramm mit negativem <br/>            ZIndex wird hinter dem Text auf der Seite platziert. |
| te_x_load_options_of_instance | Holt oder setzt TeXLoadOptions, die zum Laden (und Rendern) von LaTeX in diese Klasseninstanz verwendet werden.<br/>            Bitte verwenden Sie diese, wenn es notwendig ist, eine spezifische Einstellung für den Import von LaTeX für diese oder jene Instanz zu nutzen<br/>             (z. B. wenn diese oder jene Instanz einen bestimmten BasePath für importiertes LaTeX verwenden soll oder einen speziellen Loader für externe Ressourcen nutzen soll)<br/>            Wenn der Parameter standardmäßig (null) ist, werden die Standard‑LaTeX‑Ladeoptionen verwendet. |
| latex_load_options_of_instance | Holt oder setzt TeXLoadOptions, die zum Laden (und Rendern) von LaTeX in diese Klasseninstanz verwendet werden.<br/>            Bitte verwenden Sie diese, wenn es notwendig ist, eine spezifische Einstellung für den Import von LaTeX für diese oder jene Instanz zu nutzen<br/>             (z. B. wenn diese oder jene Instanz einen bestimmten BasePath für importiertes LaTeX verwenden soll oder einen speziellen Loader für externe Ressourcen nutzen soll)<br/>            Wenn der Parameter standardmäßig (null) ist, werden die Standard‑LaTeX‑Ladeoptionen verwendet. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| clone() | Klont Fragment. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

