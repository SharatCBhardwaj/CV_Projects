# Image I/O Basics (Day 1)

This mini-project demonstrates **reading an image from disk, displaying it**, and **inspecting its size/dimensions** using Python, OpenCV, and Jupyter Notebook.

## What's inside
- `Day1.ipynb` — Jupyter notebook with step-by-step code cells.
- `requirements.txt` — dependencies to run the notebook.
- `.gitignore` — ignores temporary files/notebook checkpoints.

## Quick start
```bash
# (Optional) create & activate a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
# then open Day1.ipynb in your browser
```

## Notes
- Update the image **path** in the notebook to point to a local image file, e.g. `./data/sample.jpg` or an absolute path.
- If you use OpenCV's `cv2.imshow` in a notebook environment, it may not open a separate window. Prefer `matplotlib.pyplot.imshow` inside notebooks.

## Next steps
- Add a `data/` folder with a sample image and show results.
- Print image **width, height, channels**, and **dtype**.
- Save a resized/gray version to `output/` and display before/after.
- Commit and push changes to GitHub.
