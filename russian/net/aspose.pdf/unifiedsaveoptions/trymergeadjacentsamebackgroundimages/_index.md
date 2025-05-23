---
title: UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages
second_title: Aspose.PDF for .NET API Reference
description: Поле UnifiedSaveOptions. Иногда PDF-файлы содержат фоновое изображение страниц или ячеек таблицы, состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов, например, MsWord для формата DOCS, иногда генерируют видимые границы между частями фоновых изображений, так как их методы сглаживания краев изображений отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, пожалуйста, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.
type: docs
weight: 40
url: /ru/net/aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/
---
## Поле UnifiedSaveOptions.TryMergeAdjacentSameBackgroundImages

Иногда PDF-файлы содержат фоновое изображение (страниц или ячеек таблицы), состоящее из нескольких одинаковых плиточных фоновых изображений, расположенных рядом друг с другом. В таком случае рендереры целевых форматов (например, MsWord для формата DOCS) иногда генерируют видимые границы между частями фоновых изображений, так как их методы сглаживания краев изображений (антиалиасинг) отличаются от Acrobat Reader. Если кажется, что экспортированный документ содержит такие видимые границы между частями одинаковых фоновых изображений, пожалуйста, попробуйте использовать эту настройку, чтобы избавиться от этого нежелательного эффекта. ВНИМАНИЕ! Эта оптимизация качества обычно существенно замедляет конвертацию, поэтому, пожалуйста, используйте эту опцию только тогда, когда это действительно необходимо.

```csharp
public bool TryMergeAdjacentSameBackgroundImages;
```

### См. также

* класс [UnifiedSaveOptions](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)