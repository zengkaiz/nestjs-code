# nestjs-code
nestjs通关秘籍demo代码

#### 5 种 http 数据传输方式
[5 种 http 数据传输方式](https://github.com/zengkaiz/nestjs-code/tree/main/five-transmission-method)  
#### 使用多种 Provider
[使用多种 Provider，灵活注入对象](https://github.com/zengkaiz/nestjs-code/tree/main/five-transmission-method)  
#### 全局模块和生命周期
[全局模块和生命周期](https://github.com/zengkaiz/nestjs-code/tree/main/global-and-lifecycle-v2)  
#### AOP架构
AOP 的好处是可以把一些通用逻辑分离到切面中，保持业务逻辑的纯粹性，这样切面逻辑可以复用，还可以动态的增删。  
Nest实现AOP的方式： 有五种，包括 Middleware、Guard、Pipe、Interceptor、ExceptionFilter  
##### Middleware
全局中间件、路由中间件  
##### Guard
是路由守卫的意思，可以用于在调用某个 Controller 之前判断权限，返回 true 或者 false 来决定是否放行  
##### Interceptor
是拦截器的意思，可以在目标 Controller 方法前后加入一些逻辑， Interceptor 要实现 NestInterceptor 接口，实现 intercept 方法  
##### Pipe
管道的意思，用来对参数做一些检验和转换， Pipe 要实现 PipeTransform 接口，实现 transform 方法  
##### ExceptionFilter
可以对抛出的异常做处理，返回对应的响应， 实现 ExceptionFilter 接口，实现 catch 方法，就可以拦截异常  
#### 全部装饰器
[Nest 全部装饰器](https://github.com/zengkaiz/nestjs-code/tree/main/all-decorator)  
#### Metadata 和 Reflector
[Metadata 和 Reflector](https://github.com/zengkaiz/nestjs-code/tree/main/argument-host)  
#### Module 和 Provider 循环依赖
[Module 和 Provider 循环依赖](https://github.com/zengkaiz/nestjs-code/tree/main/circular-dependency)  
#### 创建动态模块
[创建动态模块](https://github.com/zengkaiz/nestjs-code/tree/main/dynamic-module)  
#### Nest 和 Express 的关系
[Nest 和 Express 的关系](https://github.com/zengkaiz/nestjs-code/tree/main/fastify-test)  
#### Nest 的 Middleware
[Nest 的 Middleware](https://github.com/zengkaiz/nestjs-code/tree/main/middleware-test)  
#### Interceptor
[Interceptor](https://github.com/zengkaiz/nestjs-code/tree/main/interceptor-test)  
#### Pipe 和 自定义Pipe
[Pipe 和 自定义Pipe](https://github.com/zengkaiz/nestjs-code/tree/main/pipe-test) 
#### 自定义exception
[自定义exception](https://github.com/zengkaiz/nestjs-code/tree/mainexception-filter-test) 
#### Express 使用 multer 实现文件上传
[自定义exception](https://github.com/zengkaiz/nestjs-code/tree/multer-test) 