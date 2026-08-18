---
title: "is_linearized"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengambil nilai yang menunjukkan apakah dokumen terlinear."
type: docs
url: /id/rust-cpp/core/is_linearized/
---

_Mengambil nilai yang menunjukkan apakah dokumen terlinear._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
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

    // Dapatkan nilai yang menunjukkan apakah dokumen terlinear
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```