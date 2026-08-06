---
title: "page_is_blank"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "إرجاع ما إذا كانت الصفحة فارغة في مستند PDF."
type: docs
url: /ar/rust-cpp/core/page_is_blank/
---

_إرجاع الصفحة فارغة في مستند PDF._

```rust
pub fn page_is_blank(&self, num: i32) -> Result<bool, PdfError>
```

**Arguments**
  * **num** - the page number (1-based)


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document من ملف
    let pdf = Document::open("sample.pdf")?;

    // حدد رقم الصفحة (فهرس يبدأ من 1)
    let page_number = 1;

    // إرجاع الصفحة فارغة في مستند PDF
    let is_blank = pdf.page_is_blank(page_number)?;

    // اطبع إذا كانت الصفحة المحددة فارغة
    println!("Is page {} blank? {}", page_number, is_blank);

    Ok(())
}

```