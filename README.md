# Musical Dice Game

This repository contains a Python implementation of Mozart's musical dice game ([Musikalisches Würfelspiel](https://en.wikipedia.org/wiki/Musikalisches_W%C3%BCrfelspiel)). It allows you to automatically create pieces of music and play them over MIDI to your DAW or MIDI instrument. 

## Getting Started

### Prerequisites

* [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) must be installed on your machine.
* You should have basic knowledge of using Anaconda or Miniconda.

### Installing

1. Clone the repository:
```bash
git clone https://github.com/afvanwoudenberg/musical-dice-game.git
```

2. Navigate into the project folder:
```bash
cd musical-dice-game
```

3. Create the conda environment from the environment.yml file:
```bash
conda env create -f environment.yml
```

4. Activate the conda environment:
```bash
conda activate musical-dice-game
```

5. Start Jupyter Notebook:
```bash
jupyter notebook
```

6. Open `musikalisches_wuerfelspiel.ipynb` in the browser and run the notebook. Running all cells will create a simple GUI that allows you to create new compositions and play them over MIDI to a DAW or MIDI instrument.

### Additional Files

Some included files that might be of interest:

| File                                                                             | Description                                                                          |
|:---------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------|
| [musikalisches_wuerfelspiel_scanned.pdf](musikalisches_wuerfelspiel_scanned.pdf) | Scan of the original                                                                 |
| [musikalisches_wuerfelspiel.mscz](musikalisches_wuerfelspiel.mscz)               | Digitized version in MuseScore format                                                |
| [musikalisches_wuerfelspiel.mxl](musikalisches_wuerfelspiel.mxl)                 | Digitized version in MusicXML format                                                 |
| [musikalisches_wuerfelspiel.pdf](musikalisches_wuerfelspiel.pdf)                 | Printable version                                                                    |
| [musikalisches_wuerfelspiel.mid](musikalisches_wuerfelspiel.mid)                 | MIDI file that contains all music fragments which is loaded by the Python program    |
| [musikalisches_wuerfelspiel.mp3](musikalisches_wuerfelspiel.mp3)                 | Audio version of a composition                                                       |

### Links

Blog post: https://aswinvanwoudenberg.com/posts/musikalisches-wuerfelspiel/

## Author

Aswin van Woudenberg ([afvanwoudenberg](https://github.com/afvanwoudenberg))

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

