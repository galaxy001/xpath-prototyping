Adds the input field for XPath to the bottom of each page.
Beware: weekend project.

Usage:
Hold Alt key and mouse click on something on the page to generate XPath.
XPath is the same as generated by FireBug: `id` and `class` attributes are not used, `[1]` conditions are omitted.
You can modify XPath and watch the selection immediately being colored in pale yellow color.
Press `JSON` button to show prompt with JSON, containing innerHTML of selected elements.

Code is taken mostly from StackOverflow and other places over the internet, so I don't claim any rights on it.
Distributed with MIT license.

From: http://www.v2ex.com/t/158484

改了上面这个script，放入油猴可用
可以简单实现 xpath 选择并隐藏元素，css select 的支持就懒得研究了
例如可以在本页输入 //img 试试
兼容性不好，某些有后台ajax刷新的网页会出现跳转或关闭
无版权、无著作权，一切权利归原作者，改了@name只是为了不冲突，谁要修改自用自便，转发请参考原作者的声明

另外有兴趣的人可以装这个玩
https://addons.mozilla.org/en-US/firefox/addon/element-locator-for-webdriv
提取网页元素的xpath，支持多种语言的格式
