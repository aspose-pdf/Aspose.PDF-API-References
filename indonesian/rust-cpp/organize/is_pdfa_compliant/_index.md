---
title: "is_pdfa_compliant"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mendapatkan apakah dokumen PDF mematuhi PDF/A."
type: docs
url: /id/rust-cpp/organize/is_pdfa_compliant/
---

_Mendapatkan apakah dokumen PDF mematuhi PDF/A._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Dapatkan status kepatuhan PDF/A dokumen PDF
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```