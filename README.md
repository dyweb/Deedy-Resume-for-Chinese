Deedy-Resume-For-Chinese
=========================

[![Gitter](https://badges.gitter.im/gaocegege/Deedy-Resume-For-Chinese.svg)](https://gitter.im/gaocegege/Deedy-Resume-For-Chinese?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

[Deedy-Resume](https://github.com/deedydas/Deedy-Resume) 的中文支持版本，适合应届毕业生使用。与其他相比，该模板：

1. 实现简单，便于改写
2. 两栏式设计，可以将简历保持在一页

但与此同时，也带来了整体略显凌乱，容易抓不住重点等问题，个人建议可配合加粗重点内容来使用。

目前有三种字体支持，其中 `OpenFonts` 是开源英文字体，不支持中文简历；`OpenFonts.Chinese` 是开源中文字体；`MacFonts` 是 MacOS 所带字体，目前对此不维护。

## Preview

### OpenFonts For Chinese

<div align="center">
	<img src="./OpenFonts.Chinese/sample-image.png" width="500">
</div>

### OpenFonts

<div align="center">
	<img src="./OpenFonts/sample-image.png" width="500">
</div>

### MacFonts

由于机器原因不维护该版本模板，请前往[上游](https://github.com/deedy/Deedy-Resume/tree/master/MacFonts)查看。

## Dependencies

1. Compiles only with **XeTeX** and required **BibTex** for compiling publications and the .bib filetype.

## Known Issues:

1. Hacky space on the first bullet point on the second column.
1. Hacky redefinition of \refname to omit 'References' text for publications in the MacFonts version.

## 致谢

* 感谢 [Deedy-Resume](https://github.com/deedydas/Deedy-Resume) 提供的模板主体
* 感谢 [adobe-fonts](https://github.com/adobe-fonts) 的两款开源字体[思源黑体](https://github.com/adobe-fonts/source-han-sans)和[思源宋体](https://github.com/adobe-fonts/source-han-serif)

## License

Apache 2.0 协议开源，字体部分详见其对应开源协议
