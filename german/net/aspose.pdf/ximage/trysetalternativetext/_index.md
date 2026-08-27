---
title: "XImage.TrySetAlternativeText"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "XImage-Methode. Legt alternativen Text für ein XImage auf der Seite fest"
type: docs
weight: 180
url: /de/net/aspose.pdf/ximage/trysetalternativetext/
---
## XImage.TrySetAlternativeText method

Legt alternativen Text für ein XImage auf der Seite fest.

```csharp
public bool TrySetAlternativeText(string alternativeText, Page page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alternativeText | String | Der alternative Text, der angegeben werden soll. |
| Seite | Page | Seite, auf der das XImage sich befindet. |

### Rückgabewert

Wahr, wenn alternativeText für XImage gesetzt ist. Falsch, wenn alternativeText für XImage nicht gesetzt ist.

## Hinweise

Die Methode gibt false zurück in den folgenden Fällen: - Das XImage wurde auf der angegebenen Seite nicht gefunden. - Das XImage erscheint mehrmals auf der Seite mit unterschiedlichen Strukturelementen, wodurch unklar ist, welche Instanz den alternativen Text erhalten soll.

### Siehe auch

* class [Page](../../page/)
* class [XImage](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


