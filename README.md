## WizardLM: Empowering Large Pre-Trained Language Models to Follow Complex Instructions

<p style="font-size:50px;" align="center">
🏠 <a href="https://wizardlm.github.io/" target="_blank">Home Page</a> </p>
<p align="center">
    
<p align="center">
🤗 <a href="https://huggingface.co/WizardLMTeam" target="_blank">HF Repo</a> • 🐦 <a href="https://twitter.com/WizardLM_AI" target="_blank">Twitter</a> • 📃 <a href="https://arxiv.org/abs/2304.12244" target="_blank">[WizardLM] @ICLR2024</a>  • 📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder] @ICLR2024</a>    • 📃 <a href="https://arxiv.org/abs/2308.09583" target="_blank">[WizardMath]</a> <br>
</p>
<p align="center">
    👋 Join our <a href="https://discord.gg/VZjjHtWrKs" target="_blank">Discord</a>
</p>

<p align="center" width="100%">
<a ><img src="imgs/WizardLM.png" alt="WizardLM" style="width: 20%; min-width: 300px; display: block; margin: auto;"></a>
</p>

[![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/LICENSE)
[![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/DATA_LICENSE)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/release/python-390/)

**Unofficial Video Introductions**

Thanks to the enthusiastic friends, their video introductions are more lively and interesting.
1. [NEW WizardLM 70b 🔥 Giant Model...Insane Performance](https://www.youtube.com/watch?v=WdpiIXrO4_o)
2. [GET WizardLM NOW! 7B LLM KING That Can Beat ChatGPT! I'm IMPRESSED!](https://www.youtube.com/watch?v=SaJ8wyKMBds)
3. [WizardLM: Enhancing Large Language Models to Follow Complex Instructions](https://www.youtube.com/watch?v=I6sER-qivYk)
4. [WizardCoder AI Is The NEW ChatGPT's Coding TWIN!](https://www.youtube.com/watch?v=XjsyHrmd3Xo)

## News

- 🔥🔥🔥[2024/01/04] We released **WizardCoder-33B-V1.1**  trained from deepseek-coder-33b-base, the **SOTA OSS Code LLM** on [EvalPlus Leaderboard](https://evalplus.github.io/leaderboard.html), achieves **79.9 pass@1** on HumanEval, **73.2 pass@1** on HumanEval-Plus, **78.9 pass@1** on MBPP, and **66.9 pass@1** on MBPP-Plus. **WizardCoder-33B-V1.1** outperforms **ChatGPT 3.5**, **Gemini Pro**, and **DeepSeek-Coder-33B-instruct** on HumanEval and HumanEval-Plus pass@1. **WizardCoder-33B-V1.1** is comparable with **ChatGPT 3.5**, and surpasses **Gemini Pro** on MBPP and MBPP-Plus pass@1.
- [2023/08/26] We released **WizardCoder-Python-34B-V1.0** , which achieves the **73.2 pass@1** and surpasses **GPT4 (2023/03/15)**, **ChatGPT-3.5**, and **Claude2** on the [HumanEval Benchmarks](https://github.com/openai/human-eval). For more details, please refer to [WizardCoder](https://github.com/nlpxucan/WizardLM/tree/main/WizardCoder).
- [2023/06/16] We released **WizardCoder-15B-V1.0** , which surpasses **Claude-Plus (+6.8)**, **Bard (+15.3)** and **InstructCodeT5+ (+22.3)** on the [HumanEval Benchmarks](https://github.com/openai/human-eval). For more details, please refer to [WizardCoder](https://github.com/nlpxucan/WizardLM/tree/main/WizardCoder).


|  Model  |  Checkpoint  | Paper    | HumanEval  |   HumanEval+ | MBPP | MBPP+ |
| ----- |------| ---- |------|-------| ----- |  ----- |
|  GPT-4-Turbo (Nov 2023)  | - | - | 85.4  | 81.7 | 83.0 | 70.7 |
|  GPT-4 (May 2023)  | - | - | 88.4  | 76.8 | - | - |
|  GPT-3.5-Turbo (Nov 2023)  | - | - | 72.6  | 65.9 | 81.7 | 69.4 |
|  Gemini Pro  | - | - | 63.4  | 55.5 | 72.9 | 57.9 |
|  DeepSeek-Coder-33B-instruct | - | - |  78.7 | 72.6 | 78.7 | 66.7 |
|  WizardCoder-33B-V1.1  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-33B-V1.1" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder]</a>  | 79.9 | 73.2 | 78.9 | 66.9 |
|  WizardCoder-Python-34B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-Python-34B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder]</a>  | 73.2 | 64.6 | 73.2 | 59.9 |
|  WizardCoder-15B-V1.0  |   🤗 <a href="https://huggingface.co/WizardLMTeam/WizardCoder-15B-V1.0" target="_blank">HF Link</a>  |   📃 <a href="https://arxiv.org/abs/2306.08568" target="_blank">[WizardCoder]</a>  | 57.3 | 48.2 | 51.8 | 41.1 |

## Comparing WizardLM to Other LLMs

### WizardLM performance on NLP Foundation tasks.

The following table provides a comprehensive comparison of WizardLMs and several other LLMs on NLP foundation tasks. The evaluation metric is accuracy. The results indicate that WizardLMs consistently exhibit superior performance in comparison to the LLaMa models of the same size. Furthermore, our WizardLM-30B model showcases comparable performance to OpenAI's Text-davinci-003 on the MMLU and HellaSwag benchmarks.

| Model            | MMLU 5-shot | ARC 25-shot | TruthfulQA 0-shot | HellaSwag 10-shot | Average    |
|------------------|-------------|-------------|-------------------|-------------------|------------|
| Text-davinci-003 | <u>56.9<u/> | **85.2**    | **59.3**          | <u>82.2<u/>       | **70.9**   |
|Vicuna-13b 1.1   | 51.3        | 53.0        | 51.8              | 80.1              | 59.1       |
|Guanaco 30B   | 57.6        | 63.7        | 50.7              | **85.1**              | 64.3       |   
| WizardLM-7B 1.0      | 42.7        | 51.6        | 44.7              | 77.7              | 54.2       |
| WizardLM-13B 1.0     | 52.3        | 57.2        | 50.5              | 81.0              | 60.2       |
| WizardLM-30B 1.0    | **58.8**    | <u>62.5<u/> | <u>52.4<u/>       | 83.3          | <u>64.2<u/>|

### WizardLM performance on code generation.

The following table provides a comprehensive comparison of WizardLMs and several other LLMs on the code generation task, namely HumanEval. The evaluation metric is pass@1. The results indicate that WizardLMs consistently exhibit superior performance in comparison to the LLaMa models of the same size. Furthermore, our WizardLM-30B model surpasses StarCoder and OpenAI's code-cushman-001. Moreover, our Code LLM, WizardCoder, demonstrates exceptional performance, achieving a pass@1 score of 57.3, surpassing the open-source SOTA by approximately 20 points.


| Model            | HumanEval Pass@1 |
|------------------|------------------|
| LLaMA-7B         | 10.5             |
| LLaMA-13B        | 15.8             |
| CodeGen-16B-Multi| 18.3             |
| CodeGeeX         | 22.9             |
| LLaMA-33B        | 21.7             |
| LLaMA-65B        | 23.7             |
| PaLM-540B        | 26.2             |
| CodeGen-16B-Mono | 29.3             |
| code-cushman-001 | 33.5             |
| StarCoder        | <u>33.6<u/>      |
| WizardLM-7B 1.0      | 19.1             |
| WizardLM-13B 1.0     | 24.0             |
| WizardLM-30B  1.0   | **37.8**         |
| WizardCoder-15B  1.0 | **57.3**     |

## Call for Feedbacks
We welcome everyone to use your professional and difficult instructions to evaluate WizardLM, and show us examples of poor performance and your suggestions in the [issue discussion](https://github.com/nlpxucan/WizardLM/issues) area. We are focusing on improving the Evol-Instruct now and hope to relieve existing weaknesses and issues in the the next version of WizardLM. After that, we will open the code and pipeline of up-to-date Evol-Instruct algorithm and work with you together to improve it.



## Overview of Evol-Instruct

[Evol-Instruct](https://github.com/nlpxucan/evol-instruct) is a novel method using LLMs instead of humans to automatically mass-produce open-domain instructions of various difficulty levels and skills range, to improve the performance of LLMs. You can easily embark on your own evolutionary journey with the [Evol Script](https://github.com/nlpxucan/WizardLM/tree/main/Evol-Instruct) we provide.

<p align="center" width="100%">
<a ><img src="imgs/git_overall.png" alt="WizardLM" style="width: 86%; min-width: 300px; display: block; margin: auto;"></a>
</p>

<p align="center" width="100%">
<a ><img src="imgs/git_running.png" alt="WizardLM" style="width: 86%; min-width: 300px; display: block; margin: auto;"></a>
</p>

## Disclaimer

The resources, including code, data, and model weights, associated with this project are restricted for academic research purposes only and cannot be used for commercial purposes. The content produced by any version of WizardLM is influenced by uncontrollable variables such as randomness, and therefore, the accuracy of the output cannot be guaranteed by this project. This project does not accept any legal liability for the content of the model output, nor does it assume responsibility for any losses incurred due to the use of associated resources and output results. 

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=nlpxucan/WizardLM&type=Timeline)](https://star-history.com/#nlpxucan/WizardLM&Timeline)

Related project: [stanford_alpaca](https://github.com/tatsu-lab/stanford_alpaca)
