---
title: "MarkupAnnotation.SetReviewState"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode MarkupAnnotation. Menetapkan status tinjauan untuk sebuah anotasi. Status Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. Catat status yang disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel."
type: docs
weight: 140
url: /id/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Mengatur status tinjauan untuk sebuah anotasi. Status Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| status | AnnotationState | Status untuk penugasan. |
| userName | String | Nama pengguna yang muncul di header komentar. Nama tersebut dapat sama dengan nama di Title anotasi target atau berbeda jika status diatur oleh pengguna lain. |

### Lihat Juga

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Mengatur status tinjauan untuk sebuah anotasi. Status Marked dan Unmarked diabaikan karena tidak termasuk dalam Review StateModel. Status ditetapkan oleh pengguna yang membuat anotasi target. Nilainya diambil dari properti Title pada anotasi target. Catatan, status disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| status | AnnotationState | Status untuk penugasan. |

### Lihat Juga

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


