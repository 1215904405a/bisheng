Hyde.js
====

BI-Directional / Two-Way Data-Binding with JavaScript.

轻量级的数据双向绑定库。

## Usage

### Installing packages and dependencies

    npm install -g bower
    npm install
    bower install

### Hyde.bind(data, tpl, callback)

    // HTML 模板
    var tpl = '{{title}}'
    // 数据对象
    var data = {
      title: 'foo'
    }
    // 执行双向绑定，然后在回调函数中将绑定后的 DOM 元素插入文档中
    Hyde.bind(data, tpl, function(content){
      $('div.container').append(content)
    })

## Start

    grunt 

打开 <http://localhost:5000/>。
