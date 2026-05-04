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
|  GPT-4-Turbo (Nov 2023)  |...