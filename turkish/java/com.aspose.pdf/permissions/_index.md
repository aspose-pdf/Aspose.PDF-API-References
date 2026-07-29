---
title: "İzinler"
linktitle: "İzinler"
second_title: "Aspose.PDF for Java API Referansı"
description: "Binary Flag Bu enum, bir pdf için kullanıcının izinlerini temsil eder."
type: docs
weight: 3830
url: /tr/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Binary Flag Bu enum, bir pdf için kullanıcının izinlerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Belgeyi birleştir (sayfaları ekle, döndür veya sil ve yer imleri veya küçük resimler oluştur), {@code ModifyContent} temiz olsa bile. |
| [ExtractContent](#ExtractContent) | (2 revizyonlu güvenlik işleyicileri) Belgeden metin ve grafikleri kopyala veya başka şekilde çıkar, metin ve grafik çıkarımını da içerecek şekilde (engelli kullanıcıların erişilebilirliğini desteklemek veya diğer amaçlar için). (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Belgeden metin ve grafikleri, {@code ExtractContentWithDisabilities} tarafından kontrol edilen işlemler dışındaki işlemlerle kopyala veya başka şekilde çıkar. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Metin ve grafikleri çıkar (engelli kullanıcıların erişilebilirliğini desteklemek amacıyla). |
| [FillForm](#FillForm) | (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Mevcut etkileşimli form alanlarını doldur (imza alanları dahil), {@code ModifyTextAnnotations} temiz olsa bile. |
| [ModifyContent](#ModifyContent) | Belgenin içeriğini, {@code ModifyTextAnnotations}, {@code FillForm} ve 11 tarafından kontrol edilmeyen işlemlerle değiştir. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Metin açıklamalarını ekle veya değiştir, etkileşimli form alanlarını doldur ve {@code ModifyContent} de ayarlanmışsa, etkileşimli form alanlarını (imza alanları dahil) oluştur veya değiştir. |
| [PrintDocument](#PrintDocument) | (2 revizyonlu güvenlik işleyicileri) Belgeyi yazdır. (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Belgeyi yazdır (muhtemelen en yüksek kalite seviyesinde olmayabilir, {@code PrintingQuality} de ayarlanmışsa buna bağlı olarak). |
| [PrintingQuality](#PrintingQuality) | (Revision 3 veya daha yüksek güvenlik işleyicileri) Belgeyi, PDF içeriğinin doğru bir dijital kopyasının oluşturulabileceği bir temsile yazdırın. Bu bit temiz olduğunda (ve bit 3 ayarlıysa), yazdırma, görünümün düşük seviyeli bir temsiliyle sınırlıdır, muhtemelen bozulmuş kaliteyle. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(3 veya daha yüksek revizyonlu güvenlik işleyicileri) Belgeyi birleştir (sayfaları ekle, döndür veya sil ve yer imleri veya küçük resimler oluştur), {@code ModifyContent} temiz olsa bile.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(2 revizyonlu güvenlik işleyicileri) Belgeden metin ve grafikleri kopyala veya başka şekilde çıkar, metin ve grafik çıkarımını da içerecek şekilde (engelli kullanıcıların erişilebilirliğini desteklemek veya diğer amaçlar için). (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Belgeden metin ve grafikleri, {@code ExtractContentWithDisabilities} tarafından kontrol edilen işlemler dışındaki işlemlerle kopyala veya başka şekilde çıkar.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(3 veya daha yüksek revizyonlu güvenlik işleyicileri) Metin ve grafikleri çıkar (engelli kullanıcıların erişilebilirliğini desteklemek amacıyla).

### FillForm {#FillForm}
```
public static final int FillForm
```

(3 veya daha yüksek revizyonlu güvenlik işleyicileri) Mevcut etkileşimli form alanlarını doldur (imza alanları dahil), {@code ModifyTextAnnotations} temiz olsa bile.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Belgenin içeriğini, {@code ModifyTextAnnotations}, {@code FillForm} ve 11 tarafından kontrol edilmeyen işlemlerle değiştir.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Metin açıklamalarını ekle veya değiştir, etkileşimli form alanlarını doldur ve {@code ModifyContent} de ayarlanmışsa, etkileşimli form alanlarını (imza alanları dahil) oluştur veya değiştir.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(2 revizyonlu güvenlik işleyicileri) Belgeyi yazdır. (3 veya daha yüksek revizyonlu güvenlik işleyicileri) Belgeyi yazdır (muhtemelen en yüksek kalite seviyesinde olmayabilir, {@code PrintingQuality} de ayarlanmışsa buna bağlı olarak).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Revision 3 veya daha yüksek güvenlik işleyicileri) Belgeyi, PDF içeriğinin doğru bir dijital kopyasının oluşturulabileceği bir temsile yazdırın. Bu bit temiz olduğunda (ve bit 3 ayarlıysa), yazdırma, görünümün düşük seviyeli bir temsiliyle sınırlıdır, muhtemelen bozulmuş kaliteyle.
