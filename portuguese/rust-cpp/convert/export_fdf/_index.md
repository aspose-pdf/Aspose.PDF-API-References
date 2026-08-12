---
title: "export_fdf"
second_title: "Aspose.PDF para Rust via C++"
description: "Exporta do documento PDF previamente aberto com AcroForm para documento FDF com nome de arquivo."
type: docs
url: /pt/rust-cpp/convert/export_fdf/
---

_Exporta do documento PDF previamente aberto com AcroForm para documento FDF com nome de arquivo._

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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Exportar do documento PDF previamente aberto com AcroForm para documento FDF
    pdf.export_fdf("sample.fdf")?;

    Ok(())
}

```