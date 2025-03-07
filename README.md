# Personalization Image Generation with Generative Models

This repo is used for recording and tracking recent personalized image generation with different generative models. For more detailed information, please refer to our survey paper: [Personalized Image Generation with Deep Generative Models: A Decade Survey](https://arxiv.org/pdf/2502.13081).

![](assets/personalization_methods.png)

## Contents

![](assets/outline.png)

- [Personalization with Diffusion Models](#Personalization-with-Diffusion-Models)
    - [Subject-Driven Generation](#Subject-Driven-Generation)
    - [Face-Driven Generation](#Face-Driven-Generation)
    - [Character-Driven Generation](#Character-Driven-Generation)
    - [Style-Driven Generation](#Style-Driven-Generation)
    - [High-level Semantics Generation](#High-level-Semantics-Generation)
    - [Multiple Concepts Generation](#Multiple-Concepts-Generation)
    - [Text-driven Image Editing](#Text-driven-Image-Editing)
    - [Personalized Video Generation](#Personalized-Video-Generation)
    - [Personalized 3D Generation](#Personalized-3D-Generation)
- [Personalization with AR Models](#Personalization-with-AR-Models)
- [Personalization with GANs](#Personalization-with-GANs)
  - [GAN Inversion](#GAN-Inversion)
  - [Latent Editing](#Latent-Editing)
- [Related Surveys](#Related-Surveys)


## Personalization with Diffusion Models

### Subject-Driven Generation

**ACCORD: Alleviating Concept Coupling through Dependence Regularization for Text-to-Image Diffusion Personalization**<br>
*Shizhan Liu, Hao Zheng, Hang Yu, Jianguo Li*<br>
Arxiv 2025. / [PDF](https://www.arxiv.org/abs/2503.01122)

**Generating Multi-Image Synthetic Data for Text-to-Image Customization**<br>
*Nupur Kumari, Xi Yin, Jun-Yan Zhu, Ishan Misra, Samaneh Azadi*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.01720) / [Project](https://www.cs.cmu.edu/~syncd-project/) / [Code](https://github.com/nupurkmr9/syncd)

**Beyond Fine-Tuning: A Systematic Study of Sampling Techniques in Personalized Image Generation**<br>
*Vera Soboleva, Maksim Nakhodnov, Aibek Alanov*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.05895) 

**Nested Attention: Semantic-aware Attention Values for Concept Personalization**<br>
*Patashnik, Or and Gal, Rinon and Ostashev, Daniil and Tulyakov, Sergey and Aberman, Kfir and Cohen-Or, Daniel.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.01407)  / [Project](https://snap-research.github.io/NestedAttention/)

**AnyDressing: Customizable Multi-Garment Virtual Dressing via Latent Diffusion Models**<br>
*Li, Xinghui and Sun, Qichao and Zhang, Pengze and Ye, Fulong and Liao, Zhichao and Feng, Wanquan and Zhao, Songtao and He, Qian.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2412.04146)  / [Project](https://crayon-shinchan.github.io/AnyDressing/)  / [Code](https://github.com/Crayon-Shinchan/AnyDressing)

**Customized Generation Reimagined: Fidelity and Editability Harmonized**<br>
*Jin, Jian and Shen, Yang and Fu, Zhenyong and Yang, Jian.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2412.04831v1)  / [Code](https://github.com/jinjianRick/DCI_ICO)

**P3S-Diffusion: A Selective Subject-driven Generation Framework via Point Supervision**<br>
*Hu, Junjie and Gao, Shuyong and Hong, Lingyi and Wang, Qishan and Zhao, Yuzhou and Wang, Yan and Zhang, Wenqiang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.19533)

**Large-Scale Text-to-Image Model with Inpainting is a Zero-Shot Subject-Driven Image Generator**<br>
*Shin, Chaehun and Choi, Jooyoung and Kim, Heeseung and Yoon, Sungroh.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15466)  / [Project](https://diptychprompting.github.io/)

**DreamCache: Finetuning-Free Lightweight Personalized Image Generation via Feature Caching**<br>
*Aiello, Emanuele and Michieli, Umberto and Valsesia, Diego and Ozay, Mete and Magli, Enrico.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.17786)  / [Project](https://emanuele97x.github.io/DreamCache/)  / [Code](https://github.com/Emanuele97x/DreamCache)

**Diffusion Self-Distillation for Zero-Shot Customized Image Generation**<br>
*Cai, Shengqu and Chan, Eric and Zhang, Yunzhi and Guibas, Leonidas and Wu, Jiajun and Wetzstein, Gordon.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2411.18616)  / [Project](https://primecai.github.io/dsd/) / [Code](https://github.com/primecai/diffusion-self-distillation)

**DreamBlend: Advancing personalized fine-tuning of text-to-image diffusion models**<br>
*Ram, Shwetha and Neiman, Tal and Feng, Qianli and Stuart, Andrew and Tran, Son and Chilimbi, Trishul.*<br>
WACV 2025.  / [PDF](https://arxiv.org/abs/2411.19390v1)

**OminiControl: Minimal and Universal Control for Diffusion Transformer**<br>
*Tan, Zhenxiong and Liu, Songhua and Yang, Xingyi and Xue, Qiaochu and Wang, Xinchao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15098)  / [Code](https://github.com/Yuanshi9815/OminiControl)

**One Diffusion to Generate Them All**<br>
*Le, Duong H. and Pham, Tuan and Lee, Sangho and Clark, Christopher and Kembhavi, Aniruddha and Mandt, Stephan and Krishna, Ranjay and Lu, Jiasen.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.16318v1)  / [Project](https://lehduong.github.io/OneDiffusion-homepage/)  / [Code](https://github.com/lehduong/OneDiffusion)

**Cusconcept: Customized visual concept decomposition with diffusion models**<br>
*Xu, Zhi and Hao, Shaozhe and Han, Kai.*<br>
WACV 2025.  / [PDF](https://arxiv.org/abs/2410.00398)  / [Code](https://github.com/xzLcan/CusConcept)

**DisEnvisioner: Disentangled and Enriched Visual Prompt for Customized Image Generation**<br>
*He, Jing and Li, Haodong and Hu, Yongzhe and Shen, Guibao and Cai, Yingjie and Qiu, Weichao and Chen, Ying-Cong.*<br>
ICLR 2025.  / [PDF](https://arxiv.org/abs/2410.02067)  / [Project](https://disenvisioner.github.io/)  / [Code](https://github.com/EnVision-Research/DisEnvisioner)

**HybridBooth: Hybrid Prompt Inversion for Efficient Subject-Driven Generation**<br>
*Guan, Shanyan and Ge, Yanhao and Tai, Ying and Yang, Jian and Li, Wei and You, Mingyu.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2410.08192v1)  / [Project](https://sites.google.com/view/hybridbooth)

**Learning to Customize Text-to-Image Diffusion In Diverse Context**<br>
*Kim, Taewook and Chen, Wei and Qiu, Qiang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.10058)

**ArtiFade: Learning to Generate High-quality Subject from Blemished Images**<br>
*Yang, Shuya and Hao, Shaozhe and Cao, Yukang and Wong, Kwan-Yee K.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2409.03745) / [Project](https://wp2023.cs.hku.hk/fyp23045/)

**CustomContrast: A Multilevel Contrastive Perspective For Subject-Driven Text-to-Image Customization**<br>
*Chen, Nan and Huang, Mengqi and Chen, Zhuowei and Zheng, Yang and Zhang, Lei and Mao, Zhendong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.05606)  / [Project](https://cn-makers.github.io/CustomContrast/)

**EZIGen: Enhancing zero-shot subject-driven image generation with precise subject encoding and decoupled guidance**<br>
*Duan, Zicheng and Ding, Yuxuan and Gou, Chenhui and Zhou, Ziqin and Smith, Ethan and Liu, Lingqiao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.08091)  / [Project](https://zichengduan.github.io/pages/EZIGen/index.html)  / [Code](https://github.com/ZichengDuan/EZIGen)

**TextBoost: Towards One-Shot Personalization of Text-to-Image Models via Fine-tuning Text Encoder**<br>
*Park, NaHyeon and Kim, Kunhee and Shim, Hyunjung.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.08248)  / [Project](https://textboost.github.io/)  / [Code](https://github.com/nahyeonkaty/textboost)

**OmniGen: Unified image generation**<br>
*Xiao, Shitao and Wang, Yueze and Zhou, Junjie and Yuan, Huaying and Xing, Xingrun and Yan, Ruiran and Wang, Shuting and Huang, Tiejun and Liu, Zheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.11340)  / [Project](https://vectorspacelab.github.io/OmniGen/)  / [Code](https://github.com/VectorSpaceLab/OmniGen)

**Equilibrated Diffusion: Frequency-aware Textual Embedding for EquilibratedImage Customization**<br>
*Liyuan Ma, Xueji Fang, Guo-Jun Qi*<br>
ACM MM 2024 Oral. / [PDF](https://openreview.net/pdf?id=ERuypCHYvX) / [Project](https://maple-aigc.github.io/EqDiff/) / [Code](https://github.com/maple-research-lab/EqDiff)

**IPAdapter-Instruct: Resolving Ambiguity in Image-based Conditioning using Instruct Prompts**<br>
*Rowles, Ciara and Vainer, Shimon and De Nigris, Dante and Elizarov, Slava and Kutsy, Konstantin and Donné, Simon.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.03209)  / [Project](https://unity-research.github.io/IP-Adapter-Instruct.github.io/)  / [Code](https://github.com/unity-research/IP-Adapter-Instruct)

**BRAT: Bonus oRthogonAl Token for Architecture Agnostic Textual Inversion**<br>
*Baker, James.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.04785)  / [Code](https://github.com/jamesBaker361/tex_inv_plus)

**RealCustom++: Representing Images as Real-Word for Real-Time Customization**<br>
*Mao, Zhendong and Huang, Mengqi and Ding, Fei and Liu, Mingcong and He, Qian and Chang, Xiaojun and Zhang, Yongdong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.09744)

**CoRe: Context-Regularized Text Embedding Learning for Text-to-Image Personalization**<br>
*Wu, Feize and Pang, Yun and Zhang, Junyi and Pang, Lianyu and Yin, Jian and Zhao, Baoquan and Li, Qing and Mao, Xudong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.15914)

**Dreambench++: A human-aligned benchmark for personalized image generation**<br>
*Peng, Yuang and Cui, Yuxin and Tang, Haomiao and Qi, Zekun and Dong, Runpei and Bai, Jing and Han, Chunrui and Ge, Zheng and Zhang, Xiangyu and Xia, Shu-Tao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2406.16855)  / [Project](https://dreambenchplus.github.io/)  / [Code](https://github.com/yuangpeng/dreambench_plus)

**JeDi: Joint-Image Diffusion Models for Finetuning-Free Personalized Text-to-Image Generation**<br>
*Zeng, Yu and Patel, Vishal M and Wang, Haochen and Huang, Xun and Wang, Ting-Chun and Liu, Ming-Yu and Balaji, Yogesh.*<br>
CVPR 2024.  / [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Zeng_JeDi_Joint-Image_Diffusion_Models_for_Finetuning-Free_Personalized_Text-to-Image_Generation_CVPR_2024_paper.html)

**Improving Subject-Driven Image Synthesis with Subject-Agnostic Guidance**<br>
*Chan, Kelvin CK and Zhao, Yang and Jia, Xuhui and Yang, Ming-Hsuan and Wang, Huisheng.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2405.01356)

**Non-confusing Generation of Customized Concepts in Diffusion Models**<br>
*Lin, Wang and Chen, Jingyuan and Shi, Jiaxin and Zhu, Yichen and Liang, Chen and Miao, Junzhong and Jin, Tao and Zhao, Zhou and Wu, Fei and Yan, Shuicheng and {others}.*<br>
ICML 2024.  / [PDF](https://arxiv.org/abs/2405.06914)  / [Project](https://clif-official.github.io/clif/)  / [Code](https://github.com/clif-official/clif_code)

**FreeTuner: Any Subject in Any Style with Training-free Diffusion**<br>
*Xu, Youcan and Wang, Zhen and Xiao, Jun and Liu, Wei and Chen, Long.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.14201)

**Personalized Residuals for Concept-Driven Text-to-Image Generation**<br>
*Ham, Cusuh and Fisher, Matthew and Hays, James and Kolkin, Nicholas and Liu, Yuchen and Zhang, Richard and Hinz, Tobias.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2405.12978v1)  / [Project](https://cusuh.github.io/personalized-residuals/)

**Moma: Multimodal llm adapter for fast personalized image generation**<br>
*Song, Kunpeng and Zhu, Yizhe and Liu, Bingchen and Yan, Qing and Elgammal, Ahmed and Yang, Xiao.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2404.05674v1)  / [Project](https://moma-adapter.github.io/)  / [Code](https://github.com/bytedance/MoMA)

**Moa: Mixture-of-attention for subject-context disentanglement in personalized image generation**<br>
*Wang, Kuan-Chieh and Ostashev, Daniil and Fang, Yuwei and Tulyakov, Sergey and Aberman, Kfir.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2404.11565v2)  / [Project](https://snap-research.github.io/mixture-of-attention/)

**FaceChain-SuDe: Building Derived Class to Inherit Category Attributes for One-shot Subject-Driven Generation**<br>
*Qiao, Pengchong and Shang, Lei and Liu, Chang and Sun, Baigui and Ji, Xiangyang and Chen, Jie.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.06775v1)  / [Project](https://facechain-fact.github.io)  / [Code](https://github.com/modelscope/facechain)

**Tuning-free image customization with image and text guidance**<br>
*Li, Pengzhi and Nie, Qiang and Chen, Ying and Jiang, Xi and Wu, Kai and Lin, Yuhuan and Liu, Yong and Peng, Jinlong and Wang, Chengjie and Zheng, Feng.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.12658v1)

**Harmonizing Visual and Textual Embeddings for Zero-Shot Text-to-Image Customization**<br>
*Song, Yeji and Kim, Jimyeong and Park, Wonhark and Shin, Wonsik and Rhee, Wonjong and Kwak, Nojun.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.14155)  / [Project](https://ldynx.github.io/harmony-zero-t2i/)  / [Code](https://github.com/ldynx/harmony-zero-t2i)

**Automated Black-box Prompt Engineering for Personalized Text-to-Image Generation**<br>
*He, Yutong and Robey, Alexander and Murata, Naoki and Jiang, Yiding and Williams, Joshua and Pappas, George J and Hassani, Hamed and Mitsufuji, Yuki and Salakhutdinov, Ruslan and Kolter, J Zico.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19103)

**Locate, Assign, Refine: Taming Customized Image Inpainting with Text-Subject Guidance**<br>
*Pan, Yulin and Mao, Chaojie and Jiang, Zeyinzi and Han, Zhen and Zhang, Jingfeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19534)  / [Project](https://ali-vilab.github.io/largen-page/)  / [Code](https://github.com/modelscope/scepter)

**RealCustom: Narrowing Real Text Word for Real-Time Open-Domain Text-to-Image Customization**<br>
*Huang, Mengqi and Mao, Zhendong and Liu, Mingcong and He, Qian and Zhang, Yongdong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.00483v1)  / [Project](https://github.com/Corleone-Huang/RealCustomProject)  / [Code](https://corleone-huang.github.io/realcustom/)

**Dreammatcher: Appearance matching self-attention for semantically-consistent text-to-image personalization**<br>
*Nam, Jisu and Kim, Heesu and Lee, DongJae and Jin, Siyoon and Kim, Seungryong and Chang, Seunggyu.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2402.09812v2)  / [Project](https://cvlab-kaist.github.io/DreamMatcher/)  / [Code](https://github.com/cvlab-kaist/DreamMatcher)

**ComFusion: Personalized Subject Generation in Multiple Specific Scenes From Single Image**<br>
*Hong, Yan and Zhang, Jianfu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2402.11849)

**Direct consistency optimization for compositional text-to-image personalization**<br>
*Lee, Kyungmin and Kwak, Sangkyung and Sohn, Kihyuk and Shin, Jinwoo.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2402.12004)  / [Project](https://dco-t2i.github.io/)  / [Code](https://github.com/kyungmnlee/dco)

**Instruct-Imagen: Image generation with multi-modal instruction**<br>
*Hu, Hexiang and Chan, Kelvin CK and Su, Yu-Chuan and Chen, Wenhu and Li, Yandong and Sohn, Kihyuk and Zhao, Yang and Ben, Xue and Gong, Boqing and Cohen, William.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2401.01952)

**Memory-Efficient Personalization using Quantized Diffusion Model**<br>
*Ryu, Hyogon and Lim, Seohyun and Shim, Hyunjung.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2401.04339)  / [Code](https://github.com/ugonfor/TuneQDM)

**PALP: prompt aligned personalization of text-to-image models**<br>
*Arar, Moab and Voynov, Andrey and Hertz, Amir and Avrahami, Omri and Fruchter, Shlomi and Pritch, Yael and Cohen-Or, Daniel and Shamir, Ariel.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2401.06105v1)  / [Project](https://prompt-aligned.github.io/)

**UNIMO-G: Unified Image Generation through Multimodal Conditional Diffusion**<br>
*Li, Wei and Xu, Xue and Liu, Jiachen and Xiao, Xinyan.*<br>
ACL 2024.  / [PDF](https://arxiv.org/abs/2401.13388)  / [Project](https://unimo-ptm.github.io/)

**Bootpig: Bootstrapping zero-shot personalized image generation capabilities in pretrained diffusion models**<br>
*Purushwalkam, Senthil and Gokul, Akash and Joty, Shafiq and Naik, Nikhil.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.13974)

**Object-Driven One-Shot Fine-tuning of Text-to-Image Diffusion with Prototypical Embedding**<br>
*Lu, Jianxiang and Xie, Cong and Guo, Hui.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.15708)

**Pick-and-draw: Training-free semantic guidance for text-to-image personalization**<br>
*Lv, Henglei and Xiao, Jiayu and Li, Liang.*<br>
ACM MM 2024.  / [PDF](https://arxiv.org/abs/2401.16762)

**Decoupled textual embeddings for customized image generation**<br>
*Cai, Yufei and Wei, Yuxiang and Ji, Zhilong and Bai, Jinfeng and Han, Hu and Zuo, Wangmeng.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2312.11826v1)  / [Code](https://github.com/PrototypeNx/DETEX)

**Retrieving conditions from reference images for diffusion models**<br>
*Tang, Haoran and Zhou, Xin and Deng, Jieren and Pan, Zhihong and Tian, Hao and Chaudhari, Pratik.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.02521)

**Instructbooth: Instruction-following personalized text-to-image generation**<br>
*Chae, Daewon and Park, Nokyung and Kim, Jinkyu and Lee, Kimin.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.03011)  / [Project](https://sites.google.com/view/instructbooth)

**Orthogonal adaptation for modular customization of diffusion models**<br>
*Po, Ryan and Yang, Guandao and Aberman, Kfir and Wetzstein, Gordon.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.02432v3)  / [Project](https://ryanpo.com/ortha/)

**Customization assistant for text-to-image generation**<br>
*Zhou, Yufan and Zhang, Ruiyi and Gu, Jiuxiang and Sun, Tong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.03045v2)

**Dreamtuner: Single image is enough for subject-driven generation**<br>
*Hua, Miao and Liu, Jiawei and Ding, Fei and Liu, Wei and Wu, Jie and He, Qian.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.13691)  / [Project](https://dreamtuner-diffusion.github.io/)

**Ssr-encoder: Encoding selective subject representation for subject-driven generation**<br>
*Zhang, Yuxuan and Song, Yiren and Liu, Jiaming and Wang, Rui and Yu, Jinpeng and Tang, Hao and Li, Huaxia and Tang, Xu and Hu, Yao and Pan, Han and {others}.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.16272)  / [Project](https://ssr-encoder.github.io/)  / [Code](https://github.com/Xiaojiu-z/SSR_Encoder)

**Towards accurate guided diffusion sampling through symplectic adjoint method**<br>
*Pan, Jiachun and Yan, Hanshu and Liew, Jun Hao and Feng, Jiashi and Tan, Vincent YF.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.12030)  / [Code](https://github.com/HanshuYAN/AdjointDPM)

**Catversion: Concatenating embeddings for diffusion-based text-to-image personalization**<br>
*Zhao, Ruoyu and Zhu, Mingrui and Dong, Shiyin and Wang, Nannan and Gao, Xinbo.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2311.14631)  / [Project](https://royzhao926.github.io/CatVersion-page)  / [Code](https://github.com/RoyZhao926/CatVersion)

**Parameter-efficient orthogonal finetuning via butterfly factorization**<br>
*Liu, Weiyang and Qiu, Zeju and Feng, Yao and Xiu, Yuliang and Xue, Yuxuan and Yu, Longhui and Feng, Haiwen and Liu, Zhen and Heo, Juyeon and Peng, Songyou and {others}.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2311.06243)

**An image is worth multiple words: Multi-attribute inversion for constrained text-to-image synthesis**<br>
*Agarwal, Aishwarya and Karanam, Srikrishna and Shukla, Tripti and Srinivasan, Balaji Vasan.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2311.11919)

**Hifi tuner: High-fidelity subject-driven fine-tuning for diffusion models**<br>
*Wang, Zhonghao and Wei, Wei and Zhao, Yang and Xiao, Zhisheng and Hasegawa-Johnson, Mark and Shi, Humphrey and Hou, Tingbo.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.00079)

**Singleinsert: Inserting new concepts from a single image into text-to-image models for flexible editing**<br>
*Wu, Zijie and Yu, Chaohui and Zhu, Zhen and Wang, Fan and Bai, Xiang.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2310.08094)  / [Project](https://jarrentwu1031.github.io/SingleInsert-web)  / [Code](https://github.com/JarrentWu1031/SingleInsert)

**An image is worth multiple words: Learning object level concepts using multi-concept prompt learning**<br>
*Jin, Chen and Tanno, Ryutaro and Saseendran, Amrutha and Diethe, Tom and Teare, Philip.*<br>
ICML 2024.  / [PDF](https://arxiv.org/abs/2310.12274)  / [Project](https://astrazeneca.github.io/mcpl.github.io/)  / [Code](https://github.com/AstraZeneca/MCPL/tree/master)

**Customnet: Zero-shot object customization with variable-viewpoints in text-to-image diffusion models**<br>
*Yuan, Ziyang and Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Yuan, Chun and Shan, Ying.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2310.19784)  / [Project](https://jiangyzy.github.io/CustomNet/)

**Viewpoint textual inversion: Unleashing novel view synthesis with pretrained 2d diffusion models**<br>
*Burgess, James and Wang, Kuan-Chieh and Yeung, Serena.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2309.07986)  / [Project](https://jmhb0.github.io/view_neti/)  / [Code](https://github.com/jmhb0/view_neti)

**Ip-adapter: Text compatible image prompt adapter for text-to-image diffusion models**<br>
*Ye, Hu and Zhang, Jun and Liu, Sibo and Han, Xiao and Yang, Wei.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2308.06721)  / [Project](https://ip-adapter.github.io/)  / [Code](https://github.com/tencent-ailab/IP-Adapter)

**Anydoor: Zero-shot object-level image customization**<br>
*Chen, Xi and Huang, Lianghua and Liu, Yu and Shen, Yujun and Zhao, Deli and Zhao, Hengshuang.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2307.09481v2)  / [Project](https://ali-vilab.github.io/AnyDoor-Page/)  / [Code](https://github.com/ali-vilab/AnyDoor)

**Subject-diffusion: Open domain personalized text-to-image generation without test-time fine-tuning**<br>
*Ma, Jian and Liang, Junhao and Chen, Chen and Lu, Haonan.*<br>
SIGGRAPH 2024.  / [PDF](https://arxiv.org/abs/2307.11410)  / [Project](https://oppo-mente-lab.github.io/subject_diffusion/)  / [Code](https://github.com/OPPO-Mente-Lab/Subject-Diffusion)

**Domain-agnostic tuning-encoder for fast personalization of text-to-image models**<br>
*Arar, Moab and Gal, Rinon and Atzmon, Yuval and Chechik, Gal and Cohen-Or, Daniel and Shamir, Ariel and H. Bermano, Amit.*<br>
SIGGRAPH Asia 2023.  / [PDF](https://arxiv.org/abs/2307.06925v1)  / [Project](https://datencoder.github.io/)

**ViCo: Plug-and-play Visual Condition for Personalized Text-to-image Generation**<br>
*Hao, Shaozhe and Han, Kai and Zhao, Shihao and Wong, Kwan-Yee K.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2306.00971)  / [Code](https://github.com/haoosz/ViCo)

**Diffusion self-guidance for controllable image generation**<br>
*Epstein, Dave and Jabri, Allan and Poole, Ben and Efros, Alexei and Holynski, Aleksander.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.00986)  / [Project](https://dave.ml/selfguidance/)

**Controlling text-to-image diffusion by orthogonal finetuning**<br>
*Qiu, Zeju and Liu, Weiyang and Feng, Haiwen and Xue, Yuxuan and Feng, Yao and Liu, Zhen and Zhang, Dan and Weller, Adrian and Schölkopf, Bernhard.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.07280)  / [Project](https://oft.wyliu.com/)  / [Code](https://github.com/Zeju1997/oft)

**Enhancing detail preservation for customized text-to-image generation: A regularization-free approach**<br>
*Zhou, Yufan and Zhang, Ruiyi and Sun, Tong and Xu, Jinhui.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2305.13579)  / [Code](https://github.com/drboog/ProFusion)

**Disenbooth: Disentangled parameter-efficient tuning for subject-driven text-to-image generation**<br>
*Chen, Hong and Zhang, Yipeng and Wang, Xin and Duan, Xuguang and Zhou, Yuwei and Zhu, Wenwu.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2305.03374)  / [Code](https://github.com/forchchch/DisenBooth)

**Break-a-scene: Extracting multiple concepts from a single image**<br>
*Avrahami, Omri and Aberman, Kfir and Fried, Ohad and Cohen-Or, Daniel and Lischinski, Dani.*<br>
SIGGRAPH Asia 2023.  / [PDF](https://arxiv.org/abs/2305.16311v2)  / [Project](https://omriavrahami.com/break-a-scene/)  / [Code](https://github.com/google/break-a-scene)

**Blip-diffusion: Pre-trained subject representation for controllable text-to-image generation and editing**<br>
*Li, Dongxu and Li, Junnan and Hoi, Steven.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2305.14720)  / [Project](https://dxli94.github.io/BLIP-Diffusion-website/)  / [Code](https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion)

**Key-locked rank one editing for text-to-image personalization**<br>
*Tewel, Yoad and Gal, Rinon and Chechik, Gal and Atzmon, Yuval.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2305.01644v2)  / [Project](https://research.nvidia.com/labs/par/Perfusion/)

**A neural space-time representation for text-to-image personalization**<br>
*Alaluf, Yuval and Richardson, Elad and Metzer, Gal and Cohen-Or, Daniel.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2305.15391v1)  / [Project](https://neuraltextualinversion.github.io/NeTI/)  / [Code](https://github.com/NeuralTextualInversion/NeTI)

**Concept decomposition for visual exploration and inspiration**<br>
*Vinker, Yael and Voynov, Andrey and Cohen-Or, Daniel and Shamir, Ariel.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2305.18203v2)  / [Project](https://inspirationtree.github.io/inspirationtree/)  / [Code](https://github.com/google/inspiration_tree)

**Prospect: Prompt spectrum for attribute-aware personalization of diffusion models**<br>
*Zhang, Yuxin and Dong, Weiming and Tang, Fan and Huang, Nisha and Huang, Haibin and Ma, Chongyang and Lee, Tong-Yee and Deussen, Oliver and Xu, Changsheng.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2305.16225v3)  / [Code](https://github.com/zyxElsa/ProSpect)

**The CLIP model is secretly an image-to-prompt converter**<br>
*Ding, Yuxuan and Tian, Chunna and Ding, Haoxuan and Liu, Lingqiao.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.12716v2)

**Instantbooth: Personalized text-to-image generation without test-time finetuning**<br>
*Shi, Jing and Xiong, Wei and Lin, Zhe and Jung, Hyun Joon.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2304.03411v1)  / [Project](https://jshi31.github.io/InstantBooth)

**Subject-driven text-to-image generation via apprenticeship learning**<br>
*Chen, Wenhu and Hu, Hexiang and Li, Yandong and Ruiz, Nataniel and Jia, Xuhui and Chang, Ming-Wei and Cohen, William W.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2304.00186)  / [Project](https://cloud.google.com/vertex-ai/docs/generative-ai/image/fine-tune-model)

**Taming encoder for zero fine-tuning image customization with text-to-image diffusion models**<br>
*Jia, Xuhui and Zhao, Yang and Chan, Kelvin CK and Li, Yandong and Zhang, Han and Gong, Boqing and Hou, Tingbo and Wang, Huisheng and Su, Yu-Chuan.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2304.02642)

**Gradient-free textual inversion**<br>
*Fei, Zhengcong and Fan, Mingyuan and Huang, Junshi.*<br>
ACM MM 2023.  / [PDF](https://arxiv.org/abs/2304.05818v1)

**p+: Extended textual conditioning in text-to-image generation**<br>
*Voynov, Andrey and Chu, Qinghao and Cohen-Or, Daniel and Aberman, Kfir.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2303.09522)  / [Project](https://prompt-plus.github.io)

**Cones: Concept neurons in diffusion models for customized generation**<br>
*Liu, Zhiheng and Feng, Ruili and Zhu, Kai and Zhang, Yifei and Zheng, Kecheng and Liu, Yu and Zhao, Deli and Zhou, Jingren and Cao, Yang.*<br>
ICML 2023.  / [PDF](https://arxiv.org/abs/2303.05125)

**Svdiff: Compact parameter space for diffusion fine-tuning**<br>
*Han, Ligong and Li, Yinxiao and Zhang, Han and Milanfar, Peyman and Metaxas, Dimitris and Yang, Feng.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2303.11305)

**Highly personalized text embedding for image manipulation by stable diffusion**<br>
*Han, Inhwa and Yang, Serin and Kwon, Taesung and Ye, Jong Chul.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2303.08767)  / [Project](https://hiper0.github.io/)  / [Code](https://github.com/HiPer0/HiPer)

**Unified multi-modal latent diffusion for joint subject and text conditional image generation**<br>
*Ma, Yiyang and Yang, Huan and Wang, Wenjing and Fu, Jianlong and Liu, Jiaying.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2303.09319)

**Elite: Encoding visual concepts into textual embeddings for customized text-to-image generation**<br>
*Wei, Yuxiang and Zhang, Yabo and Ji, Zhilong and Bai, Jinfeng and Zhang, Lei and Zuo, Wangmeng.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2302.13848v2)  / [Code](https://github.com/csyxwei/ELITE)

**Encoder-based domain tuning for fast personalization of text-to-image models**<br>
*Gal, Rinon and Arar, Moab and Atzmon, Yuval and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2302.12228)  / [Project](https://tuning-encoder.github.io/)

**Multi-concept customization of text-to-image diffusion**<br>
*Kumari, Nupur and Zhang, Bingliang and Zhang, Richard and Shechtman, Eli and Zhu, Jun-Yan.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2212.04488v2)  / [Project](https://www.cs.cmu.edu/~custom-diffusion)  / [Code](https://github.com/adobe-research/custom-diffusion)

**Dreamartist: Towards controllable one-shot text-to-image generation via positive-negative prompt-tuning**<br>
*Dong, Ziyi and Wei, Pengxu and Lin, Liang.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2211.11337)

**Personalizing text-to-image generation via aesthetic gradients**<br>
*Gallego, Victor.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2209.12330)  / [Code](https://github.com/vicgalle/stable-diffusion-aesthetic-gradients)

**Re-imagen: Retrieval-augmented text-to-image generator**<br>
*Chen, Wenhu and Hu, Hexiang and Saharia, Chitwan and Cohen, William W.*<br>
ICLR 2023.  / [PDF](https://arxiv.org/abs/2209.14491)

**An image is worth one word: Personalizing text-to-image generation using textual inversion**<br>
*Gal, Rinon and Alaluf, Yuval and Atzmon, Yuval and Patashnik, Or and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ICLR 2023.  / [PDF](https://arxiv.org/abs/2208.01618)  / [Project](https://textual-inversion.github.io/)  / [Code](https://github.com/rinongal/textual_inversion)

**Dreambooth: Fine tuning text-to-image diffusion models for subject-driven generation**<br>
*Ruiz, Nataniel and Li, Yuanzhen and Jampani, Varun and Pritch, Yael and Rubinstein, Michael and Aberman, Kfir.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2208.12242v2)  / [Project](https://dreambooth.github.io)  / [Code](https://github.com/google/dreambooth)

**Lora: Low-rank adaptation of large language models**<br>
*Hu, Edward J and Shen, Yelong and Wallis, Phillip and Allen-Zhu, Zeyuan and Li, Yuanzhi and Wang, Shean and Wang, Lu and Chen, Weizhu.*<br>
ICLR 2022.  / [PDF](https://arxiv.org/abs/2106.09685)  / [Code](https://github.com/microsoft/LoRA)

### Face-Driven Generation

**PersonaHOI: Effortlessly Improving Personalized Face with Human-Object Interaction Generation**<br>
*Hu, Xinting and Wang, Haoran and Lenssen, Jan Eric and Schiele, Bernt.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.05823)  / [Code](https://github.com/JoyHuYY1412/PersonaHOI)

**IC-Portrait: In-Context Matching for View-Consistent Personalized Portrait**<br>
*Yang, Han and Simsar, Enis and Anagnostidi, Sotiris and Zang, Yanlong and Hofmann, Thomas and Liu, Ziwei.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.17159)

**EmojiDiff: Advanced Facial Expression Control with High Identity Preservation in Portrait Generation**<br>
*Jiang, Liangwei and Li, Ruida and Zhang, Zhifeng and Fang, Shuo and Ma, Chenguang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.01254)  / [Project](https://emojidiff.github.io/)

**Diff-PC: Identity-preserving and 3D-aware controllable diffusion for zero-shot portrait customization**<br>
*Xu, Yifang and Zhai, Benxiang and Zhang, Chenyu and Li, Ming and Li, Yang and Du, Sidan.*<br>
Information Fusion.  / [PDF](https://www.sciencedirect.com/science/article/pii/S156625352400647X)

**MagicNaming: Consistent Identity Generation by Finding a "Name Space" in T2I Diffusion Models**<br>
*Zhao, Jing and Zheng, Heliang and Wang, Chaoyue and Lan, Long and Hunag, Wanrong and Tang, Yuhua.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.14902)  / [Project](https://magicfusion.github.io/MagicNaming/)  / [Code](https://github.com/MagicFusion/MagicNaming)

**PersonaMagic: Stage-Regulated High-Fidelity Face Customization with Tandem Equilibrium**<br>
*Li, Xinzhe and Zhan, Jiahui and He, Shengfeng and Xu, Yangyang and Dong, Junyu and Zhang, Huaidong and Du, Yong.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.15674)  / [Code](https://github.com/xzhe-Vision/PersonaMagic)

**Omni-ID: Holistic Identity Representation Designed for Generative Tasks**<br>
*Qian, Guocheng and Wang, Kuan-Chieh and Patashnik, Or and Heravi, Negin and Ostashev, Daniil and Tulyakov, Sergey and Cohen-Or, Daniel and Aberman, Kfir.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.09694)  / [Project](https://snap-research.github.io/Omni-ID/)

**RealisID: Scale-Robust and Fine-Controllable Identity Customization via Local and Global Complementation**<br>
*Sun, Zhaoyang and Du, Fei and Chen, Weihua and Wang, Fan and Chen, Yaxiong and Rong, Yi and Xiong, Shengwu.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.16832)

**Foundation Cures Personalization: Recovering Facial Personalized Models' Prompt Consistency**<br>
*Cai, Yiyang and Jiang, Zhengkai and Liu, Yulong and Jiang, Chunyang and Xue, Wei and Luo, Wenhan and Guo, Yike.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15277)

**PersonaCraft: Personalized Full-Body Image Synthesis for Multiple Identities from Single References Using 3D-Model-Conditioned Diffusion**<br>
*Kim, Gwanghyun and Jeon, Suh Yoon and Lee, Seunggyu and Chun, Se Young.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.18068)  / [Project](https://gwang-kim.github.io/persona_craft/)  / [Code](https://github.com/gwang-kim/PersonaCraft)

**ID-Patch: Robust ID Association for Group Photo Personalization**<br>
*Zhang, Yimeng and Zhi, Tiancheng and Liu, Jing and Sang, Shen and Jiang, Liming and Yan, Qing and Liu, Sijia and Luo, Linjie.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.13632)  / [Project](https://byteaigc.github.io/ID-Patch/)

**FaceChain-FACT: Face Adapter with Decoupled Training for Identity-preserved Personalization**<br>
*Yu, Cheng and Xie, Haoyu and Shang, Lei and Liu, Yang and Dan, Jun and Bo, Liefeng and Sun, Baigui.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.12312)  / [Code](https://github.com/modelscope/facechain)

**Imagine yourself: Tuning-free personalized image generation**<br>
*He, Zecheng and Sun, Bo and Juefei-Xu, Felix and Ma, Haoyu and Ramchandani, Ankit and Cheung, Vincent and Shah, Siddharth and Kalia, Anmol and Subramanyam, Harihar and Zareian, Alireza and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.13346)

**Fusion is all you need: Face Fusion for Customized Identity-Preserving Image Synthesis**<br>
*Mohamed, Salaheldin and Han, Dong and Li, Yong.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.19111)

**ID-Booth: Identity-consistent image generation with diffusion models**<br>
*Tomašević, Darian and Boutros, Fadi and Damer, Naser and Struc, Vitomir and Peer, Peter.*<br>
OpenReview 2024.  / [PDF](https://openreview.net/forum?id=NWvsm2VxAM)

**UniPortrait: A Unified Framework for Identity-Preserving Single-and Multi-Human Image Personalization**<br>
*He, Junjie and Geng, Yifeng and Bo, Liefeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.05939)  / [Project](https://aigcdesigngroup.github.io/UniPortrait-Page/)  / [Code](https://github.com/junjiehe96/UniPortrait)

**Difflora: Generating personalized low-rank adaptation weights with diffusion**<br>
*Wu, Yujia and Shi, Yiming and Wei, Jiwei and Sun, Chengwei and Zhou, Yuyang and Yang, Yang and Shen, Heng Tao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.06740)

**MagicFace: Training-free Universal-Style Human Image Customized Synthesis**<br>
*Wang, Yibin and Zhang, Weizhong and Jin, Cheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.07433)  / [Project](https://codegoat24.github.io/MagicFace/)  / [Code](https://github.com/CodeGoat24/MagicFace)

**MagicID: Flexible ID Fidelity Generation System**<br>
*Deng, Zhaoli and Liu, Wen and Wang, Fanyi and Zhang, Junkang and Chen, Fan and Zhang, Meng and Zhang, Wendong and Mi, Zhenpeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.09248)

**Precisecontrol: Enhancing text-to-image diffusion models with fine-grained attribute control**<br>
*Parihar, Rishubh and Sachidanand, VS and Mani, Sabariswaran and Karmali, Tejan and Venkatesh Babu, R.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2408.05083)  / [Project](https://rishubhpar.github.io/PreciseControl.home/)  / [Code](https://github.com/rishubhpar/PreciseControl)

**Cross Initialization for Face Personalization of Text-to-Image Models**<br>
*Pang, Lianyu and Yin, Jian and Xie, Haoran and Wang, Qiping and Li, Qing and Mao, Xudong.*<br>
CVPR 2024.  / [PDF](https://openaccess.thecvf.com/content/CVPR2024/html/Pang_Cross_Initialization_for_Face_Personalization_of_Text-to-Image_Models_CVPR_2024_paper.html)  / [Code](https://github.com/lyuPang/CrossInitialization)

**MasterWeaver: Taming Editability and Face Identity for Personalized Text-to-Image Generation**<br>
*Wei, Yuxiang and Ji, Zhilong and Bai, Jinfeng and Zhang, Hongzhi and Zhang, Lei and Zuo, Wangmeng.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2405.05806v3)  / [Project](https://masterweaver.github.io/)  / [Code](https://github.com/csyxwei/MasterWeaver)

**RectifID: Personalizing Rectified Flow with Anchored Classifier Guidance**<br>
*Sun, Zhicheng and Yang, Zhenhao and Jin, Yang and Chi, Haozhe and Xu, Kun and Chen, Liwei and Jiang, Hao and Song, Yang and Gai, Kun and Mu, Yadong.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2405.14677)  / [Code](https://github.com/feifeiobama/RectifID)

**Pulid: Pure and lightning id customization via contrastive alignment**<br>
*Guo, Zinan and Wu, Yanze and Chen, Zhuowei and Chen, Lang and Zhang, Peng and He, Qian.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2404.16022)  / [Code](https://github.com/ToTheBeginning/PuLID)

**Lcm-lookahead for encoder-based text-to-image personalization**<br>
*Gal, Rinon and Lichter, Or and Richardson, Elad and Patashnik, Or and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2404.03620)  / [Project](https://lcm-lookahead.github.io/)  / [Code](https://github.com/OrLichter/lcm-lookahead)

**ID-Aligner: Enhancing Identity-Preserving Text-to-Image Generation with Reward Feedback Learning**<br>
*Chen, Weifeng and Zhang, Jiacheng and Wu, Jie and Wu, Hefeng and Xiao, Xuefeng and Lin, Liang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.15449)  / [Project](https://idaligner.github.io/)  / [Code](https://github.com/Weifeng-Chen/ID-Aligner)

**CharacterFactory: Sampling Consistent Characters with GANs for Diffusion Models**<br>
*Qinghe Wang, Baolu Li, Xiaomin Li, Bing Cao, Liqian Ma, Huchuan Lu, Xu Jia*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.15677)  / [Project](https://qinghew.github.io/CharacterFactory/)  / [Code](https://github.com/qinghew/CharacterFactory)


**Consistentid: Portrait generation with multimodal fine-grained identity preserving**<br>
*Huang, Jiehui and Dong, Xiao and Song, Wenhui and Li, Hanhui and Zhou, Jun and Cheng, Yuhao and Liao, Shutao and Chen, Long and Yan, Yiqiang and Liao, Shengcai and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.16771)  / [Project](https://ssugarwh.github.io/consistentid.github.io/)  / [Code](https://github.com/JackAILab/ConsistentID)

**Face2Diffusion for Fast and Editable Face Personalization**<br>
*Shiohara, Kaede and Yamasaki, Toshihiko.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.05094v1)  / [Project](https://mapooon.github.io/Face2DiffusionPage/)  / [Code](https://github.com/mapooon/Face2Diffusion)

**Infinite-ID: Identity-preserved Personalization via ID-semantics Decoupling Paradigm**<br>
*Wu, Yi and Li, Ziqiang and Zheng, Heliang and Wang, Chaoyue and Li, Bin.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.11781v1)  / [Project](https://infinite-id.github.io/)

**IDAdapter: Learning Mixed Features for Tuning-Free Personalization of Text-to-Image Models**<br>
*Cui, Siying and Guo, Jia and An, Xiang and Deng, Jiankang and Zhao, Yongle and Wei, Xinyu and Feng, Ziyong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.13535v2)

**FlashFace: Human Image Personalization with High-fidelity Identity Preservation**<br>
*Zhang, Shilong and Huang, Lianghua and Chen, Xi and Zhang, Yifei and Wu, Zhi-Fan and Feng, Yutong and Wang, Wei and Shen, Yujun and Liu, Yu and Luo, Ping.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.17008)  / [Project](https://jshilong.github.io/flashface-page/)  / [Code](https://github.com/ali-vilab/FlashFace)

**Attention Calibration for Disentangled Text-to-Image Personalization**<br>
*Zhang, Yanbing and Yang, Mengping and Zhou, Qin and Wang, Zhe.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.18551v2)  / [Code](https://github.com/Monalissaa/DisenDiff)

**Caphuman: Capture your moments in parallel universes**<br>
*Liang, Chao and Ma, Fan and Zhu, Linchao and Deng, Yingying and Yang, Yi.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2402.00627v3)  / [Project](https://caphuman.github.io/)  / [Code](https://github.com/VamosC/CapHuman)

**Instantid: Zero-shot identity-preserving generation in seconds**<br>
*Wang, Qixun and Bai, Xu and Wang, Haofan and Qin, Zekui and Chen, Anthony and Li, Huaxia and Tang, Xu and Hu, Yao.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.07519)  / [Project](https://instantid.github.io/)  / [Code](https://github.com/instantX-research/InstantID)

**Towards a simultaneous and granular identity-expression control in personalized face generation**<br>
*Liu, Renshuai and Ma, Bowen and Zhang, Wei and Hu, Zhipeng and Fan, Changjie and Lv, Tangjie and Ding, Yu and Cheng, Xuan.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2401.01207v2)  / [Project](https://diffsfsr.github.io/)

**Stableidentity: Inserting anybody into anywhere at first sight**<br>
*Wang, Qinghe and Jia, Xu and Li, Xiaomin and Li, Taiqing and Ma, Liqian and Zhuge, Yunzhi and Lu, Huchuan.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2401.15975)  / [Project](https://qinghew.github.io/StableIdentity/)  / [Code](https://github.com/qinghew/StableIdentity)

**SeFi-IDE: Semantic-Fidelity Identity Embedding for Personalized Diffusion-Based Generation**<br>
*Li, Yang and Yang, Songlin and Wang, Wei and Dong, Jing.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2402.00631)  / [Project](https://com-vis.github.io/SeFi-IDE/)

**Photomaker: Customizing realistic human photos via stacked id embedding**<br>
*Li, Zhen and Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Cheng, Ming-Ming and Shan, Ying.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.04461v1)  / [Project](https://photo-maker.github.io)  / [Code](https://github.com/TencentARC/PhotoMaker)

**Portraitbooth: A versatile portrait model for fast identity-preserved personalization**<br>
*Peng, Xu and Zhu, Junwei and Jiang, Boyuan and Tai, Ying and Luo, Donghao and Zhang, Jiangning and Lin, Wei and Jin, Taisong and Wang, Chengjie and Ji, Rongrong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.06354v1)  / [Project](https://portraitbooth.github.io/)

**Facestudio: Put your face everywhere in seconds**<br>
*Yan, Yuxuan and Zhang, Chi and Wang, Rui and Zhou, Yichao and Zhang, Gege and Cheng, Pei and Yu, Gang and Fu, Bin.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.02663)  / [Project](https://icoz69.github.io/facestudio/)  / [Code](https://github.com/TencentQQGYLab/FaceStudio)

**Portrait diffusion: Training-free face stylization with chain-of-painting**<br>
*Liu, Jin and Huang, Huaibo and Jin, Chao and He, Ran.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.02212)  / [Code](https://github.com/liujin112/PortraitDiffusion)

**When stylegan meets stable diffusion: a w+ adapter for personalized image generation**<br>
*Li, Xiaoming and Hou, Xinyu and Loy, Chen Change.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.17461)  / [Project](https://csxmli2016.github.io/projects/w-plus-adapter/)  / [Code](https://github.com/csxmli2016/w-plus-adapter)

**A data perspective on enhanced identity preservation for diffusion personalization**<br>
*He, Xingzhe and Cao, Zhiwen and Kolkin, Nicholas and Yu, Lantao and Wan, Kun and Rhodin, Helge and Kalarot, Ratheesh.*<br>
WACV 2025.  / [PDF](https://arxiv.org/abs/2311.04315)

**High-fidelity Person-centric Subject-to-Image Synthesis**<br>
*Wang, Yibin and Zhang, Weizhong and Zheng, Jianwei and Jin, Cheng.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.10329v5)  / [Code](https://github.com/CodeGoat24/Face-diffuser)

**Photoverse: Tuning-free image customization with text-to-image diffusion models**<br>
*Chen, Li and Zhao, Mengyi and Liu, Yiheng and Ding, Mingxu and Song, Yangyang and Wang, Shizun and Wang, Xu and Yang, Hao and Liu, Jing and Du, Kang and {others}.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2309.05793)  / [Project](https://photoverse2d.github.io/)

**Magicapture: High-resolution multi-concept portrait customization**<br>
*Hyung, Junha and Shin, Jaeyo and Choo, Jaegul.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2309.06895v2)

**Hyperdreambooth: Hypernetworks for fast personalization of text-to-image models**<br>
*Ruiz, Nataniel and Li, Yuanzhen and Jampani, Varun and Wei, Wei and Hou, Tingbo and Pritch, Yael and Wadhwa, Neal and Rubinstein, Michael and Aberman, Kfir.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2307.06949v2)  / [Project](HyperDreamBooth: HyperNetworks for Fast Personalization of Text-to-Image Models)

**Dreamidentity: Improved editability for efficient face-identity preserved image generation**<br>
*Chen, Zhuowei and Fang, Shancheng and Liu, Wei and He, Qian and Huang, Mengqi and Zhang, Yongdong and Mao, Zhendong.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2307.00300)  / [Project](https://dreamidentity.github.io/)

**Inserting anybody in diffusion models via celeb basis**<br>
*Yuan, Ge and Cun, Xiaodong and Zhang, Yong and Li, Maomao and Qi, Chenyang and Wang, Xintao and Shan, Ying and Zheng, Huicheng.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.00926)  / [Project](https://celeb-basis.github.io/)  / [Code](https://github.com/ygtxr1997/CelebBasis)

**Face0: Instantaneously conditioning a text-to-image model on a face**<br>
*Valevski, Dani and Lumen, Danny and Matias, Yossi and Leviathan, Yaniv.*<br>
SIGGRAPH Asia 2023.  / [PDF](https://arxiv.org/abs/2306.06638)

**Diffusion in diffusion: Cyclic one-way diffusion for text-vision-conditioned generation**<br>
*Wang, Ruoyu and Yang, Yongqi and Qian, Zhihao and Zhu, Ye and Wu, Yu.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2306.08247)  / [Project](https://wangruoyu02.github.io/cow.github.io/)  / [Code](https://github.com/wangruoyu02/COW)

**Fastcomposer: Tuning-free multi-subject image generation with localized attention**<br>
*Xiao, Guangxuan and Yin, Tianwei and Freeman, William T and Durand, Frédo and Han, Song.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2305.10431)  / [Project](https://hanlab.mit.edu/projects/fastcomposer)  / [Code](https://github.com/mit-han-lab/fastcomposer)

### Character-Driven Generation

**AnyStory: Towards Unified Single and Multiple Subject Personalization in Text-to-Image Generation**<br>
*He, Junjie and Tuo, Yuxiang and Chen, Binghui and Zhong, Chongyang and Geng, Yifeng and Bo, Liefeng.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.09503)  / [Project](https://aigcdesigngroup.github.io/AnyStory/)

**SerialGen: Personalized Image Generation by First Standardization Then Personalization**<br>
*Xie, Cong and Zou, Han and Yu, Ruiqi and Zhang, Yan and Zhan, Zhenpeng.*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2412.01485)  / [Project](https://serialgen.github.io/)

**StoryWeaver: A Unified World Model for Knowledge-Enhanced Story Character Customization**<br>
*Zhang, Jinlu and Tang, Jiji and Zhang, Rongsheng and Lv, Tangjie and Sun, Xiaoshuai.*<br>
AAAI 2025.  / [PDF](https://arxiv.org/abs/2412.07375)  / [Code](https://github.com/Aria-Zhangjl/StoryWeaver)

**Content-style disentangled representation for controllable artistic image stylization and generation**<br>
*Zhuoqi, Ma and Yixuan, Zhang and Zejun, You and Long, Tian and Xiyang, Liu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.14496)

**StoryMaker: Towards Holistic Consistent Characters in Text-to-image Generation**<br>
*Zhou, Zhengguang and Li, Jing and Li, Huaxia and Chen, Nemo and Tang, Xu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.12576)  / [Code](https://github.com/RedAIGC/StoryMaker)

**Dreamstory: Open-domain story visualization by llm-guided multi-subject consistent diffusion**<br>
*He, Huiguo and Yang, Huan and Tuo, Zixi and Zhou, Yuan and Wang, Qiuyue and Zhang, Yuhang and Liu, Zeyu and Huang, Wenhao and Chao, Hongyang and Yin, Jian.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2407.12899)  / [Project](https://dream-xyz.github.io/dreamstory)

**Character-Adapter: Prompt-Guided Region Control for High-Fidelity Character Customization**<br>
*Ma, Yuhang and Xu, Wenting and Tang, Jiji and Jin, Qinfeng and Zhang, Rongsheng and Zhao, Zeng and Fan, Changjie and Hu, Zhipeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2406.16537)  / [Project](https://github.com/Character-Adapter/Character-Adapter)

**From Parts to Whole: A Unified Reference Framework for Controllable Human Image Generation**<br>
*Huang, Zehuan and Fan, Hongxing and Wang, Lipeng and Sheng, Lu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.15267)  / [Project](https://huanngzh.github.io/Parts2Whole/)  / [Code](https://github.com/huanngzh/Parts2Whole)

**UniHuman: A Unified Model For Editing Human Images in the Wild**<br>
*Li, Nannan and Liu, Qing and Singh, Krishna Kumar and Wang, Yilin and Zhang, Jianming and Plummer, Bryan A and Lin, Zhe.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.14985)  / [Code](https://github.com/NannanLi999/UniHuman)

**Autostory: Generating diverse storytelling images with minimal human effort**<br>
*Wang, Wen and Zhao, Canyu and Chen, Hao and Chen, Zhekai and Zheng, Kecheng and Shen, Chunhua.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2311.11243)  / [Project](https://aim-uofa.github.io/AutoStory/)  / [Code](https://github.com/aim-uofa/AutoStory)

**Synthesizing coherent story with auto-regressive latent diffusion models**<br>
*Pan, Xichen and Qin, Pengda and Li, Yuhong and Xue, Hui and Chen, Wenhu.*<br>
WACV 2024.  / [PDF](https://arxiv.org/abs/2211.10950v1)  / [Code](https://github.com/xichenpan/ARLDM)

**The Chosen One: Consistent Characters in Text-to-Image Diffusion Models**<br>
*Avrahami, Omri and Hertz, Amir and Vinker, Yael and Arar, Moab and Fruchter, Shlomi and Fried, Ohad and Cohen-Or, Daniel and Lischinski, Dani.*<br>
SIGGRPAH 2024.  / [PDF](https://arxiv.org/abs/2311.10093)  / [Project](https://omriavrahami.com/the-chosen-one/)  / [Code](https://github.com/ZichengDuan/TheChosenOne)

### Style-Driven Generation

**UnZipLoRA: Separating Content and Style from a Single Image**<br>
*Liu, Chang and Shah, Viraj and Cui, Aiyu and Lazebnik, Svetlana.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.04465)  / [Project](https://unziplora.github.io/)

**LoRA. rar: Learning to Merge LoRAs via Hypernetworks for Subject-Style Conditioned Image Generation**<br>
*Shenaj, Donald and Bohdal, Ondrej and Ozay, Mete and Zanuttigh, Pietro and Michieli, Umberto.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.05148)

**Style-Friendly SNR Sampler for Style-Driven Generation**<br>
*Choi, Jooyoung and Shin, Chaehun and Oh, Yeongtak and Kim, Heeseung and Yoon, Sungroh.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.14793)  / [Project](https://stylefriendly.github.io/)

**CSGO: Content-Style Composition in Text-to-Image Generation**<br>
*Image, Style.*<br>
OpenReview 2024.  / [PDF](https://openreview.net/forum?id=E3PgLQzPob)

**FineStyle: Fine-grained Controllable Style Personalization for Text-to-image Models**<br>
*Zhang, Gong and Sohn, Kihyuk and Hahn, Meera and Shi, Humphrey and Essa, Irfan.*<br>
NeurIPS 2024.  / [PDF](https://openreview.net/forum?id=1SmXUGzrH8)  / [Code](https://github.com/SHI-Labs/FineStyle)

**Customizing text-to-image models with a single image pair**<br>
*Jones, Maxwell and Wang, Sheng-Yu and Kumari, Nupur and Bau, David and Zhu, Jun-Yan.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2405.01536v2)  / [Project](https://paircustomization.github.io/)  / [Code](https://github.com/PairCustomization/PairCustomization)

**RB-Modulation: Training-Free Personalization of Diffusion Models using Stochastic Optimal Control**<br>
*Rout, Litu and Chen, Yujia and Ruiz, Nataniel and Kumar, Abhishek and Caramanis, Constantine and Shakkottai, Sanjay and Chu, Wen-Sheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.17401) / [Code](https://github.com/google/RB-Modulation)

**InstantStyle: Free lunch towards style-preserving in text-to-image generation**<br>
*Wang, Haofan and Spinelli, Matteo and Wang, Qixun and Bai, Xu and Qin, Zekui and Chen, Anthony.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.02733)  / [Code](https://github.com/instantX-research/InstantStyle)

**Text-to-Image Synthesis for Any Artistic Styles: Advancements in Personalized Artistic Image Generation via Subdivision and Dual Binding**<br>
*Park, Junseo and Ko, Beomseok and Jang, Hyeryung.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.05256)

**Block-wise LoRA: Revisiting Fine-grained LoRA for Effective Personalization and Stylization in Text-to-Image Generation**<br>
*Li, Likun and Zeng, Haoqi and Yang, Changpeng and Jia, Haozhe and Xu, Di.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.07500)

**Break-for-make: Modular low-rank adaptations for composable content-style customization**<br>
*Xu, Yu and Tang, Fan and Cao, Juan and Zhang, Yuxin and Deussen, Oliver and Dong, Weiming and Li, Jintao and Lee, Tong-Yee.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19456)

**U-VAP: User-specified Visual Appearance Personalization via Decoupled Self Augmentation**<br>
*Wu, You and Liu, Kean and Mi, Xiaoyue and Tang, Fan and Cao, Juan and Li, Jintao.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2403.20231v1)  / [Code](https://github.com/ICTMCG/U-VAP)

**Implicit style-content separation using b-lora**<br>
*Frenkel, Yarden and Vinker, Yael and Shamir, Ariel and Cohen-Or, Daniel.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.14572)  / [Project](https://b-lora.github.io/B-LoRA/)  / [Code](https://github.com/yardenfren1996/B-LoRA)

**ArtAdapter: Text-to-Image Style Transfer using Multi-Level Style Encoder and Explicit Adaptation**<br>
*Chen, Dar-Yen and Tennent, Hamish and Hsu, Ching-Wen.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.02109v2)  / [Project](https://cardinalblue.github.io/artadapter.github.io/)  / [Code](https://github.com/cardinalblue/ArtAdapter)

**Style aligned image generation via shared attention**<br>
*Hertz, Amir and Voynov, Andrey and Fruchter, Shlomi and Cohen-Or, Daniel.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.02133v2)  / [Project](https://style-aligned-gen.github.io/)  / [Code](https://github.com/google/style-aligned/)

**Ziplora: Any subject in any style by effectively merging loras**<br>
*Shah, Viraj and Ruiz, Nataniel and Cole, Forrester and Lu, Erika and Lazebnik, Svetlana and Li, Yuanzhen and Jampani, Varun.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2311.13600v1)  / [Project](https://ziplora.github.io/)

**StyleBoost: A Study of Personalizing Text-to-Image Generation in Any Style using DreamBooth**<br>
*Park, Junseo and Ko, Beomseok and Jang, Hyeryung.*<br>
ICTC 2023.  / [PDF](https://ieeexplore.ieee.org/abstract/document/10392676)

**StyleAdapter: A Unified Stylized Image Generation Model**<br>
*Wang, Zhouxia and Wang, Xintao and Xie, Liangbin and Qi, Zhongang and Shan, Ying and Wang, Wenping and Luo, Ping.*<br>
IJCV 2024.  / [PDF](https://arxiv.org/abs/2309.01770v2)

**Styledrop: Text-to-image generation in any style**<br>
*Sohn, Kihyuk and Ruiz, Nataniel and Lee, Kimin and Chin, Daniel Castro and Blok, Irina and Chang, Huiwen and Barber, Jarred and Jiang, Lu and Entis, Glenn and Li, Yuanzhen.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2306.00983)  / [Project](https://styledrop.github.io/)

**Inversion-based style transfer with diffusion models**<br>
*Zhang, Yuxin and Huang, Nisha and Tang, Fan and Huang, Haibin and Ma, Chongyang and Dong, Weiming and Xu, Changsheng.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2211.13203v3)  / [Code](https://github.com/zyxElsa/InST)

### High-level Semantics Generation

**Event-Customized Image Generation**<br>
*Wang, Zhen and Jiang, Yilei and Zheng, Dong and Xiao, Jun and Chen, Long.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.02483)

**ImPoster: Text and Frequency Guidance for Subject Driven Action Personalization using Diffusion Models**<br>
*Kothandaraman, Divya and Kulkarni, Kuldeep and Shekhar, Sumit and Srinivasan, Balaji Vasan and Manocha, Dinesh.*<br>
COLING 2025.  / [PDF](https://arxiv.org/abs/2409.15650)  / [Code](https://github.com/divyakraman/ImPosterDiffusion2024)

**Customizing Text-to-Image Generation with Inverted Interaction**<br>
*Mengmeng Ge, Xu Jia, Takashi Isobe, Xiaomin Li, Qinghe Wang, Jing Mu, Dong Zhou, liwang Amd, Huchuan Lu, Lu Tian, Ashish Sirasao, Emad Barsoum*<br>
ACM MM 2024. / [PDF](https://openreview.net/pdf?id=3Xx2MgYX67) 

**Lego: Learning to disentangle and invert concepts beyond object appearance in text-to-image diffusion models**<br>
*Motamed, Saman and Paudel, Danda Pani and Van Gool, Luc.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2311.13833)

**Learning disentangled identifiers for action-customized text-to-image generation**<br>
*Huang, Siteng and Gong, Biao and Feng, Yutong and Chen, Xi and Fu, Yuqian and Liu, Yu and Wang, Donglin.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.15841v5)  / [Project](https://adi-t2i.github.io/ADI/)

**ReVersion: Diffusion-based relation inversion from images**<br>
*Huang, Ziqi and Wu, Tianxing and Jiang, Yuming and Chan, Kelvin CK and Liu, Ziwei.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2303.13495)  / [Project](https://ziqihuangg.github.io/projects/reversion.html)  / [Code](https://github.com/ziqihuangg/ReVersion)

### Multiple Concepts Generation

**K-LoRA: Unlocking Training-Free Fusion of Any Subject and Style LoRAs**<br>
*Ziheng Ouyang, Zhen Li, Qibin Hou*<br>
CVPR 2025.  / [PDF](https://arxiv.org/pdf/2502.18461) / [Project](https://k-lora.github.io/K-LoRA.io/) / [Code](https://github.com/HVision-NKU/K-LoRA)

**FlipConcept: Tuning-Free Multi-Concept Personalization for Text-to-Image Generation**<br>
*Young Beom Woo, Sun Eung Kim*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/pdf/2502.15203) 

**IP-Composer: Semantic Composition of Visual Concepts**<br>
*Sara Dorfman, Dana Cohen-Bar, Rinon Gal, Daniel Cohen-Or*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.13951) / [Project](https://ip-composer.github.io/IP-Composer/) / [Code](https://github.com/ip-composer)

**Multitwine: Multi-Object Compositing with Text and Layout Control**<br>
*Gemma Canet Tarrés, Zhe Lin, Zhifei Zhang, He Zhang, Andrew Gilbert, John Collomosse, Soo Ye Kim*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.05165)

**Cached Multi-Lora Composition for Multi-Concept Image Generation**<br>
*Xiandong Zou, Mingzhu Shen, Christos-Savvas Bouganis, Yiren Zhao*<br>
ICLR 2025.  / [PDF](https://www.arxiv.org/abs/2502.04923)

**Object-level Visual Prompts for Compositional Image Generation**<br>
*Parmar, Gaurav and Patashnik, Or and Wang, Kuan-Chieh and Ostashev, Daniil and Narasimhan, Srinivasa and Zhu, Jun-Yan and Cohen-Or, Daniel and Aberman, Kfir.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.01424)  / [Project](https://snap-research.github.io/visual-composer/)

**TokenVerse: Versatile Multi-concept Personalization in Token Modulation Space**<br>
*Garibi, Daniel and Yadin, Shahar and Paiss, Roni and Tov, Omer and Zada, Shiran and Ephrat, Ariel and Michaeli, Tomer and Mosseri, Inbar and Dekel, Tali.*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2501.12224)  / [Project](https://token-verse.github.io/)

**Improving Multi-Subject Consistency in Open-Domain Image Generation with Isolation and Reposition Attention**<br>
*He, Huiguo and Wang, Qiuyue and Zhou, Yuan and Cai, Yuxuan and Chao, Hongyang and Yin, Jian and Yang, Huan.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.19261)

**PersonaCraft: Personalized Full-Body Image Synthesis for Multiple Identities from Single References Using 3D-Model-Conditioned Diffusion**<br>
*Kim, Gwanghyun and Jeon, Suh Yoon and Lee, Seunggyu and Chun, Se Young.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.18068)  / [Project](https://gwang-kim.github.io/persona_craft/)  / [Code](https://github.com/gwang-kim/PersonaCraft)

**MagicTailor: Component-Controllable Personalization in Text-to-Image Diffusion Models**<br>
*Zhou, Donghao and Huang, Jiancheng and Bai, Jinbin and Wang, Jiaze and Chen, Hao and Chen, Guangyong and Hu, Xiaowei and Heng, Pheng-Ann.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.13370)  / [Project](https://correr-zhou.github.io/MagicTailor/)  / [Code](https://github.com/correr-zhou/MagicTailor)

**How to Continually Adapt Text-to-Image Diffusion Models for Flexible Customization?**<br>
*Dong, Jiahua and Liang, Wenqi and Li, Hongliu and Zhang, Duzhen and Cao, Meng and Ding, Henghui and Khan, Salman and Khan, Fahad Shahbaz.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2410.17594)  / [Code](https://github.com/JiahuaDong/CIFC)

**RelationBooth: Towards Relation-Aware Customized Object Generation**<br>
*Shi, Qingyu and Qi, Lu and Wu, Jianzong and Bai, Jinbin and Wang, Jingbo and Tong, Yunhai and Li, Xiangtai and Yang, Ming-Husang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.23280)  / [Project](https://shi-qingyu.github.io/RelationBooth/)

**GroundingBooth: Grounding Text-to-Image Customization**<br>
*Xiong, Zhexiao and Xiong, Wei and Shi, Jing and Zhang, He and Song, Yizhi and Jacobs, Nathan.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.08520)  / [Project](https://groundingbooth.github.io/)

**MS-Diffusion: Multi-subject Zero-shot Image Personalization with Layout Guidance**<br>
*Personalization, Single-subject.*<br>
ICLR 2025.  / [PDF](https://openreview.net/forum?id=PJqP0wyQek)

**Concept Conductor: Orchestrating Multiple Personalized Concepts in Text-to-Image Synthesis**<br>
*Yao, Zebin and Feng, Fangxiang and Li, Ruifan and Wang, Xiaojie.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2408.03632)  / [Project](https://nihukat.github.io/Concept-Conductor/)  / [Code](https://github.com/Nihukat/Concept-Conductor)

**Training-free Subject-Enhanced Attention Guidance for Compositional Text-to-image Generation**<br>
*Liu, Shengyuan and Wang, Bo and Ma, Ye and Yang, Te and Cao, Xipeng and Chen, Quan and Li, Han and Dong, Di and Jiang, Peng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.06948)

**Multi-Subject Personalization**<br>
*Jain, Arushi and Paliwal, Shubham and Sharma, Monika and Jamwal, Vikram and Vig, Lovekesh.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2405.12742)

**FreeCustom: Tuning-Free Customized Image Generation for Multi-Concept Composition**<br>
*Ding, Ganggui and Zhao, Canyu and Wang, Wen and Yang, Zhen and Liu, Zide and Chen, Hao and Shen, Chunhua.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2405.13870v1)  / [Project](https://aim-uofa.github.io/FreeCustom/)  / [Code](https://github.com/aim-uofa/FreeCustom)

**Identity Decoupling for Multi-Subject Personalization of Text-to-Image Models**<br>
*Jang, Sangwon and Jo, Jaehyeong and Lee, Kimin and Hwang, Sung Ju.*<br>
NeurIPS 2024.  / [PDF](https://arxiv.org/abs/2404.04243)  / [Project](https://mudi-t2i.github.io/)  / [Code](https://github.com/agwmon/MuDI)

**Concept Weaver: Enabling Multi-Concept Fusion in Text-to-Image Models**<br>
*Kwon, Gihyun and Jenni, Simon and Li, Dingzeyu and Lee, Joon-Young and Ye, Jong Chul and Heilbron, Fabian Caba.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2404.03913v1)

**MC$^2$: Multi-concept Guidance for Customized Multi-concept Generation**<br>
*Jiang, Jiaxiu and Zhang, Yabo and Feng, Kailai and Wu, Xiaohe and Zuo, Wangmeng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.05268)  / [Code](https://github.com/JIANGJiaXiu/MC-2)

**LoRA-Composer: Leveraging Low-Rank Adaptation for Multi-Concept Customization in Training-Free Diffusion Models**<br>
*Yang, Yang and Wang, Wen and Peng, Liang and Song, Chaotian and Chen, Yao and Li, Hengjia and Yang, Xiaolong and Lu, Qinglin and Cai, Deng and Wu, Boxi and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.11627)  / [Project](https://young98cn.github.io/lora_composer_page/)  / [Code](https://github.com/Young98CN/LoRA_Composer)

**Omg: Occlusion-friendly personalized multi-concept generation in diffusion models**<br>
*Kong, Zhe and Zhang, Yong and Yang, Tianyu and Wang, Tao and Zhang, Kaihao and Wu, Bizhu and Chen, Guanying and Liu, Wei and Luo, Wenhan.*<br>
ECCV 2024.  / [PDF](https://arxiv.org/abs/2403.10983v2)  / [Project](https://kongzhecn.github.io/omg-project/)  / [Code](https://github.com/kongzhecn/OMG/)

**$\lambda$-ECLIPSE: Multi-Concept Personalized Text-to-Image Diffusion Models by Leveraging CLIP Latent Space**<br>
*Patel, Maitreya and Jung, Sangmin and Baral, Chitta and Yang, Yezhou.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2402.05195)  / [Project](https://eclipse-t2i.github.io/Lambda-ECLIPSE/)  / [Code](https://github.com/eclipse-t2i/lambda-eclipse-inference)

**Compositional inversion for stable diffusion models**<br>
*Zhang, Xulu and Wei, Xiao-Yong and Wu, Jinlin and Zhang, Tianyi and Zhang, Zhaoxiang and Lei, Zhen and Li, Qing.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2312.08048v3)  / [Code](https://github.com/zhangxulu1996/Compositional-Inversion)

**Customizable image synthesis with multiple subjects**<br>
*Liu, Zhiheng and Zhang, Yifei and Shen, Yujun and Zheng, Kecheng and Zhu, Kai and Feng, Ruili and Liu, Yu and Zhao, Deli and Zhou, Jingren and Cao, Yang.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.19327v1)  / [Project](https://cones-page.github.io/)  / [Code](https://github.com/ali-vilab/Cones-V2)

**Mix-of-show: Decentralized low-rank adaptation for multi-concept customization of diffusion models**<br>
*Gu, Yuchao and Wang, Xintao and Wu, Jay Zhangjie and Shi, Yujun and Chen, Yunpeng and Fan, Zihan and Xiao, Wuyou and Zhao, Rui and Chang, Shuning and Wu, Weijia and {others}.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2305.18292)  / [Code](https://github.com/TencentARC/Mix-of-Show)

**Multi-concept customization of text-to-image diffusion**<br>
*Kumari, Nupur and Zhang, Bingliang and Zhang, Richard and Shechtman, Eli and Zhu, Jun-Yan.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2212.04488v2)  / [Project](https://www.cs.cmu.edu/~custom-diffusion)  / [Code](https://github.com/adobe-research/custom-diffusion)

### Personalized Video Generation

**FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation**<br>
*Yunpeng Zhang, Qiang Wang, Fan Jiang, Yaqi Fan, Mu Xu, Yonggang Qi*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.13995) / [Project](https://fantasy-amap.github.io/fantasy-id/) / [Code](https://github.com/Fantasy-AMAP/fantasy-id)

**Dynamic Concepts Personalization from Single Videos**<br>
*Rameen Abdal, Or Patashnik, Ivan Skorokhodov, Willi Menapace, Aliaksandr Siarohin, Sergey Tulyakov, Daniel Cohen-Or, Kfir Aberman*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.14844) / [Project](https://snap-research.github.io/dynamic_concepts/)

**Phantom: Subject-consistent video generation via cross-modal alignment**<br>
*Lijie Liu, Tianxiang Ma, Bingchuan Li, Zhuowei Chen, Jiawei Liu, Qian He, Xinglong Wu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.11079) / [Project](https://phantom-video.github.io/Phantom/) / [Code](https://github.com/Phantom-video/Phantom)

**CustomVideoX: 3D Reference Attention Driven Dynamic Adaptation for Zero-Shot Customized Video Diffusion Transformers**<br>
*D. She, Mushui Liu, Jingxuan Pang, Jin Wang, Zhen Yang, Wanggui He, Guanghao Zhang, Yi Wang, Qihan Huang, Haobin Tang, Yunlong Yu, Siming Fu*<br>
Arxiv 2025. / [PDF](https://www.arxiv.org/abs/2502.06527) / [Project](https://xiaobul.github.io/CustomVideoX/) / [Code](https://github.com/XiaoBuL/CustomVideoX-)

**Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts**<br>
*Feng Liang, Haoyu Ma, Zecheng He, Tingbo Hou, Ji Hou, Kunpeng Li, Xiaoliang Dai, Felix Juefei-Xu, Samaneh Azadi, Animesh Sinha, Peizhao Zhang, Peter Vajda, Diana Marculescu*<br>
Arxiv 2025. / [PDF](https://arxiv.org/abs/2502.07802) / [Project](https://jeff-liangf.github.io/projects/movieweaver/)

**DIVE: Taming DINO for Subject-Driven Video Editing**<br>
*Yi Huang, Wei Xiong, He Zhang, Chaoqi Chen, Jianzhuang Liu, Mingfu Yan, Shifeng Chen*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2412.03347) / [Project](https://dino-video-editing.github.io/)

**MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models**<br>
*Xiaomin Li, Xu Jia, Qinghe Wang, Haiwen Diao, Mengmeng Ge, Pengxiang Li, You He, Huchuan Lu*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2412.01343) / [Code](https://github.com/XiaominLi1997/MoTrans)

**PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation**<br>
*Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, Yujie Wei, Zekun Li, Yingya Zhang, Boxi Wu, Deng Cai*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2411.17048) / [Project](https://personalvideo.github.io/) / [Code](https://github.com/EchoPluto/PersonalVideo)

**DreamRunner: Fine-Grained Storytelling Video Generation with Retrieval-Augmented Motion Adaptation**<br>
*Zun Wang, Jialu Li, Han Lin, Jaehong Yoon, Mohit Bansal*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2411.16657) / [Project](https://zunwang1.github.io/DreamRunner) / [Code](https://github.com/wz0919/DreamRunner)

**DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise Motion Control**<br>
*Yujie Wei, Shiwei Zhang, Hangjie Yuan, Xiang Wang, Haonan Qiu, Rui Zhao, Yutong Feng, Feng Liu, Zhizhong Huang, Jiaxin Ye, Yingya Zhang, Hongming Shan*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2410.13830) / [Project](https://dreamvideo2.github.io/)

**CustomCrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities**<br>
*Tao Wu, Yong Zhang, Xintao Wang, Xianpan Zhou, Guangcong Zheng, Zhongang Qi, Ying Shan, Xi Li*<br>
AAAI 2025. / [PDF](https://arxiv.org/abs/2408.13239) / [Project](https://customcrafter.github.io/) / [Code](https://github.com/WuTao-CS/CustomCrafter)

**Text Prompting for Multi-Concept Video Customization by Autoregressive Generation**<br>
*Divya Kothandaraman, Kihyuk Sohn, Ruben Villegas, Paul Voigtlaender, Dinesh Manocha, Mohammad Babaeizadeh*<br>
CVPR 2024 AI4CC Workshop. / [PDF](https://arxiv.org/abs/2405.13951) 

**DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control**<br>
*Hong Chen, Xin Wang, Yipeng Zhang, Yuwei Zhou, Zeyang Zhang, Siao Tang, Wenwu Zhu*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2405.12796) / [Project](https://forchchch.github.io/disenstudio.github.io/)

**Magic-Me: Identity-Specific Video Customized Diffusion**<br>
*Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, Xue-She Wang, Xiuyu Li, Huanrui Yang, Zhen Dong, Kurt Keutzer, Jiashi Feng*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2402.09368) / [Project](https://magic-me-webpage.github.io/) / [Code](https://github.com/Zhen-Dong/Magic-Me)

**CustomVideo: Customizing Text-to-Video Generation with Multiple Subjects**<br>
*Zhao Wang, Aoxue Li, Lingting Zhu, Yong Guo, Qi Dou, Zhenguo Li*<br>
Arxiv 2024. / [PDF](https://arxiv.org/abs/2401.09962) / [Project](https://kyfafyd.wang/projects/customvideo/)

**VideoBooth: Diffusion-based Video Generation with Image Prompts**<br>
*Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu*<br>
CVPR 2024. / [PDF](https://arxiv.org/abs/2312.00777) / [Project](https://vchitect.github.io/VideoBooth-project/) / [Code](https://github.com/Vchitect/VideoBooth)

**Pia: Your personalized image animator via plug-and-play modules in text-to-image models**<br>
*Zhang, Yiming and Xing, Zhening and Zeng, Yanhong and Fang, Youqing and Chen, Kai.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.13964v3)  / [Project](https://pi-animator.github.io/)  / [Code](https://github.com/open-mmlab/PIA)

### Personalized 3D Generation

**A Unified Approach for Text- and Image-guided 4D Scene Generation**<br>
*Yufeng Zheng, Xueting Li, Koki Nagano, Sifei Liu, Karsten Kreis, Otmar Hilliges, Shalini De Mello*<br>
CVPR 2024. / [PDF](https://arxiv.org/abs/2311.16854) / [Project](https://research.nvidia.com/labs/nxp/dream-in-4d/) / [Code](https://github.com/NVlabs/dream-in-4d)

**Animate124: Animating One Image to 4D Dynamic Scene**<br>
*Yuyang Zhao, Zhiwen Yan, Enze Xie, Lanqing Hong, Zhenguo Li, Gim Hee Lee*<br>
Arxiv 2023. / [PDF](https://arxiv.org/abs/2311.14603) / [Project](https://animate124.github.io/) / [Code](https://github.com/HeliosZhao/Animate124)

**Chasing Consistency in Text-to-3D Generation from a Single Image**<br>
*Yichen Ouyang, Wenhao Chai, Jiayi Ye, Dapeng Tao, Yibing Zhan, Gaoang Wang*<br>
Arxiv 2023. / [PDF](https://arxiv.org/abs/2309.03599)

**DreamBooth3D: Subject-Driven Text-to-3D Generation**<br>
*Amit Raj, Srinivas Kaza, Ben Poole, Michael Niemeyer, Nataniel Ruiz, Ben Mildenhall, Shiran Zada, Kfir Aberman, Michael Rubinstein, Jonathan Barron, Yuanzhen Li, Varun Jampani*<br>
ICCV 2023. / [PDF](https://arxiv.org/abs/2303.13508) / [Project](https://dreambooth3d.github.io/) 


### Text-driven Image Editing

**Energy-Guided Optimization for Personalized Image Editing with Pretrained Text-to-Image Diffusion Models**<br>
*Rui Jiang, Xinghe Fu, Guangcong Zheng, Teng Li, Taiping Yao, Xi Li*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.04215)

**h-Edit: Effective and Flexible Diffusion-Based Editing via Doob's h-Transform**<br>
*Toan Nguyen, Kien Do, Duc Kieu, Thin Nguyen*<br>
CVPR 2025.  / [PDF](https://arxiv.org/abs/2503.02187) / [Code](https://github.com/nktoan/h-edit)

**KV-Edit: Training-Free Image Editing for Precise Background Preservation**<br>
*Tianrui Zhu, Shiyi Zhang, Jiawei Shao, Yansong Tang*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.17363)  / [Project](https://partedit.github.io/PartEdit/) 

**PartEdit: Fine-Grained Image Editing using Pre-Trained Diffusion Models**<br>
*Aleksandar Cvejic, Abdelrahman Eldesokey, Peter Wonka*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.04050)  / [Project](https://xilluill.github.io/projectpages/KV-Edit/) / [Code](https://github.com/Xilluill/KV-Edit)

**Stable Flow: Vital Layers for Training-Free Image Editing**<br>
*Avrahami, Omri and Patashnik, Or and Fried, Ohad and Nemchinov, Egor and Aberman, Kfir and Lischinski, Dani and Cohen-Or, Daniel.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2411.14430)  / [Project](https://omriavrahami.com/stable-flow/)

**HeadRouter: A Training-free Image Editing Framework for MM-DiTs by Adaptively Routing Attention Heads**<br>
*Xu, Yu and Tang, Fan and Cao, Juan and Zhang, Yuxin and Kong, Xiaoyu and Li, Jintao and Deussen, Oliver and Lee, Tong-Yee.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2411.15034)  / [Project](https://yuci-gpt.github.io/headrouter/)  / [Code](https://github.com/ICTMCG/HeadRouter)

**Unveil Inversion and Invariance in Flow Transformer for Versatile Image Editing**<br>
*Xu, Pengcheng and Jiang, Boyuan and Hu, Xiaobin and Luo, Donghao and He, Qingdong and Zhang, Jiangning and Wang, Chengjie and Wu, Yunsheng and Ling, Charles and Wang, Boyu.*<br>
CVPR  2024.  / [PDF](https://arxiv.org/abs/2411.15843)  / [Project](https://pengchengpcx.github.io/EditFT/)  / [Code](https://github.com/Pengchengpcx/FTEdit)

**GANTASTIC: GAN-based Transfer of Interpretable Directions for Disentangled Image Editing in Text-to-Image Diffusion Models**<br>
*Dalva, Yusuf and Yesiltepe, Hidir and Yanardag, Pinar.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.19645)  / [Project](https://gantastic.github.io/)

**Ledits++: Limitless image editing using text-to-image models**<br>
*Brack, Manuel and Friedrich, Felix and Kornmeier, Katharia and Tsaban, Linoy and Schramowski, Patrick and Kersting, Kristian and Passos, Apolinário.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2311.16711)  / [Project](https://leditsplusplus-project.static.hf.space/index.html)  / [Code](https://github.com/huggingface/diffusers/tree/main/src/diffusers/pipelines/ledits_pp)

**An edit friendly ddpm noise space: Inversion and manipulations**<br>
*Huberman-Spiegelglas, Inbar and Kulikov, Vladimir and Michaeli, Tomer.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2304.06140)  / [Project](https://inbarhub.github.io/DDPM_inversion)  / [Code](https://github.com/inbarhub/DDPM_inversion)

**Delta denoising score**<br>
*Hertz, Amir and Aberman, Kfir and Cohen-Or, Daniel.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2304.07090v1)  / [Project](https://delta-denoising-score.github.io/)  / [Code](https://github.com/google/prompt-to-prompt/blob/main/DDS_zeroshot.ipynb)

**Masactrl: Tuning-free mutual self-attention control for consistent image synthesis and editing**<br>
*Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Shan, Ying and Qie, Xiaohu and Zheng, Yinqiang.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2304.08465v1)  / [Project](https://ljzycmd.github.io/projects/MasaCtrl)  / [Code](https://github.com/TencentARC/MasaCtrl)

**Null-text inversion for editing real images using guided diffusion models**<br>
*Mokady, Ron and Hertz, Amir and Aberman, Kfir and Pritch, Yael and Cohen-Or, Daniel.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2211.09794v1)  / [Project](https://null-text-inversion.github.io)  / [Code](https://github.com/google/prompt-to-prompt/#null-text-inversion-for-editing-real-images)

**Prompt-to-prompt image editing with cross attention control**<br>
*Hertz, Amir and Mokady, Ron and Tenenbaum, Jay and Aberman, Kfir and Pritch, Yael and Cohen-Or, Daniel.*<br>
ICLR 2023.  / [PDF](https://arxiv.org/abs/2208.01626)  / [Project](https://prompt-to-prompt.github.io)  / [Code](https://github.com/google/prompt-to-prompt)

**Blended Latent Diffusion**<br>
*Avrahami, Omri and Fried, Ohad and Lischinski, Dani.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2206.02779)  / [Project](https://omriavrahami.com/blended-latent-diffusion-page/)  / [Code](https://github.com/omriav/blended-latent-diffusion)

**Blended Diffusion: Text-driven Editing of Natural Images**<br>
*Avrahami, Omri and Lischinski, Dani and Fried, Ohad.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2111.14818)  / [Project](https://omriavrahami.com/blended-diffusion-page/)  / [Code](https://github.com/omriav/blended-diffusion)

## Personalization with AR Models

**ILLUME: Illuminating Your LLMs to See, Draw, and Self-Enhance**<br>
*Wang, Chunwei and Lu, Guansong and Yang, Junwei and Huang, Runhui and Han, Jianhua and Hou, Lu and Zhang, Wei and Xu, Hang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.06673)

**MetaMorph: Multimodal Understanding and Generation via Instruction Tuning**<br>
*Tong, Shengbang and Fan, David and Zhu, Jiachen and Xiong, Yunyang and Chen, Xinlei and Sinha, Koustuv and Rabbat, Michael and LeCun, Yann and Xie, Saining and Liu, Zhuang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.14164)  / [Project](https://tsb0601.github.io/metamorph/)

**Liquid: Language Models are Scalable Multi-modal Generators**<br>
*Wu, Junfeng and Jiang, Yi and Ma, Chuofan and Liu, Yuliang and Zhao, Hengshuang and Yuan, Zehuan and Bai, Song and Bai, Xiang.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.04332) / [Project](https://foundationvision.github.io/Liquid/) / [Code](https://github.com/FoundationVision/Liquid)

**X-Prompt: Towards Universal In-Context Image Generation in Auto-Regressive Vision Language Foundation Models**<br>
*Sun, Zeyi and Chu, Ziyang and Zhang, Pan and Wu, Tong and Dong, Xiaoyi and Zang, Yuhang and Xiong, Yuanjun and Lin, Dahua and Wang, Jiaqi.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2412.01824)  / [Code](https://github.com/SunzeY/X-Prompt)

**Puma: Empowering unified mllm with multi-granular visual generation**<br>
*Fang, Rongyao and Duan, Chengqi and Wang, Kun and Li, Hao and Tian, Hao and Zeng, Xingyu and Zhao, Rui and Dai, Jifeng and Li, Hongsheng and Liu, Xihui.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2410.13861)  / [Project](https://rongyaofang.github.io/puma/)  / [Code](https://github.com/rongyaofang/PUMA)

**Emu3: Next-token prediction is all you need**<br>
*Wang, Xinlong and Zhang, Xiaosong and Luo, Zhengxiong and Sun, Quan and Cui, Yufeng and Wang, Jinsheng and Zhang, Fan and Wang, Yueze and Li, Zhen and Yu, Qiying and {others}.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.18869)  / [Project](https://emu.baai.ac.cn/about)  / [Code](https://github.com/baaivision/Emu3)

**Chameleon: Mixed-modal early-fusion foundation models**<br>
*Team, Chameleon.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.09818)

**Seed-x: Multimodal models with unified multi-granularity comprehension and generation**<br>
*Ge, Yuying and Zhao, Sijie and Zhu, Jinguo and Ge, Yixiao and Yi, Kun and Song, Lin and Li, Chen and Ding, Xiaohan and Shan, Ying.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2404.14396)  / [Code](https://github.com/AILab-CVC/SEED-X)

**Generative multimodal models are in-context learners**<br>
*Sun, Quan and Cui, Yufeng and Zhang, Xiaosong and Zhang, Fan and Yu, Qiying and Wang, Yueze and Rao, Yongming and Liu, Jingjing and Huang, Tiejun and Wang, Xinlong.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2312.13286)  / [Project](https://baaivision.github.io/emu2/)  / [Code](https://github.com/baaivision/Emu)

**Next-gpt: Any-to-any multimodal llm**<br>
*Wu, Shengqiong and Fei, Hao and Qu, Leigang and Ji, Wei and Chua, Tat-Seng.*<br>
ICML 2024.  / [PDF](https://arxiv.org/abs/2309.05519)  / [Project](https://next-gpt.github.io/)  / [Code](https://github.com/NExT-GPT/NExT-GPT)

**Emu: Generative pretraining in multimodality**<br>
*Sun, Quan and Yu, Qiying and Cui, Yufeng and Zhang, Fan and Zhang, Xiaosong and Wang, Yueze and Gao, Hongcheng and Liu, Jingjing and Huang, Tiejun and Wang, Xinlong.*<br>
ICLR 2024.  / [PDF](https://arxiv.org/abs/2307.05222v2)  / [Code](https://github.com/baaivision/Emu)

## Personalization with GANs 

### GAN Inversion

**Spatially-adaptive multilayer selection for gan inversion and editing**<br>
*Parmar, Gaurav and Li, Yijun and Lu, Jingwan and Zhang, Richard and Zhu, Jun-Yan and Singh, Krishna Kumar.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2206.08357v1)  / [Project](https://www.cs.cmu.edu/~SAMInversion)  / [Code](https://github.com/adobe-research/sam_inversion)

**Mystyle: A personalized generative prior**<br>
*Nitzan, Yotam and Aberman, Kfir and He, Qiurui and Liba, Orly and Yarom, Michal and Gandelsman, Yossi and Mosseri, Inbar and Pritch, Yael and Cohen-Or, Daniel.*<br>
SIGGRAPH ASIA 2022.  / [PDF](https://arxiv.org/abs/2203.17272)  / [Project](https://mystyle-personalized-prior.github.io)  / [Code](https://github.com/google/mystyle)

**Style transformer for image inversion and editing**<br>
*Hu, Xueqi and Huang, Qiusheng and Shi, Zhengyi and Li, Siyuan and Gao, Changxin and Sun, Li and Li, Qingli.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2203.07932v1)  / [Code](https://github.com/sapphire497/style-transformer)

**Near perfect gan inversion**<br>
*Feng, Qianli and Shah, Viraj and Gadde, Raghudeep and Perona, Pietro and Martinez, Aleix.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2202.11833)

**Hyperinverter: Improving stylegan inversion via hypernetwork**<br>
*Dinh, Tan M and Tran, Anh Tuan and Nguyen, Rang and Hua, Binh-Son.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2112.00719)  / [Project](https://di-mi-ta.github.io/HyperInverter)  / [Code](https://github.com/VinAIResearch/HyperInverter)

**High-fidelity gan inversion for image attribute editing**<br>
*Wang, Tengfei and Zhang, Yong and Fan, Yanbo and Wang, Jue and Chen, Qifeng.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2109.06590v4)  / [Project](https://tengfei-wang.github.io/HFGI)  / [Code](https://github.com/Tengfei-Wang/HFGI)

**Gan inversion for out-of-range images with geometric transformations**<br>
*Kang, Kyoungkook and Kim, Seongtae and Cho, Sunghyun.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2108.08998v1)  / [Project](https://kkang831.github.io/assets/publications/9998_ICCV2021_BDInvert)  / [Code](https://github.com/kkang831/BDInvert_Release)

**Pivotal tuning for latent-based editing of real images**<br>
*Roich, Daniel and Mokady, Ron and Bermano, Amit H and Cohen-Or, Daniel.*<br>
ACM TOG 2022.  / [PDF](https://arxiv.org/abs/2106.05744)  / [Code](https://github.com/danielroich/PTI)

**E2Style: Improve the efficiency and effectiveness of StyleGAN inversion**<br>
*Wei, Tianyi and Chen, Dongdong and Zhou, Wenbo and Liao, Jing and Zhang, Weiming and Yuan, Lu and Hua, Gang and Yu, Nenghai.*<br>
TIP 2022.  / [PDF](https://arxiv.org/abs/2104.07661v2)  / [Code](https://github.com/wtybest/e2style)

**Restyle: A residual-based stylegan encoder via iterative refinement**<br>
*Alaluf, Yuval and Patashnik, Or and Cohen-Or, Daniel.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2104.02699v2)  / [Project](https://yuval-alaluf.github.io/restyle-encoder)  / [Code](https://github.com/yuval-alaluf/restyle-encoder)

**Ensembling with deep generative views**<br>
*Chai, Lucy and Zhu, Jun-Yan and Shechtman, Eli and Isola, Phillip and Zhang, Richard.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2104.14551v1)  / [Project](https://chail.github.io/gan-ensembling)  / [Code](https://github.com/chail/gan-ensembling)

**Designing an encoder for stylegan image manipulation**<br>
*Tov, Omer and Alaluf, Yuval and Nitzan, Yotam and Patashnik, Or and Cohen-Or, Daniel.*<br>
SIGGRAPH 2021.  / [PDF](https://arxiv.org/abs/2102.02766v1)  / [Code](https://github.com/omertov/encoder4editing)

**Improved stylegan embedding: Where are the good latents?**<br>
*Zhu, Peihao and Abdal, Rameen and Qin, Yipeng and Femiani, John and Wonka, Peter.*<br>
Arxiv 2020.  / [PDF](https://arxiv.org/abs/2012.09036)

**Style intervention: How to achieve spatial disentanglement with style-based generators?**<br>
*Liu, Yunfan and Li, Qi and Sun, Zhenan and Tan, Tieniu.*<br>
Arxiv 2020.  / [PDF](https://arxiv.org/abs/2011.09699)

**Encoding in style: a stylegan encoder for image-to-image translation**<br>
*Richardson, Elad and Alaluf, Yuval and Patashnik, Or and Nitzan, Yotam and Azar, Yaniv and Shapiro, Stav and Cohen-Or, Daniel.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2008.00951v2)  / [Project](https://eladrich.github.io/pixel2style2pixel)  / [Code](https://github.com/eladrich/pixel2style2pixel)

**In-domain gan inversion for real image editing**<br>
*Zhu, Jiapeng and Shen, Yujun and Zhao, Deli and Zhou, Bolei.*<br>
ECCV 2020.  / [PDF](https://arxiv.org/abs/2004.00049v3)  / [Project](https://genforce.github.io/idinvert)  / [Code](https://github.com/genforce/idinvert_pytorch)

**Image2stylegan++: How to edit the embedded images?**<br>
*Abdal, Rameen and Qin, Yipeng and Wonka, Peter.*<br>
CVPR 2020.  / [PDF](https://arxiv.org/abs/1911.11544v2)

**Inverting layers of a large generator**<br>
*Bau, David and Zhu, Jun-Yan and Wulff, Jonas and Peebles, William and Strobelt, Hendrik and Zhou, Bolei and Torralba, Antonio.*<br>
ICLR 2019.  / [PDF](https://debug-ml-iclr2019.github.io/cameraready/DebugML-19_paper_18.pdf)

**Image2stylegan: How to embed images into the stylegan latent space?**<br>
*Abdal, Rameen and Qin, Yipeng and Wonka, Peter.*<br>
ICCV 2019.  / [PDF](https://arxiv.org/abs/1904.03189v2)

**Invertibility of convolutional generative networks from partial measurements**<br>
*Ma, Fangchang and Ayaz, Ulas and Karaman, Sertac.*<br>
NIPS 2018.  / [PDF](https://proceedings.neurips.cc/paper/2018/hash/e0ae4561193dbf6e4cf7e8f4006948e3-Abstract.html)  / [Code](https://github.com/fangchangma/invert-generative-networks)

**Inverting the generator of a generative adversarial network**<br>
*Creswell, Antonia and Bharath, Anil Anthony.*<br>
IEEE TNNLS 2019.  / [PDF](https://ieeexplore.ieee.org/abstract/document/8520899)  / [Code](https://github.com/ToniCreswell/InvertingGAN)

**Solving linear inverse problems using gan priors: An algorithm with provable guarantees**<br>
*Shah, Viraj and Hegde, Chinmay.*<br>
IEEE ICASSP 2018.  / [PDF](https://arxiv.org/abs/1802.08406)

**Precise recovery of latent vectors from generative adversarial networks**<br>
*Lipton, Zachary C and Tripathi, Subarna.*<br>
ICLR 2017.  / [PDF](https://arxiv.org/abs/1702.04782)

**Generative visual manipulation on the natural image manifold**<br>
*Zhu, Jun-Yan and Krähenbühl, Philipp and Shechtman, Eli and Efros, Alexei A.*<br>
ECCV 2016.  / [PDF](https://arxiv.org/abs/1609.03552)  / [Project](https://www.cs.cmu.edu/~junyanz/projects/gvm)  / [Code](https://github.com/junyanz/iGAN)

**Unsupervised representation learning with deep convolutional generative adversarial networks**<br>
*Radford, Alec.*<br>
ICLR 2016.  / [PDF](https://arxiv.org/abs/1511.06434)

### Latent Editing

**HyperGAN-CLIP: A Unified Framework for Domain Adaptation, Image Synthesis and Manipulation**<br>
*Anees, Abdul Basit and Baykal, Ahmet Canberk and Kizil, Muhammed Burak and Ceylan, Duygu and Erdem, Erkut and Erdem, Aykut.*<br>
SIGGRAPH Asia 2024.  / [PDF](https://arxiv.org/abs/2411.12832v1)  / [Project](https://cyberiada.github.io/HyperGAN-CLIP)  / [Code](https://github.com/basitanees/HyperGAN-CLIP)

**Edit One for All: Interactive Batch Image Editing**<br>
*Nguyen, Thao and Ojha, Utkarsh and Li, Yuheng and Liu, Haotian and Lee, Yong Jae.*<br>
CVPR 2024.  / [PDF](https://arxiv.org/abs/2401.10219)  / [Project](https://thaoshibe.github.io/edit-one-for-all/)  / [Code](https://github.com/WisconsinAIVision/edit-one-for-all)

**HyperEditor: Achieving Both Authenticity and Cross-Domain Capability in Image Editing via Hypernetworks**<br>
*Zhang, Hai and Wu, Chunwei and Cao, Guitao and Wang, Hailing and Cao, Wenming.*<br>
AAAI 2024.  / [PDF](https://arxiv.org/abs/2312.13537)

**Warping the residuals for image editing with stylegan**<br>
*Yildirim, Ahmet Burak and Pehlivan, Hamza and Dundar, Aysegul.*<br>
Arxiv 2023.  / [PDF](https://arxiv.org/abs/2312.11422)

**Exploring Attribute Variations in Style-based GANs using Diffusion Models**<br>
*Parihar, Rishubh and Balaji, Prasanna and Magazine, Raghav and Vora, Sarthak and Karmali, Tejan and Jampani, Varun and Babu, R Venkatesh.*<br>
NeurIPS 2023.  / [PDF](https://arxiv.org/abs/2311.16052)

**Revisiting Latent Space of GAN Inversion for Real Image Editing**<br>
*Katsumata, Kai and Vo, Duc Minh and Liu, Bei and Nakayama, Hideki.*<br>
WACV 2024.  / [PDF](https://arxiv.org/abs/2307.08995)

**StylePrompter: All Styles Need Is Attention**<br>
*Zhuang, Chenyi and Gao, Pan and Smolic, Aljosa.*<br>
ACM MM 2023.  / [PDF](https://arxiv.org/abs/2307.16151v1)  / [Code](https://github.com/I2-Multimedia-Lab/StylePrompter)

**CLIP-guided StyleGAN Inversion for Text-driven Real Image Editing**<br>
*Baykal, Ahmet Canberk and Anees, Abdul Basit and Ceylan, Duygu and Erdem, Erkut and Erdem, Aykut and Yuret, Deniz.*<br>
ACM TOG 2023.  / [PDF](https://arxiv.org/abs/2307.08397v2)  / [Project](https://cyberiada.github.io/CLIPInverter)  / [Code](https://github.com/johnberg1/CLIPInverter)

**Drag your gan: Interactive point-based manipulation on the generative image manifold**<br>
*Pan, Xingang and Tewari, Ayush and Leimkühler, Thomas and Liu, Lingjie and Meka, Abhimitra and Theobalt, Christian.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2305.10973)  / [Project](https://vcai.mpi-inf.mpg.de/projects/DragGAN)  / [Code](https://github.com/XingangPan/DragGAN)

**Deltaedit: Exploring text-free training for text-driven image manipulation**<br>
*Lyu, Yueming and Lin, Tianwei and Li, Fu and He, Dongliang and Dong, Jing and Tan, Tieniu.*<br>
CVPR 2023.  / [PDF](https://arxiv.org/abs/2303.06285)  / [Code](https://github.com/Yueming6568/DeltaEdit)

**One model to edit them all: Free-form text-driven image manipulation with semantic modulations**<br>
*Zhu, Yiming and Liu, Hongyu and Song, Yibing and Yuan, Ziyang and Han, Xintong and Yuan, Chun and Chen, Qifeng and Wang, Jue.*<br>
NeurIPS 2022.  / [PDF](https://arxiv.org/abs/2210.07883)  / [Code](https://github.com/kristen-rang/FFCLIP)

**Bridging clip and stylegan through latent alignment for image editing**<br>
*Zheng, Wanfeng and Li, Qiang and Guo, Xiaoyan and Wan, Pengfei and Wang, Zhongyuan.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2210.04506)

**clip2latent: Text driven sampling of a pre-trained stylegan using denoising diffusion and clip**<br>
*Pinkney, Justin NM and Li, Chuan.*<br>
BMVC 2022.  / [PDF](https://arxiv.org/abs/2210.02347)  / [Code](https://github.com/justinpinkney/clip2latent)

**CLIP-PAE: projection-augmentation embedding to extract relevant features for a disentangled, interpretable and controllable text-guided face manipulation**<br>
*Zhou, Chenliang and Zhong, Fangcheng and Öztireli, Cengiz.*<br>
SIGGRAPH 2023.  / [PDF](https://arxiv.org/abs/2210.03919)  / [Project](https://chenliang-zhou.github.io/CLIP-PAE)  / [Code](https://github.com/genforce/interfacegan)

**Rewriting geometric rules of a GAN.**<br>
*Wang, Sheng-Yu and Bau, David and Zhu, Jun-Yan.*<br>
SIGGRAPH 2022.  / [PDF](https://arxiv.org/abs/2207.14288v1)  / [Project](https://peterwang512.github.io/GANWarping)  / [Code](https://github.com/peterwang512/GANWarping)

**Towards diverse and faithful one-shot adaption of generative adversarial networks**<br>
*Zhang, Yabo and Yao, Mingshuai and Wei, Yuxiang and Ji, Zhilong and Bai, Jinfeng and Zuo, Wangmeng and {others}.*<br>
NeurIPS 2022.  / [PDF](https://arxiv.org/abs/2207.08736)  / [Code](https://github.com/YBYBZhang/DiFa)

**Contraclip: Interpretable gan generation driven by pairs of contrasting sentences**<br>
*Tzelepis, Christos and Oldfield, James and Tzimiropoulos, Georgios and Patras, Ioannis.*<br>
Arxiv 2022.  / [PDF](https://arxiv.org/abs/2206.02104)  / [Code](https://github.com/chi0tzp/ContraCLIP)

**Stylemc: Multi-channel based fast text-guided image generation and manipulation**<br>
*Kocasari, Umut and Dirik, Alara and Tiftikci, Mert and Yanardag, Pinar.*<br>
WACV 2022.  / [PDF](https://arxiv.org/abs/2112.08493v1)  / [Project](https://catlab-team.github.io/stylemc)  / [Code](https://github.com/catlab-team/stylemc)

**Hairclip: Design your hair by text and reference image**<br>
*Wei, Tianyi and Chen, Dongdong and Zhou, Wenbo and Liao, Jing and Tan, Zhentao and Yuan, Lu and Zhang, Weiming and Yu, Nenghai.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2112.05142v2)  / [Code](https://github.com/wtybest/HairCLIP)

**Hyperstyle: Stylegan inversion with hypernetworks for real image editing**<br>
*Alaluf, Yuval and Tov, Omer and Mokady, Ron and Gal, Rinon and Bermano, Amit.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2111.15666)  / [Project](https://yuval-alaluf.github.io/hyperstyle)  / [Code](https://github.com/yuval-alaluf/hyperstyle)

**One-shot generative domain adaptation**<br>
*Yang, Ceyuan and Shen, Yujun and Zhang, Zhiyi and Xu, Yinghao and Zhu, Jiapeng and Wu, Zhirong and Zhou, Bolei.*<br>
ICCV 2023.  / [PDF](https://arxiv.org/abs/2111.09876v1)  / [Project](https://genforce.github.io/genda)  / [Code](https://github.com/genforce/genda)

**Editgan: High-precision semantic image editing**<br>
*Ling, Huan and Kreis, Karsten and Li, Daiqing and Kim, Seung Wook and Torralba, Antonio and Fidler, Sanja.*<br>
NeurIPS 2021.  / [PDF](https://arxiv.org/abs/2111.03186v1)  / [Project](https://nv-tlabs.github.io/editGAN)  / [Code](https://github.com/nv-tlabs/editGAN_release)

**Predict, prevent, and evaluate: Disentangled text-driven image manipulation empowered by pre-trained vision-language model**<br>
*Xu, Zipeng and Lin, Tianwei and Tang, Hao and Li, Fu and He, Dongliang and Sebe, Nicu and Timofte, Radu and Van Gool, Luc and Ding, Errui.*<br>
CVPR 2022.  / [PDF](https://arxiv.org/abs/2111.13333v2)  / [Code](https://github.com/zipengxuc/PPE)

**Mind the gap: Domain gap control for single shot domain adaptation for generative adversarial networks**<br>
*Zhu, Peihao and Abdal, Rameen and Femiani, John and Wonka, Peter.*<br>
ICLR 2022.  / [PDF](https://arxiv.org/abs/2110.08398)  / [Project](https://zpdesu.github.io/MindTheGap)  / [Code](https://github.com/ZPdesu/MindTheGap)

**Warpedganspace: Finding non-linear rbf paths in gan latent space**<br>
*Tzelepis, Christos and Tzimiropoulos, Georgios and Patras, Ioannis.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2109.13357v1)  / [Code](https://github.com/chi0tzp/WarpedGANSpace)

**Stylegan-nada: Clip-guided domain adaptation of image generators**<br>
*Gal, Rinon and Patashnik, Or and Maron, Haggai and Bermano, Amit H and Chechik, Gal and Cohen-Or, Daniel.*<br>
ACM TOG 2022.  / [PDF](https://arxiv.org/abs/2108.00946)  / [Project](https://stylegan-nada.github.io)  / [Code](https://github.com/rinongal/StyleGAN-nada)

**Styleclip: Text-driven manipulation of stylegan imagery**<br>
*Patashnik, Or and Wu, Zongze and Shechtman, Eli and Cohen-Or, Daniel and Lischinski, Dani.*<br>
ICCV 2021.  / [PDF](https://arxiv.org/abs/2103.17249v1)  / [Code](https://github.com/orpatashnik/StyleCLIP)

**The geometry of deep generative image models and its applications**<br>
*Wang, Binxu and Ponce, Carlos R.*<br>
ICLR 2021.  / [PDF](https://arxiv.org/abs/2101.06006)

**Hijack-gan: Unintended-use of pretrained, black-box gans**<br>
*Wang, Hui-Po and Yu, Ning and Fritz, Mario.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2011.14107v3)  / [Code](https://github.com/hui-po-wang/hijackgan)

**Stylespace analysis: Disentangled controls for stylegan image generation**<br>
*Wu, Zongze and Lischinski, Dani and Shechtman, Eli.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2011.12799v2)

**Styleflow: Attribute-conditioned exploration of stylegan-generated images using conditional continuous normalizing flows**<br>
*Abdal, Rameen and Zhu, Peihao and Mitra, Niloy J and Wonka, Peter.*<br>
ACM TOG 2021.  / [PDF](https://arxiv.org/abs/2008.02401)  / [Project](https://rameenabdal.github.io/StyleFlow)  / [Code](https://github.com/RameenAbdal/StyleFlow)

**The hessian penalty: A weak prior for unsupervised disentanglement**<br>
*Peebles, William and Peebles, John and Zhu, Jun-Yan and Efros, Alexei and Torralba, Antonio.*<br>
ECCV 2020.  / [PDF](https://arxiv.org/abs/2008.10599v1)  / [Project](https://www.wpeebles.com/hessian-penalty)  / [Code](https://github.com/wpeebles/hessian_penalty)

**Closed-form factorization of latent semantics in gans**<br>
*Shen, Yujun and Zhou, Bolei.*<br>
CVPR 2021.  / [PDF](https://arxiv.org/abs/2007.06600v4)  / [Project](https://genforce.github.io/sefa)  / [Code](https://github.com/genforce/sefa)

**Interfacegan: Interpreting the disentangled face representation learned by gans**<br>
*Shen, Yujun and Yang, Ceyuan and Tang, Xiaoou and Zhou, Bolei.*<br>
CVPR 2020.  / [PDF](https://arxiv.org/abs/2005.09635v2)  / [Project](https://genforce.github.io/interfacegan/)  / [Code](https://genforce.github.io/interfacegan)

**Ganspace: Discovering interpretable gan controls**<br>
*Härkönen, Erik and Hertzmann, Aaron and Lehtinen, Jaakko and Paris, Sylvain.*<br>
NeurIPS 2020.  / [PDF](https://arxiv.org/abs/2004.02546)  / [Code](https://github.com/harskish/ganspace)

**Stylegan2 distillation for feed-forward image manipulation**<br>
*Viazovetskyi, Yuri and Ivashkin, Vladimir and Kashin, Evgeny.*<br>
ECCV 2020.  / [PDF](https://arxiv.org/abs/2003.03581v2)  / [Code](https://github.com/EvgenyKashin/stylegan2-distillation)

**Unsupervised discovery of interpretable directions in the gan latent space**<br>
*Voynov, Andrey and Babenko, Artem.*<br>
ICML 2020.  / [PDF](https://arxiv.org/abs/2002.03754)  / [Code](https://github.com/anvoynov/GanLatentDiscovery)

**A spectral regularizer for unsupervised disentanglement**<br>
*Ramesh, Aditya and Choi, Youngduck and LeCun, Yann.*<br>
Arxiv 2018.  / [PDF](https://arxiv.org/abs/1812.01161)

## Related Surveys

**Personalized Generation In Large Model Era: A Survey**<br>
*Yiyan Xu, Jinghao Zhang, Alireza Salemi, Xinting Hu, Wenjie Wang, Fuli Feng, Hamed Zamani, Xiangnan He, Tat-Seng Chua*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2503.02614)

**Image Inversion: A Survey from GANs to Diffusion and Beyond**<br>
*Yinan Chen, Jiangning Zhang, Yali Bi, Xiaobin Hu, Teng Hu, Zhucun Xue, Ran Yi, Yong Liu, Ying Tai*<br>
Arxiv 2025.  / [PDF](https://arxiv.org/abs/2502.11974)  / [Code](https://github.com/RyanChenYN/ImageInversion)

**Conditional Image Synthesis with Diffusion Models: A Survey**<br>
*Zhan, Zheyuan and Chen, Defang and Mei, Jian-Ping and Zhao, Zhenghe and Chen, Jiawei and Chen, Chun and Lyu, Siwei and Wang, Can.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2409.19365)  / [Code](https://github.com/zju-pi/Awesome-Conditional-Diffusion-Models)

**A Survey of Multimodal-Guided Image Editing with Text-to-Image Diffusion Models**<br>
*Shuai, Xincheng and Ding, Henghui and Ma, Xingjun and Tu, Rongcheng and Jiang, Yu-Gang and Tao, Dacheng.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2406.14555)  / [Code](https://github.com/xinchengshuai/Awesome-Image-Editing)

**A Survey on Personalized Content Synthesis with Diffusion Models**<br>
*Zhang, Xulu and Wei, Xiao-Yong and Zhang, Wengyu and Wu, Jinlin and Zhang, Zhaoxiang and Lei, Zhen and Li, Qing.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2405.05538)

**Controllable generation with text-to-image diffusion models: A survey**<br>
*Cao, Pu and Zhou, Feng and Song, Qing and Yang, Lu.*<br>
Arxiv 2024.  / [PDF](https://arxiv.org/abs/2403.04279)  / [Code](https://github.com/PRIV-Creation/Awesome-Controllable-T2I-Diffusion-Models)

**A Survey on Leveraging Pre-trained Generative Adversarial Networks for Image Editing and Restoration**<br>
*Ming Liu, Yuxiang Wei, Xiaohe Wu, Wangmeng Zuo, Lei Zhang*<br>
SCIS 2023. / [PDF](https://arxiv.org/abs/2207.10309) / [Code](https://github.com/csmliu/pretrained-GANs)

**GAN Inversion: A Survey**<br>
*Weihao Xia, Yulun Zhang, Yujiu Yang, Jing-Hao Xue, Bolei Zhou, Ming-Hsuan Yang*<br>
TPAMI 2022. / [PDF](https://arxiv.org/abs/2101.05278) / [Code](https://github.com/weihaox/GAN-Inversion)

