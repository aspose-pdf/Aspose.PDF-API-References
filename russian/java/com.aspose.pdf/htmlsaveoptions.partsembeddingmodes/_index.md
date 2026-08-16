---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Справочник API Aspose.PDF для Java"
description: "Этот enum перечисляет возможные режимы встраивания файлов, на которые ссылается HTML. Он позволяет контролировать, будут ли связанные файлы (HTML, шрифты, изображения, CSS) встроены в основной."
type: docs
weight: 2130
url: /ru/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

Этот enum перечисляет возможные режимы встраивания файлов, на которые ссылается HTML. Он позволяет контролировать, будут ли связанные файлы (HTML, шрифты, изображения, CSS) встроены в основной HTML‑файл или будут созданы как отдельные бинарные сущности.

## Поля

| Поле | Описание |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Принудительно встраивает все ссылки на файлы (Css, Images, Fonts) в сгенерированную разметку HTML (т. е. непосредственно в HTML). Этот подход генерирует один файл HTML, но общий размер вывода становится больше (из‑за использования Base64‑кодирования бинарных данных), и не все браузеры (особенно устаревшие) успешно обрабатывают бинарные данные, встроенные в HTML. Однако он позволяет получить HTML, содержащий весь результат, без дополнительных файлов. |
| [EmbedCssOnly](#EmbedCssOnly) | Принудительно отделяет все ссылки на файлы, кроме CSS (изображения и шрифты). Т. е. CSS будет встроен в результирующий HTML, а все остальные ссылки на файлы (изображения и шрифты) будут обработаны как внешние части. Он генерирует HTML, подходящий для широкого набора браузеров. |
| [NoEmbedding](#NoEmbedding) | Принудительно отделяет ссылки на файлы (Css, Images, Fonts). Этот подход генерирует набор файлов, но общий размер вывода становится меньше (поскольку Base64‑кодирование бинарных данных не используется). Кроме того, такой подход генерирует HTML, подходящий для широкого набора браузеров. |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

Принудительно встраивает все ссылки на файлы (Css, Images, Fonts) в сгенерированную разметку HTML (т. е. непосредственно в HTML). Этот подход генерирует один файл HTML, но общий размер вывода становится больше (из‑за использования Base64‑кодирования бинарных данных), и не все браузеры (особенно устаревшие) успешно обрабатывают бинарные данные, встроенные в HTML. Однако он позволяет получить HTML, содержащий весь результат, без дополнительных файлов.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

Принудительно отделяет все ссылки на файлы, кроме CSS (изображения и шрифты). Т. е. CSS будет встроен в результирующий HTML, а все остальные ссылки на файлы (изображения и шрифты) будут обработаны как внешние части. Он генерирует HTML, подходящий для широкого набора браузеров.

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

Принудительно отделяет ссылки на файлы (Css, Images, Fonts). Этот подход генерирует набор файлов, но общий размер вывода становится меньше (поскольку Base64‑кодирование бинарных данных не используется). Кроме того, такой подход генерирует HTML, подходящий для широкого набора браузеров.
