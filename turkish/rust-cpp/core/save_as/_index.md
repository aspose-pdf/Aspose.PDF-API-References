---
title: "save_as"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Açık olan PDF-document'i yeni bir dosya adıyla kaydeder."
type: docs
url: /tr/rust-cpp/core/save_as/
---

_Açık olan PDF-document'i yeni bir dosya adıyla kaydeder._

```rust
pub fn save_as(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Yeni bir PDF-document oluştur
    let pdf = Document::new()?;

    // PDF-document'i yeni bir dosya adıyla kaydet
    pdf.save_as("sample_save_as.pdf")?;

    Ok(())
}

```