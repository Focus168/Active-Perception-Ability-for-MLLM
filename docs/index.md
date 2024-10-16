# ActiView: Evaluating Active Perception Ability for Multimodal Large Language Models


<div class="header-container">
    <div class="header-content">
        <div class="button-container">
            <a href="https://arxiv.org/pdf/2410.04659" class="button">Paper</a>
            <a href="https://github.com/penghao-wu/vstar" class="button">Code</a>
            <a href="https://craigwu-vstar.hf.space" class="button">Demo</a>
        </div>
    </div>
    <div class="header-image">
        <img src="images/teaser2.png" alt="Teaser Image" class="teaser-image">
    </div>
</div>

## Authors
| Authors       | Affiliations      | Date          |
|---------------|-------------------|---------------|
| Ziyue Wang    | Tsinghua University | July. 11, 2024 |

## Abstract
Active perception, a crucial human capability, involves setting a goal based on the current understanding of the environment and performing actions to achieve that goal. Despite significant efforts in evaluating Multimodal Large Language Models (MLLMs), active perception has been largely overlooked. To address this gap, we propose a novel benchmark named ActiView1 to evaluate active perception in MLLMs. Since comprehensively assessing active perception is challenging, we focus on a specialized form of Visual Question Answering (VQA) that eases the evaluation yet challenging for existing MLLMs. Given an image, we restrict the perceptual field of a model, requiring it to actively zoom or shift its perceptual field based on reasoning to answer the question successfully. We conduct extensive evaluation over 27 models, including proprietary and open-source models, and observe that the ability to read and comprehend multiple images simultaneously plays a significant role in enabling active perception. Results reveal a significant gap in the active perception capability of MLLMs, indicating that this area deserves more attention. We hope that our benchmark could help develop methods for MLLMs to understand multimodal inputs in more natural and holistic ways.

## Contents

For full documentation visit [Actiview.org](https://www.mkdocs.org).

## Benchmark for Multimodal

Active perception, a crucial human capability, involves setting a goal based on the current understanding of the environment and performing actions to achieve that goal.  Despite significant efforts in evaluating Multimodal Large Language Models (MLLMs), active perception has been largely overlooked.  To address this gap, we propose a novel benchmark named ActiView to evaluate active perception in MLLMs.  Since comprehensively evaluating active perception is challenging, we focus on a specialized form of Visual Question Answering (VQA) that eases evaluation yet challenging for existing MLLMs.  Given an image, we restrict the perceptual field of a model, requiring it to actively zoom and shift its perceptual field based on reasoning to answer the question successfully.  Extensive evaluation results on 3 API-based models and 8 advanced open-source models reveal a significant gap in the active perception capability of MLLMs, indicating that this area deserves more attention.

## Actiview Framework

## Effectiveness of Actiview

## Acknowledgement

We extend our heartfelt gratitude to our peers whose vital contributions were instrumental in the development and curation of the manually annotated dataset employed in this research. We also wish to express our thanks to our tutors, who...
