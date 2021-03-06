## IBM 推荐系统
### 简介
> 对于此项目，你需要分析用户与 IBM Watson Studio 平台上的文章进行的互动，并向他们推荐你认为他们可能会喜欢的文章。下面是一个 IBM Watson 平台信息中心示例，其中展示了一些文章。


> 虽然上述信息中心只显示了最新的文章，但是你可以创建一个推荐系统，向特定的用户显示最相关的文章。

> 为了判断要向每个用户显示哪些文章，你需要对 IBM Watson Studio 平台上的数据展开研究。你可以创建一个帐户并加入该社区，这样可以进一步了解数据。请在此处创建帐户。

### 你的任务
该项目由以下几个任务组成

I. 分析数据

在创建任何推荐系统之前，你需要了解即将用到的数据。深入分析数据，看看有何规律。你可以针对将在 notebook 的整个后续阶段用到的数据提出几个基本问题。在此阶段先探索数据，然后在后面的部分详细思考如何创建推荐系统。

II.基于排名的推荐方法

要开始构建推荐系统，你首先需要根据互动次数查找最热门的文章。由于文章没有评分，所以互动次数最多的文章肯定最热门。然后，我们可以将这些文章推荐给新用户（或者我们已知的一些用户）。

III.基于用户-用户的协同过滤

为了针对 IBM 平台的用户构建更好的推荐系统，我们可以根据用户互动过的文章找到相似的用户。然后，向相似的用户推荐这些文章。这样就可以向用户提供更加个性化的推荐。接下来需要实施这一步。

IV.基于内容的推荐系统（选修内容）

考虑到每篇文章的内容篇幅并不相同，我们可以通过多种方式实施基于内容的推荐系统。你可以运用自然语言处理技能，以非常有创意的方式开发基于内容的推荐系统。建议完成基于内容的推荐系统，但是并非必须这么做。

V. 矩阵分解

最后，你将以机器学习的方式构建推荐系统。你需要根据用户-文章互动进行矩阵分解。然后，你将根据分解结果判断用户与新文章的互动情况（提示：效果并不好）。最后，你需要解释下继续使用哪些方法，并如何测试你的推荐系统在吸引用户方面的效果。

在提交项目之前，对照审阅标准检查是否满足所有要求。

注：审阅标准提到的 DRY原则，Don’t Repeat Yourself。
