# 泡泡笔记模板

泡泡笔记提供了一些笔记的模板！
这使您可以轻松创建具有类似结构的注释，而无需使用复制/粘贴  ：）

**模板文件**支持 [VS Code's 代码段语法](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_snippet-syntax),这意味着

- 给新创建的笔记添加一些变量(variables)
- 添加一些 tabstop 来自动导航到笔记的关键点, 就像foam一样
  下面是一个TODO List 和 时间戳的写法.

## 怎么使用

1. ${1:第一个 tabstop}
2. ${2:第二个 tabstop}
3. ${3:第三个 tabstop}

Note Created: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE}

---

试试使用 `Foam: Create New Note From Template` 这条指令然后选择一个模板,比如 `your-first-template`.然后注意看生成的项目!

如需删除模板,只需要删除文件 `.foam/templates/your-first-template.md`.

Enjoy!
