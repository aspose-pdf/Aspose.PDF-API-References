---
title: "bytes"
second_title: "Aspose.PDF para Rust via C++"
description: "Retorna o conteúdo do documento PDF como um vetor de bytes."
type: docs
url: /pt/rust-cpp/core/bytes/
---

_Retorna o conteúdo do documento PDF como um vetor de bytes._

```rust
pub fn bytes(&self) -> Result<Vec<u8>, PdfError>
```

**Arguments**


**Returns**
  * **Ok(Vec\<u8\>)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Crie um novo PDF-document
    let pdf = Document::new()?;

    // Retornar o conteúdo do documento PDF como um vetor de bytes
    let data = pdf.bytes()?;

    // Imprimir o comprimento do vetor de bytes
    println!("Length: {}", data.len());

    Ok(())
}

```