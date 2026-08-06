---
title: "page_remove_watermarks"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يزيل العلامات المائية في الصفحة."
type: docs
url: /ar/rust-cpp/organize/page_remove_watermarks/
---

_يزيل العلامات المائية في الصفحة._

```rust
pub fn page_remove_watermarks(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // إزالة العلامات المائية في الصفحة
    pdf.page_remove_watermarks(1)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_page1_remove_watermarks.pdf")?;

    Ok(())
}

```