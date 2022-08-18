# Cascading - 层叠
样式覆盖的一条重要规则是后面覆盖前面，显然，内置样式是最先加载的，然后是外部样式和嵌入样式，按照声明顺序加载，然后是内联样式。在特殊性相同的情况下，这条规则生效。
## 样式优先级

1. 行内样式
2. 外部样式、嵌入样式
3. 默认样式

### 选择器发生冲突时的优先级
一般考虑外部样式、嵌入样式的选择器之间的冲突。
特殊性：
1. id选择器。
2. class选择器。
3. 元素名选择器。

同特殊性选择器，后面的覆盖前面的。