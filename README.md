# FXV - Filename Extension Validator

## Installation
```bash
go get github.com/CasperHK/fxv
```
```go
import (
    "github.com/CasperHK/fxv"
)
```

## Usage
```go
isValidExt := fxv.isValidExt("/tmp/demo.zip", fxv.ACCEPT, []string{"zip", "7zip", "rar"})
```
