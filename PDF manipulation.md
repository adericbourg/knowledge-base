# Scale PDF

```sh
apt install texlive-extra-utils
```

```sh
pdfjam --outfile output.pdf --paper a2paper example.pdf
```

[List of paper sizes](https://texdoc.org/serve/geometry.pdf/0)

# Split PDF vertically / horizontally

```sh
apt install mupdf-tools
```

```sh
# Vertical
mutool poster -x 2 input.pdf output.pdf
```

```sh
# Horizontal
mutool poster -y 2 input.pdf output.pdf
```

#pdf #linux #tools
