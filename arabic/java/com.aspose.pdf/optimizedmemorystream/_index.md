---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد MemoryStream يمكنه احتواء سعة قياسية أكبر"
type: docs
weight: 3220
url: /ar/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

يحدد MemoryStream يمكنه احتواء سعة قياسية أكبر

## الحقول

| حقل | الوصف |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | قيمة حجم المخزن المؤقت الافتراضي بالبايت. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream} بناءً على مصفوفة البايت المحددة. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream} بناءً على مصفوفة البايت المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [canRead](#canRead--) | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم القراءة. |
| [canSeek](#canSeek--) | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم السعي. |
| [canWrite](#canWrite--) | عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم الكتابة. |
| [flush](#flush--) | تم تجاوز الدالة. |
| [getBufferSize](#getBufferSize--) | يحصل أو يضبط حجم المخازن المؤقتة الأساسية. القيمة: حجم المخازن المؤقتة. |
| [getFreeOnDispose](#getFreeOnDispose--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحرير المخازن المؤقتة الأساسية عند التخلص. |
| [getLength](#getLength--) | عند تجاوزها في فئة مشتقة، يحصل على طول الدفق بالبايت. |
| [getPosition](#getPosition--) | عند تجاوزها في فئة مشتقة، يحصل أو يعيّن الموضع داخل الدفق الحالي. |
| [read](#read-byte:A-int-int-) | عند تجاوزها في فئة مشتقة، يقرأ تسلسلًا من البايتات من الدفق الحالي ويقدّم الموضع داخل الدفق بعدد البايتات المقروءة. |
| [readByte](#readByte--) | يقرأ بايتًا من الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق. |
| [seek](#seek-long-int-) | عند تجاوزها في فئة مشتقة، يعيّن الموضع داخل الدفق الحالي. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | عند تجاوزها في فئة مشتقة، يعيّن الموضع داخل الدفق الحالي. |
| [setBufferSize](#setBufferSize-int-) | يحصل أو يضبط حجم المخازن المؤقتة الأساسية. القيمة: حجم المخازن المؤقتة. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحرير المخازن المؤقتة الأساسية عند التخلص. |
| [setLength](#setLength-long-) | عند تجاوزها في فئة مشتقة، يعيّن طول الدفق الحالي. |
| [setPosition](#setPosition-long-) | عند تجاوزها في فئة مشتقة، يحصل أو يعيّن الموضع داخل الدفق الحالي. الموضع الحالي داخل الدفق. القيمة: |
| [toArray](#toArray--) | يحوّل الدفق الحالي إلى مصفوفة بايت. |
| [write](#write-byte:A-int-int-) | عند تجاوزها في فئة مشتقة، يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| [writeByte](#writeByte-byte-) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | يكتب إلى الدفق المحدد. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

قيمة حجم المخزن المؤقت الافتراضي بالبايت.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream} بناءً على مصفوفة البايت المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المخزن المؤقت |  | المصفوفة من البايتات غير الموقعة التي يُنشأ منها الدفق الحالي. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bufferSize |  | حجم المخازن المؤقتة الأساسية. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

ينشئ نسخة جديدة من الفئة {@link OptimizedMemoryStream} بناءً على مصفوفة البايت المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bufferSize |  | حجم المخازن المؤقتة الأساسية. |
| المخزن المؤقت |  | المصفوفة من البايتات غير الموقعة التي يُنشأ منها الدفق الحالي. |

### canRead {#canRead--}
```
public boolean canRead()
```

عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم القراءة.

**Returns:**
صحيح إذا كان الدفق يدعم القراءة؛ وإلا، خطأ. القيمة:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم السعي.

**Returns:**
صحيح إذا كان الدفق يدعم السعي؛ وإلا، خطأ. القيمة:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

عند تجاوزها في فئة مشتقة، يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم الكتابة.

**Returns:**
صحيح إذا كان الدفق يدعم الكتابة؛ وإلا، خطأ. القيمة:

### flush {#flush--}
```
public void flush()
```

تم تجاوز الدالة.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

يحصل أو يضبط حجم المخازن المؤقتة الأساسية. القيمة: حجم المخازن المؤقتة.

**Returns:**
قيمة int

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحرير المخازن المؤقتة الأساسية عند التخلص.

**Returns:**
قيمة منطقية

### getLength {#getLength--}
```
public long getLength()
```

عند تجاوزها في فئة مشتقة، يحصل على طول الدفق بالبايت.

**Returns:**
قيمة طويلة تمثل طول الدفق بالبايت. القيمة:

### getPosition {#getPosition--}
```
public long getPosition()
```

عند تجاوزها في فئة مشتقة، يحصل أو يعيّن الموضع داخل الدفق الحالي.

**Returns:**
الموضع الحالي داخل الدفق. القيمة:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

عند تجاوزها في فئة مشتقة، يقرأ تسلسلًا من البايتات من الدفق الحالي ويقدّم الموضع داخل الدفق بعدد البايتات المقروءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المخزن المؤقت |  | مصفوفة من البايتات. عندما تُعيد هذه الطريقة، يحتوي المخزن المؤقت على مصفوفة البايت المحددة بالقيم |
| الإزاحة |  | الإزاحة الصفرية للبايت التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| عدد |  | الحد الأقصى لعدد البايتات التي تُقرأ من الدفق الحالي. |

**Returns:**
إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد يكون أقل من عدد البايتات المطلوبة إذا لم تتوفر تلك البايتات حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق.

### readByte {#readByte--}
```
public int readByte()
```

يقرأ بايتًا من الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية الدفق.

**Returns:**
بايت أو -1 إذا كان عند نهاية الدفق.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

عند تجاوزها في فئة مشتقة، يعيّن الموضع داخل الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإزاحة |  | إزاحة بايت نسبية إلى المعامل {@code origin}. |
| origin |  | قيمة من النوع {@link SeekOrigin} تشير إلى نقطة المرجع المستخدمة للحصول على الموضع الجديد. |

**Returns:**
الموضع الجديد داخل الدفق الحالي.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
عند تجاوزها في فئة مشتقة، يعيّن الموضع داخل الدفق الحالي.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

يحصل أو يضبط حجم المخازن المؤقتة الأساسية. القيمة: حجم المخازن المؤقتة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحرير المخازن المؤقتة الأساسية عند التخلص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

عند تجاوزها في فئة مشتقة، يعيّن طول الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الطول المطلوب للدفق الحالي بالبايتات. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

عند تجاوزها في فئة مشتقة، يحصل أو يعيّن الموضع داخل الدفق الحالي. الموضع الحالي داخل الدفق. القيمة:

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

يحوّل الدفق الحالي إلى مصفوفة بايت.

**Returns:**
مصفوفة من البايتات

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

عند تجاوزها في فئة مشتقة، يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المخزن المؤقت |  | مصفوفة من البايتات. تقوم هذه الطريقة بنسخ {@code count} بايت من {@code buffer} إلى الدفق الحالي. |
| الإزاحة |  | إزاحة البايت الصفرية في {@code buffer} التي يبدأ عندها نسخ البايتات إلى الدفق الحالي. |
| عدد |  | عدد البايتات التي سيتم كتابتها إلى الدفق الحالي. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | البايت الذي سيُكتب إلى الدفق. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
يكتب إلى الدفق المحدد.
