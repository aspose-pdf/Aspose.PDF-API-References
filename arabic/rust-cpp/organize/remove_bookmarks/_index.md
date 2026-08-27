---
title: "remove_bookmarks"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل العلامات المرجعية من PDF-document."
type: docs
url: /ar/rust-cpp/organize/remove_bookmarks/
---

_يزيل العلامات المرجعية من PDF-document._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
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

    // إزالة العلامات المرجعية من PDF-document
    pdf.remove_bookmarks()?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```