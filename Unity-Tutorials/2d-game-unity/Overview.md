# Greating a 2D game with Unity

> 本教程翻译至pixelnest.io的Unity教程：https://pixelnest.io/tutorials/2d-game-unity/



使用**Unity**自带的2D工具，你将在本教程中学习如何构建一个小型横版射击游戏（简称*shmup*）。

最终效果，如下DEMO：

[![](https://pixelnest.io/tutorials/2d-game-unity/-img/result.png)](https://pixelnest.io/tutorials/2d-game-unity/-demo/demo.html)

*(点击图片进行游戏)*

有时间和功夫你可以做出像[Steredenn](http://steredenn.pixelnest.io/)这样的游戏，实际上在我们的游戏中使用了教程里的代码。

我们将专注在横向滚动的射击游戏（*shmup*）上。不过，如果这个教程的内容可以正常工作，你将会明白如何将这些代码延展到更多的游戏类型上。

本游戏中的资源（素材），玩法和最初的点子都来源于游戏[The Great Paper Adventure](http://www.thegreatpaperadventure.com/)。Damien在几年前使用[XNA](http://en.wikipedia.org/wiki/Microsoft_XNA)制作了本游戏。当我们开始这个教程的时候，我们就在想，它是一个讲解Unity的完美素材。

## UNITY

[Unity3D](http://unity3d.com/)是一个制作跨平台游戏的流行且完美的解决方案。这个教程假设你至少熟悉一种编程语言，了解这个工具和引擎更好，不知道也无所谓。

本教程使用Unity 5 **Personal Edition**（免费）版本。

[![Unity](https://pixelnest.io/tutorials/2d-game-unity/-img/unity.png)](http://unity3d.com/unity/download)

## 视频版本

如果比起**读**你更愿意**看**本教程，可以看[Jay Jennings’s work from Game Dev Nation](http://gamedevnation.com/creating-a-2d-game-with-unity/).

> **Notice**: 章节"Making animations with Unity 2D"还没有。

## 翻译版本

- [Chinese version](http://www.litpo.com/category/%E6%98%93%E5%AD%A6%E7%9A%84%E6%95%99%E7%A8%8B/) by Zhang Qianying from LITPO
- [Chiness version](https://github.com/yuiitsu/Article/tree/master/Unity-Tutorials/2d-game-unity) by onlyfu

## 许可

- 资源和艺术使用 [CC-BY-NC](http://creativecommons.org/licenses/by-nc/2.0/fr/)许可，它们由 [Thibault Person](http://twitter.com/mrlapinou) 为游戏 [The Great Paper Adventure](http://www.thegreatpaperadventure.com/)制作。
- 源码属于Pixelnest Studio，它使用 [MIT license](http://choosealicense.com/licenses/mit/)发布。

可以从[licenses on GitHub](https://github.com/pixelnest/tutorial-2d-game-unity/blob/master/LICENSE.md)获取到更多我们的许可信息。

在[GitHub repository](https://github.com/pixelnest/tutorial-2d-game-unity/)上可以找到源码。

## 联系

如果你发现排版，拼写，内容错误，可以通过[我们的twitter](http://twitter.com/pixelnest)告诉我们，你也可以通过邮件联系我们。

如果你想知道一些特殊主题更多的信息，或者想更清楚的知道一些章节，我们非常乐意为你效劳。

最后，如果你喜欢我们，可以在[twitter](http://twitter.com/pixelnest)上关注我们。

本教程主要由[Damien](http://twitter.com/valryon)编写， [Matthieu](http://twitter.com/solarsailer)修订，我们希望你喜欢它。



那么，你准备好了吗？让我们进入Unity吧!