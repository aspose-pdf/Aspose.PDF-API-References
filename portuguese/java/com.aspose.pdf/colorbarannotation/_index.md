---
title: "ColorBarAnnotation"
linktitle: "ColorBarAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe representando a anotação ColorBarAnnotation. Propriedade Color ignorada, em vez disso usada a cor ColorsOfCMYK. Na criação, a proporção entre largura e altura determina a orientação."
type: docs
weight: 680
url: /pt/java/com.aspose.pdf/colorbarannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PrinterMarkAnnotation com.aspose.pdf.ColorBarAnnotation, com.aspose.pdf.PrinterMarkAnnotation, com.aspose.pdf.ColorBarAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class ColorBarAnnotation extends PrinterMarkAnnotation
```

Classe que representa a anotação ColorBarAnnotation. A propriedade Color é ignorada, sendo usado o color ColorsOfCMYK. Na criação, a proporção entre largura e altura determina a orientação da anotação – horizontal ou vertical. Em seguida, verifica se o retângulo da anotação está fora da TrimBox e, caso não esteja, ele é deslocado para a posição mais próxima fora da TrimBox, levando em conta a orientação da anotação. É possível reduzir a largura (altura) para que a anotação caiba fora da TrimBox. Se não houver espaço para o layout, a largura/altura pode ser definida como zero (neste caso, a anotação está presente na página, mas não é exibida).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Cria nova anotação ColorBar na página especificada. Padrão ColorsOfCMYK.Black |
| [ColorBarAnnotation](#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-) | Cria nova anotação ColorBar na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz e deslocamento fora da TrimBox, se necessário. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getColorOfCMYK](#getColorOfCMYK--) | Obtém ou define a cor (uma entre ciano, magenta, amarelo, preto) para a qual a anotação está desenhando. |
| [setColorOfCMYK](#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-) | Obtém ou define a cor (uma entre ciano, magenta, amarelo, preto) para a qual a anotação está desenhando. |

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Cria nova anotação ColorBar na página especificada. Padrão ColorsOfCMYK.Black

### ColorBarAnnotation {#ColorBarAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.ColorsOfCMYK-}
Cria nova anotação ColorBar na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Atualiza parâmetros e aparência, de acordo com a transformação da matriz e deslocamento fora da TrimBox, se necessário.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
valor int

### getColorOfCMYK {#getColorOfCMYK--}
```
public final ColorsOfCMYK getColorOfCMYK()
```

Obtém ou define a cor (uma entre ciano, magenta, amarelo, preto) para a qual a anotação está desenhando.

**Returns:**
Elemento ColorsOfCMYK

### setColorOfCMYK {#setColorOfCMYK-com.aspose.pdf.ColorsOfCMYK-}
Obtém ou define a cor (uma entre ciano, magenta, amarelo, preto) para a qual a anotação está desenhando.
