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
layout:default
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
layout: center
---

# Language

* A cognitive phenomenon
* A symbolic system
* As something that can be modeled and imitated by a computer
* A social phenomenon


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->
<!--
Here is another comment.
-->


---
layout: statement
---

# Language != Intelligence

---
layout: iframe
url: http://www.incompleteideas.net/IncIdeas/BitterLesson.html
---

---
layout: image-right
image: sutton.webp
---

# Richart Sutton

---
layout: full
---

<Youtube width=900 height=600 id="21EYKqUsPfg"/>

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
url: https://arxiv.org/pdf/2510.12766
---

---
layout: iframe
url: file:///home/santhosh/Downloads/piantadosi_24_Modern-lang.8.pdf
---

---
layout: iframe
url: https://platform.openai.com/tokenizer
---

---
layout: image
image: karpathy-tokenization.png
backgroundSize: 50%
---

---
layout: image-right
image: https://upload.wikimedia.org/wikipedia/commons/c/c6/George_Kingsley_Zipf_1917.jpg
---
# George Kingsley Zipf
1902 – 1950

<div v-click class="mt-15 text-xl color-blue">
Frequency of occurrence of words Inversely proportional to the rank in this frequency of occurrence.
</div>


<div v-click class="mt-15 text-xl color-blue">
ഒരു ഭാഷയിലെ വാക്കുകളുടെ ആവർത്തനങ്ങളുടെ അവരോഹണക്രമത്തിലുള്ള പട്ടികയിൽ,
വാക്കിന്റെ സ്ഥാനം,
അതിന്റെ ആവർത്തനത്തിന് വിപരീതാനുപതത്തിലായിരിക്കും
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
image: https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/Zipf_30wiki_en_labels.png/1365px-Zipf_30wiki_en_labels.png
backgroundSize: 70%
---

<!--
Zipf's law plot for the first 10 million words in 30 Wikipedias (as of October 2015)
-->
---
layout: image
image: ml-zipfs-law.jpg
backgroundSize: 75%
---

## മലയാളം

<div class="absolute items-center bottom-30px">
From 205k unique sentences from SMC corpus. Prepared by Kavya Manohar
</div>

---
layout: image-right
image: https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/C.E._Shannon._Tekniska_museet_43069_%28cropped%29.jpg/960px-C.E._Shannon._Tekniska_museet_43069_%28cropped%29.jpg
---
# Claude Shannon
1916 – 2001

---
layout: default
---

```
(1) THE ROOM WAS NOT VERY LIGHT A SMALL OBLONG
(2) - - - - ROO - - - - - - NOT-V- - - - -I- - - - - - SM- - - - OBL- - - -
(1) READING LAMP ON THE DESK SHED GLOW ON
(2) REA- - - - - - - - - - -O- - - - - - D- - - -SHED-GLO - -O - -
(1) POLISHED WOOD BUT LESS ON THE SHABBY RED CARPET
(2) P-L-S- - - - - - O - - - BU- -L-S- -O- - - - - - SH- - - - - RE- -C- - - - -
```

<em class="mt-5">
In his 1951 paper “Prediction and Entropy of Printed English,” Claude Shannon reported the results as follows, listing the target passage—clipped from Raymond Chandler’s 1936 detective story “Pickup on Noon Street”—above his wife’s guesses, indicating a correct guess with a bespoke system of dashes, underlining, and ellipses.
</em>

<style>
code {
 font-size: 1.5em;
}
</style>

<!--
https://hedgehogreview.com/issues/markets-and-the-good/articles/language-machinery

89/129 അക്ഷരങ്ങളും കൃത്യമായി.
69% കൃത്യത.

-->

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
image: https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/AAMarkov.jpg/788px-AAMarkov.jpg
---
# Andrey Markov
4 June 1856 – 20 July 1922

<div class="text-xl mt-6 color-blue">
What happens next depends only on the state of affairs now.
</div>

---
layout: image
image: https://upload.wikimedia.org/wikipedia/commons/thumb/f/f0/Chess_game_Staunton_No._6.jpg/960px-Chess_game_Staunton_No._6.jpg?20240420232805
backgroundSize: contain
---

---
layout: image
image: markov-good-morning.jpg
backgroundSize: contain
---
<!-- source  https://www.sitepen.com/blog/exploring-the-creative-possibilities-of-markov-chains-for-text-generation -->

---
layout: image
image: markov-good-morning-2.jpg
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
image: https://upload.wikimedia.org/wikipedia/en/d/d9/Zellig_Harris_%281909%E2%80%931992%29.jpg
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
image: https://upload.wikimedia.org/wikipedia/commons/thumb/c/ce/Distributional_semantics.png/1448px-Distributional_semantics.png
backgroundSize: 60%
---

---
layout: image
image: https://corpling.hypotheses.org/files/2018/04/3dplot-500x381.jpg
backgroundSize: 60%
---
<!--
https://corpling.hypotheses.org/495
-->

---
layout: image-left
image: https://blogs.ischool.berkeley.edu/w231/files/2021/05/Blog_image1-300x191.png
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
image: kanji.png
---

---
layout: center
---
# Learn More

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
