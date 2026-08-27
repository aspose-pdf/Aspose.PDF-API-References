---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Field SvgSaveOptions. Field ini dapat berisi strategi penyimpanan yang harus digunakan jika ada selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan seperti BMP atau JPEG yang ter-embed ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau file itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan set flag CustomProcessingCancelled pada variabel parameter imageSavingInfo dalam kode khusus. Ini memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter itu sendiri seolah-olah tidak ada kode khusus eksternal."
type: docs
weight: 30
url: /id/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file gambar eksternal yang direferensikan (seperti BMP atau JPEG yang disematkan) yang disematkan ke dalam SVG yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URI yang diinginkan dari sumber daya yang disimpan dalam SVG yang dihasilkan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' pada variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### Lihat Juga

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


