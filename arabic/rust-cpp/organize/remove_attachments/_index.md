---
title: "remove_attachments"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل المرفقات من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_attachments/
---

_يزيل المرفقات من PDF-document._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // إزالة المرفقات من PDF-document
    pdf.remove_attachments()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```