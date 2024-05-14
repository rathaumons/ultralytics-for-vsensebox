[![Test Build](https://github.com/rathaumons/ultralytics-for-vsensebox/actions/workflows/test_build.yaml/badge.svg)](https://github.com/rathaumons/ultralytics-for-vsensebox/actions/workflows/test_build.yaml) [![PyPI](https://github.com/rathaumons/ultralytics-for-vsensebox/actions/workflows/publish.yaml/badge.svg)](https://github.com/rathaumons/ultralytics-for-vsensebox/actions/workflows/publish.yaml)

# Customized Ultralytics for VSenseBox

* Updated: **May 14, 2024**
* Synced with: v8.2.15 -> [[590002f]](https://github.com/ultralytics/ultralytics/commit/590002ff6d3a936b0cb1aeb582ea2daa26fcdbb6)
* All credit and info -> [[Original Ultralytics repo]](https://github.com/ultralytics/ultralytics)
* Customized for [`VSenseBox`](https://github.com/rathaumons/vsensebox):
    - Enable OpenCV multithreading
    - Remove restrictions on customized OpenCV
    - Disable dependency auto-install
    - Disable auto update

## Installation

* Install from [PyPI](https://pypi.org/project/vsensebox-ultralytics/):
    ```
    pip install vsensebox-ultralytics
    ``` 
* Or install from GitHub directly:
    ```
    pip install git+https://github.com/rathaumons/ultralytics-for-vsensebox.git
    ```
* Or build from source:

    <details><summary><ins>Click here to expand!</ins></summary>
    
    ```
    git clone https://github.com/rathaumons/ultralytics-for-vsensebox.git
    cd ultralytics-for-vsensebox
    python -m pip install --upgrade pip
    python -m pip install -U pip setuptools
    pip install wheel build
    python -m build --wheel --skip-dependency-check --no-isolatio
    cd dist
    ```
    
    </details>
