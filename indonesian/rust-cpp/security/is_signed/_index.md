---
title: "is_signed"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Dapatkan status tertanda pada dokumen PDF."
type: docs
url: /id/rust-cpp/security/is_signed/
---

_Dapatkan status penandatanganan dokumen PDF._

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
    // Buka PDF-document bernama "sample_with_sign.pdf"
    let pdf = Document::open("sample_with_sign.pdf")?;

    // Dapatkan status penandatanganan dokumen PDF
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```