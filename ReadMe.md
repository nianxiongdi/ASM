<button>[回到首页](../index.md)</button>


- [开发辅助工具](#开发辅助工具)
    - [静态分析工具](#静态分析工具)
    - [浏览器检测工具](#浏览器检测工具)
    - [视觉测试工具](#视觉测试工具)
- [参考文献](#参考文献)

## 开发辅助工具

开发测试由软件开发人员或工程师在软件开发生命周期的构建阶段执行。目的是为了保证质量和行业或法规合理性。通过前两章了解，在开发过程中要遵循无障碍标准，这里为开发者提供一些工具，从不同的角度进行测试：

### 静态分析工具

静态分析是指在不运行程序的条件下，对程序分析的方法，但是有些程序分析需要运行程序该能够进行，这里为开发者提供[eslint-plugin-jsx-a11y](https://github.com/evcohen/eslint-plugin-jsx-a11y)，在不运行程序条件下，运行此工具对程序进行静态分析，介绍如下：

* 对JSX代码进行无障碍标准测试。
* eslint-plugin-jsx-a11y是对静态扫描，无需侵入代码，能扫到事件缺失，定义30多条比较常见规则，请[参考](https://github.com/evcohen/eslint-plugin-jsx-a11y/tree/master/docs/rules)。
* 可以在开发和集成测试中使用。

### 浏览器检测工具

开发者在开发的过程中，可以通过浏览器插件对已经编写的代码进行测试，是否符合无障碍标准，这里为开发者提供[Axe Chrome Plugin](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd),介绍如下：

* 在浏览器中测试代码是否符合无障碍标准。
* Axe可访问性检查器是一个快速、轻量级的可访问性测试工具，它基于业内最流行的开源无障碍测试库axe-core，安装成功后可在Chrome Dev Tools面板找到。可以静态分析当前已存在于document中的内容。
* 在控制台选择axe，就可以对网站进行测试，并列出不符合无障碍问题并给出解决方案。

### 视觉测试工具

在全球范围内，存在很多视觉障碍的用户，这样在设计和开发的过程中需要对这些问题解决，这里为开发者提供[I want to see like the colour blind](https://chrome.google.com/webstore/detail/i-want-to-see-like-the-co/jebeedfnielkcjlcokhiobodkjjpbjia)，介绍如下：

* 在浏览器运行，对视觉进行测试。
* Chrome插件]，开启可模拟红、绿、蓝、全色盲、色弱等用户眼中的站点，直接发现站点中存在的可辨别性问题。

##  参考文献

* [Development Testing](https://en.wikipedia.org/wiki/Development_testing)
* [无障碍访问工具](https://www.w3cschool.cn/front_end_handbook_2017/front_end_handbook_2017-jtqp26ec.html)
