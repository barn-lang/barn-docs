+++
title = "Download Barn to your machine"
weight = 1
sort_by = "weight"
insert_anchor_links = "right"
+++

# Dependeces
- GoLang compiler
- Bash (for unix)
- GCC
# MacOS & Linux
```bash
git clone https://github.com/solindekdev/barn
cd barn
bash build.sh
cp ./barn /bin/barn
barn # Should work fine
```
# Windows
```bash
git clone https://github.com/solindekdev/barn
cd barn
go build
./barn # Should work fine
```