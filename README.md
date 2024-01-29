# Efficient_Prompt_Paper

**Table of content:**
 - [Prompt Compression](#item-one)
 - [Few-shot pruning](#item-two)
 - [Add adapter](#item-three)
 
 <!-- headings -->
 <a id="item-one"></a>
 ### Prompt Compression
 > Compress prompt :wink:

| Name | Description |Task|
| ------ | ----------- |---------------|
|[Prompt Compression and Contrastive Conditioning for Controllability and Toxicity Reduction in Language Models](https://arxiv.org/pdf/2210.03162.pdf)| train the soft prompt to match the Distribution (KL) of a complex prompt|Toxicity reduction|
 
 <a id="item-two"></a>
 ### Few-shot pruning
 > Select, prune and improve useless prompts :wink:

| Name | Description |Task|
|------ | ----------- |---------|
|[LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models](https://arxiv.org/pdf/2310.05736.pdf?trk=public_post_comment-text)|train a small model to compress few-shot prompts| GSM8K, BBH, ShareGPT: Reasoning, Contextual understanding, Conversation, Summarization |

 <a id="item-three"></a>
 ### Add adapter
> Adding small overheads that are useful for inference:wink:

| Name | Description |Task|
| ------ | ----------- |---------|
|[Learning to Compress Prompts with Gist Tokens](https://arxiv.org/pdf/2304.08467.pdf)|add "Gist" tokens while training to replace prompts in the inference|Alpaca dataset: multiple tasks|
|[LEARNING BY DISTILLING CONTEXT](https://arxiv.org/pdf/2209.15189.pdf)|KD from complex prompts to short promt|Natural-Instructions-V2,text-to-SQL|
