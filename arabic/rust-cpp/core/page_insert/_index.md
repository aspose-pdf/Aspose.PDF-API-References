---
title: "page_insert"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يدرج صفحة جديدة في الموضع المحدد داخل مستند PDF-document."
type: docs
url: /ar/rust-cpp/core/page_insert/
---

_يدرج صفحة جديدة في الموضع المحدد داخل مستند PDF-document._

```rust
pub fn page_insert(&self, num: i32) -> Result<(), PdfError>
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

    // إدراج صفحة جديدة في الموضع المحدد داخل مستند PDF-document
    pdf.page_insert(1)?;

    // احفظ مستند PDF-document المفتوح مسبقًا
    pdf.save()?;

    Ok(())
}

```