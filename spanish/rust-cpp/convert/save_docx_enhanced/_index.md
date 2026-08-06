---
title: "save_docx_enhanced"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el PDF-documento previamente abierto como un documento DOCX con Modo de Reconocimiento Mejorado (tablas y párrafos totalmente editables)."
type: docs
url: /es/rust-cpp/convert/save_docx_enhanced/
---

_Convierte y guarda el PDF-documento previamente abierto como un documento DOCX con Modo de Reconocimiento Mejorado (tablas y párrafos totalmente editables)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
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

    // Convertir y guardar el PDF-documento previamente abierto como documento DocX con Modo de Reconocimiento Mejorado (tablas y párrafos totalmente editables)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```