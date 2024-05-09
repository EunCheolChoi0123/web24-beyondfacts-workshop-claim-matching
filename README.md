# Automated Claim Matching Data and Code

The repository contains scripts and data used in the paper [Automated Claim Matching with Large Language Models: Empowering Fact-Checkers in the Fight Against Misinformation](https://doi.org/10.1145/3589335.3651910).

Below are short descriptions for each of the scripts and files:
1. Script for synthetic tweet generation, as described in section 3.5.1. and Figure 8.
2. Script for fine-tuning gpt-3.5-turbo, as described in section 3.5.2.
3. Script for prompting LLMs, as described in section 3.4. and Figure 7.
4. Script for fine-tuning Llama models, as described in section 3.5.2.
5. Script for performance evaluation, as described in section 4.1., Table 3 and 4, and Figure 9.

We used [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory) v0.1.8, formerly named as LLaMa-Efficient-Tuning. Replace LLaMA-Factory\src\llmtuner\extras\template.py file with the one in this repository to use the same format for system, input, and output prompts in our paper.

As for Twitter data used for the test set, we used a dataset collected, documented, and managed by [Chen et al., 2020](https://github.com/echen102/COVID-19-TweetIDs). To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), we are only publicly releasing the Tweet IDs of the collected Tweets. The data is released for non-commercial research use.

This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), Meta's [Llama 2 Community License Agreement](https://ai.meta.com/llama/license/), and OpenAI's [Terms of Use](https://openai.com/policies/terms-of-use) and cite the following manuscript: 

Eun Cheol Choi and Emilio Ferrara. 2024. Automated Claim Matching with Large Language Models: Empowering Fact-Checkers in the Fight Against Misinformation. In Companion Proceedings of the ACM Web Conference 2024 (WWW ’24 Companion), May 13–17, 2024, Singapore, Singapore. ACM, New York, NY, USA, 9 pages. https://doi.org/10.1145/3589335.3651910

BibTeX:
```bibtex
@inproceedings{choi2024claim,
  title={Automated Claim Matching with Large Language Models: Empowering Fact-Checkers in the Fight Against Misinformation},
  author={Choi, Eun Cheol and Ferrara, Emilio},
  booktitle={Companion Proceedings of the ACM Web Conference 2024},
  year={2024}
}
```
