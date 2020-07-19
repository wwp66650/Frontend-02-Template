# 语法 Grammar

## 语法树跟运算符优先级的关系 
Grammar Tree vs Priority
### 优先级最高-语法树最末端
- Mumber - 成员运算符

    ```js
    a.b;
    a[b];
    foo`string`;
    super.b
    super['b']
    new.target
    new Foo(); // 带括号的new

    new a()() // 先第一个括号与`new`结合
    ```

- New - New Expression

    优先级比`Member`低
    ```js
    new Foo

    new new a() // 先括号与第二个new结合
    ```

- Call

    优先级低于前面几项
    ```js
    foo()
    super()

    // 如果在括号之后加上取属性，比如.比如[]又比如反引号，那么它会让表达式降级为 Call Expression
    foo()['b']
    foo().b
    foo()`abc`

    new a()['b'] // 先new出来一个对象，再调用这个对象的b属性
    ```


## 运算符左值与右值 
Left hand side & Right hand side

# 运行时 Runtime
## 类型转换 
Type Convertion

## 引用类型 
Reference