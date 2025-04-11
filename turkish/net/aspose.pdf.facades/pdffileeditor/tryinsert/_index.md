---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor yöntemi. Diğer bir dosyadan sayfaları giriş Pdf dosyasına ekler
type: docs
weight: 420
url: /tr/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

Diğer bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Giriş Pdf dosyası. |
| insertLocation | Int32 | Giriş dosyasındaki ekleme konumu. |
| portFile | String | Pdf dosyasından sayfalar. |
| pageNumber | Int32[] | portFile'daki taşınan sayfa numarası. |
| outputFile | String | Çıkış Pdf dosyası. |

### Dönüş Değeri

Başarı için true, aksi takdirde false.

## Açıklamalar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

Diğer bir dosyadan sayfaları giriş Pdf dosyasına ekler.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Pdf dosyasının Giriş Akışı. |
| insertLocation | Int32 | Giriş dosyasındaki ekleme konumu. |
| portStream | Stream | Sayfalar için Pdf dosyasının Akışı. |
| pageNumber | Int32[] | portFile'daki taşınan sayfa numarası. |
| outputStream | Stream | Çıkış Akışı. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi işlem başarısız olursa bir istisna atmaz.

## Örnekler

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

Dosyanın içeriğini kaynak dosyaya ekler ve sonucu HttpResponse nesnesine kaydeder.

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputFile | String | Kaynak dosya adı. |
| insertLocation | Int32 | İkinci dosyanın ekleneceği sayfa numarası. |
| portFile | String | Eklenecek dosyanın yolu. |
| pageNumber | Int32[] | Eklenecek kaynak dosyadaki sayfa numaralarının dizisi. |
| response | HttpResponse | Sonucun saklanacağı yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi işlem başarısız olursa bir istisna atmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

Belgeyi diğer belgeye ekler ve sonucu yanıt nesnesine kaydeder.

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputStream | Stream | Kaynak belge ile akış |
| insertLocation | Int32 | Diğer belgenin ekleneceği konum. |
| portStream | Stream | Eklenecek belge. |
| pageNumber | Int32[] | Eklenecek ikinci belgede sayfa numaralarının dizisi. |
| response | HttpResponse | Sonucun saklanacağı yanıt nesnesi. |

### Dönüş Değeri

İşlem başarıyla tamamlandıysa true; aksi takdirde false.

## Açıklamalar

TryInsert yöntemi, Insert yöntemine benzer, ancak TryInsert yöntemi işlem başarısız olursa bir istisna atmaz.

### Ayrıca Bakınız

* sınıf [PdfFileEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)