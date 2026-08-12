---
title: "get_meta_info"
second_title: "Aspose.PDF para Rust via C++"
description: "Obtém o valor da informação meta do documento PDF."
type: docs
url: /pt/rust-cpp/core/get_meta_info/
---

_Obtém o valor da informação meta do documento PDF._

```rust
pub fn get_meta_info(&self, key: &str) -> Result<String, PdfError>
```

**Arguments**
  * **key** - the key whose value to get

**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Obter valor da informação meta do documento PDF
    let author = pdf.get_meta_info("Author")?;

    // Imprimir o resultado
    println!("Author: {}", author);

    Ok(())
}

```