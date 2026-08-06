---
title: "export_xfdf"
second_title: "Aspose.PDF para Rust via C++"
description: "Exporta do PDF-documento previamente aberto com AcroForm para XFDF-documento com nome de arquivo."
type: docs
url: /pt/rust-cpp/convert/export_xfdf/
---

_Exporta do PDF-documento previamente aberto com AcroForm para XFDF-documento com nome de arquivo._

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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Exportar do PDF-documento previamente aberto com AcroForm para XFDF-documento
    pdf.export_xfdf("sample.xfdf")?;

    Ok(())
}

```