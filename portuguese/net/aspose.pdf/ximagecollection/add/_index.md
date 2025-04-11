---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Método XImageCollection. Adiciona nova imagem à lista de Imagens. Este método adiciona a imagem como referência ao mesmo PdfObject, o que permite reduzir o tamanho do arquivo
type: docs
weight: 70
url: /pt/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

Adiciona nova imagem à lista de Imagens. Este método adiciona a imagem como referência ao mesmo PdfObject (o que permite reduzir o tamanho do arquivo)

```csharp
public string Add(XImage image)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | XImage | XImage a ser adicionada. |

### Valor de Retorno

Nome da imagem adicionada.

### Veja Também

* class [XImage](../../ximage/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

Adiciona entidade ao final da coleção, para que a entidade possa ser acessada pelo último índice.

```csharp
public string Add(Stream image)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | Stream | Stream contendo dados da imagem (em formato JPEG). |

### Valor de Retorno

Nome da imagem adicionada.

### Veja Também

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

Adiciona entidade ao final da coleção, para que a entidade possa ser acessada pelo último índice.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objeto contendo array de pixels e informações do bitmap (Largura, Altura, Formato de Pixel). |

### Valor de Retorno

Nome da imagem adicionada.

### Veja Também

* class [BitmapInfo](../../bitmapinfo/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

Adiciona entidade ao final da coleção, para que a entidade possa ser acessada pelo último índice.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | Stream | Stream contendo dados da imagem. |
| filterType | ImageFilterType | O tipo de filtro de imagem. |

### Valor de Retorno

Nome da imagem adicionada.

### Veja Também

* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

Adiciona entidade ao final da coleção, para que a entidade possa ser acessada pelo último índice.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | Objeto contendo array de pixels e informações do bitmap (Largura, Altura, Formato de Pixel). |
| filterType | ImageFilterType | O tipo de filtro de imagem. |

### Valor de Retorno

Nome da imagem adicionada.

### Veja Também

* class [BitmapInfo](../../bitmapinfo/)
* enum [ImageFilterType](../../imagefiltertype/)
* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

Adiciona entidade ao final da coleção, para que a entidade possa ser acessada pelo último índice.

```csharp
public void Add(Stream image, int quality)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | Stream | Stream contendo dados da imagem (em formato JPEG). |
| quality | Int32 | Qualidade JPEG. |

### Veja Também

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)