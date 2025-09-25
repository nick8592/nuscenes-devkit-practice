
# nuscenes-devkit-practice

## Project Overview
Practice and experimentation with the nuScenes devkit and dataset in Python/Jupyter.

## Setup Instructions
1. Clone this repository.
2. Install dependencies:
	```bash
	pip install -r requirements.txt
	```
3. Link your nuScenes dataset folder:
	```bash
	ln -s /path/to/your/nuscenes ./nuscenes
	```
	Replace `/path/to/your/nuscenes` with the actual path to your dataset. The folder should contain subfolders like `v1.0-mini`.

## Usage
Open `main.ipynb` in Jupyter or VS Code and run the cells to explore scenes, samples, annotations, and more.

## Notes
- The `.gitignore` excludes the dataset symlink and cache files.
- Make sure your dataset path is correct and accessible.
