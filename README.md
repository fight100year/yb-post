# YB's BLOG

![markdownlint](https://github.com/fight100year/yb-post/workflows/markdownlint-lint/badge.svg)

仓库说明 : 这个仓库主要用于将以前零散的文章集合在一处管理

仓库结构说明:

- waiting-for-review: 等待review的post
- reviewed：已reviewed的post

## reviewed

- hugo, 静态站点生成器 | [官方文档](/reviewed/hugo-office-doc.md)
- kurento, 一个开源的sfu 项目，主要承载的是webrtc流
  - [二次开发需要了解的faq](/reviewed/kurento-faq.md)
  - ppt等演讲资料(包括技术选型的一个分析，源码分析)
  - openvidu(kurento的姐妹项目)的[入门教程](/reviewed/kurento-openvidu-office-doc-tutorials.md)、[demo](/reviewed/kurento-openvidu-office-doc-demo.md)
- [redis学习笔记](/reviewed/redis-office-doc.md)
- c++相关资料
  - [cpp基础](/reviewed/cpp-basic.md)
  - [cpp自定义类型](/reviewed/cpp-type.md)
- i3wm,一个平铺窗口管理器，[学习笔记](/reviewed/i3wm-office-doc.md)
- oh my zsh, 已配置好的zsh配置，[学习笔记](/reviewed/oh-my-zsh.md)
- spf13 vim配置，[学习笔记](/reviewed/spf13-usage.md)
- docker环境安装,并配置了常用的vim和yb用户，[学习笔记](/reviewed/docker-install.md)
- grpc系列:
  - [grpc的介绍](/reviewed/grpc-introduce.md)
  - [设计原则](/reviewed/grpc-post.md)
  - [教程](/reviewed/grpc-tutorial.md)
  - [概念](/reviewed/grpc-concepts.md)
  - [异步调用](/reviewed/grpc-async.md)
  - [faq](/reviewed/grpc-faq.md)
- go 官方文档
  - 官方文档,对go的一个大致描述
    - [介绍](/reviewed/go-introduce.md),[安装](/reviewed/go-install.md)
    - [基础教程](/reviewed/go-tour.md)
    - [如何写go代码](/reviewed/go-code.md)
    - [effective go](/reviewed/go-effective.md)
    - [go命令行参数](/reviewed/go-cmd.md)
    - [命令行文档](/reviewed/go-cmd-other.md)
    - [诊断](/reviewed/go-diagnose.md)
  - spec
    - [spec介绍](/reviewed/go-spec-introduce.md)
    - [符号](/reviewed/go-spec-notation.md)
    - [源码格式](/reviewed/go-spec-source-fmt.md)
    - [词法](/reviewed/go-spec-lexical.md)
    - [常量](/reviewed/go-spec-constants.md)
    - [变量](/reviewed/go-spec-variables.md)
    - [类型](/reviewed/go-spec-types.md)
    - [类型和值的属性](/reviewed/go-spec-properties.md)
    - [代码块](/reviewed/go-spec-blocks.md)
    - [声明和作用域](/reviewed/go-spec-scope.md)
    - [表达式](/reviewed/go-spec-expressions.md)
    - [语句](/reviewed/go-spec-statements.md)
    - [内置函数说明](/reviewed/go-spec-builtin.md)
    - [包](/reviewed/go-spec-package.md)
    - [程序的初始化和执行](/reviewed/go-spec-exec.md)
    - [错误和运行时异常](/reviewed/go-spec-error.md)
    - [系统注意事项](/reviewed/go-spec-system.md)
  - 内存模型
    - [内存模型](/reviewed/go-memory-model.md)
  - faq
    - [项目起源](/reviewed/faq/go-faq-origins.md)
    - [使用情况](/reviewed/faq/go-faq-usage.md)
    - [设计](/reviewed/faq/go-faq-design.md)
    - [类型](/reviewed/faq/go-faq-type.md)
    - [值](/reviewed/faq/go-faq-value.md)
    - [代码编写](/reviewed/faq/go-faq-writing-code.md)
    - [指针和内存申请](/reviewed/faq/go-faq-pointer.md)
    - [并发](/reviewed/faq/go-faq-concurrency.md)
    - [函数和方法](/reviewed/faq/go-faq-func-method.md)
    - [控制流](/reviewed/faq/go-faq-flow.md)
    - [包和测试](/reviewed/faq/go-faq-package-testing.md)
    - [实现](/reviewed/faq/go-faq-impl.md)
    - [性能](/reviewed/faq/go-faq-performance.md)
    - [和c的不同](/reviewed/faq/go-faq-c.md)
- go发布历史:[v1.12](/reviewed/go-history-v1.12.md),[v1.13](/reviewed/go-history-v1.13.md)
- go [标准库](/reviewed/go-pkg.md)
- 树,[二叉树](/reviewed/binary-tree.md)[二叉搜索树](/reviewed/binary-search-tree.md)
- 页面置换算法[了解](/reviewed/page-replacement-algorithm.md),[缓存替换策略](/reviewed/cache-replacement-policies.md)
- 使用github，git commit怎么写[才高效](/reviewed/github-commit.md)
- github issues的[基本使用](/reviewed/github-issue.md)
- github codeowners的[基本使用](/reviewed/github-codeowners.md)
- test
  - BDD 行为驱动测试，常用在用户验收测试(UAT)。BDD概念的[补充](/reviewed/test-bdd.md)
  - GoConvey,一个BDD测试框架
    - GoConvey的[介绍](/reviewed/goconvey-introduce.md),第一次试用感觉真心好，不愧是chrome都集成的开源库
    - GoConvey[测试的编写](/reviewed/goconvey-composition.md)
    - [断言](/reviewed/goconvey-assert.md)
    - [执行顺序和忽略](/reviewed/goconvey-exec.md)
    - [配置](/reviewed/goconvey-profile.md)
    - [faq](/reviewed/goconvey-faq.md)
    - [reset](/reviewed/goconvey-reset.md)
- 多路复用[了解](/reviewed/multiplexing.md),[事件循环](/reviewed/event-loop.md),i/o多路复用[select/pselect/poll/epoll](/reviewed/multiplexing-network.md)
- uber[Go编码规范](/reviewed/go-uber.md)
- Dave Cheney 系列
  - [self-referential functions and the design of option](/reviewed/function-options-hello.md)
  - [functional options for friendly apis](/reviewed/function-options.md)
  - [Do not fear first class functions](/reviewed/function-options-again.md)

## waiting for review

## TODO

- hugo, 官方文档未补全
- redis, 官方文档学习时的详细笔记没有，后面可补全，正好redis也更新了新内容
- cpp笔记，只有最前面两章，还少很多
- grpc的文档还缺少一部分，后面需要基于实际的例子补全
