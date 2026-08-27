---
title: "flatten"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يقوم بتسطيح مستند PDF."
type: docs
url: /ar/rust-cpp/organize/flatten/
---

_يقوم بتسطيح مستند PDF._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
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