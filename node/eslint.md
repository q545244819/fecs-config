# fecs 配置文件描述

## ESlint 部分

 - indent: 强制使用一致的缩进
 - semi: 要求或禁止使用分号而不是 ASI
 - comma-dangle: 要求或禁止末尾逗号
 - eqeqeq: 要求使用 === 和 !==
 - no-unused-vars: 禁止出现未使用过的变量
 - no-console: 禁用 console
 - no-empty: 禁止空语句块
 - no-eval: 禁用 eval()
 - no-lone-blocks: 禁用不必要的嵌套块
 - no-native-reassign: 禁止对原生对象赋值
 - global-require: 要求 require() 出现在顶层模块作用域中
 - no-extra-semi: 禁止不必要的分号
 - no-duplicate-case: 禁止重复的 case 标签
 - no-dupe-keys: 禁止对象字面量中出现重复的 key
 - no-cond-assign: 禁止条件表达式中出现赋值操作符
 - no-use-before-define: 不允许在变量定义之前使用它们
 - eol-last: 强制文件末尾至少保留一行空行
 - no-unexpected-multiline: 禁止出现令人困惑的多行表达式
 - arrow-spacing: 强制箭头函数的箭头前后使用一致的空格
 - no-const-assign: 禁止修改 const 声明的变量
 - no-dupe-class-members: 禁止类成员中出现重复的名称
 - prefer-arrow-callback: 要求使用箭头函数作为回调
 - newline-before-return: 要求 return 语句之前有一空行
 - space-infix-ops: 要求中缀操作符周围有空格 (space-infix-ops)
 - no-nested-ternary: 不允许使用嵌套的三元表达式
 - no-multiple-empty-lines: 不允许多个空行
 - no-mixed-spaces-and-tabs: 不允许空格和 tab 混合缩进
 - no-array-constructor: 禁止使用 Array 构造函数

```JSON
  "eslint": {
    "parserOptions": {
      "ecmaVersion": 6
    },
    "env": {
      "node": true,
      "browser": false
    },
    "rules": {
      "indent": [2, 2, {"SwitchCase": 1}],
      "semi": ["never"],
      "comma-dangle": ["error", "never"],
      "eqeqeq": ["error"],
      "no-unused-vars": 2,
      "no-console": {"allow": ["warn", "error"]},
      "no-empty": ["error"],
      "no-eval": ["error"],
      "no-lone-blocks": ["error"],
      "no-native-reassign": ["error", {"exceptions": ["Object"]}],
      "global-require": ["error"],
      "no-extra-semi": ["error"],
      "no-duplicate-case": ["error"],
      "no-dupe-keys": ["error"],
      "no-cond-assign": ["error", "always"],
      "no-use-before-define": ["error"],
      "no-plusplus": ["error", { "allowForLoopAfterthoughts": true }],
      "eol-last": ["error"],
      "no-unexpected-multiline": ["error"],
      "arrow-spacing": ["error"],
      "no-const-assign": ["error"],
      "no-dupe-class-members": ["error"],
      "prefer-arrow-callback": ["error"],
      "newline-before-return": ["error"],
      "space-infix-ops": ["error"],
      "no-nested-ternary": ["error"],
      "no-multiple-empty-lines": ["error"],
      "no-mixed-spaces-and-tabs": ["error"],
      "no-array-constructor": ["error"]
    }
  }
```
