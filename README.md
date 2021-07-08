# DeePROG

## This is the readme file that contains the guidelines and information about the compilation of the code of the following paper

**Paper Name:-** DeePROG: Deep Attention-based Model for Diseased Gene Prognosis by Fusing Multi-omics Data
- **Authors:** Pratik Dutta, Aditya Prakash Patra, and Sriparna Saha 
- **Affiliation:**  Department of Computer Science and Engineering, IIT Patna, India. 
- **Accepted:** [IEEE/ACM Transactions on Computational Biology and Bioinformatics](https://www.computer.org/csdl/journal/tb)

![multi-modal](https://user-images.githubusercontent.com/29531232/72711214-9508d400-3b8e-11ea-8016-dc25a37e87f8.png)

## Prerequisities
* **[Python 2.7+](https://www.python.org/downloads/release/python-2713/)**
* **[sklearn](https://scikit-learn.org/stable/install.html)**
* **[matplotlib 2.0+](https://matplotlib.org/users/installing.html)**
* **[mpl_toolkits](https://matplotlib.org/2.0.2/mpl_toolkits/index.html)**
* **[numpy 1.10+](https://pypi.org/project/numpy/)**
* **[Pytorch](https://pytorch.org/)**
* **[Keras](https://keras.io/)**


## Dataset
It contains three modalities of all three disease gene datsets. These three modalities are
* **Gene Expression Profile**  Uploaded in Github.
* **Underlying FASTA sequence** Download from the [google link](https://drive.google.com/drive/folders/1qg_FRrRQn8k9JGNJaRlEY1no2Q5Xlo3-?usp=sharing).
* **3D PDB structure** Due to large size, you can download partial data from the [google link](https://drive.google.com/drive/folders/1ZfaqRF3QlhrWzWc53IDAmLSUEaHZ714R?usp=sharing).


## Multi-modality Codes

It contains `.ipynb` (Jupyter Notebok) files for all deep learning-based multi-modal architectures for all three disease gene datasets(**_BCLL_**, **_ILD_** and **_Prostrate_**). For each datasets, we have created three separate folders. Each folders contain `Unimodal`, `Bimodal` and `Trimodal` subfolders that contains the `python` scripts of **`self attention-based`** deep multi-modal architectures.   

The details procedure of running the code will be described after accepting or upon a personal request in my [official email ID](mailto:pratik.pcs16@iitp.ac.in).  




## Contribution
This work currently is under revision in a peer reviewed journal. For use the code or the preprocessed dataset, please open an issue first to discuss what you would like to do. Also you can contact to the corresponding author Pratik Dutta (pratik.pcs16@iitp.ac.in / pratik24111991@gmail.com)

## Citation
If you consider this work as useful, please cite it as 
```bash
@article{dutta2021deeprog,
  title={DeePROG: Deep Attention-based Model for Diseased Gene Prognosis by Fusing Multi-omics Data.},
  author={Dutta, Pratik and Patra, Aditya Prakash and Saha, Sriparna},
  journal={IEEE/ACM Transactions on Computational Biology and Bioinformatics},
  year={2021}
}
```


