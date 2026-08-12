---
title: "정보"
second_title: "C++를 통해 Rust용 Aspose.PDF"
description: "C++를 통해 Aspose.PDF for Rust에 대한 메타데이터 정보를 반환합니다."
type: docs
url: /ko/rust-cpp/miscellaneous/about/
---

_C++를 통해 Aspose.PDF for Rust에 대한 메타데이터 정보를 반환합니다._

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // 새 PDF 문서를 생성합니다
    let pdf = Document::new()?;

    // C++를 통해 Aspose.PDF for Go에 대한 메타데이터 정보를 반환합니다.
    let info = pdf.about()?;

    // 메타데이터 필드 출력
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```