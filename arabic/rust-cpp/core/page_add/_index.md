---
title: "page_add"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف صفحة جديدة إلى PDF-document."
type: docs
url: /ar/rust-cpp/core/page_add/
---

_يضيف صفحة جديدة إلى PDF-document._

```rust
pub fn page_add(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // إضافة صفحة جديدة في PDF-document
    pdf.page_add()?;

    // احفظ مستند PDF-document المفتوح مسبقًا
    pdf.save()?;

    Ok(())
}

```