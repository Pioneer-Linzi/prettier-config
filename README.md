
# Table of Contents

1.  [私用的 prettier 的配置](#orgd9bb666)
2.  [使用说明](#orge29ebe4)
3.  [字段示意](#orgdc5c50d)


<a id="orgd9bb666"></a>

# 私用的 prettier 的配置

用于自己以后的项目引用


<a id="orge29ebe4"></a>

# 使用说明

    yarn add --dev @zhaolinlin/prettier-config

在 package.json 中加入

    {
        ...
            "prettier": "@zhaolinlin/prettier-config"
    }


<a id="orgdc5c50d"></a>

# 字段示意

    "$schema": "http://json.schemastore.org/prettierrc",
    "trailingComma": "es5", // 默认值 在对象或数组最后一个元素后面是否加逗号（在 ES5 中加尾逗号）
    "endOfLine": "lf",  // 使用 \n 换行符
    "arrowParens": "avoid",  //  (x) => {} 箭头函数参数只有一个时是否要有小括号。avoid：省略括号
    "bracketSpacing": true, // 在对象，数组括号与文字之间加空格 "{ foo: bar }"
    "semi": false, // 行尾不加 ;
    "tabWidth":4, // tab 有几个 spaces
    "useTabs": true, // 使用 tab 缩进
    "bracketSameLine": false, // 将>元素放在最后一行的末尾，而不是单独放在下一行（不适用于自闭合元素）。 
    "proseWrap": "preserve", // 默认值。因为使用了一些折行敏感型的渲染器（如 GitHub comment）而按照 markdown 文本样式进行折行
    "tslintIntegration": false, // 不让 prettier 使用 tslint 的代码格式进行校验
    "eslintIntegration": false, // 不让 prettier 使用 eslint 的格式进行校验
    "htmlWhitespaceSensitivity": "css", // 是否对 html 中的空格敏感

