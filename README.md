
# Table of Contents

1.  [私用的prettier的配置](#org2e51de9)


<a id="org2e51de9"></a>

# 私用的prettier的配置

用于自己以后的项目引用

    "$schema": "http://json.schemastore.org/prettierrc",
    "trailingComma": "es5", // 默认值 在对象或数组最后一个元素后面是否加逗号（在ES5中加尾逗号）
    "endOfLine": "lf",  // 使用 \n 换行符
    "arrowParens": "avoid",  //  (x) => {} 箭头函数参数只有一个时是否要有小括号。avoid：省略括号
    "bracketSpacing": true, // 在对象，数组括号与文字之间加空格 "{ foo: bar }"
    "semi": false, // 行尾不加 ;
    "tabWidth":4, // tab 有几个 spaces
    "useTabs": true, // 使用 tab 缩进
    "bracketSameLine": false, // 将>元素放在最后一行的末尾，而不是单独放在下一行（不适用于自闭合元素）。 
    "proseWrap": "preserve", // 默认值。因为使用了一些折行敏感型的渲染器（如GitHub comment）而按照markdown文本样式进行折行
    "tslintIntegration": false, // 不让prettier使用tslint的代码格式进行校验
    "eslintIntegration": false, // 不让prettier使用eslint的格式进行校验
    "htmlWhitespaceSensitivity": "css", // 是否对html中的空格敏感 

