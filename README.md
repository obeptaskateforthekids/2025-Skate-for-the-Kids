
# Build Process
Using [pdf2htmlEX](https://github.com/pdf2htmlEX/pdf2htmlEX)
- Download Docker [Image](https://hub.docker.com/r/pdf2htmlex/pdf2htmlex/tags)
- ```docker run -ti --rm -v "$(pwd)":/pdf -w /pdf pdf2htmlex/pdf2htmlex:0.18.8.rc2-master-20200820-alpine-3.12.0-x86_64 --zoom 1.3 "assets/SFTK Community Partner Flyer 2025.pdf"```
- mv "SFTK Community Partner Flyer 2025.html" index.html

# TODO:
- Add a build script to automate the process
- Add a script to update the index.html with the latest pdf
- Add a script to update the assets/pdf folder with the latest pdf

# Add Your Domain to GitHub Pages
[Add Custom Domain](https://github.com/obeptaskateforthekids/2025-Skate-for-the-Kids/settings/pages)
www   CNAME   obeptaskateforthekids.github.io

This has been set up for skateforthekidsob.com via https://ap.www.namecheap.com/Domains/DomainControlPanel/skateforthekidsob.com/advancedns
