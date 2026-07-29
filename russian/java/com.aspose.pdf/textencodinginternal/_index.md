---
title: "java.lang.Object, com.aspose.pdf.TextEncodingInternal"
linktitle: "java.lang.Object, com.aspose.pdf.TextEncodingInternal"
second_title: "Справочник API Aspose.PDF для Java"
description:
type: docs
weight: 5030
url: /ru/java/com.aspose.pdf/textencodinginternal/
---
**Inheritance:**
Внутренний конструктор

```
public final class TextEncodingInternal extends Object
```



## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextEncodingInternal](#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-) | Получает кодировку для набора символов ASCII (7‑бит). |

## Методы

| Метод | Описание |
| --- | --- |
| [getASCII](#getASCII--) | Получает кодировку для формата UTF-16, использующего порядок байтов big endian. |
| [getBigEndianUnicode](#getBigEndianUnicode--) | Получает кодировку для текущей ANSI‑страницы кодов операционной системы. |
| [getDefault](#getDefault--) | Возвращает кодировку, связанную с указанным именем кодовой страницы. |
| [getEncoding](#getEncoding-java.lang.String-) | Внутренний метод |
| [getInternalFormat](#getInternalFormat--) | Получает массив с именами кодировок. |
| [getNames](#getNames--) | При переопределении в производном классе декодирует все байты в указанном массиве байтов в строку. |
| [getString](#getString-byte:A-) | Получает кодировку для формата UTF-16, использующего порядок байтов little endian. |
| [getUnicode](#getUnicode--) | Получает кодировку для формата UTF-32, использующего порядок байтов little endian. |
| [getUTF32](#getUTF32--) | Получает кодировку для формата UTF-7. |
| [getUTF32BE](#getUTF32BE--) | Получает кодировку для текущей ANSI‑страницы кодов операционной системы. |
| [getUTF7](#getUTF7--) | Получает кодировку для формата UTF-8. |
| [getUTF8](#getUTF8--) | Получает кодировку для формата UTF-8. |
| [getUTF8Unmarked](#getUTF8Unmarked--) | Получает кодировку для формата UTF-8 Unmarked. |
| [toString](#toString-com.aspose.pdf.TextEncodingInternal-) | Возвращает строку, представляющую текущий объект. |

### TextEncodingInternal {#TextEncodingInternal-com.aspose.ms.System.Text.Encoding-}
Получает кодировку для набора символов ASCII (7‑бит).

### getASCII {#getASCII--}
```
public static TextEncodingInternal getASCII()
```

Получает кодировку для формата UTF-16, использующего порядок байтов big endian.

**Returns:**
Экземпляр TextEncodingInternal

### getBigEndianUnicode {#getBigEndianUnicode--}
```
public static TextEncodingInternal getBigEndianUnicode()
```

Получает кодировку для текущей ANSI‑страницы кодов операционной системы.

**Returns:**
Экземпляр TextEncodingInternal

### getDefault {#getDefault--}
```
public static TextEncodingInternal getDefault()
```

Возвращает кодировку, связанную с указанным именем кодовой страницы.

**Returns:**
Экземпляр TextEncodingInternal

### getEncoding {#getEncoding-java.lang.String-}
Внутренний метод

### getInternalFormat {#getInternalFormat--}
```
public com.aspose.ms.System.Text.Encoding getInternalFormat()
```

Получает массив с именами кодировок.

**Returns:**
Внутренний объект

### getNames {#getNames--}
```
public static String [] getNames()
```

При переопределении в производном классе декодирует все байты в указанном массиве байтов в строку.

**Returns:**
Массив строк

### getString {#getString-byte:A-}
```
public String getString(byte[] value)
```

Получает кодировку для формата UTF-16, использующего порядок байтов little endian.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Массив байтов, содержащий последовательность байтов для декодирования. |

**Returns:**
Строка, содержащая результаты декодирования указанной последовательности байтов.

### getUnicode {#getUnicode--}
```
public static TextEncodingInternal getUnicode()
```

Получает кодировку для формата UTF-32, использующего порядок байтов little endian.

**Returns:**
Экземпляр TextEncodingInternal

### getUTF32 {#getUTF32--}
```
public static TextEncodingInternal getUTF32()
```

Получает кодировку для формата UTF-7.

**Returns:**
Экземпляр TextEncodingInternal

### getUTF32BE {#getUTF32BE--}
```
public static TextEncodingInternal getUTF32BE()
```

Получает кодировку для текущей ANSI‑страницы кодов операционной системы.

**Returns:**
Экземпляр TextEncodingInternal

### getUTF7 {#getUTF7--}
```
public static TextEncodingInternal getUTF7()
```

Получает кодировку для формата UTF-8.

**Returns:**
Экземпляр TextEncodingInternal

### getUTF8 {#getUTF8--}
```
public static TextEncodingInternal getUTF8()
```

Получает кодировку для формата UTF-8.

**Returns:**
Экземпляр TextEncodingInternal

### getUTF8Unmarked {#getUTF8Unmarked--}
```
public static TextEncodingInternal getUTF8Unmarked()
```

Получает кодировку для формата UTF-8 Unmarked.

**Returns:**
Экземпляр TextEncodingInternal

### toString {#toString-com.aspose.pdf.TextEncodingInternal-}
Возвращает строку, представляющую текущий объект.
