---
title: "export_xfdf"
second_title: "Aspose.PDF para Rust vía C++"
description: "Exportaciones del PDF-document previamente abierto con AcroForm a XFDF-document con nombre de archivo."
type: docs
url: /es/rust-cpp/convert/export_xfdf/
---

_Exportaciones del PDF-document previamente abierto con AcroForm a XFDF-document con nombre de archivo._

```rust
pub fn export_xfdf(&self, filename: &str) -> Result<(), PdfError>
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

    // Exportar del PDF-document previamente abierto con AcroForm a XFDF-document
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```