---
title: "page_to_pdf"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتحويل وحفظ الصفحة المحددة كمستند PDF."
type: docs
url: /ar/rust-cpp/convert/page_to_pdf/
---

_يقوم بتحويل وحفظ الصفحة المحددة كمستند PDF._

```rust
pub fn page_to_pdf(&self, num: i32, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // تحويل وحفظ الصفحة المحددة كمستند PDF
    pdf.page_to_pdf(1, "sample_page1.pdf")?;

    Ok(())
}

```