---
Название: IIndexBitmapConverter
second_title: Aspose.PDF для справки по Java API
описание: Этот интерфейс заявлен для настройки алгоритмов квантования.
тип: документы
вес: 435
URL-адрес: /java/com.aspose.pdf/iindexbitmapconverter/
---```
открытый интерфейс IIndexBitmapConverter
```

This interface declared for customization algorithms of quantization. Users can implement their own realization of this algorithms (for example algorithms based on unmanaged code).
## Methods

| Method | Description |
| --- | --- |
| [get1BppImage(BufferedImage src)](#get1BppImage-java.awt.image.BufferedImage-) | Returns 1Bpp bitmap representation |
| [get4BppImage(BufferedImage src)](#get4BppImage-java.awt.image.BufferedImage-) | Returns 4Bpp bitmap representation |
| [get8BppImage(BufferedImage src)](#get8BppImage-java.awt.image.BufferedImage-) | Returns 4Bpp bitmap representation |
### get1BppImage(BufferedImage src) {#get1BppImage-java.awt.image.BufferedImage-}
```
открытый абстрактный BufferedImage get1BppImage (BufferedImage src)
```


Returns 1Bpp bitmap representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Source bitmap. |

**Returns:**
java.awt.image.BufferedImage - Bitmap in 1 bpp image format.
### get4BppImage(BufferedImage src) {#get4BppImage-java.awt.image.BufferedImage-}
```
общедоступный абстрактный BufferedImage get4BppImage (BufferedImage src)
```


Returns 4Bpp bitmap representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Source bitmap. |

**Returns:**
java.awt.image.BufferedImage - Bitmap in 4 bpp image format.
### get8BppImage(BufferedImage src) {#get8BppImage-java.awt.image.BufferedImage-}
```
общедоступный абстрактный BufferedImage get8BppImage (BufferedImage src)
```


Returns 4Bpp bitmap representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | java.awt.image.BufferedImage | Source bitmap. |

**Returns:**
java.awt.image.BufferedImage - Bitmap in 4 bpp image format.