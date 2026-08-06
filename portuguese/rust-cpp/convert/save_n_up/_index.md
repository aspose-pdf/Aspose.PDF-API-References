---
title: "save_n_up"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o documento PDF aberto anteriormente como um documento PDF N-Up."
type: docs
url: /pt/rust-cpp/convert/save_n_up/
---

_Converte e salva o documento PDF aberto anteriormente como um documento PDF N-Up._

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
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converter e salvar o documento PDF aberto anteriormente como documento PDF N-Up
    pdf.save_n_up("sample_n_up.pdf", 2, 2)?;

    Ok(())
}
```