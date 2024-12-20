# Image Clustering Project

This project implements image clustering using embeddings generated by the ImageBind model. The goal is to group similar images based on their visual features.

## Project Structure

- **data/images**: This directory contains the images used for clustering.
- **notebooks/image_clustering.ipynb**: A Jupyter notebook that includes code for:
  - Loading images
  - Generating embeddings using ImageBind
  - Performing clustering on the embeddings
  - Visualizing the results
- **requirements.txt**: Lists the dependencies required for the project.

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd image-clustering-project
   ```

2. **Create a virtual environment** (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```
   pip install -r requirements.txt
   ```

## Running the Notebook

1. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

2. Open `notebooks/image_clustering.ipynb`.

3. Follow the instructions in the notebook to load images, generate embeddings, perform clustering, and visualize the results.

## License

This project is licensed under the MIT License.