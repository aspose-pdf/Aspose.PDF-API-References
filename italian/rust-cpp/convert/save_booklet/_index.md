---
title: "save_booklet"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Converte e salva il PDF-document precedentemente aperto come PDF-document booklet."
type: docs
url: /it/rust-cpp/convert/save_booklet/
---

_Converte e salva il PDF-document precedentemente aperto come PDF-document booklet._

```rust
pub fn save_booklet(&self, filename: &str) -> Result<(), PdfError>
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
    // Apri un documento PDF con nome file
    let pdf = Document::open("sample.pdf")?;

    // Converti e salva il PDF-document precedentemente aperto come PDF-document booklet
    pdf.save_booklet("sample_booklet.pdf")?;

    Ok(())
}
```