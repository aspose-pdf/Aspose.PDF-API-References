---
title: Page.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Método da página. Adiciona imagem na página e a localiza no meio do retângulo especificado, mantendo a proporção das imagens
type: docs
weight: 350
url: /pt/net/aspose.pdf/page/addimage/
---
## AddImage(Stream, Rectangle, Rectangle, bool) {#addimage}

Adiciona imagem na página e a localiza no meio do retângulo especificado, mantendo a proporção da imagem.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, Rectangle bbox = null, 
    bool autoAdjustRectangle = true)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | O fluxo da imagem. |
| imageRect | Rectangle | A posição da imagem. |
| bbox | Rectangle | Bbox da imagem. |
| autoAdjustRectangle | Boolean | Ajusta a imagem no centro do retângulo de entrada. |

### Veja Também

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Stream, Rectangle, Rectangle) {#addimage_3}

Adiciona imagem pesquisável na página e a localiza no meio do retângulo especificado, mantendo a proporção da imagem.

```csharp
public void AddImage(string hocr, Stream imageStream, Rectangle imageRect, Rectangle bbox = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hocr | String | O hocr da imagem. |
| imageStream | Stream | O fluxo da imagem. |
| imageRect | Rectangle | A posição da imagem. |
| bbox | Rectangle | O bbox da imagem. |

### Veja Também

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, Rectangle, int, int, bool, Rectangle) {#addimage_1}

Adiciona imagem na página e a coloca dependendo da posição do retângulo da imagem.

```csharp
public void AddImage(Stream imageStream, Rectangle imageRect, int imageWidth, int imageHeight, 
    bool saveImageProportions, Rectangle bbox = null)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imageStream | Stream | O fluxo da imagem. |
| imageRect | Rectangle | A posição padrão da imagem na página. |
| imageWidth | Int32 | A largura da imagem. |
| imageHeight | Int32 | A altura da imagem. |
| saveImageProportions | Boolean | Se a flag estiver definida como verdadeira, a imagem será colocada na posição do retângulo; caso contrário, o tamanho do retângulo se tornará igual ao tamanho da imagem. |
| bbox | Rectangle | O bbox da imagem. |

### Veja Também

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, Rectangle) {#addimage_2}

Adiciona imagem na página e a localiza no meio do retângulo especificado, mantendo a proporção da imagem.

```csharp
public void AddImage(string imagePath, Rectangle rectangle)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| imagePath | String | O caminho para a imagem. |
| rectangle | Rectangle | A posição da imagem. |

### Veja Também

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)