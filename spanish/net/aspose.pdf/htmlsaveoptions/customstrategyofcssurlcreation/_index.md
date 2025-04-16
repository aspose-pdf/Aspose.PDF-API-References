---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: Campo HtmlSaveOptions. Este campo puede contener un método personalizado que devuelve una URL o plantilla de URL si la generación de múltiples páginas está activada; vea los detalles a continuación sobre el tema CSS como debería ser puesto en el HTML generado. Por ejemplo, si desea que el convertidor ponga una URL específica en lugar del nombre de archivo CSS estándar en el CSS generado, entonces solo debe crear y poner en esta propiedad un método que genere la URL deseada. Si la bandera 'SplitCssIntoPages' está activada, entonces esta estrategia personalizada debe devolver no la URL exacta del CSS, sino más bien una cadena de plantilla que puede resolverse en la URL del CSS de esta o aquella página.
type: docs
weight: 300
url: /es/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## Campo HtmlSaveOptions.CustomStrategyOfCssUrlCreation

Este campo puede contener un método personalizado que devuelve una URL (o plantilla de URL si la generación de múltiples páginas está activada - vea los detalles a continuación) del CSS como debería ser puesto en el HTML generado. Por ejemplo, si desea que el convertidor ponga una URL específica en lugar del nombre de archivo CSS estándar en el CSS generado, entonces solo debe crear y poner en esta propiedad un método que genere la URL deseada. Si la bandera 'SplitCssIntoPages' está activada, entonces esta estrategia personalizada (si la hay) debe devolver no la URL exacta del CSS, sino más bien una cadena de plantilla que (después de la sustitución del marcador de posición con el número de página usando la función string.Format() dentro del convertidor) puede resolverse en la URL del CSS de esta o aquella página. Ejemplos de la cadena de retorno esperada en tal caso son: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### Véase También

* delegado [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* clase [HtmlSaveOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)