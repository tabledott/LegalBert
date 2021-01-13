<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>
			README.md · nlpaueb/legal-bert-base-uncased at main
	</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
	<link rel="stylesheet" href="/front/build/style.23d26d3.css">
	<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,600,700">
	<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@200;400;600;700&display=swap" >
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.css">
	
		<meta property="og:title" content="README.md · nlpaueb/legal-bert-base-uncased at main">
	<meta property="og:type"   content="website">
	<meta property="og:url"    content="https://huggingface.co/nlpaueb/legal-bert-base-uncased/blob/main/README.md">
			<meta property="og:image"  content="https://huggingface.co/front/thumbnails/30k.png">
	<meta property="fb:app_id" content="1321688464574422">
	<meta name="twitter:card"  content="summary_large_image">
	<meta name="twitter:site"  content="@huggingface">
		<meta name="description" content="We’re on a journey to solve and democratize artificial intelligence through natural language.">
	
	<script defer src="/front/assets/github-buttons.js"></script>
	<script defer src="/front/build/bundle.23d26d3.js"></script>
</head>
<body class="index_blob">
	<div class="navbar">
		<div class="navbar-inner">
			<div class="menu primer">
				<a class="neo-link" href="/models">🚀 Models</a>
				<a class="neo-link" href="/datasets">🔥 Datasets</a>
				<a class="neo-link" href="/pricing">⚡️ Pricing</a>
				
				<details class="dropdown details-reset">
					<summary class="nav-menu">
						<img class="inline" src="/front/assets/icon-menu.svg">
						<div class="dropdown-caret"></div>
					</summary>
					<ul class="dropdown-menu dropdown-menu-sw">
						<li>
							<a href="/models" class="dropdown-item">Models</a>
						</li>
						<li>
							<a href="/datasets" class="dropdown-item">Datasets</a>
						</li>
						<li>
							<a href="/metrics" class="dropdown-item">Metrics</a>
						</li>
						<li>
							<a href="/languages" class="dropdown-item">Languages</a>
						</li>
						<li>
							<a href="/users" class="dropdown-item">Contributors</a>
						</li>
						<li>
							<a href="/organizations" class="dropdown-item">Organizations</a>
						</li>
						<li class="dropdown-divider"></li>
						<li>
							<a href="/docs" class="dropdown-item">Model Hub doc</a>
						</li>
						<li>
							<a target="_blank" href="https://api-inference.huggingface.co/docs/" class="dropdown-item">Inference API doc ⚡️</a>
						</li>
						<li>
							<a target="_blank" href="https://huggingface.co/transformers" class="dropdown-item">Transformers doc 📖</a>
						</li>
						<li>
							<a target="_blank" href="https://huggingface.co/docs/tokenizers" class="dropdown-item">Tokenizers doc 📖</a>
						</li>
						<li>
							<a target="_blank" href="https://huggingface.co/docs/datasets" class="dropdown-item">Datasets doc 📖</a>
						</li>
						<li class="dropdown-divider"></li>
						<li>
							<a href="/blog" class="dropdown-item">Blog</a>
						</li>
						<li>
							<a target="_blank" href="https://discuss.huggingface.co" class="dropdown-item">Forum 💬</a>
						</li>
					</ul>
				</details>
				
					<a class="nav-link" href="/welcome">🔥 Sign in</a>
				
			</div>
			
				<auto-complete src="/api/quicksearch" for="items-popup">
					<input
						type="text"
						placeholder="Search models, datasets, users..."
					>
					<ul class="autocomplete-results" name="items-popup" hidden></ul>
				</auto-complete>
		</div>
	</div>
	
	<header class="compact">
	<a href="/">
		<img class="logo inline" src="/front/assets/huggingface_logo.svg">
		<svg class="logo-text inline" viewBox="0 0 263 25">
			<use href="/front/assets/huggingface_text.svg#text"></use>
		</svg>
	</a>
</header>
<div class="title-container">
	<div class="title-container-inner">
			<a class="back" href="/nlpaueb/legal-bert-base-uncased">
				<img class="info inline" src="/front/assets/icon-back.svg">
				Back to model page
			</a>
		<div class="page-title">
			Model: <a href="/nlpaueb/legal-bert-base-uncased"><code>nlpaueb/legal-bert-base-uncased</code></a>
		</div>
			<div class="model-tags">
						<a href="/models?filter=pytorch">pytorch</a>
						<a href="/models?filter=tf">tf</a>
						<a href="/models?filter=bert">bert</a>
						<a href="/models?filter=pretraining">pretraining</a>
						<a href="/models?filter=en">en</a>
						<a href="/models?filter=arxiv:2010.02559">arxiv:2010.02559</a>
						<a href="/models?filter=legal">legal</a>
						<a href="/models?filter=fill-mask">fill-mask</a>
						<a href="/models?filter=pipeline_tag:fill-mask">pipeline_tag:fill-mask</a>
			</div>
	</div>
	
	<div class="
		container-narrow text-left
		title-navbar
	">
		<a
			class="navbar-item "
			href="/nlpaueb/legal-bert-base-uncased"
		>
			Model card
		</a>
		<a
			class="navbar-item "
			href="/nlpaueb/legal-bert-base-uncased/tree/main"
		>
			Files and versions
		</a>
		
		<a
			class="btn-readme js-how_to_use float-right"
			href="#"
		>
			<img src="/front/assets/icon-code.svg">
				Use in transformers
		</a>
	</div>
</div>



<div class="modal hide how-to-use">
	<div class="modal-inner">
		<div class="modal-content">
			<div class="cli-details">
				<div class="details-heading">
					<p>
						How to use this model directly from the
							<a target="_blank" href="https://github.com/huggingface/transformers"><code>🤗/transformers</code></a>
						library:
					</p>
				</div>
				<pre class="cli js-copy-clipboard">
					<div class="copy-trigger"><img src="/front/assets/icon-copy.svg" alt="Copy to clipboard"></div>
						from transformers import AutoTokenizer, AutoModelForPreTraining
						
						tokenizer = AutoTokenizer.from_pretrained("nlpaueb/legal-bert-base-uncased")
						
						model = AutoModelForPreTraining.from_pretrained("nlpaueb/legal-bert-base-uncased")
					
				</pre>
				<div class="bottom-links">
						<a target="_blank" href="/nlpaueb/legal-bert-base-uncased/blob/main/config.json">See raw config file</a>
				</div>
				
				<div class="details-heading">
					<p>
						How to clone the model repo 
					</p>
				</div>
				<pre class="cli js-copy-clipboard">
					<div class="copy-trigger"><img src="/front/assets/icon-copy.svg" alt="Copy to clipboard"></div>
					git lfs install
					git clone https://huggingface.co/nlpaueb/legal-bert-base-uncased
					<div class="text-gray-500 text-xs">
						# if you want to clone without large files – just their pointers
						# prepend your git clone with the following env var:
					</div>
					GIT_LFS_SKIP_SMUDGE=1
				</pre>
			</div>
		</div>
		<img class="js-loader hide" src="/front/assets/oval.svg">
		<div class="buttons">
			<a href="#" class="js-close">Done</a>
		</div>
	</div>
</div>

<header class="container mx-auto pb-4 pt-8 flex items-center justify-between font-semibold">
	<div class="container flex items-center">
			<details
				class="dropdown details-reset mr-6 user-select-none"
			>
				<summary
					class="
						flex items-center border dark:border-gray-800 px-1.5 py-0.5 rounded bg-gradient-to-b from-white to-gray-100 dark:from-gray-800 dark:to-gray-900
						cursor-pointer
					"
				>
					<svg class="mx-1 text-gray-700 dark:text-gray-400" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" role="img" class="iconify iconify--mdi" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="transform: rotate(360deg);"><path d="M13 14c-3.36 0-4.46 1.35-4.82 2.24C9.25 16.7 10 17.76 10 19a3 3 0 0 1-3 3a3 3 0 0 1-3-3c0-1.31.83-2.42 2-2.83V7.83A2.99 2.99 0 0 1 4 5a3 3 0 0 1 3-3a3 3 0 0 1 3 3c0 1.31-.83 2.42-2 2.83v5.29c.88-.65 2.16-1.12 4-1.12c2.67 0 3.56-1.34 3.85-2.23A3.006 3.006 0 0 1 14 7a3 3 0 0 1 3-3a3 3 0 0 1 3 3c0 1.34-.88 2.5-2.09 2.86C17.65 11.29 16.68 14 13 14m-6 4a1 1 0 0 0-1 1a1 1 0 0 0 1 1a1 1 0 0 0 1-1a1 1 0 0 0-1-1M7 4a1 1 0 0 0-1 1a1 1 0 0 0 1 1a1 1 0 0 0 1-1a1 1 0 0 0-1-1m10 2a1 1 0 0 0-1 1a1 1 0 0 0 1 1a1 1 0 0 0 1-1a1 1 0 0 0-1-1z" fill="currentColor"></path></svg>
					main
					<svg class="text-gray-500 ml-0.5" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" role="img" class="iconify iconify--ic" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24" style="transform: rotate(360deg);"><path d="M7 10l5 5l5-5z" fill="currentColor"></path></svg>
				</summary>
				<div class="
					absolute
					bg-white
					dark:bg-gray-800
					border-1
					border-gray-200
					shadow-xl
					px-4
					py-2
					z-50
				">
					<div>
						<ul class="branches">
								<li>
									<a
										class="hover:underline"
										href="/nlpaueb/legal-bert-base-uncased/blob/main/README.md"
									>
										main
									</a>
								</li>
						</ul>
						<ul class="tags">
						</ul>
					</div>
				</div>
			</details>
		
			<a class="hover:underline text-gray-800 dark:text-gray-300" href="/nlpaueb">nlpaueb</a>
			<span class="text-gray-300 mx-1 font-light">/</span>
		<a class="hover:underline text-gray-800 dark:text-gray-300" href="/nlpaueb/legal-bert-base-uncased/tree/main">
			legal-bert-base-uncased
		</a>
		<span class="text-gray-300 mx-1 font-light">/</span>
		
					<span class="font-light dark:text-gray-300">README.md</span>

	</div>
	
	<div class="container flex justify-end">
	</div>
</header>


<div class="container mx-auto mb-8">
	<div class="leading-none border border-b-0 dark:border-gray-800 px-3 h-12 flex items-center rounded-t-lg bg-gradient-to-b from-white to-gray-50 dark:from-gray-800 dark:to-gray-900">
					<img src="https://aeiljuispo.cloudimg.io/v7/https://s3.amazonaws.com/moonup/production/uploads/1602178762706-5e32b20f9435f568d86092f2.jpeg?w&#x3D;200&amp;h&#x3D;200&amp;f&#x3D;face" alt="" class="avatar-user max-h-3/4 mr-2">
					<a class="mr-2 lg:mr-4 truncate" href="/nlpaueb">nlpaueb</a>
			<a class="ml-2 font-mono text-gray-500 dark:text-gray-300 truncate hover:underline" href="/nlpaueb/legal-bert-base-uncased/commit/68ec85c0bfcddf9d8324d676d9fe7d628339b705">
				Update README.md
			</a>
			<a class="ml-2 lg:ml-4 border dark:border-gray-800 px-1 py-0.5 rounded bg-gray-50 dark:bg-gray-900 hover:underline" href="/nlpaueb/legal-bert-base-uncased/commit/68ec85c0bfcddf9d8324d676d9fe7d628339b705">68ec85c</a>
			<p title="Wed Jan 06 2021 20:02:48 GMT+0100 (Central European Standard Time)" class="ml-auto hidden lg:block text-gray-500 dark:text-gray-400 truncate flex-none pl-2">
				6 days ago
			</p>
	</div>

	<div class="flex items-center p-3 border dark:border-gray-800 text-sm text-gray-700 dark:bg-gray-900">
		<a class="flex items-center hover:underline mr-4" href="/nlpaueb/legal-bert-base-uncased/raw/main/README.md">
			<svg class="mr-2 text-gray-500 dark:text-gray-300" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" role="img" class="iconify iconify--carbon" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32" style="transform: rotate(360deg);"><path d="M31 16l-7 7l-1.41-1.41L28.17 16l-5.58-5.59L24 9l7 7z" fill="currentColor"></path><path d="M1 16l7-7l1.41 1.41L3.83 16l5.58 5.59L8 23l-7-7z" fill="currentColor"></path><path d="M12.419 25.484L17.639 6l1.932.518L14.35 26z" fill="currentColor"></path></svg>
			raw
		</a>
		<a class="flex items-center hover:underline mr-4" href="/nlpaueb/legal-bert-base-uncased/commits/main/README.md">
			<svg class="mr-1.5 text-gray-500 dark:text-gray-300" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" role="img" class="iconify iconify--la" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32" style="transform: rotate(360deg);"><path d="M16 4C9.383 4 4 9.383 4 16s5.383 12 12 12s12-5.383 12-12S22.617 4 16 4zm0 2c5.535 0 10 4.465 10 10s-4.465 10-10 10S6 21.535 6 16S10.465 6 16 6zm-1 2v9h7v-2h-5V8z" fill="currentColor"></path></svg>
			history
		</a>
			<a class="flex items-center hover:underline mr-4" href="/nlpaueb/legal-bert-base-uncased/blame/main/README.md">
				<svg class="mr-1.5 text-gray-500 dark:text-gray-300" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" role="img" class="iconify iconify--carbon" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32" style="transform: rotate(360deg);"><path d="M16 2a14 14 0 1 0 14 14A14 14 0 0 0 16 2zm0 26a12 12 0 1 1 12-12a12 12 0 0 1-12 12z" fill="currentColor"></path><path d="M11.5 11a2.5 2.5 0 1 0 2.5 2.5a2.48 2.48 0 0 0-2.5-2.5z" fill="currentColor"></path><path d="M20.5 11a2.5 2.5 0 1 0 2.5 2.5a2.48 2.48 0 0 0-2.5-2.5z" fill="currentColor"></path></svg>
				blame
			</a>
		<div class="ml-auto dark:text-gray-300">
			9,342 Bytes
		</div>
	</div>

		<div class="border border-t-0 rounded-b-lg dark:bg-gray-900 dark:border-gray-800"
		>
			<table>
				<tr>
					<td class="align-top text-right select-none">
						<pre class="p-3 text-sm overflow-x-auto">1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
94
95
96
97
98
99
100
101
102
103
104
105
106</pre>
					</td>
					<td class="align-top w-full">
						<pre class="p-3 text-sm overflow-x-auto">---
language: en
pipeline<span class="hljs-emphasis">_tag: fill-mask
thumbnail: https://i.ibb.co/p3kQ7Rw/Screenshot-2020-10-06-at-12-16-36-PM.png
tags:
- legal
widget:
- text: &quot;The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of police.&quot;
---

# LEGAL-BERT: The Muppets straight out of Law School

<span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name">img</span> <span class="hljs-attr">align</span>=<span class="hljs-string">&quot;left&quot;</span> <span class="hljs-attr">src</span>=<span class="hljs-string">&quot;https://i.ibb.co/p3kQ7Rw/Screenshot-2020-10-06-at-12-16-36-PM.png&quot;</span> <span class="hljs-attr">width</span>=<span class="hljs-string">&quot;100&quot;</span>/&gt;</span></span> 

LEGAL-BERT is a family of BERT models for the legal domain, intended to assist legal NLP research, computational law, and legal technology applications.  To pre-train the different variations of LEGAL-BERT, we collected 12 GB of diverse English legal text from several fields (e.g., legislation, court cases,  contracts) scraped from publicly available resources. Sub-domains variants (CONTRACTS-, EURLEX-, ECHR-) and/or general LEGAL-BERT perform better than using BERT out of the box for domain-specific tasks. A light-weight model (33% the size of BERT-BASE) pre-trained from scratch on legal data with competitive perfomance is also available.
<span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name">br</span>/&gt;</span></span><span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name">br</span>/&gt;</span></span><span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name">br</span>/&gt;</span></span><span class="xml"><span class="hljs-tag">&lt;<span class="hljs-name">br</span>/&gt;</span></span>

---

I. Chalkidis, M. Fergadiotis, P. Malakasiotis, N. Aletras and I. Androutsopoulos. &quot;LEGAL-BERT: The Muppets straight out of Law School&quot;. In Findings of Empirical Methods in Natural Language Processing (EMNLP 2020) (Short Papers), to be held online, 2020. (https://arxiv.org/abs/2010.02559)

---

## Pre-training corpora

The pre-training corpora of LEGAL-BERT include:

* 116,062 documents of EU legislation, publicly available from EURLEX (http://eur-lex.europa.eu), the repository of EU Law running under the EU Publication Office.
    
* 61,826 documents of UK legislation, publicly available from the UK legislation portal (http://www.legislation.gov.uk).
    
* 19,867 cases from European Court of Justice (ECJ), also available from EURLEX.
    
* 12,554 cases from HUDOC, the repository of the European Court of Human Rights (ECHR) (http://hudoc.echr.coe.int/eng).
    
* 164,141 cases from various courts across the USA, hosted in the Case Law Access Project portal (https://case.law).
    
* 76,366 US contracts from EDGAR, the database of US Securities and Exchange Commission (SECOM) (https://www.sec.gov/edgar.shtml).

## Pre-training details

* We trained BERT using the official code provided in Google BERT&#x27;s github repository (https://github.com/google-research/bert).
* We released a model similar to the English BERT-BASE model (12-layer, 768-hidden, 12-heads, 110M parameters).
* We chose to follow the same training set-up: 1 million training steps with batches of 256 sequences of length 512 with an initial learning rate 1e-4.
* We were able to use a single Google Cloud TPU v3-8 provided for free from [<span class="hljs-string">TensorFlow Research Cloud (TFRC)</span>](<span class="hljs-link">https://www.tensorflow.org/tfrc</span>), while also utilizing [<span class="hljs-string">GCP research credits</span>](<span class="hljs-link">https://edu.google.com/programs/credits/research</span>). Huge thanks to both Google programs for supporting us!
* Part of LEGAL-BERT is a light-weight model pre-trained from scratch on legal data, which achieves comparable performance to larger models, while being much more efficient (approximately 4 times faster) with a smaller environmental footprint.
## Models list

| Model name          | Model Path                            | Training corpora    |
| ------------------- | ------------------------------------  | ------------------- |
| CONTRACTS-BERT-BASE | `nlpaueb/bert-base-uncased-contracts` | US contracts        |
| EURLEX-BERT-BASE    | `nlpaueb/bert-base-uncased-eurlex`    | EU legislation      |
| ECHR-BERT-BASE      | `nlpaueb/bert-base-uncased-echr`      | ECHR cases          |
| LEGAL-BERT-BASE     | `nlpaueb/legal-bert-base-uncased`     | All                 |
| LEGAL-BERT-SMALL    | `nlpaueb/legal-bert-small-uncased`    | All                 |

## Load Pretrained Model

```python
from transformers import AutoTokenizer, AutoModel

tokenizer = AutoTokenizer.from_</span>pretrained(&quot;nlpaueb/legal-bert-base-uncased&quot;)
model = AutoModel.from<span class="hljs-emphasis">_pretrained(&quot;nlpaueb/legal-bert-base-uncased&quot;)
```

## Use LEBAL-BERT variants as Language Models

| Corpus                             | Model                               | Masked token | Predictions  |
| --------------------------------- | ---------------------------------- | ------------ | ------------ |
|  | <span class="hljs-strong">**BERT-BASE-UNCASED**</span>                 |
| (Contracts) | This [MASK] Agreement is between General Motors and John Murray . | employment | (&#x27;new&#x27;, &#x27;0.09&#x27;), (&#x27;current&#x27;, &#x27;0.04&#x27;), (&#x27;proposed&#x27;, &#x27;0.03&#x27;), (&#x27;marketing&#x27;, &#x27;0.03&#x27;), (&#x27;joint&#x27;, &#x27;0.02&#x27;)
| (ECHR) | The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of Adana Security Directorate | torture | (&#x27;torture&#x27;, &#x27;0.32&#x27;), (&#x27;rape&#x27;, &#x27;0.22&#x27;), (&#x27;abuse&#x27;, &#x27;0.14&#x27;), (&#x27;death&#x27;, &#x27;0.04&#x27;), (&#x27;violence&#x27;, &#x27;0.03&#x27;)
| (EURLEX) | Establishing a system for the identification and registration of [MASK] animals and regarding the labelling of beef and beef products . | bovine | (&#x27;farm&#x27;, &#x27;0.25&#x27;), (&#x27;livestock&#x27;, &#x27;0.08&#x27;), (&#x27;draft&#x27;, &#x27;0.06&#x27;), (&#x27;domestic&#x27;, &#x27;0.05&#x27;), (&#x27;wild&#x27;, &#x27;0.05&#x27;)
|  | <span class="hljs-strong">**CONTRACTS-BERT-BASE**</span>                 |
| (Contracts) | This [MASK] Agreement is between General Motors and John Murray . | employment | (&#x27;letter&#x27;, &#x27;0.38&#x27;), (&#x27;dealer&#x27;, &#x27;0.04&#x27;), (&#x27;employment&#x27;, &#x27;0.03&#x27;), (&#x27;award&#x27;, &#x27;0.03&#x27;), (&#x27;contribution&#x27;, &#x27;0.02&#x27;)
| (ECHR) | The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of Adana Security Directorate | torture | (&#x27;death&#x27;, &#x27;0.39&#x27;), (&#x27;imprisonment&#x27;, &#x27;0.07&#x27;), (&#x27;contempt&#x27;, &#x27;0.05&#x27;), (&#x27;being&#x27;, &#x27;0.03&#x27;), (&#x27;crime&#x27;, &#x27;0.02&#x27;)
| (EURLEX) | Establishing a system for the identification and registration of [MASK] animals and regarding the labelling of beef and beef products . | bovine | ((&#x27;domestic&#x27;, &#x27;0.18&#x27;), (&#x27;laboratory&#x27;, &#x27;0.07&#x27;), (&#x27;household&#x27;, &#x27;0.06&#x27;), (&#x27;personal&#x27;, &#x27;0.06&#x27;), (&#x27;the&#x27;, &#x27;0.04&#x27;)
|  | <span class="hljs-strong">**EURLEX-BERT-BASE**</span>                 |
| (Contracts) | This [MASK] Agreement is between General Motors and John Murray . | employment | (&#x27;supply&#x27;, &#x27;0.11&#x27;), (&#x27;cooperation&#x27;, &#x27;0.08&#x27;), (&#x27;service&#x27;, &#x27;0.07&#x27;), (&#x27;licence&#x27;, &#x27;0.07&#x27;), (&#x27;distribution&#x27;, &#x27;0.05&#x27;)
| (ECHR) | The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of Adana Security Directorate | torture | (&#x27;torture&#x27;, &#x27;0.66&#x27;), (&#x27;death&#x27;, &#x27;0.07&#x27;), (&#x27;imprisonment&#x27;, &#x27;0.07&#x27;), (&#x27;murder&#x27;, &#x27;0.04&#x27;), (&#x27;rape&#x27;, &#x27;0.02&#x27;)
| (EURLEX) | Establishing a system for the identification and registration of [MASK] animals and regarding the labelling of beef and beef products . | bovine | (&#x27;live&#x27;, &#x27;0.43&#x27;), (&#x27;pet&#x27;, &#x27;0.28&#x27;), (&#x27;certain&#x27;, &#x27;0.05&#x27;), (&#x27;fur&#x27;, &#x27;0.03&#x27;), (&#x27;the&#x27;, &#x27;0.02&#x27;)
|  | <span class="hljs-strong">**ECHR-BERT-BASE**</span>                 |
| (Contracts) | This [MASK] Agreement is between General Motors and John Murray . | employment | (&#x27;second&#x27;, &#x27;0.24&#x27;), (&#x27;latter&#x27;, &#x27;0.10&#x27;), (&#x27;draft&#x27;, &#x27;0.05&#x27;), (&#x27;bilateral&#x27;, &#x27;0.05&#x27;), (&#x27;arbitration&#x27;, &#x27;0.04&#x27;)
| (ECHR) | The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of Adana Security Directorate | torture | (&#x27;torture&#x27;, &#x27;0.99&#x27;), (&#x27;death&#x27;, &#x27;0.01&#x27;), (&#x27;inhuman&#x27;, &#x27;0.00&#x27;), (&#x27;beating&#x27;, &#x27;0.00&#x27;), (&#x27;rape&#x27;, &#x27;0.00&#x27;)
| (EURLEX) | Establishing a system for the identification and registration of [MASK] animals and regarding the labelling of beef and beef products . | bovine | (&#x27;pet&#x27;, &#x27;0.17&#x27;), (&#x27;all&#x27;, &#x27;0.12&#x27;), (&#x27;slaughtered&#x27;, &#x27;0.10&#x27;), (&#x27;domestic&#x27;, &#x27;0.07&#x27;), (&#x27;individual&#x27;, &#x27;0.05&#x27;)
|  | <span class="hljs-strong">**LEGAL-BERT-BASE**</span>                |
| (Contracts) | This [MASK] Agreement is between General Motors and John Murray . | employment | (&#x27;settlement&#x27;, &#x27;0.26&#x27;), (&#x27;letter&#x27;, &#x27;0.23&#x27;), (&#x27;dealer&#x27;, &#x27;0.04&#x27;), (&#x27;master&#x27;, &#x27;0.02&#x27;), (&#x27;supplemental&#x27;, &#x27;0.02&#x27;)
| (ECHR) | The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of Adana Security Directorate | torture | (&#x27;torture&#x27;, &#x27;1.00&#x27;), (&#x27;detention&#x27;, &#x27;0.00&#x27;), (&#x27;arrest&#x27;, &#x27;0.00&#x27;), (&#x27;rape&#x27;, &#x27;0.00&#x27;), (&#x27;death&#x27;, &#x27;0.00&#x27;)
| (EURLEX) | Establishing a system for the identification and registration of [MASK] animals and regarding the labelling of beef and beef products . | bovine | (&#x27;live&#x27;, &#x27;0.67&#x27;), (&#x27;beef&#x27;, &#x27;0.17&#x27;), (&#x27;farm&#x27;, &#x27;0.03&#x27;), (&#x27;pet&#x27;, &#x27;0.02&#x27;), (&#x27;dairy&#x27;, &#x27;0.01&#x27;)
|  | <span class="hljs-strong">**LEGAL-BERT-SMALL**</span>                |
| (Contracts) | This [MASK] Agreement is between General Motors and John Murray . | employment | (&#x27;license&#x27;, &#x27;0.09&#x27;), (&#x27;transition&#x27;, &#x27;0.08&#x27;), (&#x27;settlement&#x27;, &#x27;0.04&#x27;), (&#x27;consent&#x27;, &#x27;0.03&#x27;), (&#x27;letter&#x27;, &#x27;0.03&#x27;)
| (ECHR) | The applicant submitted that her husband was subjected to treatment amounting to [MASK] whilst in the custody of Adana Security Directorate | torture | (&#x27;torture&#x27;, &#x27;0.59&#x27;), (&#x27;pain&#x27;, &#x27;0.05&#x27;), (&#x27;ptsd&#x27;, &#x27;0.05&#x27;), (&#x27;death&#x27;, &#x27;0.02&#x27;), (&#x27;tuberculosis&#x27;, &#x27;0.02&#x27;)
| (EURLEX) | Establishing a system for the identification and registration of [MASK] animals and regarding the labelling of beef and beef products . | bovine | (&#x27;all&#x27;, &#x27;0.08&#x27;), (&#x27;live&#x27;, &#x27;0.07&#x27;), (&#x27;certain&#x27;, &#x27;0.07&#x27;), (&#x27;the&#x27;, &#x27;0.07&#x27;), (&#x27;farm&#x27;, &#x27;0.05&#x27;)



## Evaluation on downstream tasks

Consider the experiments in the article &quot;LEGAL-BERT: The Muppets straight out of Law School&quot;. Chalkidis et al., 2018, (https://arxiv.org/abs/2010.02559)

## Author

Ilias Chalkidis on behalf of [<span class="hljs-string">AUEB&#x27;s Natural Language Processing Group</span>](<span class="hljs-link">http://nlp.cs.aueb.gr</span>)

| Github: [<span class="hljs-string">@ilias.chalkidis</span>](<span class="hljs-link">https://github.com/seolhokim</span>) | Twitter: [<span class="hljs-string">@KiddoThe2B</span>](<span class="hljs-link">https://twitter.com/KiddoThe2B</span>) |
</span></pre>
					</td>
				</tr>
			</table>
		</div>
	</div>

	
	<script>
	(function() {
		if (
			['localhost', 'huggingface.test'].includes(window.location.hostname)
			|| window.location.hostname.includes('ngrok.io')
		) {
			console.log('[livereload]', 'on');
			const s = document.createElement('script');
			s.setAttribute('src', '//localhost:35729/livereload.js');
			document.body.appendChild(s);
		}
	})();
	</script>
	<script>
	if (! (
		['localhost', 'huggingface.test'].includes(window.location.hostname)
		|| window.location.hostname.includes('ngrok.io')
	)) {
		(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
		(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
		m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
		})(window,document,'script','https://www.google-analytics.com/analytics.js','ganalytics');
		ganalytics('create', 'UA-83738774-2', 'auto');
		ganalytics('send', 'pageview');
	}
	</script>
</body>
</html>