---
title: "save"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Açık olan PDF-document'i kaydeder."
type: docs
url: /tr/rust-cpp/core/save/
---

_Açık olan PDF-document'i kaydeder._

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
    // "sample.pdf" adlı bir PDF-document aç
    let pdf = Document::open("sample.pdf")?;

    // Önceden açılmış PDF-document'i kaydet
    pdf.save()?;

    Ok(())
}

```