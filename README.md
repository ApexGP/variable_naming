# 变量命名规范

---

|       类型       |               命名规则               |     示例     |
| :--------------: | :----------------------------------: | :----------: |
|     普通变量     |          全小写 + 蛇形命名           | `snake_case` |
|       常量       |          全大写 + 蛇形命名           | `UPPER_CASE` |
|     类和模板     |               驼峰命名               | `CamelCase`  |
|   类的公有变量   |  全小写 + 蛇形命名 + 尾部下划线命名  | `variable_`  |
| 类的公有成员函数 |      驼峰命名 + 尾部下划线命名       | `argvFunc_`  |
|   类的私有变量   | 全小写 + 蛇形命名 + 头部单下划线命名 | `_variable`  |
| 类的私有成员函数 |     驼峰命名 + 头部双下划线命名      | `__argvFunc` |
