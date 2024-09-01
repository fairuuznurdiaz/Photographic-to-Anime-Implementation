# UNSBAnime
## From Photographic to Anime  with Unpaired Image-to-Image Translation via Neural Schrödinger Bridge

# Implementation UNSB in dataset Photographic, to generate photographic image to Anime Image 

We implemented the Unsupervised Neural Style Blending (UNSB) model on a photographic dataset to generate anime-style images, using the Scenimefy dataset available on [GitHub](https://github.com/Yuxinn-J/Scenimefy). The model was based on the implementation found in the [UNSB repository](https://github.com/cyclomon/UNSB). After training the model, the generated images were reviewed, and the results can be viewed in the File ResultUNSB. The output images demonstrated the model's ability to transform photographic images into anime-style visuals effectively.

However, the results are not perfect, primarily due to computational limitations. We were only able to train the model for 6 epochs, which required six days of processing. The extended training time was necessary because of the model's computational demands, which hindered our ability to explore more epochs and potentially improve the quality further. Despite these constraints, the generated images show promise, indicating that with more computational resources and additional training, even higher-quality anime-style images could be produced.


## Refference
Dataset from https://github.com/Yuxinn-J/Scenimefy
Model Implementation from https://github.com/cyclomon/UNSB

## Citation
@inproceedings{jiang2023scenimefy,
  title={Scenimefy: Learning to Craft Anime Scene via Semi-Supervised Image-to-Image Translation},
  author={Jiang, Yuxin and Jiang, Liming and Yang, Shuai and Loy, Chen Change},
  booktitle={ICCV},
  year={2023}
}

## Citation
@InProceedings{
  kim2023unsb,
  title={Unpaired Image-to-Image Translation via Neural Schrödinger Bridge},
  author={Beomsu Kim and Gihyun Kwon and Kwanyoung Kim and Jong Chul Ye},
  booktitle={ICLR},
  year={2024}
}



