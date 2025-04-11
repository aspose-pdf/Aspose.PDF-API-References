---
title: HtmlSaveOptions.CssClassNamesPrefix
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. Cuando el convertidor PDFtoHTML genera los CSSs de resultado, se generan y utilizan nombres de clase CSS como .stl_01 ... .stl_NN en el CSS de resultado. Esta propiedad permite establecer forzosamente el prefijo del nombre de clase. Por ejemplo, si desea que todos los nombres de clase comiencen con my_prefix_, es decir, sean algo como my_prefix_1 ... my_prefix_NNN, entonces simplemente asigne my_prefix_ a esta propiedad antes de la conversión. Si esta propiedad permanece sin tocar, es decir, se deja null como valor, entonces el convertidor generará los nombres de clase por sí mismo, será algo como .stl_01 ... .stl_NN
type: docs
weight: 250
url: /es/net/aspose.pdf/htmlsaveoptions/cssclassnamesprefix/
---
## Campo HtmlSaveOptions.CssClassNamesPrefix

Cuando el convertidor PDFtoHTML genera los CSSs de resultado, se generan y utilizan nombres de clase CSS (algo como ".stl_01 {}" ... ".stl_NN {}") en el CSS de resultado. Esta propiedad permite establecer forzosamente el prefijo del nombre de clase. Por ejemplo, si desea que todos los nombres de clase comiencen con 'my_prefix_' (es decir, sean algo como 'my_prefix_1' ... 'my_prefix_NNN'), entonces simplemente asigne 'my_prefix_' a esta propiedad antes de la conversión. Si esta propiedad permanece sin tocar (es decir, se deja null como valor), entonces el convertidor generará los nombres de clase por sí mismo (será algo como ".stl_01 {}" ... ".stl_NN {}")

```csharp
public string CssClassNamesPrefix;
```

### Ver También

* clase [HtmlSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)