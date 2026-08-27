---
title: "save"
second_title: "Aspose.PDF لـ Rust عبر C++"
description: "يحفظ مستند PDF-document المفتوح مسبقًا."
type: docs
url: /ar/rust-cpp/core/save/
---

_يحفظ مستند PDF-document المفتوح مسبقًا._

```rust
pub fn save(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // فتح مستند PDF-document باسم "sample.pdf"
    let pdf = Document::open("sample.pdf")?;

    // احفظ مستند PDF-document المفتوح مسبقًا
    pdf.save()?;

    Ok(())
}

```