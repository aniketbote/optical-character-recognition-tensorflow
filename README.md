# Optical Character Recognition using CRNN Tensorflow

The code uses concepts from the paper "An end-to-end trainable neural network for image-based sequence recognition and its application to scene text recognition".   
The dataset used for training the model is IAM-database

## Software requirements
- Python 3.8.6
- Tensorflow 2.3.0

## Installation
Create virtual environment (Optional)
```sh
pip install virtualenv
virtualenv venv
```

Install the libraries using req.txt.

```sh
pip install -r req.txt
```

Run the **optical character recognition** notebook

## Citations
> @article{shi2016end,
  title={An end-to-end trainable neural network for image-based sequence recognition and its application to scene text recognition},
  author={Shi, Baoguang and Bai, Xiang and Yao, Cong},
  journal={IEEE transactions on pattern analysis and machine intelligence},
  volume={39},
  number={11},
  pages={2298--2304},
  year={2016},
  publisher={IEEE}
}

> @article{marti2002iam,
  title={The IAM-database: an English sentence database for offline handwriting recognition},
  author={Marti, U-V and Bunke, Horst},
  journal={International Journal on Document Analysis and Recognition},
  volume={5},
  number={1},
  pages={39--46},
  year={2002},
  publisher={Springer}
}
