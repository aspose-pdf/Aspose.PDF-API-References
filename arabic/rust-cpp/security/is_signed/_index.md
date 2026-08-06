---
title: "is_signed"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "الحصول على حالة التوقيع لمستند PDF."
type: docs
url: /ar/rust-cpp/security/is_signed/
---

_احصل على حالة التوقيع لـ PDF-document._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF باسم "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // احصل على حالة التوقيع لـ PDF-document
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```