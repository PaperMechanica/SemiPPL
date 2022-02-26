<div align='center' ><font size='5'>Polyphone Disambiguation in Mandarin Chinese with Semi-Supervised Learning</font></div>&nbsp;


<div align='center' ><font size='2'>Interspeech 2021</font></div>


<div align='center' >Yi&nbsp;Shi*&emsp;Congyi&nbsp;Wang**&emsp;Yu&nbsp;Chen&emsp;Bin&nbsp;Wang</div>&nbsp;

\*First Author \**Corresponding Author

This is the official repo of the interspeech 2021 paper: Polyphone Disambiguation in Mandarin Chinese with Semi-Supervised Learning. Here we provide data and other useful links.

Links
--------

[Paper](https://www.isca-speech.org/archive/interspeech_2021/shi21d_interspeech.html "paper link")&nbsp;|&nbsp;[Video](https://www.youtube.com/watch?v=NTKiiesM8xY "video link")&nbsp;|&nbsp;[Slides](https://drive.google.com/file/d/1lw-d7wbtpt5rzGLdZyI9vQjvtTbh7SQ7/view?usp=sharing)&nbsp;|&nbsp;[DataTest](https://drive.google.com/drive/folders/1pIijtCDfdNzgS5lWHnN3TX_Nrbsa2rwi?usp=sharing)&nbsp;|&nbsp;[DataTrain](https://drive.google.com/drive/folders/1ncEnpttZNxmNMXsQSmytgrK1_2wKujkX?usp=sharing)

Dataset: 
--------
The data is split into training set and test set. The training set is scraped from the internet. The corresponding annotations are auto-labeled using traditional techniques and then fixed manually. The correstness of the training set is not guaranteed, so if you are able to find incorrect labels, please report in the issue section. The testset is created manually and cover some most difficult cases in real life conversations for robustness evaluation.  

The format of training data file: <Char>_aug_<#local label>   
The format of data: Pinyin/space/position/space/sentence/\n 

License:
-------
This is a research conducted by ([Xmov|魔珐科技]https://www.xmov.ai/about/). The usage of the dataset is restricted to eductaion and research purposes only. 

If you would like to cite our paper:

    @inproceedings{shi21semp,
      author={Shi,Yi and Wang,Congyi and Chen,Yu and Wang,Bin},
      title={Polyphone Disambiguation in Mandarin Chinese with Semi-Supervised Learning},
      year={2021},
      booktitle={Proc. Interspeech 2021},
      pages={4109--4113},
      doi={10.21437/Interspeech.2021-502}
    }

For further question, you are welcome to contact shiyi2008@gmail.com 
