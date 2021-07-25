# Usage of this repository
This is just an modified version to fix the encoding bug of Chinese characters, in the extension of VS-Code which named VSCode-Speech.
The VSCode-Speech is using the Say.js, that's why I fixed several lines for Say.js here.
1. This repository is just made little update for Chinese support.
2. The origional [Marak/say.js](https://github.com/Marak/say.js) is very good, just little bug in Chinese due to the encoding problem  inherited from from Node.js
3. The encoding is done with [iconv-lite](https://github.com/ashtuchkin/iconv-lite), so a ready-to-use package should be in path.
4. Please find out the 3-lines-change in file [base.js](https://github.com/silence19/say.js/blob/master/platform/base.js).
5. The extension vscode-speech in VS-Code works well with this modification.

# 中文使用方法
中文VSCode阅读与朗读tts方案见[此处](https://github.com/silence19/say.js/Win10 PC 桌面端中文阅读解决方案.md)或者本人[知乎文章](https://zhuanlan.zhihu.com/p/392655592)
