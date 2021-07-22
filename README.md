# person
底层探索的方法:
```diff
@@ 断点，汇编，源码三者相结合 @@
# 1. xcode > Debug > Debug Workflow > Always Show Disassembly   
# 2. 打一个OC断点 > ctrl + ↓ > 进入汇编单步调试
# 3. 锁定函数符号，打符号断点进一步跟进，符号断点与上面的汇编代码有区别
# 4. Apple opensource ,通过源码跟进流程
```

