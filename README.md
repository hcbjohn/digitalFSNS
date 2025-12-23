# 食品安全标准数字化 Food Safety National Standards Digitalization

A programme for digitalize National Standard for Food Safety. 一个食品安全国家标准数字化项目。

通过[MinerU](https://github.com/opendatalab/MinerU)将pdf格式的食品安全国家标准转化为markdown和html格式。

## 目标


1. 使食品安全国家标准无论在桌面端还是移动端都有良好且统一的阅读体验
2. 使标准文本可以轻易复制，并且不会因为pdf统一的文档结构导致复制出的文本带有奇怪的换行
3. 通过强行OCR绕过部分标准文本复制后变成乱码的问题
4. 可以利用RAG等技术生成知识库
5. 正文可以直接复制进顶顶文档、飞书文档中，完整保留格式
6. 标准的修改单直接嵌入至正文中
7. 产品标准中检测方法的更新直接嵌入至正文中

## 使用说明

- [digitalFSNS](https://github.com/hcbjohn/digitalFSNS/tree/main/digitalFSNS)：优化后的标准文件。*.md格式的可以直接打开，也可以下载后打开；*.html格式的请下载后再打开

请pull整个库或者下载整个库的zip文件。

## 路线图


1. 通用标准
2. 生产经营规范
3. 产品标准
4. 检验方法

排除已有第三方数据库的标准，如GB 2760、GB 14880、GB 2762等。

## 关于标准的知识产权

本库只收录强制性国家标准。根据相关法规，强制性标准文本全文公开。因此理论上不存在版权问题。