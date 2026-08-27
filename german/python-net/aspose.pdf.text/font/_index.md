---
title: "Font"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt ein Schriftart-Objekt dar."
type: docs
weight: 100
url: /de/python-net/aspose.pdf.text/font/
---

## Font class

Stellt ein Schriftart-Objekt dar.

Der Typ Font stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| font_name | Liefert den Schriftartnamen des [Font](/pdf/python-net/aspose.pdf.text/font/)‑Objekts. |
| decoded_font_name | Manchmal können PDF‑Schriften (häufig chinesische/japanische/koreanische Schriften) einen spezifischen Schriftartnamen haben.<br/>            Dieser Name ist der Wert der PDF‑Schrift‑Eigenschaft "BaseFont" und kann manchmal<br/>            in hexadezimaler Form dargestellt werden. Wird dieser Name direkt gelesen, kann er<br/>            in nicht lesbarer Form vorliegen. Um eine lesbare Form zu erhalten, muss der Schriftname nach<br/>            für diese Schrift spezifischen Regeln dekodiert werden. <br/>            Diese Eigenschaft gibt den dekodierten Schriftartnamen zurück, verwenden Sie sie also in Fällen, in denen Sie auf einen nicht lesbaren [font_name](/pdf/python-net/aspose.pdf.text/font/) stoßen.<br/>            Hat die Eigenschaft [font_name](/pdf/python-net/aspose.pdf.text/font/) eine lesbare Form, ist diese Eigenschaft dieselbe wie<br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), sodass Sie diese Eigenschaft in allen Fällen verwenden können, in denen Sie den Schriftartnamen in lesbarer Form benötigen. |
| base_font | Liefert den BaseFont‑Wert des PDF‑Schriftobjekts. Auch bekannt als PostScript‑Name der Schrift. |
| is_embedded | Liefert oder setzt einen Wert, der angibt, ob die Schrift eingebettet ist.<br/>            Schrift basierend auf IFont wird automatisch als Subset erstellt und eingebettet |
| is_subset | Liefert oder setzt einen Wert, der angibt, ob die Schrift ein Subset ist.<br/>             Schrift basierend auf IFont wird automatisch als Subset erstellt und eingebettet |
| is_accessible | Gibt an, ob die Schriftart im System vorhanden (installiert) ist. |
| font_options | Nützliche Eigenschaften, um das Verhalten von Schriftarten anzupassen |
## Methoden
| Name | Beschreibung |
| :- | :- |
| get_last_font_embedding_error() | Ziel dieser Methode – die Fehlermeldung zurückzugeben, wenn ein Versuch<br/>            die Schriftart einzubetten fehlgeschlagen ist. Gibt es keine Fehlersituationen, wird ein leerer String zurückgegeben. |
| save(stream) | Speichert die Schriftart in den Stream.<br/>            Beachten Sie, dass die Schriftart im Zwischformat TTF gespeichert wird, das nur in einer konvertierten Kopie des Originaldokuments verwendet werden soll.<br/>            Die Schriftartdatei ist nicht für die Verwendung außerhalb des ursprünglichen Dokumentkontexts vorgesehen. |
| measure_string(str, font_size) | Misst die Zeichenkette. |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

