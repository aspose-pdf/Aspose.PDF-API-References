---
title: "optimize"
second_title: "Aspose.PDF para Rust via C++"
description: "Otimiza o conteúdo do documento PDF."
type: docs
url: /pt/rust-cpp/organize/optimize/
---

_Otimiza o conteúdo do documento PDF._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // Otimizar o conteúdo do documento PDF
    pdf.optimize()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```