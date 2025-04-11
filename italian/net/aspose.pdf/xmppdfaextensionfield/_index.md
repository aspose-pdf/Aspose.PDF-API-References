---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XmpPdfAExtensionField. Questo schema descrive un campo in un tipo strutturato. È molto simile allo schema del tipo di valore della proprietà PDF/A, ma definisce un campo in una struttura invece di una proprietà. URI dello schema namespace http//www.aiim.org/pdfa/ns/field Prefisso dello schema namespace richiesto pdfaField
type: docs
weight: 11440
url: /it/net/aspose.pdf/xmppdfaextensionfield/
---
## Classe XmpPdfAExtensionField

Questo schema descrive un campo in un tipo strutturato. È molto simile allo schema del tipo di valore della proprietà PDF/A, ma definisce un campo in una struttura invece di una proprietà. URI dello schema namespace: http://www.aiim.org/pdfa/ns/field# Prefisso dello schema namespace richiesto: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | Inizializza l'oggetto. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | Ottiene la descrizione. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | Nome del campo. I nomi dei campi devono essere nomi di elementi XML validi. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | Ottiene o imposta il valore. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | Tipo di valore del campo, tratto dalla specifica XMP 2004, o uno schema di estensione del tipo di valore PDF/A incorporato. Nomi di tipo XMP predefiniti o nomi di tipi personalizzati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | Restituisce l'elenco degli elementi xml che rappresentano il campo nell'albero xml. |

### Vedi Anche

* classe [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)