# algorithm
算法问题总结，持续更新


#### 1. 开根号实现
实现一个函数, 完成 开根号 的操作, 方法签名如下：

	``` double sqrt(int v, double t) ```

要求：
	1. 不能调用系统库函数, 诸如 Math.sqrt(v) 之类的;
	2. 假设计算出的结果为 r, 要求满足如下条件 |r –v√|≤t, 其中, v√ 是真实的值, t 为给定的一个误差, 例如0.1等. 千万别被这个不等式吓住, 其实就是希望你计算出的答案 r 要在给定的误差范围内. 举个例子, 我调用你的接口 sqrt(9, 0.21) 返回值属于 [2.79, 3.21] 这个区间的任意一个都满足条件. 因为 9‾√=3, 对于任意的 r∈[2.79,3.21], 都满足 |r – 3| ≤0.21;
	3. 实现语言不限, 你条件可以比上述更加苛刻, 但不能宽松;


实现： 开根号实现


参考文章： [从一道面试题谈谈一线码农应该具备的基本素质](http://blog.jobbole.com/109249/)
