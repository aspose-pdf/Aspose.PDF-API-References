---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: Propriedade HtmlSaveOptions. Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, números válidos de páginas devem ser retirados do intervalo 1...NúmeroDePáginasNoDocumentoConvertido. A ordem de aparecimento das páginas nesta lista não afeta sua ordem nas páginas HTML resultantes - nas páginas resultantes, elas sempre aparecerão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é por padrão), todas as páginas serão convertidas. Se qualquer número de página desta lista estiver fora do intervalo das páginas presentes (1-[quantidadeDePáginasNoDocumento]), uma exceção será lançada.
type: docs
weight: 70
url: /pt/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## Propriedade HtmlSaveOptions.ExplicitListOfSavedPages

Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, números válidos de páginas devem ser retirados do intervalo (1...[NúmeroDePáginasNoDocumentoConvertido]). A ordem de aparecimento das páginas nesta lista não afeta sua ordem nas páginas HTML resultantes - nas páginas resultantes, elas sempre aparecerão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é por padrão), todas as páginas serão convertidas. Se qualquer número de página desta lista estiver fora do intervalo das páginas presentes (1-[quantidadeDePáginasNoDocumento]), uma exceção será lançada.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### Veja Também

* classe [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)