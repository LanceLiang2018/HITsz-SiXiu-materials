# 使用 LaTeX 排版的哈工大（深圳）本科思修课程复习纲要

> 目前本项目正在施工中……

这是一份由 Hans Wan（<hanswan@tom.com>） 基于老师所给出的知识点梳理列表，依照《思想道德修养与法律基础》教材内容所制作整理的，适用于哈尔滨工业大学（深圳）大一《思想道德修养与法律基础》考试复习的纲要。

这份《纲要》特点如下：

- 采用 LaTeX 排版制作，既具有便于修改的原始文档（.tex），也能导出美观的 PDF 文档。
- 按章节、知识点分点罗列，结构清晰。
- 大多数语句直接整理合并自教材原文，语言组织准确率较高。
- 使用 Git 作为版本管理系统，便于反复修改；托管在 GitHub 上，便于多人协作。

## 文件说明

在本 Repo 之下，核心关注的文件为：

- `article.tex`：这是本纲要的正文部分的 TeX 文档文件。
- `main.tex`：这是记录了各种排版参数的主 TeX 文件。
- `main.pdf`：这是使用 XeLaTeX 排版生成的 PDF 文件。

## 如何获得这份纲要

### 直接下载 PDF 文件

每次 Commit 之后，都会上传一份最新的 PDF 文件：`main.pdf`。您可以直接下载这个文件，它就是这份纲要的本体。

### 手动排版

克隆整个项目，并在同目录下执行 `xelatex main.tex` 手动进行发排。这样会生成一份新的 `main.tex`，覆盖掉原有的这个文件（如果存在）。

注意：我使用了方正书宋、方正小标宋字体（均为 GBK 字体）和 STIX 字体，如果您的系统中没有正确地为 XeTeX 配置这些字体，可能无法完成排版。

## 如何为这份纲要做出贡献

自然地，这份纲要肯定存在这样和那样的不足。如果您发现：

- 有知识点概括有误；
- 有错别字或病句；
- 有更好的答题方式，

非常欢迎您以以下几种方式为这份《纲要》做出贡献：

1. 提出一个 Issue；
2. Fork 这个项目，进行修改后，提起 Pull Requests；
3. 直接使用电子邮件联系我。

## 著作权声明

这份《纲要》的大多数内容均截取自《思修》课本。本项目以去商业化的教育用途使用了这些内容。

导出的 PDF 中，使用了方正公司制作的中文字体。本项目以去商业化的教育用途使用了这些字体。

如果您认为有任何的侵权行为，请联系我。