---
title: "flatten"
second_title: "Aspose.PDF para Rust via C++"
description: "Achata PDF-documento."
type: docs
url: /pt/rust-cpp/organize/flatten/
---

_Achata PDF-documento._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Retornar o conteúdo do documento PDF como texto simples
    let txt = pdf.extract_text()?;

    // Imprimir texto extraído
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```