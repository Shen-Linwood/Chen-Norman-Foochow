## 陈立鸥、罗杰瑞的闽语拼音 RIME 输入方案 Input Method of Foochow Romanization by Leo Chen and Jerry Norman

在陈立鸥、罗杰瑞所著的福州话教材《闽语入门》（An Introduction to the Foochow Dialect）中，二位创造了一套福州话的拉丁化拼音体系。本输入方案可以使用通用的美式键盘，方便地键入该拼音体系中的一些特殊符号。

本输入方案基于 [RIME](https://github.com/rime) 输入法引擎。

2024 年春，作者参加了[真鸟囝团队](https://www.zingzeu.org/)的《闽语入门》录入计划。由于书中的拼音方案没有较为方便的现成输入方式，于是自己基于 RIME 写了一个输入方案，已方便我们的录入工作。

### 食用指南 User Guide
#### 安装
安装 [RIME 输入法](https://rime.im/download/)后，添加此输入方案。可在【輸入法設定】-【獲取更多輸入方案…】中调出的命令行窗口中输入本 repo 网址 `https://github.com/Shen-Linwood/Chen-Norman-Foochow` 或输入 `Shen-Linwood/Chen-Norman-Foochow` 添加；也可直接将 `chen_norman_foochow.dict.yaml` 和 `chen_norman_foochow.schema.yaml` 文件复制到输入法用户文件夹后，点【重新部署】添加。

参见：[說明書 · rime](https://github.com/rime/home/wiki/UserGuide)；[Rime 定製指南 · rime](https://github.com/rime/home/wiki/CustomizationGuide#%E9%87%8D%E6%96%B0%E4%BD%88%E7%BD%B2%E7%9A%84%E6%93%8D%E4%BD%9C%E6%96%B9%E6%B3%95)

#### 输入方法
下面给出了陈-罗闽语拼音体系中的特殊符号：
```
ā á ǎ à a̱ â
ō ó ǒ ò o̱ ô
ē é ě è e̱ ê
ī í ǐ ì i̱ î
ū ú ǔ ù u̱ û
ȳ ý y̌ ỳ y̱ ŷ
ø̄ ǿ ø̌ ø̀ ø̱ ø̂ ø
ḡ ǵ ǧ g̀ g̠ ĝ
Ā Á Ǎ À A̱ Â
Ō Ó Ǒ Ò O̱ Ô
Ē É Ě È E̱ Ê
Ī Í Ǐ Ì I̱ Î
Ū Ú Ǔ Ù U̱ Û
Ȳ Ý Y̌ Ỳ Y̱ Ŷ
Ø̄ Ǿ Ø̌ Ø̀ Ø̱ Ø̂ Ø
Ḡ Ǵ Ǧ G̀ G̱ Ĝ
```
本输入方案使用加在字母后的字符表示声调。如下：
| 打出的字符 | 键入的字符 |
|-------|-------|
| ā | a1 |
| á | a2 |
| ǎ | a3 |
| à | a4 |
| a̱ | a_ 或 a= |
| â | a^ 或 a6 |

（由于该拼音方案中有使用连字符 `-`，为输入方便，规避该符号。因此 `a̱` 是 `a_ 或 a=`，而不是 `a_ 或 a-`。）

对于 `ø`，本输入方案中有两种方式输入：`o/` 或 `q`。例如，欲输入 `ø̌`，可键入 `o/3` 或 `q3`；欲输入 `Ø̂`，可键入 `O/6` 或 `Q6`。

除上表中所用到的字母外，其他字母键入均可直接上屏。输入 `a`、`o`、`e`、`i`、`u`、`y`、`ø` 和 `g` 以及其对应大写字母时，该字母会进入输入窗口；此时再输入词中的下一个字母或空格，窗口中的字母即自动上屏。此外，按右 shift 键，可切换为西文模式（直接输入）。

### 外部链接 External links
- [福州话教材《闽语入门》- 知乎](https://www.zhihu.com/column/ming-ngy-ik-muong)。
- [RIME - github](https://github.com/rime)。
- [RIME | 中州韻輸入法引擎](https://rime.im/)。
- [真鸟囝输入法](https://www.zingzeu.org/)
- [福州话教会罗马字输入法](https://github.com/ZySieng/Lo-ma-ci)
