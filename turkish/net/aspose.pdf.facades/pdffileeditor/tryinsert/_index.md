---
title: TryInsert
second_title: Aspose.PDF for .NET API Referansı
description: Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler.
type: docs
weight: 450
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_2}

Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Pdf dosyasını girin. |
| insertLocation | Int32 | Giriş dosyasına konum ekleyin. |
| portFile | String | Pdf dosyasından sayfalar. |
| pageNumber | Int32[] | portFile içinde taşınan sayfa numarası. |
| outputFile | String | Çıktı pdf dosyası. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Notlar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Başka bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Pdf dosyasının Giriş Akışı. |
| insertLocation | Int32 | Giriş dosyasına konum ekleyin. |
| portStream | Stream | Sayfalar için Pdf dosyası akışı. |
| pageNumber | Int32[] | portFile içinde taşınan sayfa numarası. |
| outputStream | Stream | Çıkış Akışı. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi, işlem başarısız olursa bir istisna atmaz.

### Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine depolar.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| insertLocation | Int32 | İkinci dosyanın ekleneceği sayfa numarası. |
| portFile | String | Eklenecek dosyanın yolu. |
| pageNumber | Int32[] | Eklenecek olan kaynak dosyadaki sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı yanıt nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Belgeyi başka bir belgeye ekler ve sonucu yanıt nesnesine kaydeder.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| inputStream | Stream | Kaynak belgeyle akış |
| insertLocation | Int32 | Diğer belgenin ekleneceği konum. |
| portStream | Stream | Eklenecek belge. |
| pageNumber | Int32[] | Eklenecek ikinci belgedeki sayfa numaraları dizisi. |
| response | HttpResponse | Sonucun saklanacağı yanıt nesnesi. |

### Geri dönüş değeri

işlem başarıyla tamamlandıysa true ; aksi halde yanlış.

### Notlar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi, işlem başarısız olursa bir istisna atmaz.

### Ayrıca bakınız

* class [PdfFileEditor](../../pdffileeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdffileeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->