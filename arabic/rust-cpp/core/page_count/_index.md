---
title: "page_count"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يعيد عدد الصفحات في مستند PDF."
type: docs
url: /ar/rust-cpp/core/page_count/
---

_يعيد عدد الصفحات في مستند PDF._

```rust
pub fn page_count(&self) -> Result<i32, PdfError>
```

**Arguments**


**Returns**
  * **Ok(i32)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // إرجاع عدد الصفحات في مستند PDF
    let count = pdf.page_count()?;

    // اطبع عدد الصفحات
    println!("Count: {}", count);

    Ok(())
}

```