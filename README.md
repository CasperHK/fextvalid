# FXV - Filename Extension Validator
A light-weight implementation of filename extension validator with no depandencies.

<br/>

## Installation
```bash
go get github.com/CasperHK/fxv
```

<br/>

## Usage

```go
import (
    "github.com/CasperHK/fxv"
)
```

```go
isValidExt := fxv.isValidExt("/tmp/demo.zip", fxv.ACCEPT, []string{"zip", "7zip", "rar"})
```
