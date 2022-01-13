# 巨硬的NumPy

`巨硬的NumPy` 教程包括两部分：《从小白到入门》和《从入门到精通》。

- 《从小白到入门》旨在帮助没有基础的同学快速掌握 `numpy` 的常用功能，保证日常绝大多数场景的使用。
- 《从入门到精通》目的是帮助有进一步需要的同学对 `numpy` 进行更深入地了解，主要包括基本介绍、原理分析、基本操作和例子。

设计思想：

- 两部分侧重点不同的教程
- 章节互相独立可单独学习


## 从小白到入门

### 原则

- 偏实用高频 API
- 展示实际用法
- 简单直接

### 大纲

- [创建和生成](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#创建和生成)
    - [从 python 列表或元组创建](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#从-python-列表或元组创建)
    - [使用 arange 生成](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#使用-arange-生成)
    - [使用 linspace/logspace 生成](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#使用-linspace/logspace-生成)
    - [使用 ones/zeros 创建](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#使用-ones/zeros-创建)
    - [使用 random 生成](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#使用-random-生成)
    - [从文件读取](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#从文件读取)
- [统计和属性](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#统计和属性)
    - [尺寸相关](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#尺寸相关)
    - [最值分位](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#最值分位)
    - [平均求和标准差](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#平均求和标准差)
- [形状和转换](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#形状和转换)
    - [改变形状](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#改变形状)
    - [反序](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#反序)
    - [转置](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#转置)
- [分解和组合](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#分解和组合)
    - [切片和索引](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#切片和索引)
    - [拼接](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#拼接)
    - [重复](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#重复)
    - [分拆](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#分拆)
- [筛选和过滤](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#筛选和过滤)
    - [条件筛选](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#条件筛选)
    - [提取](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#提取)
    - [抽样](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#抽样)
    - [最值 Index](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#最值-Index)
- [矩阵和运算](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#矩阵和运算)
    - [算术](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#算术)
    - [广播](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#广播)
    - [矩阵](https://render.githubusercontent.com/view/ipynb?color_mode=light&commit=f9f04a68b192c786dcb251144a8f541b576ccd96&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f646174617768616c656368696e612f706f77657266756c2d6e756d70792f663966303461363862313932633738366463623235313134346138663534316235373663636439362f7372632f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382f2545342542422538452545352542302538462545372539392542442545352538382542302545352538352541352545392539372541382e6970796e623f746f6b656e3d41425a4451344b5948415341484f5a3756375743513533424e48415251&nwo=datawhalechina%2Fpowerful-numpy&path=src%2F从小白到入门%2F从小白到入门.ipynb&repository_id=417589574&repository_type=Repository#矩阵)


## 从入门到精通

### 原则

- 系统全面
- 原理介绍
- 例子辅助理解

### 大纲

- 概念
    - 常量
    - 数组对象
    - 标量
    - 数据类型
- 操作
    - 创建
    - 转换
    - 变形
    - 排列
    - 拆分
    - 组合
    - 索引
    - 切片
    - 选择
- 广播
- 统计
    - 基本描述
    - 均值方差
    - 相关性
    - 排序
- 分布
    - 离散
    - 连续
    - 抽样
- 函数
    - 四则运算
    - 三角函数
    - 指数对数
    - 四舍五入
    - 复数运算
- 线代
    - 向量积
    - 分解
    - 特征值
    - 范数
    - 逆矩阵

