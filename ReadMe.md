<button>[回到首页](../index.md)</button>

<!-- TOC -->

-   [开发阶段测试](#开发阶段测试)
    -   [如何进行测试](#如何进行测试)
-   [结论](#结论)
-   [参考文献](#参考文献)


## 开发阶段测试

测试是为了保证软件质量采取的措施，通过测试可以帮助开发者：验证程序的正确性、发现缺陷、验证需求。开发测试由软件开发人员或工程师在软件开发生命周期的构建阶段执行。

### 如何进行测试

尽早和不断地进行软件测试，目的是为了保证质量和行业或法规合理性。通过前两章了解，在开发过程中要遵循无障碍标准，这里为开发者提供一些工具，从不同的角度进行测试：

* 浏览器检测工具 - 在浏览器中测试代码是否符合无障碍标准

    [Axe Chrome Plugin](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd)

    * Axe可访问性检查器是一个快速、轻量级的可访问性测试工具，它基于业内最流行的开源无障碍测试库axe-core，安装成功后可在Chrome Dev Tools面板找到。可以静态分析当前已存在于document中的内容。
    * 在控制台选择axe，就可以对网站进行测试，并列出不符合无障碍问题并给出解决方案。

* 静态分析工具 - 对JSX代码进行无障碍标准测试
    
    [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)
    * eslint-plugin-jsx-a11y是对静态扫描，无需侵入代码，能扫到事件缺失，定义30多条比较常见规则，请[参考](https://github.com/evcohen/eslint-plugin-jsx-a11y/tree/master/docs/rules)。
    * 可以在开发和集成测试中使用。

* 视觉测试工具 - 在浏览器中运行，对视觉进行测试

    [I want to see like the colour blind](https://chrome.google.com/webstore/detail/i-want-to-see-like-the-co/jebeedfnielkcjlcokhiobodkjjpbjia)

    * Chrome插件，开启可模拟红、绿、蓝、全色盲、色弱等用户眼中的站点，直接发现站点中存在的可辨别性问题。


### 结论

在开发过程中遵循第一章和第二章规则，要合理的使用role和aria-*,避免在测试阶段出现不必要的错误。其次参照上节[如何进行测试](#如何进行测试),在开发阶段进行完整测试。



###  参考文献

* [Wikipedia](https://en.wikipedia.org/wiki/Development_testing)
* [a11y tools](https://www.digitala11y.com/accessibility-plug-ins-ie-chrome-firefox-browsers/)
* [eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)
* [I want to see like the colour blind](https://websitecreationworkshop.com/blog/design-tips/see-like-color-blind/)
