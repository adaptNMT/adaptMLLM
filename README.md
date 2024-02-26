# adaptMLLM

The advent of Multilingual Language Models (MLLMs) and Large Language Models (LLMs) has spawned innovation in many areas of natural language processing. Despite the exciting potential of this technology, its impact on developing high-quality Machine Translation (MT) outputs for low-resource languages remains relatively under-explored. Furthermore, an open-source application, dedicated to both fine-tuning MLLM and managing the complete MT workflow, remains unavailable. We aim to address these imbalances through the development of adaptMLLM which streamlines all processes involved in the fine-tuning of MLLMs for MT. As an open-source application, it is designed for developers, translators and end users who work in the field of MT. The application is particularly useful for new entrants to the field since the setup of the development environment is greatly simplified. Hyperparameter customisation is facilitated through an intuitive user interface and models can be evaluated using a range of metrics and deployed as a translation service within the application. As a multilingual tool, we used adaptMLLM to fine-tune models for two low-resource language pairs: English to Irish (EN<-->GA) and English to Marathi (EN<-->MR). Compared with baselines from the LoResMT2021 Shared Task, the adaptMLLM system demonstrated significant improvements. In the EN->GA direction, an improvement of 5.2 BLEU points was observed and an increase of 40.5 BLEU points was recorded in the GA->EN direction representing relative improvements of 14% and 117% respectively. Significant improvements in the translation performance of the EN<-->MR pair were also observed notably in the MR->EN direction with an increase of 21.3 BLEU points which corresponds to a relative improvement of 68%. Finally, a fine-grained human evaluation of the MLLM output on the EN->GA pair was conducted using the Multidimensional Quality Metrics and Scalar Quality Metrics error taxonomies.

# Download paper
[adaptMLLM: Fine-Tuning MLLMs on Low-Resource Languages with Integrated LLM Playgrounds](https://www.mdpi.com/2078-2489/14/12/638)"

## Citation

```
@Article{lankford-adaptMLLM-2023,
AUTHOR = {Lankford, Séamus and Afli, Haithem and Way, Andy},
TITLE = {adaptMLLM: Fine-Tuning Multilingual Language Models on Low-Resource Languages with Integrated LLM Playgrounds},
JOURNAL = {Information},
VOLUME = {14},
YEAR = {2023},
NUMBER = {12},
ARTICLE-NUMBER = {638},
URL = {https://www.mdpi.com/2078-2489/14/12/638},
ISSN = {2078-2489},
ABSTRACT = {The advent of Multilingual Language Models (MLLMs) and Large Language Models (LLMs) has spawned innovation in many areas of natural language processing. Despite the exciting potential of this technology, its impact on developing high-quality Machine Translation (MT) outputs for low-resource languages remains relatively under-explored. Furthermore, an open-source application, dedicated to both fine-tuning MLLMs and managing the complete MT workflow for low-resources languages, remains unavailable. We aim to address these imbalances through the development of adaptMLLM, which streamlines all processes involved in the fine-tuning of MLLMs for MT. This open-source application is tailored for developers, translators, and users who are engaged in MT. It is particularly useful for newcomers to the field, as it significantly streamlines the configuration of the development environment. An intuitive interface allows for easy customisation of hyperparameters, and the application offers a range of metrics for model evaluation and the capability to deploy models as a translation service directly within the application. As a multilingual tool, we used adaptMLLM to fine-tune models for two low-resource language pairs: English to Irish (EN&harr; GA) and English to Marathi (EN&harr;MR). Compared with baselines from the LoResMT2021 Shared Task, the adaptMLLM system demonstrated significant improvements. In the EN&rarr;GA direction, an improvement of 5.2 BLEU points was observed and an increase of 40.5 BLEU points was recorded in the GA&rarr;EN direction representing relative improvements of 14% and 117%, respectively. Significant improvements in the translation performance of the EN&harr;MR pair were also observed notably in the MR&rarr;EN direction with an increase of 21.3 BLEU points which corresponds to a relative improvement of 68%. Finally, a fine-grained human evaluation of the MLLM output on the EN&rarr;GA pair was conducted using the Multidimensional Quality Metrics and Scalar Quality Metrics error taxonomies. The application and models are freely available.},
DOI = {10.3390/info14120638}
}
```
