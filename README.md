# DIKWP-MESH 5.9 MONOGENESIS DECISOR v5.0.0

**单一续生关系、全命题极性决断与七个千禧年问题证明候选系统**

系统将 `CAN_CONTINUE_AS` 作为唯一原语，为36个精确传统命题生成可复算 TRUE/FALSE 极性包。它严格区分：

- `ESTABLISHED_TRUE/FALSE`：绑定现有证明或同对象反例；
- `SEMANTIC_CANDIDATE_TRUE/FALSE`：公开特征、权重、决定性引理、反世界和 Kill Tests 的研究裁定。

候选极性不是数学共同体已经接受的定理，也不是概率。它是可被明确推翻、可重复计算的证明战役起点。

## 运行

```bash
python -m pip install dist/dikwp_mesh59_monogenesis_decisor-5.0.0-py3-none-any.whl

decisor59 conformance --out outputs/conformance.json
decisor59 demo --out outputs/run
decisor59 artifacts-validate --root outputs/run --out outputs/artifact-validation.json
```

打开 `outputs/run/dashboard.html` 和 `outputs/run/studio.html`。

## 七个千禧年问题的发行基线

- 庞加莱猜想：TRUE，已建立；
- P=NP：FALSE 语义候选，即候选 `P != NP`；
- 黎曼猜想、BSD、Hodge、三维 Navier-Stokes 整体正则、Yang-Mills 存在性与质量间隙：TRUE 语义候选。

除庞加莱猜想外，上述条目都仍要求其决定性引理获得独立证明和核验。
