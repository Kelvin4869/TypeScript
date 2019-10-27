# TypeScript  

TypeScript学习笔记及相关demo  

## 目录

1. 概述
    1. js语言的问题
        1. 大多数大萨达
    2. ts语言的特点
2. 在node环境中搭建开发环境
    1. 安装TypeScript
    2. TypeScript的配置文件
    2. 使用第三方库简化流程 
3. 基本类型检查
    1. 类型约束和编译结果对比
    2. 基本类型
    3. 其它类型
    4. 类型别名
    5. 函数的相关约束
    6. demo：创建并打印扑克牌
4. 扩展类型-枚举
    1. 字面量类型的问题
    2. 枚举的使用
    3. demo：使用枚举优化扑克牌程序
    4. 扩展：枚举的位运算 
5. 模块化
    1. 在ts中使用使用模块化
    2. 编译结果中的模块化
    3. 解决默认导入的错误
    4. 如何在ts中书写commonjs模块化代码
    5. 模块解析
    6. demo：使用模块化优化扑克牌程序
6. 接口类型和类型兼容性
    1. 接口的概念
    2. 接口的使用
    3. readonly修饰符
    4. 类型兼容性
    5. demo： 用接口改造扑克牌程序
7. TS中的类
    1. 概述
    2. 新增的类语法
    3. 访问器
    4. demo：增加洗牌和发牌功能
8. 泛型
    1. 在函数中使用泛型
    2. 在类、接口、类型别名中使用泛型
    3. 泛型约束
    4. 多泛型
    5. demo： 自定义字典类
9. Demo-使用React+TS开发三字棋游戏
    1. 效果展示和工程搭建
    2. 在react中使用ts
    3. 制作棋子组件
    4. 制作棋盘组件
    5. 制作Game组件-项目完结
    6. 总结
10. 深入理解类和接口
    1. 面向对象概述
    2. 类的继承
    3. 抽象类
    4. 静态成员
    5. 再谈接口
    6. 索引器
    7. this指向约束
11. Demo-使用webpack+ts开发俄罗斯方块
    1. 概述
    2. 工程搭建
    3. 小方块类
    4. 小方块的展示类
    5. 开发方块组合类
    6. 开发俄罗斯方块生产者模块
    7. 开发俄罗斯方块规则类
    8. 实现俄罗斯方块的旋转功能
    9. 实习游戏类
    10. 触底处理
    11. 消除处理
    12. 游戏结束盘点和积分功能
    13. 完成游戏界面
    14. 项目总结
12. 装饰器
    1. 概述
    2. 类装饰器
    3. 成员装饰器
    4. demo
    5. reflect-metadata库
    6. class-validator和class-transformer库
    7. 装饰器补充
13. 类型演算
    1. 三个关键字
    2. 预定义的类型演算
14. 声明文件
    1. 概述
    2. 编写声明文件
    3. 发布
15. 项目实战
    1. 概述
    2. 服务器开发环境搭建
    3. 使用tslint进行代码风格检查
    4. 开发Movie实体类
    5. 处理plainobject的转换
    6. 定义数据库模型
    7. 增删改查功能
    8. 按条件查询电影
    9. 完成api接口
    10. 完成图片上传接口
    11. 搭建客户端工程并完成ajax请求
    12. 创建reducer和action
    13. 创建仓库
    14. 用thunk处理副作用
    15. 添加路由功能
    16. 制作布局
    17. 制作电影表格组件（1）
    18. 制作电影表格组件（2）
    19. 制作电影表格组件（3）
    20. 制作图片上传组件
    21. 制作电影表单组件
    22. 制作修改电影页面
    23. 项目打包


## 说明
    1. 不同在章节对应的不同的分支，分支上有相关笔记及对应的demo；
    2. 仓库创建日期2019.10.27，本仓库将持续更新；