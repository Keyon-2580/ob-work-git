
## bean的生命周期
1. 初始化bean实例
2. 初始化属性
3. 实现Aware接口并引入相关依赖
4. 如果有前置处理（postProcessor）
5. 检查是不是InitializingBean决定是否调用afterPropertiesSet
6. 检查是否有定义的init-method方法
7. 后置处理
8. 注册必要的Destruction回调接口
9. 使用Bean
10. 是否实现DisposableBean接口
11. 是否配置destroy方法

## boot的启动过程
