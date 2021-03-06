## 第一章	焦油坑   
程序变成编程系统产品，它的成本高达九倍。然而，只有它才是真正有用的产品，是大多数系统开发的目标。
编程的乐趣：1.创造事物的快乐。2.来自开发对别人有帮助的东西。3. 将各个零件组装起来并精确运行得到预先想要得到的效果。4.学习的乐趣。5.代码这种介质可以使程序员轻松的创造自己的“城堡”。总之编程非常有趣，在于它不仅满足了我们内心深处进行创造的渴望，而且还愉悦了每个人内在的情感。
编程的苦恼：1.追求完美。2.寻找bug。3.产品完成时已经过时的威胁。4编程人员很少能控制工作环境和工作目标。实际的权威来自于每次任务的完成。5.常常需要依赖别人糟糕的程序和文档。

## 第二章	人月神话
在众多软件项目中，缺乏合理的时间进度是造成项目滞后的最主要原因，它比其他所有因素加起来的影响还大。
导致这种灾难的原因：
1.	乐观主义：编程人员潜在认为程序会一切运行良好，但我们的构思总会存在缺陷，因此总会存在bug，在大型的编程任务中一切正常的概率非常小甚至接近于无。
2.	人月：作者认为用人月作为衡量一项工作的规模是一个危险和带有欺骗性的神话。 它暗示着人员数量和时间是可以相互替换的。人数和时间的互换仅仅适用于以下情况：某个任务可以分解给参与人员，并且他们之间不需要相互的交流。这在割小麦或收获棉花的工作中是可行的；而在系统编程中近乎不可能。系统编程在增加人力的时候需要额外增加的交流成本，这种交流和沟通的工作量巨大，在相同人月下，增加更多的人手实际上会增加时间进度而不是减少。
3.	系统测试：传统项目往往不重视测试，不安排足够的时间但实际中测试占用了大量时间，因此作者提出1/3 计划 1/6 编码1/4 构件测试和早期系统测试 1/4 系统测试
4.	空泛的估算：产品经理要对自己的估算自信，避免为了顾客的期望的日期而造成不合理的进度安排
5.	重复产生的进度灾难：作者认为向进度落后的项目中增加人手，只会使进度更加落后

## 第三章	外科手术队伍
优秀的程序员和较差的程序员之间生产率的差异惊人
对于效率和概念的完整性来说最好由少数干练的人员设计和开发。
对于大型系统，需要大量人手来满足产品在时间上的要求
为了调和上述矛盾Mills提出了一种提出了一种类似外科手术队伍组建方式即十人组成的团队由一个人来完成问题的分解，其他人给予他所需要的支持以提高效率和生产力。
对十人的团队进行扩建仅仅对 “外科医生”进行协调即可

## 第四章	贵族专制,民主政治和系统设计
作者主张在系统设计中，概念完整性应该是最重要的考虑因素，概念的完整性要求设计必须由一个人或者非常少数由默契的人员来实现。对于大型的项目将设计方法，体系结构方面的工作与具体实现相分离是获得概念完整性的强有力方法。
外部体系结构规定实际上是增强小组的创造性，在毫无限制的实现小组中会产生大量的想法和争议而忽视了具体实现。

## 第五章	画蛇添足
实际情况中，尽早的交流和持续沟通能使结构师有较好的成本意识，以及使开发人员获得对设计的信息。
当实现产品时，某些次要特性的修改会造成意料不到的成本开销。
第二个系统是设计师们所设计的最危险的系统。过分的设计，添加很多不需要的功能

## 第六章	贯彻执行
为了开发人员准确理解并实现架构师的决策以及架构师小组内的概念一致性，作者提出了以下办法
1.手册或者书面规格说明是非常必要的。
2.形式化定义精确但难以理解，规格说明要形式化定义要与记述性文字相结合。
3.周会和年会是必要的。
4.当存在多重实现时如实地遵从手册更新机器所造成的延迟和成本的消耗，比根据机器调整手册要低。
5.一种有用的机制是由结构师保存电话日志。日志中，他记录了每一个问题和相应的回答。每周，对若干结构师的日志进行合并，重新整理，并发布给用户和实现人员。
6.设立测试小组是使设计决策得以贯彻执行的必要手段，同样也是需要尽早着手，与设计同时实施的重要环节。 

## 第七章	为什么巴比伦塔会失败
巴比伦塔可能是第一个工程上的彻底失败，但它不是最后一个。交流和交流的结果—组织，是成功的关键。交流和组织的技能需要管理者仔细考虑，相关经验的积累和能力的提高同软件技术本身一样重要。
作者总结巴比伦塔项目失败的原因是缺乏交流和缺乏组织，因此作者认为在软件项目中有效的交流和组织是十分重要的，项目工作手册作为成员交流的成果并且保证了项目的概念一致性。在大型编程项目的组织架构中，为了减少交流的数量提出了树状管理结构。作者建议在小型团队以技术主管为主产品负责人为辅，大型团队中产品负责人为主技术主管为辅。

## 第八章	胸有成足
对编码时间的估计使用时间的比值反推各个任务的时间是不合理的并且很可能会带来糟糕的后果
不能以小型程序的工作量来估计大型编程系统产品，两者之间的关系不是线性的。
使用适当的高级语言，编程的生产率可以提高 5 倍。

## 第九章	削足适履
开发人员必须设置规模的目标，控制规模，考虑减少规模的方法。同任何开销一样，规模本身不是坏事，但不必要的规模是不可取的。
仅仅对核心程序设定规模目标是不够的，必须把所有方面的规模都编入预算。在指明模块有多大的同时，确切定义模块的功能。开发人员从系统整体出发，面向用户。

## 第十章	提纲挈领
项目经理的任务是制订计划，并根据计划实现。但是只有书面计划是精确和可以沟通的。计划中包括了时间、地点、人物、做什么、资金。这些少量的关键文档封装了一些项目经理的工作。如果一开始就认识到它们的普遍性和重要性，那么就可以将文档作为工具友好地利用起来，而不会让它成为令人厌烦的繁重任务。通过遵循文档开展工作，项目经理能更清晰和快速地设定自己的方向。

## 第十一章	未雨绸缪
软件开发过程中一定会出现抛弃最初开发的实验性系统因此一定要为舍弃而计划
变化是与生俱来的，不是不合时宜和令人生厌的异常情况，开发人员是交付的用户满意度而不仅仅是有形的产品。
程序后期维护的成本惊人，在解决bug的同时会产生新的bug，所有的修改都倾向于破坏系统的架构，增加了系统的混乱程度

## 第十二章	干将莫邪
在软件项目中开发和维护公共的通用编程工具的效率更高。作者建议在团队中加入工具管理人员来统一管理通用工具并且对此不能吝啬人力和物力。
目标机器的使用时间分配成连续的块，机器的利用程度会降低但生产率却能提高。不在使用机器的时间块中的小组可以从事文档书写工作。
作者在开发OS/360中使用了程序库和程序库的管理，是现在版本控制工具的雏形，该工具使得程序是可控的并且程序的开发进展变得正式。
高级语言和交互式编程工具极大的提高开发的效率。

## 第十三章	整体部分
开发一个能用的系统容易，但开发一个可靠好用的系统并不容易。本章作者讨论了如何设计一个可靠的系统，首先是前面已经说过的程序开发要保持概念完整性，其次是编写任何代码之前，规格说明必须交给外部测试小组进行测试。作者又提到了自上而下的设计即将系统开发划分为体系结构设计，设计实现和物理编码实现以及结构化编程的概念。无疑这些思想在当时都是比较先进的。并且这些概念现在也有应用。作者再一次强调了测试的复杂性和困难度，作者认为在系统集成测试中使用经过调试的构建单元比“合在一起尝试”更节省时间。可以在集成测试中搭建辅助测试平台，简单来说就是现在测试中使用的桩模块和驱动模块。还有控制变更，一次添加一个构件以及阶段化、定期变更等方法来进行集成。

## 第十四章	祸起萧墙
项目进度大幅度落后的原因往往不是重大灾害造成的而是一天一天进度落后造成的。项目进度表的每一件事被称为“里程碑”。里程碑的选择只有一个原则，那就是，里程碑必须是具体的、特定的、可度量的事件，能够进行清晰定义。必须关心每一天的滞后，他们是大灾祸的基本组成部分。计划偏离时一线经理的利益和老板的利益是内在冲突的，但为了解决计划偏离就必须把问题暴露给老板，作者提出了两种办法一是老板和一线经理应该减少角色的冲突，在经理可以处理的情况下老板不要插手，二是以周和月为单位进行项目评审，评审中使得每个人都知道问题的所在，而产品构件经理应准备解释延迟的原因，什么时候结束，采取的步骤和需要的任何帮助——老板提供的，或者是其他小组间接提供的。

## 第十五章	另外一面
书写文档是必要的即使是完全开发给自己使用的程序。因为记忆衰退的规律会使用户－作者失去对程序的了解，于是他不得不重拾自己劳动的各个细节。不同用户需要不同的文档作。对使用程序的用户来说需要从文档中了解目的、环境、范围、输入输出等信息这份文档的绝大部分需要在程序编制之前书写。
对验证程序的用户来说需要从文档中了解程序边界值进行测试。
对于修改程序的用户来说需要从文档中了解程序详细的实现细节包括结构图、算法描述、接口描述等。
流程图是被吹捧得最过分的一种程序文档。事实上，很多程序甚至不需要流程图，很少有程序需要一页纸以上的流程图。
作者提倡自文档化的程序即把文档整合到源代码。这对正确维护是直接有力的推动，保证编程用户能方便、即时地得到文档资料。

## 第十六章	没有银弹
在未来的十年内，无论是在技术还是管理方法上，都看不出有任何突破性的进步，能够保证在十年内大幅度地提高软件的生产率、可靠性和简洁性。软件活动包括根本任务和次要任务，软件近年来出现的进步都在次要任务上但除非次要任务占了所有工作的9/10，否则即使全部次要任务的时间缩减到零也不会带来生产率数量级上的提高。
作者认为不是软件发展太慢而是硬件发展地太快。软件开发中困难的部分是规格化、设计和测试这些概念上的结构，而不是对概念进行表达和对实现逼真程度进行验证。如果这是事实，那么软件开发总是非常困难的。天生就没有银弹。软件开发具有复杂度、一致性、可变性和不可见性等特点。
针对软件开发中的根本问题的解决方法作者认为目前有购买而不是开发软件、需求精炼和快速原型、增量开发、培养卓越的设计人员这几种。

