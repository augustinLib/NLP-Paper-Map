---
markmap:
  colorFreezeLevel: 10
  maxWidth: 800
---
# NLP

## [Bahdanau attention](https://arxiv.org/abs/1409.0473)

## [Luong attention](https://arxiv.org/abs/1508.04025)

## [Weight tying](https://arxiv.org/abs/1608.05859)

## [Transformer](https://arxiv.org/abs/1706.03762)

### Encoder-Only [BERT](https://arxiv.org/abs/1810.04805)
- 성능 향상
  - [RoBERTa](https://arxiv.org/abs/1907.11692)
  - [Big Bird](https://arxiv.org/abs/2007.14062)
  - [XLNet](https://arxiv.org/abs/1906.08237)
  - [ELECTRA](https://arxiv.org/abs/2003.10555)
  - [SpanBERT](https://arxiv.org/abs/1907.10529)

- domain 적용
  - [BioBERT](https://arxiv.org/abs/1901.08746)
  - [LogBERT](https://arxiv.org/abs/2103.04475)
  - [ClinicalBERT](https://arxiv.org/abs/1904.05342)

- 경량화
  - [DistilBERT](https://arxiv.org/abs/1910.01108)
  - [ALBERT](https://arxiv.org/abs/1909.11942)


### Decoder-Only [GPT-1](https://openai.com/research/language-unsupervised)
- [GPT-2](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf)
  - [GPT-3](https://arxiv.org/abs/2005.14165)
    - Self-Instruction
      - [Self-Instruct](https://arxiv.org/abs/2212.10560)
    - Open Access
      - [LLAMA](https://arxiv.org/abs/2302.13971)
        - Instruction-follwing
          - [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)
          - [LIMA](https://arxiv.org/abs/2305.11206)
      - [BLOOM](https://arxiv.org/abs/2211.05100)
        - [BLOOMZ](https://arxiv.org/abs/2211.01786)
    - RLHF (Reinformcement Learning Human Feedback)
      - [InstructGPT](https://arxiv.org/abs/2203.02155)
        - [GPT-4](https://arxiv.org/abs/2303.08774)
    - [PALM](https://arxiv.org/abs/2204.02311)
      - [PALM2](https://ai.google/static/documents/palm2techreport.pdf)
      - [Flan-PALM](https://arxiv.org/abs/2210.11416)

### Encoder-Decoder [BART](https://arxiv.org/abs/1910.13461)
- 성능 향상
  - [T5](https://arxiv.org/abs/1910.10683)
    - [FLAN-T5](https://arxiv.org/abs/2210.11416)
    - [T0](https://arxiv.org/abs/2110.08207)
- multimodal
  - [METALM](https://arxiv.org/abs/2206.06336)
    - [KOSMOS-1](https://arxiv.org/abs/2302.14045)
  - [Flamingo](https://arxiv.org/abs/2204.14198)


### Transformer 구조 수정
- Layernorm + initialization
  - [DeepNet](https://arxiv.org/abs/2203.00555)
  - [MAGNETO](https://arxiv.org/abs/2210.06423)
- Self-attention 관련
  - [Reformer](https://arxiv.org/abs/2001.04451)
  - [Relative positional encoding](https://arxiv.org/abs/1803.02155)
  - [Longformer](https://arxiv.org/abs/2004.05150)
  - [FNet](https://arxiv.org/abs/2105.03824)

### LM with External Knowledge
- with Document
  - [DPR](https://arxiv.org/abs/2004.04906)
  - [ORQA](https://arxiv.org/abs/2108.13817)
    - [REALM](https://arxiv.org/abs/2002.08909)
      - Reader -> Generator [RAG](https://arxiv.org/abs/2005.11401)
        - [Re2G](https://arxiv.org/abs/2207.06300)
        - [FiD](https://arxiv.org/abs/2007.01282)
        - [Atlas](https://arxiv.org/abs/2208.03299)
        - [REPLUG](https://arxiv.org/abs/2301.12652)
        - [Contriever](https://arxiv.org/abs/2112.09118)
- with KG
  - [DiFaR](https://arxiv.org/abs/2305.12416)
  - [Retrieve-Rerank Framework](https://aclanthology.org/2021.eacl-main.26/)

- Document + KG
  - [UniK-QA](https://arxiv.org/abs/2012.14610)



## Benchmark
### [GLUE](https://arxiv.org/abs/1804.07461)
- [SQuAD](https://arxiv.org/abs/1606.05250)
- [SuperGLUE](https://arxiv.org/abs/1905.00537)

### [DecaNLP](https://arxiv.org/abs/1806.08730)

### [BIG-Bench](https://arxiv.org/abs/2206.04615)

### [SUPER-NATURALINSTRUCTIONS](https://arxiv.org/abs/2204.07705)

### [MMLU](https://arxiv.org/abs/2009.03300)

### Knowledge-Intensive Task 
  - [KILT](https://arxiv.org/abs/2009.02252)
    - [FEVER](https://arxiv.org/abs/1803.05355)
  - [BEIR](https://arxiv.org/abs/2104.08663)


## Effficient Training
- [Mixed Precision](https://arxiv.org/abs/1710.03740)
- Distributed learning
  - [Megatron-LM](https://arxiv.org/abs/1909.08053)
  - [Zero](https://arxiv.org/abs/1910.02054)
    - [Zero-Infinity](https://arxiv.org/abs/2104.07857)
- [LoRA](https://arxiv.org/abs/2106.09685)
- [Prompt Tuning](https://arxiv.org/abs/2104.08691)