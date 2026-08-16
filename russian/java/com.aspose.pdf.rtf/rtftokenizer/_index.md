---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс, предназначенный для извлечения потокового содержимого RTF в виде набора токенов."
type: docs
weight: 40
url: /ru/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Класс, предназначенный для извлечения потокового содержимого RTF в виде набора токенов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Методы

| Метод | Описание |
| --- | --- |
| [readNextToken](#readNextToken--) | Читает входной поток и возвращает следующий токен. |
| [skip](#skip-int-) | Потребляет и отбрасывает указанное количество символов из входного потока. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Читает входной поток и возвращает следующий токен.

### skip {#skip-int-}
```
public final void skip(int count)
```

Потребляет и отбрасывает указанное количество символов из входного потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| количество |  | Количество символов для пропуска. |
