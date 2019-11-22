# AndroidBug5497WorkaroundKt
Kotlin version of AndroidBug5497Workaround

该版本是在[AndroidBug5497Workaround](https://github.com/madebycm/AndroidBug5497Workaround)的基础上进行的改进，除了将语言改为kotlin实现以外，同时修复了原版本会被导航栏遮挡住的问题。

对于有无状态栏的情况也进行了优化，通过注入原始页面的高度和状态栏的状态，能够有效的在键盘弹出和收起后恢复到正确的高度。
