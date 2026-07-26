---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini berisi parameter yang menentukan perilaku PdfContentEditor saat operasi ReplaceText dilakukan."
type: docs
weight: 650
url: /id/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Kelas ini berisi parameter yang menentukan perilaku PdfContentEditor saat operasi ReplaceText dilakukan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Aksi yang dilakukan ketika tidak ditemukan font yang sesuai untuk teks yang diubah (Melempar pengecualian / Mengganti dengan font lain / Tetap mengganti). |
| [getReplaceScope](#getReplaceScope--) | Lingkup operasi penggantian (ganti kemunculan pertama atau ganti semua kemunculan). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Jika false, string yang dicari adalah teks sederhana. Jika true, string yang dicari adalah ekspresi reguler. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Aksi yang dilakukan ketika tidak ditemukan font yang sesuai untuk teks yang diubah (Melempar pengecualian / Mengganti dengan font lain / Tetap mengganti). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Jika false, string yang dicari adalah teks sederhana. Jika true, string yang dicari adalah ekspresi reguler. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Lingkup operasi penggantian (ganti kemunculan pertama atau ganti semua kemunculan). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Aksi yang dilakukan ketika tidak ditemukan font yang sesuai untuk teks yang diubah (Melempar pengecualian / Mengganti dengan font lain / Tetap mengganti).

**Returns:**
Nilai NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Lingkup operasi penggantian (ganti kemunculan pertama atau ganti semua kemunculan).

**Returns:**
Elemen Scope @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Jika false, string yang dicari adalah teks sederhana. Jika true, string yang dicari adalah ekspresi reguler.

**Returns:**
nilai boolean

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Aksi yang dilakukan ketika tidak ditemukan font yang sesuai untuk teks yang diubah (Melempar pengecualian / Mengganti dengan font lain / Tetap mengganti).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Jika false, string yang dicari adalah teks sederhana. Jika true, string yang dicari adalah ekspresi reguler.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Lingkup operasi penggantian (ganti kemunculan pertama atau ganti semua kemunculan).
