# ActiView: Evaluating Active Perception Ability for Multimodal Large Language Models


<div class="header-container">
    <div class="header-content">
        <div class="button-container">
            <a href="https://arxiv.org/abs/2312.14135" class="button">Paper</a>
            <a href="https://github.com/penghao-wu/vstar" class="button">Code</a>
            <a href="https://craigwu-vstar.hf.space" class="button">Demo</a>
        </div>
    </div>
    <div class="header-image">
        <img src="images/teaser_eye.png" alt="Teaser Image" class="teaser-image">
    </div>
</div>

## Authors
| Authors       | Affiliations      | Date          |
|---------------|-------------------|---------------|
| Penghao Wu    | UC San Diego      | Dec. 21, 2023 |
| Saining Xie   | New York University|               |

## Abstract
Active perception, a crucial human capability, involves setting a goal based on the current understanding of the environment and performing actions to achieve that goal. Despite significant efforts in evaluating Multimodal Large Language Models (MLLMs), active perception has been largely overlooked. To address this gap, we propose a novel benchmark named ActiView to evaluate active perception in MLLMs. Since comprehensively evaluating active perception is challenging, we focus on a specialized form of Visual Question Answering (VQA) that eases evaluation yet challenging for existing MLLMs. Given an image, we restrict the perceptual field of a model, requiring it to actively zoom and shift its perceptual field based on reasoning to answer the question successfully. Extensive evaluation results on 30 API-based models and 8 advanced open-source models reveal a significant gap in the active perception capability of MLLMs, indicating that this area deserves more attention.

## Contents

For full documentation visit [Actiview.org](https://www.mkdocs.org).

## Benchmark for Multimodal

Active perception, a crucial human capability, involves setting a goal based on the current understanding of the environment and performing actions to achieve that goal.  Despite significant efforts in evaluating Multimodal Large Language Models (MLLMs), active perception has been largely overlooked.  To address this gap, we propose a novel benchmark named ActiView to evaluate active perception in MLLMs.  Since comprehensively evaluating active perception is challenging, we focus on a specialized form of Visual Question Answering (VQA) that eases evaluation yet challenging for existing MLLMs.  Given an image, we restrict the perceptual field of a model, requiring it to actively zoom and shift its perceptual field based on reasoning to answer the question successfully.  Extensive evaluation results on 3 API-based models and 8 advanced open-source models reveal a significant gap in the active perception capability of MLLMs, indicating that this area deserves more attention.

## Actiview Framework

## Effectiveness of Actiview

## References

[^1]: Phil Ammirato, Patrick Poirson, Eunbyung Park, Jana Košecká, and Alexander C. Berg. 2017. A dataset for developing and benchmarking active vision. In 2017 IEEE International Conference on Robotics and Automation (ICRA), pages 1378-1385.
[^2]: Stanislaw Antol, Aishwarya Agrawal, Jiasen Lu, Margaret Mitchell, Dhruv Batra, C. Lawrence Zitnick, and Devi Parikh. 2015. VQA: visual question answering. In 2015 IEEE International Conference on Computer Vision, ICCV 2015, Santiago, Chile, December 7-13, 2015, pages 2425-2433. IEEE Computer Society.
[^3]: Ruzena Bajcsy. 1988. Active perception. Proceedings of the IEEE, 76(8):966-1005.
[^4]: Ruzena Bajesy, Yiannis Aloimonos, and John K Tsotsos. 2018. Revisiting active perception. Autonomous Robots, 42:177-196.
[^5]: Lauren Biernacki, Meron Zerihun Demissie, Kidus Birkayehu Workneh, Galane Basha Namomsa, Plato Gebremedhin, Fitsum Assamnew Andargie, Brandon Reagen, and Todd Austin. 2021. VIP-bench: a benchmark suite for evaluating privacy-enhanced computation frameworks. In 2021 International Symposium on Secure and Private Execution Environment Design (SEED), pages 139-149. IEEE.
[^6]: Rizhao Cai, Zirui Song, Dayan Guan, Zhenhao Chen, Xing Luo, Chenyu Yi, and Alex Kot. 2023. Benchlmm: Benchmarking cross-style visual capability of large multimodal models. arXiv preprint arXiv:2312.02896.
[^7]: Zhengxiao Du, Yujie Qian, Xiao Liu, Ming Ding, Jiezhong Qiu, Zhilin Yang, and Jie Tang. 2022. Glm: General language model pretraining with autoregressive blank infilling. In Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 320-335.
[^8]: Chaoyou Fu, Peixian Chen, Yunhang Shen, Yulei Qin, Mengdan Zhang, Xu Lin, Jinrui Yang, Xiawu Zheng, Ke Li, Xing Sun, Yunsheng Wu, and Rongrong Ji. 2023. MME: A comprehensive evaluation benchmark for multimodal large language models. Preprint, arXiv:2306.13394.
[^9]: Xingyu Fu, Yushi Hu, Bangzheng Li, Yu Feng, Haoyu Wang, Xudong Lin, Dan Roth, Noah A Smith, Wei-Chiu Ma, and Ranjay Krishna. 2024. Blink: Multimodal large language models can see but not perceive. arXiv preprint arXiv:2404.12390.
[^10]: Alexander Kirillov, Eric Mintun, Nikhila Ravi, Hanzi Mao, Chloe Rolland, Laura Gustafson, Tete Xiao, Spencer Whitehead, Alexander C Berg, Wan-Yen Lo, et al. 2023. Segment anything. In Proceedings of the IEEE/CVF International Conference on Computer Vision, pages 4015-4026.
[^11]: Bo Li, Peiyuan Zhang, Jingkang Yang, Yuanhan Zhang, Fanyi Pu, and Ziwei Liu. 2023a. Otterhd: A high-resolution multi-modality model. arXiv preprint arXiv:2311.04219.
[^12]: Bohao Li, Yuying Ge, Yi Chen, Yixiao Ge, Ruimao Zhang, and Ying Shan. 2024a. Seed-bench-2-plus: Benchmarking multimodal large language models with text-rich visual comprehension. arXiv preprint arXiv:2404.16790.
[^13]: Bohao Li, Rui Wang, Guangzhi Wang, Yuying Ge, Yixiao Ge, and Ying Shan. 2023b. SEED-Bench: Benchmarking multimodal llms with generative comprehension. Preprint, arXiv:2307.16125.
[^14]: Yanwei Li, Yuechen Zhang, Chengyao Wang, Zhisheng Zhong, Yixin Chen, Ruihang Chu, Shaoteng Liu, and Jiaya Jia. 2024b. Mini-gemini: Mining the potential of multi-modality vision language models. arXiv preprint arXiv:2403.18814.
[^15]: Fuxiao Liu, Tianrui Guan, Zongxia Li, Lichang Chen, Yaser Yacoob, Dinesh Manocha, and Tianyi Zhou. 2023a. Hallusionbench: You see what you think? or you think what you see? an image-context reasoning benchmark challenging for gpt-4v (ision), llava-1.5, and other multi-modality models. arXiv preprint arXiv:2310.14566.
[^16]: Haotian Liu, Chunyuan Li, Yuheng Li, Bo Li, Yuanhan Zhang, Sheng Shen, and Yong Jae Lee. 2024. Llavanext: Improved reasoning, ocr, and world knowledge.
[^17]: Haotian Liu, Chunyuan Li, Qingyang Wu, and Yong Jae Lee. 2023b. Visual instruction tuning. ArXiv preprint, abs/2304.08485.
[^18]: Yuan Liu, Haodong Duan, Yuanhan Zhang, Bo Li, Songyang Zhang, Wangbo Zhao, Yike Yuan, Jiaqi Wang, Conghui He, Ziwei Liu, Kai Chen, and Dahua Lin. 2023c. Mmbench: Is your multi-modal model an all-around player? Preprint, arXiv:2307.06281.
[^19]: Pan Lu, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, and Jianfeng Gao. 2023. Mathvista: Evaluating mathematical reasoning of foundation models in visual contexts. arXiv preprint arXiv:2310.02255.
[^20]: Fuwen Luo, Chi Chen, Zihao Wan, Zhaolu Kang, Qidong Yan, Yingjie Li, Xiaolong Wang, Siyu Wang, Ziyue Wang, Xiaoyue Mi, et al. 2024. Codis: Benchmarking context-dependent visual comprehension for multimodal large language models. arXiv preprint arXiv:2402.13607.






