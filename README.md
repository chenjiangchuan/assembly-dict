# assembly-dict
星际译王-汇编词典

## 使用

文件夹 *assembly* 就是星际译王（StartDict）的词典，把它导入 词典软件中即可使用

## 添加词条

文件 *kdic-assembly-gb.txt* 就是字典词条，需要注意，保存需要以“UTF-8”的编码，不然生成词典中文都是乱码。

因为星际译王词条生成的软件只有 Windows 版本，所以如果系统是 Windows 就直接安装*stardict-3.0.3-2011.06.12.exe*，
如果是 Mac 只能先安装 `CrossOver` （在 Mac OS运行 exe 的的软件），然后通过它安装*stardict-3.0.3-2011.06.12.exe*。

安装完*stardict-3.0.3-2011.06.12.exe*打开，选择“Compile” -> “Browse” 选择 *kdic-assembly-gb.txt* 文件路径，最后点击右下角的“Compile”。如果成功的话，会在窗口显示类型的输出：

```
Building...
[message] Convertion is over.
[message] kdic-assembly-gb wordcount: 58.
Done!
```

完成之后会在*kdic-assembly-gb.txt* 同级目录下生成三个文件：`kdic-assembly-gb.idx`、`kdic-assembly-gb.ifo`、`kdic-assembly-gb.dict`，这三个文件就是词典了。可以看 `使用`。