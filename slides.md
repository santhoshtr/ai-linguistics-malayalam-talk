---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Malayalam in the age of Artificial Intelligence
info: |
  ## Presentation for Symposium at Malayalam University

  Made with [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
fonts:
  sans: Roboto, Manjari
  serif: Roboto Slab
  mono: JetBrains Mono
---

# നിർമിതബുദ്ധി ഭാഷ പഠിക്കുന്നതെങ്ങനെ?
## How AI learns Malayalam?


<!--
introduction
-->
---
layout: default
---

# Language

### Phonetics, Phonology
Speech Sounds, Phonemes

### Morphology

Words and Forms

### Syntax

Sentences and Phrases

### Semantics

Literal meaning of various kinds

### Pragmatics

Language usage, Meaning in context of discourse

<style>
h3 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>



---
layout: two-cols
---

### അപരാഹ്നത്തിന്റെ അനന്തപഥങ്ങളിൽ ആകാശനീലിമയിൽ അവൻ നടന്നകന്നു.
### ഭീമനും യുധിഷ്ഠിരനും ബീഡി വലിച്ചു.
### സീതയുടെ മാറുപിളർന്ന് രക്തം കുടിച്ചു ദുര്യോധനൻ.
### ഗുരുവായൂരപ്പന് ജലദോഷമായിരുന്നു അന്ന്.
### അമ്പലത്തിന്റെ അകാൽവിളക്കുകൾ തെളിയുന്ന സന്ധ്യയിൽ അവൾ അവനോട് ചോദിച്ചു,
### "ഇനിയും നീ ഇതുവഴി വരില്ലേ, ആനകളെയും തെളിച്ചുകൊണ്ട്?"

::right::

<Youtube id="q8uvDnthq94?start=383" width="500" height="300"/>

<!--
https://www.youtube.com/clip/UgkxfJYLEyYeRCq3pkBOfLimnfqnjY2j3-Ra
-->

---
layout: center
---

### ഭാഗം 1

# ഭാഷ എങ്ങനെ പഠിക്കാം?

---
layout: image-right
image: 960px-Noam_Chomsky_portrait_2017_retouched.webp
---
# Noam Chomsky

---
layout: iframe-right
url: Chomsky1957.pdf
---

# Syntactic structures (1957)
<div class="color-blue">
"Colorless green ideas sleep furiously"
</div>
An example of a grammatically correct sentence that has no discernible meaning

Independence of
- syntax (the study of sentence structures)
- semantics (the study of meaning)

---
layout: image-right
image: chomsky-tree.webp
backgroundSize: 70%
---

# Noam Chomsky

## Syntactic structures (1957)

<v-clicks class="color-blue">

* grammar is autonomous and independent of meaning.
* probabilistic models give no particular insight into some of the basic problems of syntactic structure.
</v-clicks>

---
layout: two-cols
---

# Chomsky's Theory

* Humans have innate "Universal Grammar" - built-in language rules we're born with
* Language cannot be learned from examples alone due to "poverty of the stimulus"
* Children learn language from limited input (few million words by age 5)
* Language requires understanding deep structural rules, not just pattern matching

::right::

# Large Language Models

* Learn language entirely from statistical patterns in data - no built-in grammar rules
* Require massive training data (billions to trillions of words)
* Generate grammatically correct and coherent text through pattern prediction alone
* Challenge: May lack true understanding despite producing fluent language-machinery


---
layout: fact
---


## LLMs demonstrate that powerful statistical learning from data can produce sophisticated language without innate grammar

<v-click class="color-blue">
but use far more data than humans and may lack deeper comprehension.
</v-click>
---
layout: iframe-left
url: 2021-bender-parrots.pdf
---

# Stochastic Parrots 🦜
Emily Bender and others - 2021

<v-clicks class="color-blue">

* **No true understanding**: <small>LLMs are systems for stitching together linguistic forms from vast training data, without any reference to context or meaning - it's the human makes sense of it, not the computer</small>
* **Form without meaning**: <small>For LLMs, words may correspond only to other words/patterns fed into their training data, whereas in human minds, words and language correspond to things one has experienced</small>
* **Evidence from failures**: <small>The tendency of LLMs to pass off false information as fact (hallucinations) is held as support that they can't connect words to a comprehension of the world, as humans do</small>
</v-clicks>

---
layout: image
image: sam-altman-tweet.webp
backgroundSize: 50%
---

---
layout: statement
---

# Language != Intelligence

---
layout: default
---

# Hallucination
*   [OpenAI: Why language models hallucinate](https://openai.com/index/why-language-models-hallucinate/)
*   [Oxford University: Large Language Models pose risk to science with false answers, says Oxford study](https://www.ox.ac.uk/news/2023-11-20-large-language-models-pose-risk-science-false-answers-says-oxford-study)
*   [New York Times: A.I. Is Getting More Powerful, but Its Hallucinations Are Getting Worse](https://www.nytimes.com/2025/05/05/technology/ai-hallucinations-chatgpt-google.html) ([Archived Version](https://archive.is/CD7Ge))
*   [MIT Media Lab: People Overtrust AI-Generated Medical Advice despite Low Accuracy](https://www.media.mit.edu/publications/NEJM-AI-people-overtrust-ai-generated-medical-advice-despite-low-accuracy/)
*   [Business Insider: Why AI chatbots hallucinate, according to OpenAI researchers](https://www.businessinsider.com/why-ai-chatbots-hallucinate-openai-chatgpt-anthropic-claude-2025-9)
*   [Reuters: AI 'hallucinations' in court papers spell trouble for lawyers](https://www.reuters.com/technology/artificial-intelligence/ai-hallucinations-court-papers-spell-trouble-lawyers-2025-02-18/)
*   [Nature: AI chatbots are sycophants — researchers say it’s harming science](https://www.nature.com/articles/d41586-025-03390-0)
*   [CNN: Parents of 16-year-old sue OpenAI, claiming ChatGPT advised on his suicide](https://www.cnn.com/2025/08/26/tech/openai-chatgpt-teen-suicide-lawsuit)
*   [Financial Times: The ‘hallucinations’ that haunt AI: why chatbots struggle to tell the truth](https://www.ft.com/content/7a4e7eae-f004-486a-987f-4a2e4dbd34fb) ([Archived Version](https://archive.is/P1Wpc))
*   [The Guardian: ‘Sycophantic’ AI chatbots tell users what they want to hear, study shows](https://www.theguardian.com/technology/2025/oct/24/sycophantic-ai-chatbots-tell-users-what-they-want-to-hear-study-shows)

---
layout: iframe
url: 2510.12766.pdf
---

<!-- Language Models Model Language -->



---
layout: image
image: ex-gen-gram.webp
backgroundSize: 75%
---
<div class="absolute items-center bottom-30px">
Example of a simple context-free generative grammar and derived sentence, based on a corpus
</div>

<!-- On the Compatibility of Generative AI and Generative Linguistics
https://arxiv.org/html/2411.10533v2
-->

---
layout: image
image: CS-hierarchy.webp
backgroundSize: 75%
---

<div class="absolute items-center bottom-30px">
Chomsky-Schützenberger hierarchy
</div>

<!-- On the Compatibility of Generative AI and Generative Linguistics
https://arxiv.org/html/2411.10533v2
-->

---
layout: iframe
url: santhosh-mlmorph-W19-6801.pdf
---


---
layout : iframe
url: https://morph.smc.org.in/
---

---
layout: image
image: mlmorph-analysis.webp
backgroundSize: 80%
---

---
layout: image
image: mlmorph-generator.webp
backgroundSize: 80%
---

---
layout: image
image: mlmoprh-spellchecker.webp
backgroundSize: 80%
---

---
layout: image-right
image: sutton.webp
---

# Richard Sutton

Winner of 2024 Turing Award ("Nobel Prize of Computing,") for Reinforcement Learning

<!--
Richard Sutton is a Canadian computer scientist known for his pioneering work in reinforcement learning, a branch of AI that involves agents learning from interaction and consequences. He is a professor at the University of Alberta and was awarded the 2024 Turing Award for his foundational contributions to the field. Sutton developed influential algorithms like temporal-difference learning and policy-gradient methods, which are used in machine learning and as models for natural learning in psychology and neuroscience
-->
---
layout: iframe-left
url: http://www.incompleteideas.net/IncIdeas/BitterLesson.html
---
<q  class="color-orange">
General methods that leverage computational power will outperform more complex systems that integrate domain-specific human knowledge
</q>

because they take better advantage of Moore's law

<v-clicks class="color-blue">

* Stop trying to understand how intelligence works
* Stop encoding domain knowledge (whether innate grammar or grounded meaning)
* Just scale computation and learning
</v-clicks>

<!--
Core argument: AI researchers have often tried to build knowledge into their agents, which helps in the short term and is personally satisfying to the researcher, but in the long run it plateaus and even inhibits further progress, and breakthrough progress eventually arrives by an opposing approach based on scaling computation by search and learning

-->

---
layout: default
---

# കഥ ഇതുവരെ

<v-clicks class="color-blue">

* Chomsky: Build in innate linguistic structure
* Bender: LLMs lack grounded meaning and understanding
* Sutton: None of that matters - just add more compute
</v-clicks>

---
layout: two-cols
---

# Sutton - October 2025

* LLMs are dead end
* Need world model
* Text is not enough

::right::
<Youtube width=500 height=300 id="21EYKqUsPfg"/>


---
layout: center
---

### ഭാഗം 2

# എഴുതിയ ഭാഷയിൽ നിന്ന് എന്തു പഠിക്കാം?

---
layout: image-right
image: George_Kingsley_Zipf_1917.webp
---
# George Kingsley Zipf
1902 – 1950

<div v-click class="mt-15 text-xl color-blue">
Frequency of occurrence of words Inversely proportional to the rank in this frequency of occurrence.
</div>


<div v-click class="mt-15 text-xl color-blue">
ഒരു ഭാഷയിലെ വാക്കുകളുടെ ആവർത്തനങ്ങളുടെ അവരോഹണക്രമത്തിലുള്ള പട്ടികയിൽ,
വാക്കിന്റെ സ്ഥാനം,
അതിന്റേ ആവർത്തനത്തിന് വിപരീതാനുപതത്തിലായിരിക്കും
</div>

---
layout: two-cols
---
# Zipf's Law

<div  class="mt-15 text-xl color-blue">
 ഏറ്റവും കൂടുതൽ തവണ വരുന്ന വാക്ക് തൊട്ടുപുറകിൽ വരുന്ന വാക്കുകളെക്കാൾ ഇരട്ടി വരും
</div>

::right::

## English

| Word | Percentag| Ratio |
|-------|-----------|--------|
|the    | 7%| 1
|of   |    3.5%   | (7 * ½)|
|and |   2.3%    |(7 * ⅓)}
|to |     1.75%  |(7* ¼)|

<div v-click>

ഇംഗ്ലീഷ് ഭാഷയിലെ 25% വാക്കുകളും "the," "be," "to," "of," "and," "a," "in," "that," "have," and "I." എന്നീ പത്തുവാക്കുകളിലൊന്നാണ്.

</div>

---
layout: image
image: 1365px-Zipf_30wiki_en_labels.webp
backgroundSize: 70%
---

<!--
Zipf's law plot for the first 10 million words in 30 Wikipedias (as of October 2015)
-->
---
layout: image
image: ml-zipfs-law.webp
backgroundSize: 75%
---

## മലയാളം

<div class="absolute items-center bottom-30px">
From 205k unique sentences from SMC corpus. Prepared by Kavya Manohar
</div>

---
layout: iframe
url: https://kavyamanohar.com/post/malayalam-entropy
---

---
layout: center
class: text-center
---

# മലയാളത്തിൽ

<div class="text-xl mt-5">
ഏറ്റവും കൂടുതൽ ആവർത്തിക്കപ്പെടുന്ന അക്ഷരമേത്?
</div>

<div class="text-xl mt-5" v-click>
ഏറ്റവും കുറവ് ആവർത്തിക്കപ്പെടുന്ന അക്ഷരമേത്?
</div>


---
layout: image-right
image: 788px-AAMarkov.webp
---
# Andrey Markov
4 June 1856 – 20 July 1922

<div class="text-xl mt-6 color-blue">
What happens next depends only on the state of affairs now.
</div>

---
layout: image
image: 960px-Chess_game_Staunton_No._6.webp
backgroundSize: contain
---

---
layout: image
image: markov-good-morning.webp
backgroundSize: contain
---
<!-- source  https://www.sitepen.com/blog/exploring-the-creative-possibilities-of-markov-chains-for-text-generation -->

---
layout: image
image: markov-good-morning-2.webp
backgroundSize: contain
---

<!-- source  https://www.sitepen.com/blog/exploring-the-creative-possibilities-of-markov-chains-for-text-generation -->

---
layout: center
---

<div class="text-xl mt-10" >
    എന്ത് പ്രഹസനാണ് ‌______
</div>


<div  class="text-xl mt-10" v-click>
അവിടെ കല്യാണം. ഇവിടെ —---

</div>

<div class="text-xl mt-10" v-click>
കർണൻ, നെപ്പോളിയൻ, —--

</div>


---
layout: center
---

## അപരാഹ്നത്തിന്റെ അനന്തപഥങ്ങളിൽ ആകാശനീലിമയിൽ അവൻ നടന്നകന്നു.
## ഭീമനും യുധിഷ്ഠിരനും ബീഡി വലിച്ചു.
## സീതയുടെ മാറുപിളർന്ന് രക്തം കുടിച്ചു ദുര്യോധനൻ.
## ഗുരുവായൂരപ്പന് ജലദോഷമായിരുന്നു അന്ന്.
## അമ്പലത്തിന്റെ അകാൽവിളക്കുകൾ തെളിയുന്ന സന്ധ്യയിൽ അവൾ അവനോട് ചോദിച്ചു,
## "ഇനിയും നീ ഇതുവഴി വരില്ലേ, ആനകളെയും തെളിച്ചുകൊണ്ട്?"


<!--
https://www.youtube.com/clip/UgkxfJYLEyYeRCq3pkBOfLimnfqnjY2j3-Ra
-->
---
layout: image-right
image: Zellig_Harris_(1909–1992).webp
---
# Zellig Harris
1909 – 1992

<div class="text-xl mt-6 color-blue">
“words that occur in similar contexts tend to have similar meanings”
</div>

<div class="text-xl mt-6 color-blue">
How the statistical patterns of human word usage can be used to figure out
what people mean,
at least to a level sufficient for information access

</div>
<div class="text-xl mt-6 color-blue">
- Distributional hypothesis - Harris, 1954

</div>

---
layout: default
url: https://ig.ft.com/generative-ai/
---
<!-- https://ig.ft.com/generative-ai/ -->

---
layout: image
image: 1448px-Distributional_semantics.webp
backgroundSize: 60%
---

---
layout: image
image: 3dplot-500x381.webp
backgroundSize: 60%
---
<!--
https://corpling.hypotheses.org/495
-->

---
layout: image-left
image: Blog_image1-300x191.webp
background-size: contain
---
## Man + royal = King
## Woman + royal = Queen

Similarly

### Man + medical occupation = Doctor
### Woman + medical occupation = Nurse
<!-- http://blogs.ischool.berkeley.edu/w231/2021/05/31/machine-learning-bias-in-word-embedding-algorithms/ -->


---
layout: center
---
<h2>

കഞ്ഞി +  പഞ്ചസാര = പായസം

</h2>

<h2 v-click>
 ചായ - പാൽ = കട്ടൻ ചായ

</h2>

<h2 v-click>
 പാൽ + കഞ്ഞി = പാൽക്കഞ്ഞി

</h2>

<h2 v-click>
 പായസം - പഞ്ചസാര = കഞ്ഞി

</h2>

---
layout: center
---

<h2>
        കേരളം +  തലസ്ഥാനം =  തിരുവനന്തപുരം
</h2>

<h2 v-click>
 കർണാടക + ( കേരളം - തിരുവനന്തപുരം) = ?

</h2>
---
layout: image
image: kanji.webp
---

---
layout: image
image: attention-paper.webp
backgroundSize: 50%
---


---
layout: image
image: transformer_self-attention_visualization_3.webp
backgroundSize: 50%
---

---
layout: iframe
url: language_models_are_unsupervised_multitask_learners.pdf
---


---
layout: iframe
url: 2005.14165.pdf
---

---
layout: image
image: english-tokens.webp
backgroundSize: 70%
---
<!-- Source https://huggingface.co/spaces/santhosh/tokenizers-languages -->

---
layout: image
image: malayalam-tokens.webp
backgroundSize: 70%
---



<!-- Source https://huggingface.co/spaces/santhosh/tokenizers-languages -->
---
layout: image
image: top-langs-token-length.webp
---

<!-- Source https://huggingface.co/spaces/santhosh/tokenizers-languages -->

---
layout: image
image: medium-token-length.webp
backgroundSize: 70%
---

---
layout: image
image: karpathy-tokenization.webp
backgroundSize: 66%
---


---
layout: iframe
url: https://kavyamanohar.com/post/malayalam-morphological-complexity/
---


---
layout: image
image: tsd1030a.webp
backgroundSize: 50%
---
---
layout: image
image: TypeTokengrowth-comparison.webp
backgroundSize: 60%
---
---
layout: two-cols
---

# English Word Order

## Subject-Verb-Object

* The boy is reading a book

::right::

# മലയാളം - Free Word Order

* രാമൻ രാവണനെ കൊന്നു

* രാവണനെ രാമൻ കൊന്നു

* കൊന്നു രാവണനെ രാമൻ

* കൊന്നു രാമൻ രാവണനെ

---
layout: center
---

# Training data

## 93% of ChatGPT-3’s data set was in English

### 0.00165% was in Malayalam

<!--
https://github.com/openai/gpt-3/blob/master/dataset_statistics/languages_by_word_count.csv
-->

---
layout: center
---

#  ഇന്റർനെറ്റിലുള്ള മലയാളം ഉള്ളടക്കങ്ങളുടെ സ്വഭാവം എന്താണ്?

---
layout: center
---

# നന്ദി
