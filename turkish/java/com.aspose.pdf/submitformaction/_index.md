---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "Aspose.PDF for Java API Referansı"
description: "Submit-form eylemini tanımlayan sınıf."
type: docs
weight: 4690
url: /tr/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

Submit-form eylemini tanımlayan sınıf.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | Ayarlanırsa, gönderilen tarih temsil eden alan değerleri standart formata dönüştürülecektir. |
| [EMBED_FORM](#EMBED_FORM) | Ayarlanırsa, gönderilen FDF'nin F girdisi, FDF'nin gönderildiği PDF dosyasını temsil eden gömülü bir dosya akışı içeren bir dosya spesifikasyonu olacaktır. |
| [EXCL_F_KEY](#EXCL_F_KEY) | Ayarlanırsa, gönderilen FDF F girdisini dışarı bırakacaktır. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | Ayarlanırsa, yalnızca T girdisi geçerli kullanıcının adıyla eşleşen işaretleme ek açıklamalarını içerecektir. |
| [EXCLUDE](#EXCLUDE) | Temizlenirse, Fields dizisi gönderime dahil edilecek alanları belirtir. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | Ayarlanırsa, alan adları ve değerleri HTML Form biçiminde gönderilecektir. |
| [GET_METHOD](#GET_METHOD) | Ayarlanırsa, alan adları ve değerleri bir HTTP GET isteği kullanılarak gönderilecektir. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | Ayarlanırsa, gönderilen FDF dosyası temel PDF belgesindeki tüm işaretleme ek açıklamaları içerecektir. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | Ayarlanırsa, gönderilen FDF dosyası tüm artımlı güncellemelerin içeriğini içerecektir. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | Ayarlanırsa, Fields dizisi ve Include/Exclude bayrağı tarafından belirlenen tüm alanlar gönderilecektir. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | Ayarlanırsa, submit-form eylemine neden olan fare tıklamasının koordinatları form verisinin bir parçası olarak iletilecektir. |
| [SUBMIT_PDF](#SUBMIT_PDF) | Ayarlanırsa, belge MIME içerik türü application/pdf kullanılarak PDF olarak gönderilecektir. |
| [XFDF](#XFDF) | Ayarlanırsa, alan adları ve değerleri XFDF olarak gönderilecektir. |

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | SubmitFormAction nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFlags](#getFlags--) | Gönderme eyleminin bayraklarını alır. |
| [getUrl](#getUrl--) | Hedef URL. |
| [setFlags](#setFlags-int-) | Gönderme eyleminin bayraklarını ayarlar. |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | Hedef URL. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

Ayarlanırsa, gönderilen tarih temsil eden alan değerleri standart formata dönüştürülecektir.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

Ayarlanırsa, gönderilen FDF'nin F girdisi, FDF'nin gönderildiği PDF dosyasını temsil eden gömülü bir dosya akışı içeren bir dosya spesifikasyonu olacaktır.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

Ayarlanırsa, gönderilen FDF F girdisini dışarı bırakacaktır.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

Ayarlanırsa, yalnızca T girdisi geçerli kullanıcının adıyla eşleşen işaretleme ek açıklamalarını içerecektir.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

Temizlenirse, Fields dizisi gönderime dahil edilecek alanları belirtir.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

Ayarlanırsa, alan adları ve değerleri HTML Form biçiminde gönderilecektir.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

Ayarlanırsa, alan adları ve değerleri bir HTTP GET isteği kullanılarak gönderilecektir.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

Ayarlanırsa, gönderilen FDF dosyası temel PDF belgesindeki tüm işaretleme ek açıklamaları içerecektir.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

Ayarlanırsa, gönderilen FDF dosyası tüm artımlı güncellemelerin içeriğini içerecektir.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

Ayarlanırsa, Fields dizisi ve Include/Exclude bayrağı tarafından belirlenen tüm alanlar gönderilecektir.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

Ayarlanırsa, submit-form eylemine neden olan fare tıklamasının koordinatları form verisinin bir parçası olarak iletilecektir.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

Ayarlanırsa, belge MIME içerik türü application/pdf kullanılarak PDF olarak gönderilecektir.

### XFDF {#XFDF}
```
public static final int XFDF
```

Ayarlanırsa, alan adları ve değerleri XFDF olarak gönderilecektir.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

SubmitFormAction nesnesini başlatır.

### getFlags {#getFlags--}
```
public int getFlags()
```

Gönderme eyleminin bayraklarını alır.

**Returns:**
int değer

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

Hedef URL.

**Returns:**
FileSpecification değeri

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Gönderme eyleminin bayraklarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
Hedef URL.
