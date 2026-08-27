---
title: "export_fdf"
second_title: "Aspose.PDF per Rust tramite C++"
description: "Esporta dal documento PDF precedentemente aperto con AcroForm a documento FDF con nome file."
type: docs
url: /it/rust-cpp/convert/export_fdf/
---

_Esporta dal documento PDF precedentemente aperto con AcroForm a documento FDF con nome file._

```rust
pub fn export_fdf(&self, filename: &str) -> Result<(), PdfError>
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

    // Esporta dal documento PDF precedentemente aperto con AcroForm a documento FDF
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```