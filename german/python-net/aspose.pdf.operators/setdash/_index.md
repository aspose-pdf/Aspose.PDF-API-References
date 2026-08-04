---
title: "SetDash"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die den d-Operator darstellt (Linien-Strichmuster festlegt)."
type: docs
weight: 580
url: /de/python-net/aspose.pdf.operators/setdash/
---

## SetDash class

Klasse, die den d-Operator darstellt (Linien-Strichmuster festlegt).

Der SetDash-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| SetDash(pattern, phase) | Initialisiert eine neue Instanz der SetDash-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Index | Operatorindex in der Liste der Seitenoperatoren. |
| pattern | Strichmuster. Die Elemente des Arrays müssen Zahlen sein, die die Längen von abwechselnden Strichen und Lücken angeben.<br/>            Im Falle eines Arrays mit einem Element sind die Strich- und Lückenlängen gleich. |
| phase | Strichphase. Bevor ein Pfad gezeichnet wird, muss das Stricharray durchlaufen werden, wobei die Längen der Striche und Lücken addiert werden.<br/>            Wenn die akkumulierte Länge dem durch die Strichphase angegebenen Wert entspricht, beginnt das Zeichnen des Pfades,<br/>            und das Stricharray wird ab diesem Punkt zyklisch verwendet. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| accept(visitor) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| is_text_show_operator(op) | Bestimmt, ob der Operator ein Operator ist, der für die Textausgabe verantwortlich ist (Tj, TJ usw.) |

### Siehe auch

* namespace [aspose.pdf.operators](/pdf/python-net/aspose.pdf.operators/)
* assembly [Aspose.PDF](/pdf/python-net/)

