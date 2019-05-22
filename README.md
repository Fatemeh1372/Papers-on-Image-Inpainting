# Papers-on-Image-Inpainting

Image inpainting is the process of reconstructing missing parts of an image so that observers are unable to tell that these regions have undergone restoration. This technique is often used to remove unwanted objects from an image or to restore damaged portions of old photos. The figures below show example image-inpainting results.

# Categories base on the Method, and Dataset (faces vs ImageNet)

| Paper-Name                                             | Method                         | Dataset       | Code      |      
| :---                                                   |     :---:                      |    :---:      |  ---:     |
|  [[Deep_image_prior]](https://arxiv.org/abs/1711.10925)| Deep convolutional networks    | git status    |           |
| [[Generative_inpainting_release]](https://arxiv.org/abs/1801.07892)|                    | Faces (CelebA, CelebA-HQ),
textures (DTD) and natural images (ImageNet, Places2)     | git diff  |           |


## Image-Inpainting

[1]	Deep_image_prior: Deep Image Prior. [[paper]](https://arxiv.org/abs/1711.10925)                                    [[code]](https://github.com/DmitryUlyanov/deep-image-prior)

[2]	Generative_inpainting_release: Generative Image Inpainting With Contextual Attention [[paper]](https://arxiv.org/abs/1801.07892) [[code]](https://github.com/JiahuiYu/generative_inpainting)

[3] W.-S. Lai, J.-B. Huang, N. Ahuja, and M.-H. Yang. Deeplaplacian pyramid networks for fast and accurate superresolution. In The IEEE Conference on Computer Vision and Pattern Recognition (CVPR), July 2017. [[project]](http://vllab.ucmerced.edu/wlai24/LapSRN/)

[4] C. Ledig, L. Theis, F. Huszar, J. Caballero, A. Cunningham, A. Acosta, A. Aitken, A. Tejani, J. Totz, Z. Wang, and
W. Shi. Photo-realistic single image super-resolution using a generative adversarial network. In The IEEE Conference
on Computer Vision and Pattern Recognition (CVPR), July 2017. [[paper]](https://arxiv.org/abs/1609.04802) [[code]](https://github.com/tensorlayer/srgan)


## Early methods (Non Learning Based)
[1] Marcelo Bertalmio and Guillermo Sapiro, Vicent Caselles and Coloma Ballester, Image Inpainting, SIGGRAPH, 2000. [[paper]](http://www.dtic.upf.edu/~mbertalmio/bertalmi.pdf)  

[2] Marcelo Bertalmio, Luminita Vese, Guillermo Sapiro, Simultaneous Structure and Texture Image Inpainting, TIP, 2003. [[paper]](http://www.math.ucla.edu/~lvese/PAPERS/01217265.pdf)

[3] A. Criminisi, P. P´erez and K. Toyama, Region Filling and Object Removal by Exemplar-Based Image Inpainting, TIP, 2004. [[paper]](http://www.irisa.fr/vista/Papers/2004_ip_criminisi.pdf)

[4] Jian Sun, Lu Yuan, Jiaya Jia, Heung-Yeung Shum, Image Completion with Structure Propagation, SIGGRAPH, 2005. [[paper]](http://webee.technion.ac.il/cgm/Computer-Graphics-Multimedia/Undergraduate-Projects/2009/ImageCompletion/ImageCompletion_SIGGRAPH05.pdf)

[5] J.-B Huang, S.B. kang, N. Ahuja, and j. Kopf. Image completion using Planar structure guidance. ACM Transactions on graohics (TOG). [[paper]](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/structure_completion_small.pdf) [[code]](https://github.com/jbhuang0604/StructCompletion) [[project]](https://sites.google.com/site/jbhuang0604/publications/struct_completion)



## Deep Architectures (Learning Based)

### CVPR 2019

[1] Zheng, Chuanxia and Cham, Tat-Jen and Cai, Jianfei. Pluralistic Image Completion. CVPR 2019. [[paper]](https://arxiv.org/abs/1903.04227) [[code]](https://github.com/lyndonzheng/Pluralistic-Inpainting) [[project]](http://www.chuanxiaz.com/publication/pluralistic/)

[2] Zeng, Yanhong and Fu, Jianlong and Chao, Hongyang and Guo, Baining. Learning Pyramid-Context Encoder Network for High-Quality Image Inpainting. CVPR 2019. [[paper]](https://arxiv.org/abs/1904.07475) [[code]](https://github.com/researchmm/PEN-Net-for-Inpainting)

[3] Wei Xiong, Jiahui Yu, Zhe Lin, Jimei Yang, Xin Lu, Connelly Barnes, and Jiebo Luo. Foreground-aware Image Inpainting. CVPR 2019. [[paper]](https://arxiv.org/abs/1901.05945)


### Arxiv 2018-2019

[1] Zeyuan Chen, Shaoliang Nie, Tianfu Wu, Christopher G. Healey. High Resolution Face Completion with Multiple Controllable Attributes via Fully End-to-End Progressive Generative Adversarial Networks. Arxiv 2018. [[paper]](https://arxiv.org/pdf/1812.01458.pdf)

[2] Sandipan Banerjee, Walter J. Scheirer, Kevin W. Bowyer, and Patrick J. Flynn. On Hallucinating Context and Background Pixels from a Face Mask using Multi-scale GANs, Arxiv 2018. [[paper]](https://arxiv.org/pdf/1811.07104.pdf)

[3] Jiahui Yu, Zhe Lin, Jimei Yang, Xiaohui Shen, Xin Lu, Thomas S. Huang, Free-Form Image Inpainting with Gated Convolution, arxiv, 2018. [[paper]](https://arxiv.org/abs/1806.03589) [[project]](http://jiahuiyu.com/deepfill2/)

[4] Kamyar Nazeri, Eric Ng, Tony Joseph, Faisal Z. Qureshi, Mehran Ebrahimi. EdgeConnect: Generative Image Inpainting with Adversarial Edge Learning. Arxiv 2019. [[paper]](http://arxiv.org/abs/1901.00212) [[code]](https://github.com/knazeri/edge-connect)

[5] Qingguo Xiao,Guangyao Li,Qiaochuan Chen. Deep Inception Generative network for Cognitive Image Inpainting. Arxiv 2019. [[paper]]( https://arxiv.org/pdf/1812.01458.pdf)

[6] Ryan Webster, Julien Rabin, Lo¨ıc Simon and Fred´ eric Jurie. Detecting Overfitting of Deep Generative Networks via Latent Recovery. Arxiv 2019. [[paper]](https://arxiv.org/pdf/1901.03396.pdf)

[7] Youngjoo Jo, Jongyoul Park. SC-FEGAN: Face Editing Generative Adversarial Network with User’s Sketch. Arxiv 2019. [[paper]](https://arxiv.org/abs/1902.06838) [[code]](https://github.com/JoYoungjoo/SC-FEGAN)

[8] Xin Hong and Pengfei Xiong and Renhe Ji and Haoqiang Fan. Deep Fusion Network for Image completion. Arxiv 2019. [[paper]](https://arxiv.org/abs/1904.08060) [[code]](https://github.com/hughplay/DFNet)


### CVPR 2018

[1] Jiahui Yu, Zhe Lin, Jimei Yang, Xiaohui Shen, Xin Lu, Thomas S. Huang, Generative Image Inpainting with Contextual Attention, CVPR, 2018. [[paper]](https://arxiv.org/abs/1801.07892) [[code]](https://github.com/JiahuiYu/generative_inpainting)  [[project]](http://jiahuiyu.com/deepfill/)

[2] Qianru Sun, Liqian Ma, Seong Joon Oh, Luc Van Gool, Bernt Schiele, Mario Fritz1. Natural and Effective Obfuscation by Head Inpainting, CVPR 2018. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Natural_and_Effective_CVPR_2018_paper.pdf)

[3] Brian Dolhansky, Cristian Canton Ferrer. Eye In-Painting With Exemplar Generative Adversarial Networks, CVPR 2018. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Dolhansky_Eye_In-Painting_With_CVPR_2018_paper.pdf) [[project]](https://bdol.github.io/exemplar_gans/) [[code]](https://github.com/bdol/exemplar_gans)

[4] Jiankang Deng, Shiyang Cheng, Niannan Xue, Yuxiang Zhou, Stefanos Zafeiriou. UV-GAN: Adversarial Facial UV Map Completion for Pose-invariant Face Recognition, CVPR 2018. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Deng_UV-GAN_Adversarial_Facial_CVPR_2018_paper.pdf)

[5] Andrew Gilbert, John Collomosse, Hailin Jin, and Brian Price. Disentangling Structure and Aesthetics for Style-aware Image Completion, CVPR 2018. [[paper]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gilbert_Disentangling_Structure_and_CVPR_2018_paper.pdf)


### ECCV 2018

[1] Guilin Liu, Fitsum A. Reda, Kevin J. Shih, Ting-Chun Wang, Andrew Tao, Bryan Catanzaro, Image Inpainting for Irregular Holes Using Partial Convolutions, ECCV, 2018. [[paper]](https://arxiv.org/abs/1804.07723) [[code]](https://github.com/Jasonnor/PConv-Keras-Food) [[project]](http://masc.cs.gmu.edu/wiki/partialconv)

[2] Yuhang Song, Chao Yang, Zhe Lin, Xiaofeng Liu, Qin Huang, Hao Li, C.-C. Jay Kuo, Contextual-based Image Inpainting: Infer, Match, and Translate, ECCV 2018, [[paper]](https://arxiv.org/abs/1711.08590)

[3] Zhaoyi Yan, Xiaoming Li, Mu Li, Wangmeng Zuo, Shiguang Shan, Shift-Net: Image Inpainting via Deep Feature Rearrangement, ECCV, 2018. [[paper]](https://arxiv.org/abs/1801.09392v2) [[code]](https://github.com/Zhaoyi-Yan/Shift-Net)


### NIPS 2018

[1] Yi Wang, Xin Tao, Xiaojuan Qi, Xiaoyong Shen, Jiaya Jia, Image Inpainting via Generative Multi-column Convolutional Neural Networks, NIPS, 2018. [[paper]](https://arxiv.org/abs/1810.08771) [[code]](https://github.com/shepnerd/inpainting_gmcnn)


### BMVC 2018

[1] Yuhang Song, Chao Yang, Yeji Shen, Peng Wang, Qin Huang, C.-C. Jay Kuo, SPG-Net: Segmentation Prediction and Guidance Network for Image Inpainting, BMVC, 2018. [[paper]](https://arxiv.org/abs/1805.03356)


### MM 2018

[1] Huy V. Vo, Ngoc Q. K. Duong, Patrick Perez, Structural inpainting, MM, 2018. [[paper]](https://arxiv.org/abs/1803.10348)

[2] Haoran Zhang, Zhenzhen Hu, Changzhi Luo, Wangmeng Zuo, Meng Wang. Semantic Image Inpainting with Progressive Generative Networks. MM 2018. [[paper]](https://dl.acm.org/citation.cfm?id=3240625) [[code]](https://github.com/crashmoon/Progressive-Generative-Networks)


### ACCV 2018

[1] Haofu Liao1, Gareth Funka-Lea, Yefeng Zheng, Jiebo Luo and S. Kevin Zhou. Face Completion iwht Semantic Knowledge and Collaborative Adversarial Learning, ACCV, 2018. [[paper]](https://arxiv.org/pdf/1812.03252.pdf)


### ICASSP 2018
[1] Liang Liao, Ruimin Hu, Jing Xiao, Zhongyuan Wang. Edge-Aware Context Encoder for Image Inpainting. [[paper]](http://mirlab.org/conference_papers/International_Conference/ICASSP%202018/pdfs/0003156.pdf)


### ACM Transactions on Graphics (TOG) 2018
[1] Portenier, Tiziano, et al. Faceshop: Deep sketch-based face image editing. [[paper]](https://arxiv.org/abs/1804.08972)


### Siggraph 2017

[1] SATOSHI IIZUKA, EDGAR SIMO-SERRA, HIROSHI ISHIKAWA, Globally and Locally Consistent Image Completion, SIGGRAPH 2017. [[paper]](http://hi.cs.waseda.ac.jp/~iizuka/projects/completion/data/completion_sig2017.pdf) [[code]](https://github.com/satoshiiizuka/siggraph2017_inpainting) [[project]](http://hi.cs.waseda.ac.jp/~iizuka/projects/completion/en/)


### CVPR 2017

[1] Chao Yang, Xin Lu, Zhe Lin, Eli Shechtman, Oliver Wang, Hao Li, High-Resolution Image Inpainting using Multi-Scale Neural Patch Synthesis, CVPR, 2017. [[paper]](https://arxiv.org/abs/1611.09969) [[code]](https://github.com/leehomyc/Faster-High-Res-Neural-Inpainting)

[2] Yijun Li, Sifei Liu, Jimei Yang, and Ming-Hsuan Yang, Generative Face Completion. CVPR, 2017. [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Li_Generative_Face_Completion_CVPR_2017_paper.pdf) [[code]](https://github.com/Yijunmaverick/GenerativeFaceCompletion)

[3] Raymond A. Yeh, Chen Chen, Teck Yian Lim, Alexander G. Schwing, Mark Hasegawa-Johnson, Minh N. Do. Semantic Image Inpainting With Deep Generative Models, CVPR 2017. [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Yeh_Semantic_Image_Inpainting_CVPR_2017_paper.pdf) [[code]](https://github.com/moodoki/semantic_image_inpainting) [[project]](http://www.isle.illinois.edu/~yeh17/projects/semantic_inpaint/index.html)


### CVPR 2016

[1] Deepak Pathak, Philipp Krahenbuhl, Jeff Donahue, Trevor Darrell, Alexei A. Efros, Context Encoders: Feature Learning by Inpainting, CVPR, 2016. [[paper]](https://arxiv.org/abs/1604.07379) [[code]](https://github.com/pathak22/context-encoder)


### NIPS 2015

[1] Jimmy SJ. Ren, Li xu, Qiong Yan, Wenxiu Sun, Shepard Convolutional Neural Networks, NIPS, 2015. [[paper]](https://papers.nips.cc/paper/5774-shepard-convolutional-neural-networks.pdf) [[code]](https://github.com/jimmy-ren/vcnn_double-bladed/tree/master/applications/Shepard_CNN)


## Course Assignments: 

[1] Zhuang Zijun. Pytorch-image-inpainting-using-mixed-convolution.  [[project]](https://github.com/zzj0311/pytorch-image-inpainting-using-mixed-convolution)

[2]  Abhinav Gupta, Suyash Shukla, Vaishnav S. Menon. An Efficient Segmentation Based Pipeline For Image Inpainting. [[project]](https://github.com/abhigupta768/inpainting-pipeline)



# Reference:

[1] Image Inpainting: Humans vs. AI [[Survey blog]](https://github.com/1900zyh/Awesome-Image-Inpainting)

[2] Awesome-Image-Inpainting [[GitHub topics]](https://towardsdatascience.com/image-inpainting-humans-vs-ai-48fc4bca7ecc) 




