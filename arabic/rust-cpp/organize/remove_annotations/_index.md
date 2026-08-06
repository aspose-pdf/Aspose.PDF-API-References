---
title: "remove_annotations"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل التعليقات التوضيحية من مستند PDF."
type: docs
url: /ar/rust-cpp/organize/remove_annotations/
---

_يزيل التعليقات التوضيحية من مستند PDF._

```rust
pub fn remove_annotations(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إزالة التعليقات التوضيحية من PDF-document
    pdf.remove_annotations()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_annotations.pdf")?;

    Ok(())
}

```