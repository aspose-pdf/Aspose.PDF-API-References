---
title: HtmlSaveOptions.CssClassNamesPrefix
second_title: Aspose.PDF for .NET API Reference
description: Champ HtmlSaveOptions. Lorsque le convertisseur PDFtoHTML génère des CSS de résultat, des noms de classes CSS tels que .stl_01 ... .stl_NN sont générés et utilisés dans le CSS de résultat. Cette propriété permet de définir de manière forcée le préfixe du nom de classe. Par exemple, si vous souhaitez que tous les noms de classes commencent par my_prefix_, c'est-à-dire quelque chose comme my_prefix_1 ... my_prefix_NNN, il suffit d'assigner my_prefix_ à cette propriété avant la conversion. Si cette propriété reste intacte, c'est-à-dire que null sera laissé comme valeur, alors le convertisseur générera lui-même les noms de classes, ce qui sera quelque chose comme .stl_01 ... .stl_NN
type: docs
weight: 250
url: /fr/net/aspose.pdf/htmlsaveoptions/cssclassnamesprefix/
---
## Champ HtmlSaveOptions.CssClassNamesPrefix

Lorsque le convertisseur PDFtoHTML génère des CSS de résultat, des noms de classes CSS (quelque chose comme ".stl_01 {}" ... ".stl_NN {}") sont générés et utilisés dans le CSS de résultat. Cette propriété permet de définir de manière forcée le préfixe du nom de classe. Par exemple, si vous souhaitez que tous les noms de classes commencent par 'my_prefix_' (c'est-à-dire quelque chose comme 'my_prefix_1' ... 'my_prefix_NNN'), il suffit d'assigner 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste intacte (c'est-à-dire que null sera laissé comme valeur), alors le convertisseur générera lui-même les noms de classes (ce qui sera quelque chose comme ".stl_01 {}" ... ".stl_NN {}")

```csharp
public string CssClassNamesPrefix;
```

### Voir aussi

* classe [HtmlSaveOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)