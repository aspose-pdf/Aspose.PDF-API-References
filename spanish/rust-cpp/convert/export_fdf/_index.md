---
title: "export_fdf"
second_title: "Aspose.PDF para Rust vía C++"
description: "Exporta del documento PDF previamente abierto con AcroForm a un documento FDF con nombre de archivo."
type: docs
url: /es/rust-cpp/convert/export_fdf/
---

_Exporta del documento PDF previamente abierto con AcroForm a un documento FDF con nombre de archivo._

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
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Exportar del documento PDF previamente abierto con AcroForm a documento FDF
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```