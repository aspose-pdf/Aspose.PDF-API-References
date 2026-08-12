---
title: "save_n_up"
second_title: "Aspose.PDF para Rust vía C++"
description: "Convierte y guarda el PDF-documento previamente abierto como un documento PDF N-Up."
type: docs
url: /es/rust-cpp/convert/save_n_up/
---

_Convierte y guarda el PDF-documento previamente abierto como un documento PDF N-Up._

```rust
pub fn save_n_up(&self, filename: &str, columns: i32, rows: i32) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file
  * **columns** - the number of columns
  * **rows** - the number of rows

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Convertir y guardar el PDF-documento previamente abierto como documento PDF N-Up
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```