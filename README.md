Direction1: Understanding of explicit and implicit translation ability of multilingual LLM and closing the gap for better cross-lingual transfer


**Experimental Setup**

Model: google/gemma-2-2b-it

Language Pair: English -> German 

Dataset: WMT: Workshop on Statistical Machine Translation
- WMT19

Harware: Google Colab T4 GPU


**Results**

Evaluation Metrics:

BLEU => 28.87

ChrF => 60.37 

Observations: 

Translation Quality: The model produces grammatically correct and semantically appropriate translations most of the time, though word choices sometimes differ from the reference.

Length Preservation: Average translation length (17.1 words) closely matches reference length (16.0 words), with a compression ratio of 0.88, which is appropriate for English→German translation.


