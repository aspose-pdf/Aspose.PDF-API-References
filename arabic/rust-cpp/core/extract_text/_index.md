---
title: "extract_text"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يرجع محتويات مستند PDF كنص عادي."
type: docs
url: /ar/rust-cpp/core/extract_text/
---

_يرجع محتويات مستند PDF كنص عادي._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF مع اسم الملف
    let pdf = Document::open("sample.pdf")?;

    // إرجاع محتويات مستند PDF كنص عادي
    let txt = pdf.extract_text()?;

    // اطبع النص المستخرج
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```