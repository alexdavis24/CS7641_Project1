# CS7641_Project1
Machine Learning at Georgia Tech OMSCS - Project 1 (Supervised Learning). This project is focused on exploring the relationships between datasets and several algorithms. To avoid plagiarism, this repository includes only code and no analysis.

## Running Directions
- If a Colab Pro account is available, open the following link: https://colab.research.google.com/drive/1rS4qKo2JteYuVFWaUJSFSESrizCwrAHQ?usp=sharing
  - Run cells #1-4 one after another, waiting until the last one finishes. Then run cells 5 & 6, the latter installing RAPIDS and will take about 15 minutes.
    - Cell #1 should output some kind of GPU – if not, go to Runtime -> Change runtime type -> select "GPU"
    -	Cell #2 should output a message like “Woo! Your instance has the right kind of GPU, a Tesla T4!” If not, Colab has allocated a weak, non-RAPIDS compatible GPU.
    - Go to Runtime -> Factory reset runtime until a valid GPU is installed
    -	Cell #7 (import cuml) imports a RAPIDS package and should load without issues.
- If a Colab Pro account is not active, it is unlikely that a RAPIDS-compatible GPU will be available. Install the attached yml file located here: [TODO], and run all cells in the following link: [TODO]. 
  - As above, the first cell (import cuml) is a good indication that RAPIDS is working properly.
