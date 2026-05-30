# Translation Notes

## Source
`毕业论文+作者简介.docx` — Chinese undergraduate thesis at Zhejiang University

## Methodology

Translated using [nature-skills](https://github.com/Yuan1z0825/nature-skills) `nature-polishing` skill in `zh-to-en` mode, with `paper_type=research`, `journal=generic`.

## Terminology Decisions

| Chinese Term | English Translation | Notes |
|---|---|---|
| 自噬 | autophagy | Standard term |
| ATG4家族 | ATG4 family | Gene family name, kept in original case |
| 自噬相关基因 | autophagy-related genes | Standard |
| 双等位基因变异 | biallelic variant | Used over "biallelic mutation" — variant is more neutral |
| 预测功能丧失性变异 | predicted loss-of-function (pLOF) variant | Standard genetics terminology |
| 非同义变异 | nonsynonymous variant | Standard |
| 纯化选择 | purifying selection | Used over "negative selection" for precision |
| 先天性免疫缺陷 | inborn error of immunity | Standard clinical term; also "primary immunodeficiency" |
| 体外表达 | in vitro expression | Standard |
| 瞬时转染 | transient transfection | Standard |
| 慢病毒转导 | lentiviral transduction | Standard |
| 催化三联体 | catalytic triad | Standard biochemistry term |
| 自噬流 | autophagic flux | Standard |
| 自噬体 | autophagosome | Standard |
| 自噬溶酶体 | autolysosome | Standard |
| 中山大学/浙江大学 | — | University names preserved in pinyin with English gloss |

## Protein / Gene Naming

| Source | Conventions Applied |
|---|---|
| Human genes | Italicized: *ATG4C*, *ATG4D*, *MAP1LC3B2* |
| Human proteins | Roman, uppercase: ATG4C, LC3B2, GABARAPL1 |
| Mouse/other species | Lowercase: Atg4 (when referring to mouse homologs) |

## Citation Format Change

Chinese thesis used `[1]` numbered format in text, with reference list in `et al.` / `等` style. Converted to standard English journal style: numbered in-text citations, consistent with Nature-family conventions.

## Figures / Tables

Figure and table callouts preserved with their original numbering (Fig. 3.1, Fig. 3.3, etc.). Image assets extracted to `assets/`. Actual figures need to be inserted manually. EMF vector files are available in the source .docx but were too large for git storage.

## Known Limitations

1. **Figures not embedded in thesis_English.md** — only figure references are present. The original .docx contains 10 image relationships; 5 (PNG/JPEG) are in `assets/`, 3 EMF files (~22 MB total) are too large for version control.
2. **Chinese acknowledgements** — the 致谢 section contains culturally specific expressions (平安顺遂, 初心) that carry nuanced meaning. The English translation provides a gloss for the culturally key term.
3. **Reference URLs** — references 7, 8, 10, 18 were originally provided as URLs in the source document without standard DOI formatting. DOI identifiers should be verified against the published literature.
4. **Discussion section** — the original Discussion in the .docx was a partial/truncated version (starting mid-sentence at para 173). The complete Discussion text was extracted from a different location in the document.

## License

This translation is produced for academic reference. The original Chinese thesis is the work of Ce Fang (方策) under the supervision of Prof. Shen-Ying Zhang at Zhejiang University.