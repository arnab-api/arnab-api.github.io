---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- <center style="color:#b35900 ;font-size:12px">
<i> 
  "A process cannot be understood by stopping it. Understanding must move with the flow of the process, must join it and flow with it"
</i> <br>
 - First Law of Mentat, Dune, Frank Herbert
</center>
<br> -->

I am a PhD student in the [Interpretable Neural Networks](https://baulab.info/) lab at Northeastern University, Boston. I am fortunate to be advised by [Prof. David Bau](https://www.khoury.northeastern.edu/people/david-bau/).

<!-- <p style="text-align: justify">
Broadly, I am interested in understanding the inner workings of large language models. Specifically, my research focuses on understanding what factual informations (<a href="https://en.wikipedia.org/wiki/Bayesian_network" target="_blank">belief</a>s about the real world) the LMs has learned, how LMs store this information in their parameters, how this information is retrieved during inference to inform their decision making process. Also, I am interested in how this findings can help us detect bugs (bias, false/outdated associations) in LMs and develop tools to steer their behavior with the goal of making them more reliable.
</p> -->

<p style="text-align: justify">
My research focuses on understanding what factual informations (<a href="https://en.wikipedia.org/wiki/Bayesian_network" target="_blank">belief</a>s about the real world) a language model has learned, how the LM stores this information in its parameters, and how this information is retrieved. Below are some of the key questions I am exploring:
</p>

* <p style="text-align: justify">How to edit a factual association with appropriate entailments?</p>
* <p style="text-align: justify">How can we enable the LMs to do <a href="https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow" target="_blank">System-2</a> reasoning? Is CoT enough or the only way?</p>

<p style="text-align: justify">
Broadly, I am interested in understanding the inner workings of large language models. And how such findings can help us detect bugs (bias, false/outdated associations) in LMs and develop tools to steer their behavior with the goal of making them more reliable.
</p>

<p style="text-align: justify">
Before starting my PhD, I was a Software Engineer at <a href="https://research.samsung.com/" target="_blank">Samsung Research</a> and used to teach at <a href="https://www.sust.edu/d/cse/faculty-profile-detail/700" target="_blank">Shahjalal University of Science and Technology</a>, from where I have completed my B.Sc. in Computer Science and Engineering.
</p>

<p style="text-align: junsity"><i>
Feel free to reach out to me if you would like to chat about research, collaboration, or if you have any questions about my work.
</i></p>


# News

<!-- * [October-7-2024] Attending MATS 7.0 -->

* [July-1-2024] Serving as a reviewer for NeurIPS 2024. Excited to see many interesting works on interpretability, some of them directly building upon works from our lab!

* [June-1-2024] Serving as a reviewer for COLM 2024.

* [April-4-2014] New paper, [Locating and Editing Factual Associations in Mamba](https://arxiv.org/pdf/2404.03646). [Mamba](https://github.com/state-spaces/mamba) is a new generation of sequence modeling architecture that achives per-parameter performance with Transformers in multiple modalities, including language modeling. With the development of such novel architectures, we interpretability researchers must ask - To what extent our insights on certain mechanism (at a high-level) generalize across different architectures? This paper is a case study where we apply the tools developed for understanding and editing factual associations in Transformers to Mamba and check if the insights generalize. Fine more at [project page](https://romba.baulab.info/), [\[code\]](https://github.com/arnab-api/romba). (Update: Accepted at **COLM 2024**!)


* [October-23-2023] Another paper! [Function Vectors in Large Language Models](https://arxiv.org/pdf/2310.15213.pdf). In this cool paper we show that LLMs encode *functions* (input-output mappings under a relation, or for performing a certain task, like translation) as a vector in their representation. Checkout [this](https://twitter.com/ericwtodd/status/1717277426873766104) Twitter thread for more information. (Update: Accepted at **ICLR 2024**!)

* [August-17-2023] New paper! [Linearity of Relation Decoding in Transformer LMs](https://browse.arxiv.org/pdf/2308.09124.pdf).  In this paper we show that for a subset of relations LLMs (highly non-linear) relation decoding procedure can be well-approximated by a single linear transformation (LRE) on the subject representation after some intermediate layer. And this LRE can be achived by constructing a first-order approximation to the LLM computation from a single input. Fine more at [project page](https://lre.baulab.info/), [\[code\]](https://github.com/evandez/relations) (Update: Accepted at **ICLR 2024**!)

* [January-20-2023] Our paper [Mass-Editing Memory in a Transformer](https://memit.baulab.info/) has been accepted at **ICLR 2023** (top 25%)!

* [October-13-2022] New paper! [Mass-Editing Memory in a Transformer](https://memit.baulab.info/). Here we scale up [ROME](https://rome.baulab.info/) to edit upto 10K memories in a LLM. Find more at [project page](https://memit.baulab.info/).

* [September-1-2022] Starting my PhD at Northeastern University, Boston. I will be working with [Prof. David Bau](https://www.khoury.northeastern.edu/people/david-bau/) on interpretability of LLMs.