# CRSpapers
This repo contains conversational recommender system papers.
 
## [[01-Surveys](https://github.com/Chengkai-Huang/CRSpapers/edit/main/README.md)]

- [`arXiv 2020`] A Survey on Conversational Recommender Systems. Dietmar Jannach, Ahtsham Manzoor, Wanling Cai & Li Chen [[pdf](https://arxiv.org/pdf/2004.00646v1.pdf)]
- [`arXiv 2020`] Advances and Challenges in Conversational Recommender Systems: A Survey. Chongming Gao, Wenqiang Lei, Xiangnan He, Maarten de Rijke & Tat-Seng Chua [[pdf](http://staff.ustc.edu.cn/~hexn/papers/CRS-survey-2021.pdf)] [[slide](http://staff.ustc.edu.cn/~hexn/slides/sigir20-tutorial-CRS-slides.pdf)]
- [`arXiv 2021`] Deep Conversational Recommender System:A New Frontier for Goal-Oriented Dialogue Systems. Dai Hoang Tran, Quan Z. Sheng, Wei Emma Zhang, Salma Abdalla Hamad, Munazza Zaib, Nguyen H. Tran, Lina Yao & Nguyen Lu Dang Khoa [[pdf](https://arxiv.org/pdf/2004.13245.pdf)]

## [[02-Regular papers](https://github.com/Chengkai-Huang/CRSpapers/edit/main/README.md)]
- [`ACL 2021`] You Sound Like Someone Who Watches Drama Movies: Towards Predicting Movie Preferences from Conversational Interactions. S Volokhin, J Ho，O Rokhlenko, E Agichtein [[pdf](https://aclanthology.org/2021.naacl-main.246.pdf)] [[video](https://underline.io/events/122/sessions/4208/lecture/20062-you-sound-like-someone-who-watches-drama-movies-towards-predicting-movie-preferences-from-conversational-interactions)] 

<details>
<summary>Click to expand</summary>
 
- Contributions:
 
  - Development of a public conversational dataset **MovieSent** [[link](https://github.com/sergey-volokhin/conversational-movies)] 
  - A new conversational recommendation method **ConvExtr**:
    - Estimates user's sentiment towards first 2 movies.
    - Uses External dataset of reviwes to predict user score towards the 3rd movie.

</details>

- [`arxiv 2021`] CRSLab: An Open-Source Toolkit for Building Conversational Recommender System. Kun Zhou, Xiaolei Wang, Yuanhang Zhou, Chenzhan Shang, Yuan Cheng, Wayne Xin Zhao, Yaliang Li, Ji-Rong Wen [[pdf](https://arxiv.org/pdf/2101.00939.pdf)] [[toolkit](https://github.com/RUCAIBox/CRSLab)]
- [`CIKM 2020`] Leveraging Historical Interaction Data for Improving Conversational Recommender System. Kun Zhou, Wayne Xin Zhao, Hui Wang, Sirui Wang, Fuzheng Zhang, Zhongyuan Wang and Ji-Rong Wen [[pdf](https://arxiv.org/pdf/2008.08247.pdf)] `Sequential recommendation`
- [`Resys 2021`] Large-scale Interactive Conversational Recommendation System using Actor-Critic Framework. Ali Montazeralghaem, James Allan & Philip S. Thomas [[pdf](https://maroo.cs.umass.edu/pub/web/getpdf.php?id=1418)] `Actor-Critic`
- [`SIGIR 2021`] Comparison-based Conversational Recommender System with Relative Bandit Feedback. Zhihui Xie，Tong Yu，Canzhe Zhao，Shuai Li. [[pdf](https://dl.acm.org/doi/10.1145/3404835.3462920)]

### RL-based CRS
- [`SIGIR 2018`] Conversational Recommender System. Yueming Sun, Yi Zhang. [[pdf](https://arxiv.org/pdf/1806.03277.pdf)]
- [`WSDM 2020`] Estimation–Action–Reflection: Towards Deep Interaction Between Conversational and Recommender Systems. Wenqiang Lei, Xiangnan He, Yisong Miao, Qingyun Wu, Richang Hong, Min-Yen Kan, Tat-Seng Chua. [[pdf](https://arxiv.org/pdf/2002.09102.pdf)] [[code](https://ear-conv-rec.github.io/manual.html)]
- [`TOIS 2021`] Seamlessly Unifying Attributes and Items: Conversational Recommendation for Cold-Start Users. Shijun Li, Wenqiang Lei, Qingyun Wu, Xiangnan He, Peng Jiang, and Tat-seng Chua [[pdf](https://arxiv.org/pdf/2005.12979.pdf)] `Thompson sampling` 
- [`SIGIR 2021`] Unified Conversational Recommendation Policy Learning via Graph-based Reinforcement Learning. Yang Deng, Yaliang Li, Fei Sun, Bolin Ding & Wai Lam. [[pdf](https://arxiv.org/pdf/2105.09710.pdf)]

### Explainable/Reasoning CRS
- [`COLING 2020`] User Memory Reasoning for Conversational Recommendation. Hu Xu, Seungwhan Moon, Honglei Liu, Bing Liu, Pararth Shah, Bing Liu, Philip S. Yu [[pdf](https://aclanthology.org/2020.coling-main.463.pdf)]
- [`arxiv 2020`] NUANCED: Natural Utterance Annotation for Nuanced Conversation with Estimated Distributions [[pdf](https://arxiv.org/pdf/2010.12758.pdf)] [[dataset](https://github.com/facebookresearch/nuanced)]
`This paper builds a user-centric dialogue system for conversational recommendation.(5.1k dialogues, 26k turns)`
- [`IJCAI 2020`] Towards Explainable Conversational Recommendation. Zhongxia Chen, Xiting Wang, Xing Xie, Mehul Parsana,Akshay Soni, Xiang Ao & Enhong Chen [[pdf](https://www.ijcai.org/proceedings/2020/0414.pdf)]
- [`SIGIR 2021`] HOOPS: Human-in-the-Loop Graph Reasoning for Conversational Recommendation. Zuohui Fu, Yikun Xian, Yaxin Zhu, Shuyuan Xu, Zelong Li, Gerard de Melo and Yongfeng Zhang. [[pdf](http://yongfeng.me/attach/fu-sigir2021.pdf)] [[dataset](https://github.com/zuohuif/HOOPS)]
- [`CIKM 2021`] Popcorn: Human-in-the-loop Popularity Debiasing in Conversational Recommender Systems. Zuohui Fu, Yikun Xian, Shijie Geng, Gerard de Melo and Yongfeng Zhang.
- [`EMNLP 2021`] CR-Walker: Tree-Structured Graph Reasoning and Dialog Acts for Conversational Recommendation. Ryuichi Takanobu, Wenchang Ma* and Minlie Huang. [[pdf](https://truthless11.github.io/pdf/CRWalker.pdf)] [[code](https://github.com/truthless11/CR-Walker)]

### Knowledge-based CRS
- [`EMNLP 2019`] Towards Knowledge-Based Recommender Dialog System. Qibin Chen, Junyang Lin, Yichang Zhang, Ming Ding, Yukuo Cen, Hongxia Yang, Jie Tang [[pdf](https://aclanthology.org/D19-1189.pdf)] [[code](https://github.com/THUDM/KBRD)] `Dbpedia` [`RGCN`]()
- [`SIGIR 2021`] Learning to Ask Appropriate Questions in Conversational Recommendation. Xuhui Ren，Hongzhi Yin，Tong Chen，Hao Wang，Kai Zheng. [[pdf](https://arxiv.org/pdf/2105.04774.pdf)] [[code](https://github.com/XuhuiRen/KBQG)] `TransH`
- [`WSDM 2021`] Adapting User Preference to Online Feedback in Multi-round Conversational Recommendation. Kerui Xu, Jingxuan Yang, Jun Xu, Sheng Gao, Jun Guo, Ji-Rong Wen [[pdf](https://dl.acm.org/doi/abs/10.1145/3437963.3441791)] [[code](https://github.com/xxkkrr/FPAN)]

### Human-computer Interaction
- [`CHI 2021`] Developing a Conversational Recommendation System for Navigating Limited Options. [[pdf](https://arxiv.org/pdf/2104.06552.pdf)]

### Other
- [`TKDE 2020`] Deep Conversational Recommender in Travel. Lizi Liao, Ryuichi Takanobu, Yunshan Ma, Xun Yang, Minlie Huang and Tat-Seng Chua [[pdf](https://truthless11.github.io/pdf/DCR.pdf)]


## [[03-Video material](https://github.com/Chengkai-Huang/CRSpapers/edit/main/README.md)]
- Web, IR and NLP Public Reading Group. Min-Yen Kan [[video](https://wing-nus.github.io/cs6101/)] [[group](https://github.com/wing-nus)]


## [[04-Conference tutorial](https://github.com/Chengkai-Huang/CRSpapers/edit/main/README.md)]
- [RecSys 2020, WSDM 2021, IUI 2021] Tutorial on Conversational Recommendation Systems. Yongfeng Zhang [[website](https://conversational-recsys.github.io/)]



