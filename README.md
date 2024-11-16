# Notes

You can view the rendered version of these notes at TBD.

---

This repository contains a collection of literature notes I've been accumulating since 2024 and a [slipbox](https://en.wikipedia.org/wiki/Zettelkasten) of ideas that I've more recently accumulating. The aim is not to provide a collection of information that will be very useful to many people, as it's very tailor to my own interested, but to provide an example of Zettelkasten tailored towards software develpoers.

The notes are taken using Notion.
## Reference

The [literature](literature) folder contains notes collected mostly from MOOCs but also books, papers and videos.

## Slipbox

The [slipbox](slipbox) folder contains permanent notes which I've collected from reading and thinking. The idea is that each note contains one idea and all ideas are interlinked.

## Generating HTML

This project uses Pelican to generate a HTML version of the notes. You can generate the notes using the following command:

### Create a virtualenv (optional)

```
python3 -m venv .env
source .env/bin/activate
```

### Run setup script

```
./setup.sh
```

### Build

To build the blog without running setup, use the `build.sh` script:

```
./build.sh
