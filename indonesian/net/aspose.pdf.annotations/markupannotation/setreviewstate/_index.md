---
title: MarkupAnnotation.SetReviewState
second_title: Aspose.PDF for .NET API Reference
description: Metode MarkupAnnotation. Mengatur status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Perhatikan status yang disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel
type: docs
weight: 140
url: /id/net/aspose.pdf.annotations/markupannotation/setreviewstate/
---
## SetReviewState(AnnotationState, string) {#setreviewstate_1}

Mengatur status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Perhatikan, status yang disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

```csharp
public void SetReviewState(AnnotationState state, string userName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| state | AnnotationState | Status untuk penugasan. |
| userName | String | Nama pengguna yang muncul di header komentar. Nama dapat sama dengan nama di Judul anotasi target atau berbeda jika status diatur oleh pengguna lain. |

### Lihat Juga

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetReviewState(AnnotationState) {#setreviewstate}

Mengatur status tinjauan untuk anotasi. Status Ditandai dan Tidak Ditandai diabaikan karena tidak termasuk dalam Model Status Tinjauan. Status diatur oleh pengguna yang membuat anotasi target. Nilai diambil dari properti Judul anotasi target. Perhatikan, status yang disimpan dalam anotasi teks lain yang memiliki kunci state dan statemodel.

```csharp
public void SetReviewState(AnnotationState state)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| state | AnnotationState | Status untuk penugasan. |

### Lihat Juga

* enum [AnnotationState](../../annotationstate/)
* class [MarkupAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)