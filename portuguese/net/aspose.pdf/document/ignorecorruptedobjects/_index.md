---
title: Document.IgnoreCorruptedObjects
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do documento. Obtém ou define a flag de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com uma exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando essa flag for falsa. Se essa flag estiver definida como verdadeira, então objetos corrompidos serão substituídos por valores vazios. Por padrão, verdadeiro.
type: docs
weight: 270
url: /pt/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Propriedade Document.IgnoreCorruptedObjects

Obtém ou define a flag de ignorar erros em arquivos de origem. Quando páginas do documento de origem são copiadas para o documento de destino, o processo de cópia é interrompido com uma exceção se alguns objetos nos arquivos de origem estiverem corrompidos quando essa flag for falsa. exemplo: dest.Pages.Add(src.Pages); Se essa flag estiver definida como verdadeira, então objetos corrompidos serão substituídos por valores vazios. Por padrão: verdadeiro.

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### Veja Também

* classe [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)