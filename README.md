## 陈立鸥、罗杰瑞的闽语拼音 RIME 输入方案 Input Method of Foochow Romanization by Leo Chen and Jerry Norman

在陈立鸥、罗杰瑞所著的福州话教材《闽语入门》（An Introduction to the Foochow Dialect）中，二位创造了一套福州话的拉丁化拼音体系。本输入方案可以使用美式键盘方便地键入该拼音体系中的一些特殊符号。

本输入法基于 [RIME](https://github.com/rime) 输入法引擎。

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
Ø̄ Ǿ Ø̌ Ø̀ Ø̱ Ø̂
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

对于 `ø`，本输入方案中有两种方式输入：`o/` 或 `q`。例如，欲输入 `ø̌`，可键入 `o/3` 或 `q3`。

除上表中所用到的字母外，其他字母键入均可直接上屏。输入 `a`、`o`、`e`、`i`、`u`、`y`、`ø` 和 `g` 以及其对应大写字母时，可以双击对应按键，例如键入 `aa` 打出 `a`，键入 `OO` 打出 `O`，键入 `o//` 或 `qq` 打出 `ø`，键入 `O//` 或 `QQ` 打出 `Ø`。也可按对应按键后加 `0`，例如键入 `o/0` 或 `q0` 打出 `ø`。还可按右 shift 键，切换为西文模式（直接输入）。

### 外部链接 External links
- [福州话教材《闽语入门》- 知乎](https://www.zhihu.com/column/ming-ngy-ik-muong)。
- [RIME - github](https://github.com/rime)。
- [RIME | 中州韻輸入法引擎](https://rime.im/)。
