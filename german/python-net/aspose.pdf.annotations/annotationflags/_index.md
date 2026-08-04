---
title: "AnnotationFlags"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Eine Menge von Flags, die verschiedene Eigenschaften der Annotation spezifizieren."
type: docs
weight: 930
url: /de/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Eine Menge von Flags, die verschiedene Eigenschaften der Annotation spezifizieren.

## Members
| Member-Name | Beschreibung |
| :- | :- |
| DEFAULT | Standardwert. |
| INVISIBLE | Wenn gesetzt, wird die Annotation nicht angezeigt, wenn sie nicht zu einem der Standard‑Annotation‑Typen gehört<br/> und kein Annotation‑Handler verfügbar ist. Wenn nicht gesetzt, wird eine solche unbekannte Annotation angezeigt<br/> indem ein Erscheinungs‑Stream verwendet wird, der im Erscheinungs‑Dictionary angegeben ist, falls vorhanden. |
| HIDDEN | Wenn gesetzt, wird die Annotation weder angezeigt noch gedruckt und sie kann nicht mit dem Benutzer interagieren,<br/> unabhängig von ihrem Annotationstyp oder ob ein Annotation‑Handler verfügbar ist.<br/> In Fällen, in denen der Bildschirmplatz begrenzt ist, kann die Möglichkeit, Annotationen selektiv zu verbergen und anzuzeigen,<br/> in Kombination mit Erscheinungs‑Streams verwendet werden, um zusätzliche Popup‑Informationen darzustellen,<br/> die in ihrer Funktion Online‑Hilfesystemen ähneln. |
| PRINT | Wenn gesetzt, wird die Annotation beim Drucken der Seite ausgedruckt. Wenn nicht gesetzt, wird die Annotation niemals gedruckt,<br/> unabhängig davon, ob sie auf dem Bildschirm angezeigt wird. Dies kann beispielsweise nützlich sein für Annotationen,<br/> die interaktive Schaltflächen darstellen, da diese auf der gedruckten Seite keinen sinnvollen Zweck erfüllen würden. |
| NO_ZOOM | Wenn gesetzt, wird das Erscheinungsbild der Annotation nicht an die Vergrößerung der Seite angepasst.<br/> Die Position der Annotation auf der Seite (definiert durch die obere linke Ecke ihres Annotationsrechtecks)<br/> bleibt unverändert, unabhängig von der Seitenvergrößerung. |
| NO_ROTATE | Wenn gesetzt, wird das Erscheinungsbild der Annotation nicht an die Drehung der Seite angepasst.<br/> Die obere linke Ecke des Annotationsrechtecks bleibt an einer festen Position auf der Seite,<br/> unabhängig von der Seitendrehung. |
| NO_VIEW | Wenn gesetzt, wird die Annotation nicht auf dem Bildschirm angezeigt und kann nicht mit dem Benutzer interagieren.<br/> Die Annotation kann gedruckt werden (abhängig von der Einstellung des Print‑Flags),<br/> sollte jedoch für die Anzeige auf dem Bildschirm und die Benutzerinteraktion als verborgen betrachtet werden. |
| READ_ONLY | Wenn gesetzt, darf die Annotation nicht mit dem Benutzer interagieren. Die Annotation kann angezeigt<br/> oder gedruckt werden (abhängig von den Einstellungen der NoView‑ und Print‑Flags), darf jedoch nicht auf Mausklicks reagieren oder ihr Erscheinungsbild bei Mausbewegungen ändern. Dieses Flag wird bei Widget‑Annotationen ignoriert;<br/> seine Funktion wird durch das ReadOnly‑Flag des zugehörigen Formularfeldes übernommen. |
| LOCKED | Wenn gesetzt, darf die Annotation nicht vom Benutzer gelöscht oder ihre Eigenschaften (einschließlich Position und Größe)<br/> geändert werden. Dieses Flag schränkt jedoch nicht die Änderungen am Inhalt der Annotation ein,<br/> wie zum Beispiel den Wert eines Formularfeldes. |
| TOGGLE_NO_VIEW | Wenn gesetzt, wird die Interpretation des NoView‑Flags für bestimmte Ereignisse umgekehrt.<br/> Ein typischer Anwendungsfall ist eine Annotation, die nur angezeigt wird, wenn der Mauszeiger darüber gehalten wird. |
| LOCKED_CONTENTS | Wenn gesetzt, dürfen die Inhalte der Anmerkung nicht vom Benutzer geändert werden.<br/>            Dieses Flag schränkt das Löschen der Anmerkung oder Änderungen anderer Anmerkungs‑Eigenschaften nicht ein,<br/>            wie Position und Größe. |

### Siehe auch

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

