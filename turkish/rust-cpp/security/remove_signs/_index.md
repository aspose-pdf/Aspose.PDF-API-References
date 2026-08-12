---
title: "remove_signs"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanından imzaları kaldır."
type: docs
url: /tr/rust-cpp/security/remove_signs/
---

_PDF-document üzerindeki imzaları kaldır._

```rust
pub fn remove_signs(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the resulting PDF-document without signatures


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample_with_sign.pdf" adlı bir PDF-document aç
    let pdf = Document::open("sample_with_sign.pdf")?;

    // PDF-document üzerindeki imzaları kaldır
    pdf.remove_signs("sample_remove_signs.pdf")?;

    Ok(())
}

```