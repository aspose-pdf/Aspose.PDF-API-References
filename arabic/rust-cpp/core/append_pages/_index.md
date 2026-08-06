---
title: "append_pages"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يضيف الصفحات المحددة من مستند PDF آخر."
type: docs
url: /ar/rust-cpp/core/append_pages/
---

_يضيف الصفحات المحددة من مستند PDF آخر._

```rust
pub fn append_pages(&self, other: &Document, page_range: &str) -> Result<(), PdfError>
```

**Arguments**
  * **other** - a reference to another PDF-document to append pages from
  * **page_range** - a string defining the page ranges to append (e.g. "-2,4,6-8,10-")

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document الأساسي
    let pdf = Document::open("sample1page.pdf")?;

    // افتح مستند PDF آخر للإلحاق
    let another_pdf = Document::open("sample.pdf")?;

    // أضف الصفحات المحددة (1 و 3) من مستند PDF آخر
    pdf.append_pages(&another_pdf, "1,3")?;

    // احفظ مستند PDF المفتوح مسبقًا باسم ملف جديد
    pdf.save_as("sample_append_pages.pdf")?;

    Ok(())
}

```