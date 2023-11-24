# C++多线程编程作业

## 练习题：

编写一个C++程序，模拟一个发布者-订阅者模型。在这个模型中，有一个发布者线程和多个订阅者线程。发布者线程生成数据并将其发布，订阅者线程订阅数据并进行处理。

参考流程：

- 发布者线程不断生成数据，每次生成一个1到100的随机整数，并将其发布。
- 订阅者线程订阅数据，如果订阅的数据是偶数，就将其打印出来。
- 使用互斥锁保护数据，防止同时读写导致的数据竞争。
- 使用条件变量使订阅者线程在没有新数据时等待，直到发布者线程发布新数据。

提示：
你可以使用C++11的std::thread, std::mutex, std::condition_variable来完成这个练习。

--- 

### 作业提交方法：

- 第一步：创建新issue
![new_issue](https://github.com/Adam-QLUT/cpp_mutex_homework/assets/133772875/b354206e-f117-4098-8ff9-5fa4da087593)

- 第二步：填写作业内容，格式要求如下图
![Screenshot_20231124_162506](https://github.com/Adam-QLUT/cpp_mutex_homework/assets/133772875/0f82f3c3-3a27-48de-aad6-cc6657486ab1)

- 第三步：提交
点击绿色`Submit New issue`按钮提交
