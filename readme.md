# Puzzle Wiki Source Doc

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

## Wiki 构成

|名称|解释与要求|
|:---|:----|
|title|Puzzle 的名称|
|image|Puzzle 的主视觉图，长宽比应为 16:9，分辨率应为 1280*720，webp 格式。由于经费不足，目前使用路过图床服务，后期将转移至私有图床中。|
|intro|Puzzle 的简短介绍，建议不多于 30 字|
|categories|Puzzle 的分类，有 正在进行，已结束，尚未开始，长期运营 四种，只能选择一个。|
|tags|Puzzle 的标签，目前有 Misc（涉猎范围广）、Tech（以网络、计算机等技术为主）、Crypto（以古典密码为主）三种。可选择多个标签。后期会增加更多的标签。|
|介绍|简单介绍一下这个 Puzzle，或是做一个引入。如果是一场比赛，请在此部分说明相关时间|
|游玩方式|Puzzle 的游玩方式，请在此加入必要的链接|
|相关链接|Puzzle 的相关链接及信息。如 Writeup、玩家讨论组、策划团队通信方式等，建议使用无序列表|
|策划团队|策划团队成员的信息，包括 工作、ID、头像（长宽比应为 1:1，分辨率应为 128*128，webp 格式）、简介/签名、个人地址 四部分|

## 贡献指南

### 通过 Pull Request

请在 `_post` 文件夹下以 Puzzle **系列的名称**建立文件夹，若文件夹已存在则无需建立。随后请进入文件夹，以 Puzzle 名称建立 markdown 文件。文件名中请不要带空格。

> 示例：
> 如果想要将 Phi Project 002 的相关信息加入到 wiki，则应该建立 `/_post/Phi Project/PhiProject002.md` 文件，因为 Phi Project 002 属于 Phi Project 系列，且该文件夹已经存在。

随后请按照以下格式书写文档内容：

```markdown
---
title: Puzzle 的名称
image: Puzzle 的主 KV
intro: Puzzle 的简短介绍
categories: 
  - Puzzle 的分类
tags:
  - Puzzle 的标签
---

#### 介绍

Puzzle 的介绍

---

#### 游玩方式

Puzzle 的游玩方式

#### 相关链接

Puzzle 的相关链接

#### 策划团队

Puzzle 策划团队的成员信息

<ul class = "author">

<li>工作</li>
<li>ID</li>
<li>个人地址</li>
<li>个人头像</li>
<li>个人简介/签名</li>

//可以添加多个成员的信息
<li>工作</li>
<li>ID</li>
<li>个人地址</li>
<li>个人头像</li>
<li>个人简介/签名</li>

</ul>
```

文档中所用的图像文件请以 webp 格式上传至 `/image` 文件夹，并以图像文件的 MD5 值命名，在文档中直接以 `/image/<文件名>` 的方式引用即可。

填写完毕后，直接向 `main` 分支发起 Pull Request 即可完成贡献。