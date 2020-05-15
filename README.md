LibUIDK是什么
---

简单来说，LibUIDK是用来开发QQ、360安全卫士那样的漂亮软件界面的。  
LibUIDK原来是商业界面库，2019年9月8号开源。是专业开发Windows平台下图形用户界面的开发包，也是国内第一款商业的高级界面开发工具。  
该开发包基于Microsoft的MFC库。使用此开发工具包可轻易把美工制作的精美界面用Visual C++实现，由于LibUIDK采用所见即所得的方式创建产品界面，所以极大的提高了产品的开发速度，并大增强图形用户界面(GUI)的亲和力。  
LibUIDK还可以使您的软件轻松具有当今流行的换肤功能，以提高产品的竞争力。
在很多公司或个人研发换肤产品的时候，我们就推出了第一款界面开发工具。与换肤工具不同的是，界面工具贯穿整个项目开发周期，整个项目的界面，都可由LibUIDK完成。LibUIDK提供了比换肤工具彻底的多的界面自由定制功能。

LibUIDK的目标用户:
---
任何使用MFC的程序开发人员。

为什么使用LibUIDK:

* 加快开发速度

    开发一个中等规模的UI产品, 大约需要一个熟练掌握MFC的开发人员写三个月(并且还不包含Debug的时间). 而使用LibUIDK, 可以提高数百倍的效率, 一般几个小时就可以完成. 这是由于LibUIDK所见即所得的开发方式，以及引入的窗口类向导，使开发效率的提升突破您的想象。这不仅节约了时间成本, 还节约了财力成本. 最重要的是, 您可以快速推出产品, 从而使您在与您的竞争对手的较量中处理优势地位。 
	LibUIDK使您的开发由手工作坊式变为机械化大生产式。
	
* 节约成本

	使用LibUIDK开发产品，不仅所需时间大为减少， 所需人力也大减少，通常情况，只需要1个初级程序员来开发界面。所以会使贵公司在人力资源方面减少投入。
	
* 减小程序Bug数量

	一般一个中等规模产品的UI大约有5000-10000行代码, 按每100行代码1个Bug的概率, 可能整个UI有50-100个Bug. 而LibUIDK经过多年的发展和数万用户的使用, 系统已经非常稳定可靠, 所以可以大幅减少您的产品的UI部分的Bug数量，节约大量的Debug时间。
	
* 学习门槛低

	由于LibUIDK提供了所见即所得的界面开发工具UIShop，使得LibUIDK学习门槛大降低，低到甚至非程序员（如美工、产品经理等）都可以完成一些界面开发。使用LibUIDK，界面90%的开发过程，都是在UIShop中进行。而UIShop，不要求使用者具有程序员背景。只有界面在运行中需要交互时，才需要程序员介入。
	
* 完全基于MFC

    基于MFC，而不是由我们自己设计控件的好处是显而易见的：   
    1. 学习成本极低  
    大部分MFC程序员不经过培训可以直接使用LibUIDK开发界面。即使需要培训，LibUIDK全部培训时间，也仅需要1---2个小时；
    由于LibUIDK基本上仅对MFC控件的外观进行修改，不涉及控件功能，所以对于控件的操作，仍然是调用原MFC控件类的相关接口，可以方便的从MSDN或网络上获得及时帮助  
    2. 后期维护成本低  
    程序员以前所学的所有关于编程的经验，仍然可以运用到LibUIDK上，并且MFC程序员是一支庞大的队伍，很容易找到相关人才。  
    3. 风险可控---有问题可以绕过去    
    即使在没有我们支持的情况下，程序员也可以利用子类化、替换窗口过程等技术来控制控件；使用MoveWindow移动控件；使用ShowWindow隐藏控件；或者用您自己编写的控件替换LibUIDK控件。LibUIDK是开放式平台，与直接使用MFC一致，您可以选择使用或部分使用LibUIDK中的控件，也可以任意使用第三方控件。不会由于使用LibUIDK导致在开发过程中，引入无穷无尽，莫名其妙的各类问题，使用LibUIDK与使用标准MFC开发项目对风险的期望值是相同的。  
    4. 兼容性好  
    LibUIDK完全由MFC开发，除了MFC没有的控件外，其它控件都是在MFC控件类基础上派生的，所以完全杜绝了自己模拟控件模拟不全的情况发生。因为很多MFC标准控件的细节不容易被发现，更不容易被全部发现，模拟时，总会有或多或少的遗漏。一旦用户恰好需要那个未模拟的形为，就得修改界面库，重新模拟，模拟需要时间去开发、测试。甚至可能由于时间关系，导致客户项目流产，模拟控件的代码健壮性恐怕也没有微软的成熟控件强。  
    5. 移植成本低，与原有项目无缝集成  
    如果原项目采用MFC来开发，那么在移植到LibUIDK项目时，只要保持新旧工程界面控件类型、ID一致，那么旧工程中的相关代码，仍然可以应用到新的工程中，而不需要重写一套。  

* 容易对客户的需求做出改变  

	一个产品在开发过程中, 常常会根据客户的要求, 进行反复修改. 大量的修改常令程序员感到无所适从. 由于LibUIDK采用所见既所得的方式生成代码, 所以修改起来非常方便。
	
* 贵公司的GUI开发能力可能不足

	如果贵公司的专业领域不在GUI的开发, 但临时有项目需要较高水平的GUI规格. 那您可以使用LibUIDK来进行开发.
