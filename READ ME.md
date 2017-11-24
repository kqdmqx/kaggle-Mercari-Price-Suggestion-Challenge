* 翻译下[比赛概况][overview]
[overview]: https://www.kaggle.com/c/mercari-price-suggestion-challenge#Kernels-FAQ

## Description

It can be hard to know how much something’s really worth. Small details can mean big differences in pricing. For example, one of these sweaters cost $335 and the other cost $9.99. Can you guess which one’s which?

* 知晓一件东西真正值得的价格是困难的。
* 小细节的差异可能意味着巨大的价格差异。
* 比如，一件毛衣标价$335，而另一件标价$9.99。
* 你能猜到哪件是哪件么？

> **Sweater A:**
> "Vince Long-Sleeve Turtleneck Pullover Sweater, Black, Women's. size, great condition"

***

> **Sweater B:**
> "St. John's Long-Sleeve Turtleneck Pullover Sweater, size L, greate condition"

Product pricing gets even harder at scale, considering just how many products are sold online. Clothing has strong seasonal pricing trends and is heavily influenced by brand names, while electronics have fluctuating prices based on product specs.

* 考虑到在线销售的商品数量，商品定价变得愈加困难。
* 在电商基于不同商品种类影响价格同时，服装的价格有强烈的季节性而且严重受品牌影响。

Mercari, Japan’s biggest community-powered shopping app, knows this problem deeply. They’d like to offer pricing suggestions to sellers, but this is tough because their sellers are enabled to put just about anything, or any bundle of things, on Mercari's marketplace.

* **Mercari**，日本最大的community-powered电商APP，确切地知晓这个问题。
* 他们愿意向卖家提供定价建议，但这很困难。
* 因为在**Mercai**的市场上销售任何东西。（？）

In this competition, Mercari’s challenging you to build an algorithm that automatically suggests the right product prices. You’ll be provided user-inputted text descriptions of their products, including details like product category name, brand name, and item condition.

* 在这项比赛中，**Mercari**像你发起挑战，创建个自动建议商品价格的算法。
* 你将被提供用户输入的商品文本描述，包括以下细节：
	* 商品类别名称
	* 品牌名称
	* 商品状态

Note that, because of the public nature of this data, this competition is a “Kernels Only” competition. In the second stage of the challenge, files will only be available through Kernels and you will not be able to modify your approach in response to new data. Read more details in the data tab and Kernels FAQ page.

* 注意，因为数据的公开特性，这是一个“Kernels Only”比赛。
* 在比赛的第二阶段，文件只能通过Kernels访问，且你不可根据新数据来调整方法。
* 从数据标签和Kernels FAQ页面读取更多细节。

## Evaluation

RMSLE

## Kernels FAQ

### How do I upload external data? 如何上传额外数据？

Use of external data is encouraged in this competition. You'll need to publish your data as an Open Dataset. Then you can import it into your Kernel.

Please check the Rules for the types of external data that are allowed in this competition. Please note that we will be monitoring closely on the external data used for this competition and may remove the data and ban your team if rules are violated.

* 本竞赛鼓励使用额外数据。
* 你需要将数据作为公开数据发布。
* 然后你就可以在Kernel中引用了。
* 检查可用额外数据的规则...

### What will happen when you run everyone's Kernels in the 2nd stage? 大家的Kernel在第二阶段会发生什么？

We will re-run your Kernels that generated the selected submissions. In particular, we will re-run the version of Kernels that you used to generate that submission. We will submit the same file name that you used to generate your selected submission. To view your selected submissions, go to "My Submissions" to view them, along with the Kernel version that generated your submissions.

* 我们将重新运行你用于生成**selected submissions**的Kernel。
* 特别的，我们会重新运行用于生成那个结果的Kernel的版本。
* 我们会用同样的文件名提交你生成**selected submissions**。
* 你可以在**My Submissions**页面查看**selected submissions**，一并查看Kernel版本。

### How do I select the version of code to re-run? 我如何选择重新运行的版本？

This is the same as any Kaggle competitions where you select submissions. You can view your list of submissions from "My submissions", then check "use for final score" to select them. Each submission is "tagged" with a Kernel version. Please make sure you selected the version that you want the re-runs to be based on. 

* 


### How should I save my submission file?

When we re-run your code, we will submit the same file name that you generated. For example, if you submitted submission_123.csv, we will submit that same file name for you in Stage 2. Please don't use anything that might change in your file name if your code is re-run. For example, time stamp should be avoided in your file name.

### How can I make sure my code will not fail in a re-run?

You should anticipate there to be unseen data that might break your code. Please plan ahead with good try/catch blocks to make sure you still make valid predictions even when your code encounters an error.

### What are the compute limits of Kernels?

Both your training and prediction should fit in a single Kernel. That means ensembles will need to be done in a single Kernel, and not from uploaded external data.

Kernels offer: 4 cores / 16 GB RAM / 60 minutes run-time / 1 GB scratch and output disk space

### How do I team up in a Kernels-only competition?

All the competitions setup is the same as normal competitions, except that submissions are only made through Kernels. So to team up, go to the "Team" tab and invite others.