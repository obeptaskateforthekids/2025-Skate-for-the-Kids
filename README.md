
## Build Process
Using [pdf2htmlEX](https://github.com/pdf2htmlEX/pdf2htmlEX)
- Download Docker [Image](https://hub.docker.com/r/pdf2htmlex/pdf2htmlex/tags)
- ```docker run -ti --rm -v "$(pwd)":/pdf -w /pdf pdf2htmlex/pdf2htmlex:0.18.8.rc2-master-20200820-alpine-3.12.0-x86_64 --zoom 1.3 "assets/SFTK Community Partner Flyer 2025.pdf"```
- mv "SFTK Community Partner Flyer 2025.html" to index.html