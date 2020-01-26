# Install

download template: https://arc42.org/download

install gem: 

```bash
sudo apt-get install rubygems
```

install asciidoctor: 

```bash
sudo gem install asciidoctor
```

install asciidoctor-diagram: 

```bash
sudo gem install asciidoctor-diagram
```

## Build

```bash
asciidoctor architecture.adoc -r asciidoctor-diagram -D build
```

## VS Code

add this to `settings.json`

```json
    "asciidoc.preview.useEditorStyle": false,
    "asciidoc.use_asciidoctor_js": false,
    "asciidoc.asciidoctor_command": "asciidoctor -r asciidoctor-diagram -o-"
```