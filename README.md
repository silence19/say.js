1. [Marak/say.js](https://github.com/Marak/say.js) is very good, just little but in Chinese due to the encoding bug from Node.js
2. This fork just made little update for Chinese support.
3. The encoding is done with [iconv-lite](https://github.com/ashtuchkin/iconv-lite), so this package should be in path.
4. The extension vscode-speech in VS-Code works well with this.
5. Please find out the 3-lines-change in file [base.js](https://github.com/silence19/say.js/blob/master/platform/base.js).
