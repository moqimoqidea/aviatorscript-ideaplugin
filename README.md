## aviator script IDEA plugin

AviatorScript表达式引擎的IDEA插件

主要功能
- 高亮显示   （已实现）
- 语法检查   （已实现）
- 执行代码   （已实现）
- 快捷注释   （已实现）
- 格式化代码 （计划中）
- 代码补全   （计划中）

AviatorScript在线文档：https://www.yuque.com/boyan-avfmj/aviatorscript/guhmrc

开发参考如下
- BNF grammar https://blog.csdn.net/wzbclock/article/details/3943498
- IDEA doc https://jetbrains.org/intellij/sdk/docs/reference_guide/custom_language_support.html
- IDEA demo https://jetbrains.org/intellij/sdk/docs/tutorials/custom_language_support/lexer_and_parser_definition.html
- BNF from https://github.com/JetBrains/Grammar-Kit/blob/master/grammars/Grammar.bnf
- Go BNF https://github.com/go-lang-plugin-org/go-lang-idea-plugin/blob/master/grammars/go.bnf


用法： gradle task  myBuildPlugin
