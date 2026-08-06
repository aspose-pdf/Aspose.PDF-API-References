---
title: "append"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف صفحات من مستند PDF-document آخر."
type: docs
url: /ar/rust-cpp/core/append/
---

_يضيف صفحات من مستند PDF-document آخر._

```rust
pub fn append(&self, other: &Document) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document الأساسي
    let pdf = Document::open("sample.pdf")?;

    // افتح مستند PDF آخر للإلحاق
    let another_pdf = Document::open("sample1page.pdf")?;

    // إلحاق صفحات من مستند PDF آخر
    pdf.append(&another_pdf)?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_append.pdf")?;

    Ok(())
}

```