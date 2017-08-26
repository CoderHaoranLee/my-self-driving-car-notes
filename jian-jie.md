# 以翻译一篇综述为框架进行整理


# Perception, Planning, Control, and Coordination for Autonomous Vehicles
# 自动驾驶的感知，规划，控制和协作

本文以英文论文为基础，在翻译的基础上会添加最近接触领域的最近进展和其他的见解。

```Abstact``` 自动驾驶汽车由于其在增强安全，提高生产率，增加便捷，改善道路效率，和对环境有积极影响等方面的潜力，被认为会在未来的城市交通系统中扮演着重要角色。由于计算能力的增加，传感器价格的降低以及计算技术的发展，近几年关于自动驾驶系统的研究也是急剧增加，全自动驾驶技术也逐渐走向成熟。这篇论文的目的是对近几年来自动驾驶软件系统的发展提供一个广泛的视野。主要回顾自动驾驶软件的基本组成部分，以及这些部分在几年的发展。

```Introduction``` 自动驾驶汽车被期望通过提供更高的运输能力缓解道路拥堵的压力，通过减少人为失误提高道路安全，能够将驾驶员从沉重的驾驶负担中解放出来，可以提高生产能力并且增加休息的时间，以及还有大量没有意识到的优势。在过去的三十多年，关于研发自动驾驶的研究工作越来越多，一方面是得益于感知和计算技术的发展可以使硬件的尺寸和成本越来越小。。。。

最早进行自动驾驶汽车的研究可以追溯到1918年，而电视广播才起于1958年。1988年，卡耐基梅隆（Carnegie Mellon）的NAVLAB汽车可以根据摄像头图像进行车道保持。2004年和2005年的DARPA Grand Challenges的要求汽车能够自动穿过沙漠，以及2007年的城市挑战赛（DARPA Urban Challenge，DUC）要求穿过城市街道，这大大加速了自动驾驶的发展。自此自动驾驶在学术界迎来的飞速的发展，此外，工业界也迎来越来越多的关注。

由于自动驾驶技术的研究基本成熟，在不同尺寸的平台上也实现了许多令人印象深刻的演示。Recent studies have also been conducted to model and anticipate the social impact of implementing autonomous Mobility-on-Demand(MoD). The case studies have shown that MoD system would make access to mobility more affordable and convenient compared to traditional mobility system characterized by extensive private vechile ownership.

由于几个商业实体推动学术界的极限，近几年在城市道路上自动驾驶汽车的发展也是突飞猛进。谷歌在这个领域有最多的经验，其自动驾驶汽车已经进行了200万英里（mile）的测试， with experience to soon launch a pilot MoD service project using 100 self-driving vehicles.