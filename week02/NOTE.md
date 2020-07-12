# 产生式（BNF）
还不是很理解，需查阅更多资料

# 语言的分类
## 形式语言 - 用途
- 数据描述语言：Json Html Sql Css
- 编程语言：PHP C C++ Java C# Python Go JavaScript
## 形式语言 - 表达方式
- 声明式语言：Json Html Sql Css
- 命令型语言：PHP C C++ Java C# Python Go JavaScript

# 类型
1. Undefined;
2. Null;
3. Boolean;
4. String;
5. Number;
6. Symbol;
7. Object;

## Undefined
- `Undefined` 类型只有一个值：`undefined`
- 任何变量在赋值前都是 `Undefined` 类型，值为 `undefined`
- `undefined` 是全局变量，并非关键字，这是 JavaScript 语言公认的设计失误之一
- 为了避免无意中被篡改，建议使用 `void 0` 来获取 `undefined` 值

## Null
- `Null` 类型也只有一个值，就是 `null`，它的语义表示空值
- `Null` 表示的是：“定义了但是为空”
- 在实际编程时，我们一般不会把变量赋值为 `undefined`，这样可以保证所有值为 `undefined` 的变量，都是从未赋值的自然状态。
- 与 `undefined` `不同，null` 是 JavaScript 关键字，所以在任何代码中，你都可以放心用 `null` 关键字来获取 `null` 值

## Boolean
- `Boolean` 类型有两个值， `true` 和 `false`
- 用于表示逻辑意义上的真和假
- `true` 和 `false` 都是关键字

## String
- bfnrtv 特殊字符