---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Metadata-Klasse. Bietet Zugriff auf den XMP-Metadatenstrom
type: docs
weight: 6950
url: /de/net/aspose.pdf/metadata/
---
## Metadatenklasse

Bietet Zugriff auf den XMP-Metadatenstrom.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Gibt das Wörterbuch der Erweiterungsfelder zurück. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Überprüft, ob die Sammlung eine feste Größe hat. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Überprüft, ob die Sammlung schreibgeschützt ist. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Überprüft, ob die Sammlung synchronisiert ist. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Ruft Daten aus den Metadaten ab oder setzt sie. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Gibt die Sammlung der Metadaten-Schlüssel zurück. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Gibt den Namespace-Manager zurück. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Gibt das Synchronisationsobjekt der Sammlung zurück. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Gibt die Werte in den Metadaten zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Fügt ein Paar mit Schlüssel und Wert in das Wörterbuch ein. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Fügt einen Wert zu den Metadaten hinzu. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Fügt eine PDF-Erweiterung zu den Metadaten hinzu. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Fügt einen Wert zu den Metadaten hinzu. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Löscht die Metadaten. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Überprüft, ob das angegebene Schlüssel-Wert-Paar im Wörterbuch enthalten ist. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Überprüft, ob der Schlüssel in den Metadaten enthalten ist. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Bestimmt, ob dieses Wörterbuch den angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Gibt den Enumerator des Wörterbuchs zurück. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Gibt die Namespace-URI nach Präfix zurück. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Gibt das Präfix nach Namespace-URI zurück. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Registriert die Namespace-URI. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Registriert die Namespace-URI. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Entfernt das Schlüssel/Wert-Paar aus der Sammlung. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Entfernt den Eintrag aus den Metadaten. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Versucht, den Schlüssel im Wörterbuch zu finden und gibt den Wert zurück, wenn er gefunden wurde. |

### Siehe auch

* Klasse [XmpValue](../xmpvalue/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)