<div align="center">

# kai

*my little ai/ml workshop.*
*i break things, find out why, then build it better.*

[linkedin](https://www.linkedin.com/in/khadeja-ahmad) · [email](mailto:khadejaworks@gmail.com)

</div>

---

## the vibe

i think in systems. data → model → users → feedback → repeat.
when something breaks, i don't patch it, i trace it back until i know *why*.

---

## on the workbench

**[kaiRAG](https://github.com/khadejalabs/kaiRAG)** · *in progress*
a fully local rag pipeline that reads messy technical docs (tables, diagrams, formulas and all) and actually answers questions about them.
`docling` `llamaindex` `qdrant` `qwen`

**[leukemia-predictor](https://github.com/khadejalabs/leukemia-predictor)** · *done*
classifies leukemia from gene expression data. one docker command to run it.
`python` `scikit-learn` `docker`

**[flutter-counter-plus](https://github.com/khadejalabs/flutter-counter)** · *done*
a tiny flutter app for learning state + persistence.
`dart` `flutter`

---

## things that broke (and why)

| what broke | why it actually broke |
| :--- | :--- |
| gpu ran out of memory on diagrams | vlm tokens scale with image size. capped the crops |
| content filed under the wrong section | parser thought "Notes:" was a heading |
| tables looked identical to the embedder | the text i embedded left out what made them different |

---

## currently exploring

retrieval · multimodal models · mlops · automation & agents · eventually bioinformatics

---

<div align="center">
<sub>still learning. still building. 🖤</sub>
</div>
