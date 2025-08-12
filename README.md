# imaginary-loong64

```bash
# get https://github.com/h2non/imaginary manally for network issuse
cd imaginary-master
go env -w GOPROXY=https://goproxy.cn,direct
go mod tidy       # Ensures go.mod/go.sum have all deps
go mod vendor     # Downloads and stores all deps locally
```