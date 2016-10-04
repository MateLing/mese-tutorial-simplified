MESE-TUTORIAL(SIMPLIFIED)
=============================


# 基本概念

## 概述

MESE 全称 Management and Economics Simulation Exercise，最初是哈佛大学制作的商业模拟软件。在上世纪末本世纪初，青年成就（JA）组织广泛地使用这套软件来进行高中、大学经济学课程（JA Economics）教学。

## 赛制

MESE 是回合制的，每一回合（称为一“期”）中，玩家要阅读报表，然后提交五项决策。在比赛进行到指定的期数后，获得最高 MPI 的玩家获胜。

*请注意，网赛为正赛的极度简化版*

MESE 的总回合数通常为八。

## 五项决策

每一期中，玩家要提交五项决策，分别为价格（Price）、生产量（Production，简称 Prod）、营销投资（Marketing，简称 Mk）、生产投资（Capital Investment，简称 CI）、研发投资（Research & Development，简称 RD）。

MESE 中平衡开工率默认为 80%，低于此的产量很少出现。同时在 80% 产能时单位成本为最小。

Mk 是单期起效的。效果与所有玩家的投入负相关。

CI 即通过投资获得更多的产能。自行考虑。

RD 类似于 Mk，但它的作用效果来自每期平均值，且与价格无关。

## MPI

MPI 由六项指标组成：每期利润之和，历史累计的 Mk 和 RD 投入之和，总产能，开工率，销量，增长率。其中每期利润之和起最关键的作用。

# 决策

## 快速决策流程

MESE 并不存在唯一正确的决策。

下面介绍一套简单、易于上手的决策流程，适用于单人、三到五分钟的快速决策。

拿到一张报表时，先查看公司的存货和 *Unfilled Orders*。在没有囤货计划的情况下，如果有超过产量15%的存货或超过产量5%的UFO，意味着之前对市场形势的判断很可能已经失准。

接着看玩家栏中的情况，尤其要关注两类玩家，其一是自己主要的对手，其二是有数据异于寻常的“搅局者”。

如果可用的现金和贷款限额有限，需要根据实际情况酌情减配。

*RD 在后四期时没有特别考虑时请不要投入*

价格多数情况下，目标是使供需平衡，即既不产生过多存货，也尽量避免 UFO 的出现。新手定价时应偏向存货。

定价的第一步是预测市场走势。

*市场的变化与所有玩家每期平均 RD 的关系最为紧密。前期市场会快速增长，而后期大部分玩家停止投入 RD 后，市场会由盛转衰。*

*MESE 一大吸引人之处在于，它具有“少数占优”的原则，与众不同的决策往往能获得优势，这就带来了博弈的乐趣。价格、Mk 和 RD 都具有竞争性，
越多人来争取，每人分到的份额就越少。因此，最优的决策往往是差异化的，而决策相近的玩家很可能需要一起面对失利。值得注意的是，玩家不仅需
要在战略方向上作出取舍，还需要在考虑为决策保留多少变化的可能性。战略上的应变能力往往是以利润为代价换取的。*

RD 是与战略关联最紧密的决策，通常我们把决策风格分成裸奔、轻 RD、中 RD、重 RD 和超重 RD 五档。在八玩家的标准局中，它们分别对应约 15000 以下、15000 至 25000、25000 至 35000、35000 至 45000、45000 以上的累计 RD。

裸奔通常策略是前期快速获得利润，而中后期领先降价。有时需要舍弃利润，主动降价，来拉低整个市场的利润空间。

轻、中、重 RD 是主流的决策风格，打法是前期累积 RD，中期放 RD 并赚取利润，后期通过比拼细节来攻防。RD 的投入量要根据对市场走势的预判来选择，市场衰落越快，越少的 RD 占优，反之越多的 RD 占优。对于主流 RD 量的决策，Mk 的配合也是非常重要的，通常市场较好、自己的 RD 越多时，投入 Mk 越有可能有利。

超重 RD 是较为反常识的决策方式，与重 RD 相反，它适合于很早衰落的市场，包括后文将提到的恶性竞争等情形。超重 RD 主要的优势来自少数占优原则，垄断地位随期数逐渐形成。常见的对超重 RD 有利的局面是，其他玩家因为市场不佳或设定限制，RD 投入明显较少，导致该玩家一人独得可观的 RD 份额。超重 RD 经常与后期的反弹战术结合。

Mk 与价格是共同配合的，利润较大时，高价格、高 Mk 经常出现，反之则会有大量的低价格、低 Mk 的决策。但由于少数占优，在玩家的 Mk 决策趋同时，少数派会取得优势。例如当整个市场普遍资金紧张时，市场总 Mk 就会较少，此时投入 Mk 虽然会牺牲其它决策，但可能有意想不到的效果。同样，当大量玩家同时堆起 Mk 时，放 Mk 而降价的玩家能取得较高的利润。

*MESE-Next 中无论实际玩家数多少，都是按照八玩家设置参数的*

# 高级话题

*普通玩家可不看此章，上述知识已经足够上手*

## 特殊设定与规则

大部分 MESE 比赛的设定通常会类似于 343 或 262 标准局，手感没有太大差别，只需要根据宏观信息调整决策即可。但是，有一些特殊的设定会大大改变比赛风格。“生产荒废”就是一例，由于后期市场上只有极少的订单，所有公司几乎都将亏本。这类设定中，玩家会分化出前期赚取利润、后期防守，和前期控制成本、后期赶上等不同战略风格。MESE网上局中有极低贷款限额的“生存”局，玩家如果操作不当，可能会出现资金不足以致无法维持生产的情况。除了特殊设定，两期之间的设定突变也能增加局面的复杂度。例如，宏观信息中预告之后某期需求将暴增，往往会使玩家选择囤货。另外，特殊的税率、利率、存货费等，也可以带来特殊的局面和玩法。

在 MESE 比赛中最常见的特殊规则是随机期数，例如在第七期结束后抛硬币决定是否进入第八期。随机期数可以阻止最后一期大幅降价以提高 MPI 的做法出现。一种效果类似的方法是将最后的决策重复提交若干次。另一大类特殊规则主要针对报表和决策的可见性，例如隐藏部分报表内容，甚至隐藏整个报表而要求玩家“盲做”决策。IMese 的报表系统带有隐藏内容的功能。与隐藏对应，也有在特定期数公开所有玩家的决策或报表，甚至是多次决策，每次决策后随机决定是公开所有玩家决策、还是使用当前决策关闭本期这样的规则。

## 恶性竞争

一些 MESE 比赛中，出现过恶性竞争的情况。主要的恶性竞争方式包括同盟和差异化两类。同盟主要指价格同盟，即数名玩家约定在某期（通常发生在中期）低价甩货，使其他不知情的玩家遭遇滞销。差异化则是利用少数占优原则获利，例如反弹和低价之间、高 Mk 和低 Mk 之间的互相配合。差异化决策除了双方获利之外，也有牺牲一方使另一方获利的模式，例如用明显亏本的极低价保护反弹。在比赛中，这类行为是被严格禁止的。尤其是带牺牲性质的差异化决策，可能导致玩家被直接禁止决策。

## MESE-Realtime

MESE-Realtime 是基于 MESE-Next 创建的一种新玩法。MESE-Realtime 中，玩家不再按期决策，而是随时都可以修改自己的决策。无论玩家是否、何时提交决策，每秒都将进行百分之一期（约合现实中的 22 小时）的模拟。

由于模拟近似于连续，玩家可以做到几乎没有存货和 UFO，跟踪也变得非常容易。另一方面，MESE-Realtime 允许玩家进行试错，即试验性地调整决策，寻找最优的方案，而不会产生太大的损失。因此，MESE-Realtime 中大部分玩家的表现将很接近，这对玩家的操作精细度和反应速度提出了较高的要求。

MESE-Realtime 中的经验对 MESE 玩家也有参考价值，例如 MESE-Realtime 的中期，最优的价格经常会停留在 40 这条特殊的分界线上，这在 MESE 的一些局面中同样适用。



*本文由Ling zeheng(Matt)重新修订自[hczhcz/mese-tutorial](https://github.com/hczhcz/mese-tutorial)
为方便非圈内玩家对于MESE的使用与完善而设。*
