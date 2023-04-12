# adaptLLM

The advent of Large Language Models (LLMs) has spawned innovation in many areas of
Natural Language Processing. Despite the exciting potential of this technology, its impact
on developing high-quality Machine Translation (MT) outputs for low-resource languages
remains relatively under-explored. Furthermore, an open-source application, dedicated to
both fine-tuning LLMs and managing the complete MT workflow, remains unavailable. We
aim to address these imbalances through the development of adaptLLM which streamlines
all processes involved in the fine-tuning of LLMs for MT. As an open-source application, it is
designed for both technical and non-technical users who work in the field of MT. The appli-
cation is particularly useful for new entrants to the field since the setup of the development
environment is greatly simplified. Hyperparameter customization is facilitated through an
intuitive user interface and models can be evaluated using a range of metrics and deployed
as a translation service within the application. As a multilingual tool, we used adaptLLM
to fine-tune models for two low-resource language pairs: English to Irish (EN↔GA) and
English to Marathi (EN↔MR). Compared with baselines from the LoResMT2021 Shared
Task, the adaptLLM system demonstrated significant improvements. In the EN→GA di-
rection, an improvement of 5.2 BLEU points was observed and an increase of 40.5 BLEU
points was recorded in the GA→EN direction representing relative improvements of 14%
and 112% respectively. Significant improvements in the translation performance of the
EN↔MR pair were also observed notably in the MR→EN direction with an increase 21.3
BLEU point which corresponds to a relative improvement of 68%. Finally, a fine-grained
human evaluation of the LLM output on the EN→GA pair was conducted using the Multi-
dimensional Quality Metrics and Scalar Quality Metrics error taxonomies. The application
and models are freely available.
