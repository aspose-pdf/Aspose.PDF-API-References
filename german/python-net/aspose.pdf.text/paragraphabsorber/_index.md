---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein Absorber‑Objekt für Seitenstruktur‑Objekte wie Abschnitte und Absätze dar.<br/>            Führt die Suche nach Abschnitten und Absätzen im Text durch und bietet Zugriff auf Rechtecke und Polygone, die sie im Textkoordinatenraum beschreiben. <br/>            Führt außerdem die Suche nach Textsegmenten durch und bietet Zugriff auf die Suchergebnisse über TextFragments‑Sammlungen, die nach Strukturelementen gruppiert sind."
type: docs
weight: 240
url: /de/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Stellt ein Absorber‑Objekt für Seitenstruktur‑Objekte wie Abschnitte und Absätze dar.<br/>            Führt die Suche nach Abschnitten und Absätzen im Text durch und bietet Zugriff auf Rechtecke und Polygone, die sie im Textkoordinatenraum beschreiben. <br/>            Führt außerdem die Suche nach Textsegmenten durch und bietet Zugriff auf die Suchergebnisse über TextFragments‑Sammlungen, die nach Strukturelementen gruppiert sind.

Der ParagraphAbsorber-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| ParagraphAbsorber() | Initialisiert eine neue Instanz von [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/), die die Suche nach Abschnitten/Absätzen des Dokuments oder der Seite durchführt. |
| ParagraphAbsorber(sections_search_depth) | Initialisiert eine neue Instanz der ParagraphAbsorber-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| page_markups | Liest die Sammlung von [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/), die absorbiert wurden. |
| sections_search_depth | Liest oder setzt den Wert, der angibt, wie oft sequentielle Suchen nach feineren Strukturelementen durchgeführt werden sollen.<br/>            Die Standardsuchtiefe beträgt 3.<br/>            Das bedeutet drei Suchen nach horizontal unterteilten Abschnitten (Überschriften, Absätze usw.) und drei Suchen nach vertikal unterteilten Abschnitten (Spalten). |
| is_multicolumn_paragraphs_allowed | Liefert oder setzt den Wert, der angibt, ob die Anfangszeilen eines nächsten Abschnitts als Fortsetzung des letzten Absatzes eines vorherigen Abschnitts behandelt werden dürfen. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| visit(doc) | Führt die Suche nach Abschnitten und Absätzen im angegebenen [Document](/pdf/python-net/aspose.pdf/document/) durch. |
| visit(page) | Führt die Suche auf der angegebenen [Page](/pdf/python-net/aspose.pdf/page/) durch. |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

