[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)

# Path Integral

## Dependency

- [python](https://www.python.org/)
  - version 3.10 or higher is recommended.

- [poetry](https://python-poetry.org/)
  - seting up python environment easily and safely.

- [ffmpeg](https://ffmpeg.org/)
  - mp4 movie writer
  - <details>
    <summary>installation details</summary>

    - For Ubuntu Users
        - `sudo apt-get update`
        - `sudo apt-get -y install ffmpeg`
    - For Windows Users
        - Install [scoop](https://scoop.sh/)
        - `scoop install ffmpeg`
    - For macOS Users
        - Install [homebrew](https://brew.sh/)
        - `brew install ffmpeg`
    - Check the official website if necessary
        - https://ffmpeg.org/

    </details>

## Setup
```sh
git clone https://github.com/MizuhoAOKI/python_simple_mppi.git
cd python_simple_mppi
poetry install
```

## Run Diffusion Process Simulations

### Ex. 1
```sh
cd path_integral
poetry run jupyter notebook notebooks/path_integral_diffusion_ex1.ipynb
```
https://github.com/MizuhoAOKI/path_integral/assets/63337525/5ed2dd19-884a-452f-a303-33b11c874280

### Ex. 2
```sh
cd path_integral
poetry run jupyter notebook notebooks/path_integral_diffusion_ex2.ipynb
```
https://github.com/MizuhoAOKI/path_integral/assets/63337525/68e19968-61b2-4041-b754-8cb8e946e93a

### Ex. 3
```sh
cd path_integral
poetry run jupyter notebook notebooks/path_integral_diffusion_2d.ipynb
```
https://github.com/MizuhoAOKI/path_integral/assets/63337525/043c4714-5b6d-4a8d-afa9-857a8bd11911

### Ex. 4
```sh
cd path_integral
poetry run jupyter notebook notebooks/path_integral_diffusion_2d_double_slit.ipynb
```
https://github.com/MizuhoAOKI/path_integral/assets/63337525/2c59f96e-dcff-4299-9284-dbbd78885a74
