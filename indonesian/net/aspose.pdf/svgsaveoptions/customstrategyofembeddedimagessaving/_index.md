---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: Bidang SvgSaveOptions. Bidang ini dapat berisi strategi penyimpanan yang harus digunakan jika ada selama konversi untuk penanganan khusus dari file gambar eksternal yang dirujuk yang dibuat seperti BMP atau JPEG yang disematkan ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan di dalam konverter itu sendiri seolah-olah tidak ada kode kustom eksternal.
type: docs
weight: 30
url: /id/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## Bidang SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving

Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus dari file gambar eksternal yang dirujuk (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom bendera 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan di dalam konverter itu sendiri seolah-olah tidak ada kode kustom eksternal.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Lihat Juga

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)