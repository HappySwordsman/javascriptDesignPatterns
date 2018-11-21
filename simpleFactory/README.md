# 工厂模式
## 介绍
* 将new操作单独封装<br>
* 遇到new时，就要考虑是否该使用工厂模式<br>
## 示例
* 你去购买汉堡，直接点餐、取餐，不会自己亲手做<br>
* 商店要"封装"做汉堡的工作，做好直接给买者<br>
## UML类图
![avatar](https://github.com/wsyxl365/javascriptDesignPatterns/blob/master/simpleFactory/readmeImages/simpleFactory-01.png)
## 简化后的JS类图
![avatar](https://github.com/wsyxl365/javascriptDesignPatterns/blob/master/simpleFactory/readmeImages/simpleFactory-02.png)
#场景
* 1.jQuery - $('div')
* $('div')和 new $('div')有何区别？
* 第一:书写麻烦，jQuery的链式操作将成为噩梦
* 第二:一旦jQuery名字变化，将是灾难性的
![avatar](https://github.com/wsyxl365/javascriptDesignPatterns/blob/master/simpleFactory/readmeImages/simpleFactory-03.png)
* 2.React.createElement
![avatar](https://github.com/wsyxl365/javascriptDesignPatterns/blob/master/simpleFactory/readmeImages/simpleFactory-04.png)
![avatar](https://github.com/wsyxl365/javascriptDesignPatterns/blob/master/simpleFactory/readmeImages/simpleFactory-05.png)
* 3.vue异步组件
![avatar](https://github.com/wsyxl365/javascriptDesignPatterns/blob/master/simpleFactory/readmeImages/simpleFactory-06.png)
#设计原则验证
* 构造函数和创建者分离
* 符合开放封闭原则
