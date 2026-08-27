---
title: "page_delete"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحذف الصفحة المحددة من مستند PDF-document."
type: docs
url: /ar/rust-cpp/core/page_delete/
---

_يحذف الصفحة المحددة من مستند PDF-document._

```rust
pub fn page_delete(&self, num: i32) -> Result<(), PdfError>
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

    // حذف الصفحة المحددة في مستند PDF-document
    pdf.page_delete(1)?;

    // احفظ مستند PDF-document المفتوح مسبقًا
    pdf.save()?;

    Ok(())
}

```