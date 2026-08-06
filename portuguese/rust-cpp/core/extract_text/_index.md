---
title: "extract_text"
second_title: "Aspose.PDF para Rust via C++"
description: "Retorna o conteúdo do documento PDF como texto simples."
type: docs
url: /pt/rust-cpp/core/extract_text/
---

_Retorna o conteúdo do documento PDF como texto simples._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
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