<h1 align="center">GWaste: Get to know your Waste</h1>
<h3 align="center">Waste Classifer</h3>

This repository contains our notebooks and dataset that we used when exploring our dataset, building our model, and testing our middleware. These notebooks was run on Google Colab environment.

## Dataset

We used trashnet by Gary Thung. You can get the original one from [here](https://github.com/garythung/trashnet).

We have our two versions of that dataset, which is `v1` and `v2`. Both of this dataset originally from [`dataset-resized.zip`](https://github.com/garythung/trashnet/raw/master/data/dataset-resized.zip). [`v1`](https://github.com/GWaste/waste-classifer/raw/main/datasets/dataset-v1.zip) is the version where we manually classify and merged the "trash" class to the other classes. While [`v2`](https://github.com/GWaste/waste-classifer/raw/main/datasets/dataset-v2.zip) is the version with "trash" class entirely removed from the dataset.

<!-- GETTING STARTED -->

## Getting Started

<p align="center">
  <table>
    <td>
      <a target="_blank" href="https://colab.research.google.com/github/GWaste/waste-classifer/blob/main/notebooks/models/model_final.ipynb"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>
    </td>
    <td>
      <a target="_blank" href="https://github.com/GWaste/waste-classifer/blob/main/notebooks/models/model_final.ipynb"><img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />View source on GitHub</a>
    </td>
    <td>
      <a href="https://github.com/GWaste/waste-classifer/raw/main/notebooks/models/model_final.ipynb"><img src="https://www.tensorflow.org/images/download_logo_32px.png" />Download notebook</a>
    </td>
  </table>
</p>

For all of process that we do, we are using Google Colab (you can choose on the link above). But you can use local instead by several steps:

### Prerequisites

- [Python 3.6 - 3.8](https://www.python.org/downloads/)
- [Python Virtual Environtment](https://www.python.org/downloads/)

### Run Locally

1. Download [notebook](https://github.com/GWaste/waste-classifer/raw/main/notebooks/models/model_final.ipynb)

2. Clone the project [Optional]

   ```sh
   $ git clone https://github.com/GWaste/waste-classifer
   ```

3. Go to the project directory

   ```sh
   $ cd waste-classifer
   ```

4. Install the required library with virtualenv

   - Linux/ MacOS
     ```sh
     $ virtualenv env
     $ source env/bin/activate
     (venv) $ pip install numpy matplotlib tensorflow
     ```
   - Windows
     ```sh
     python -m venv env
     env\scripts\activate
     pip install numpy matplotlib tensorflow
     ```

5. Run with [jupyter notebook](https://jupyter.org/)

   ```sh
   $ jupyter notebook
   ```
<!-- CONTRIBUTING -->
  
## Contributing

Contributions are always welcome!

Feel free to clone, use, and contribute via pull request.

Got an issue? Please use [issues panel](https://github.com/GWaste/waste-classifer/issues)

We are exciting to see your contributions!

<!-- FEEDBACK -->

## Feedback

If you have any feedback, please reach out to us at b21-cap0331@bangkit.academy
or contact one of our member.

<!-- AUTHORS -->

## Authors

### Model
- [Ilham Syahid S](https://www.github.com/ilhamsyahids)
- [Antony Kurniawan S](https://github.com/Smankusors)

### Other member
- [Denny Rezky S](https://github.com/sinulingga23)
- [Defi Oktri S](https://github.com/defioktri99)

<!-- RELATED PAPER -->
  
## Related Paper

Here are some related paper that we used:

[Fine-Tuning Models Comparisons on Garbage Classification for
Recyclability](https://arxiv.org/ftp/arxiv/papers/1908/1908.04393.pdf)

[Comparative Analysis of Multiple Deep CNN Models for Waste
Classification](https://arxiv.org/pdf/2004.02168.pdf)

<!-- APPENDIX -->

## Appendix

- [Original Dataset](https://github.com/garythung/trashnet)

<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

 - [Bangkit](http://bangkit.academy/)
 - [GWaste](https://github.com/GWaste/Introduction)

