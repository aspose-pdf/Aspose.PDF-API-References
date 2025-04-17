---
title: Document.IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del documento. Ottiene o imposta il flag per ignorare gli errori nei file sorgente. Quando le pagine del documento sorgente vengono copiate nel documento di destinazione, il processo di copia si interrompe con un'eccezione se alcuni oggetti nei file sorgente sono corrotti quando questo flag è falso. Se questo flag è impostato su true, allora gli oggetti corrotti verranno sostituiti con valori vuoti. Per impostazione predefinita true
type: docs
weight: 270
url: /it/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Proprietà Document.IgnoreCorruptedObjects

Ottiene o imposta il flag per ignorare gli errori nei file sorgente. Quando le pagine del documento sorgente vengono copiate nel documento di destinazione, il processo di copia si interrompe con un'eccezione se alcuni oggetti nei file sorgente sono corrotti quando questo flag è falso. esempio: dest.Pages.Add(src.Pages); Se questo flag è impostato su true, allora gli oggetti corrotti verranno sostituiti con valori vuoti. Per impostazione predefinita: true.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### Vedi Anche

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)