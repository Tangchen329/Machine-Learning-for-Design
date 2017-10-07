# Literature Review of Machine Learning for Design


-------------------------------------------------------------------


## Machine Learning Application in Design Process & Tools

### Reference List
* 教机器画画  [Teaching Machines to Draw](https://research.googleblog.com/2017/04/teaching-machines-to-draw.html)  Thursday, April 13, 2017  Posted by David Ha, Google Brain Resident 
   
     > 抽象的视觉传达是人们传达彼此想法的关键部分。 从小时候开始，孩子们培养了用少量笔画来描绘物体甚至是情感的能力。 这些简单的绘画可能不像照片所捕获的现实那样，但它们告诉我们一些关于人们如何表现和重建周围世界的图像的方式。在论文《草图的神经表示》（《A Neural Representation of Sketch Drawings》）中，提出了一个生成递归神经网络(recurrent neural network)，能够产生普通物体的草图，目的是训练机器以类似于人类的方式绘制和概括抽象概念。我们在手绘草图的数据集上训练我们的模型，每一个草图代表一系列控制钢笔的动作：哪个方向移动，什么时候提起钢笔，何时停止画画。在这样做的过程中，创建了一个潜在的应用模型，从帮助艺术家的创作过程到帮助学生如何绘画。除此之外，即使在最简单的用例中，图案设计师可以通过sketch—RNN产生大量相似但独特的设计，用于纺织品或墙纸版画。如果将这一结果推广到应用程序中，这些应用程序可能有助于设计师创造性地设计出能与目标受众产生更多共鸣的抽象设计。也可以利用该神经网络来预测不同可能的最终草图，这种技术可能会给艺术家的创作过程带来帮助，因为系统可以推荐多种可选择的其他方式来完成一个不完整的草图。该系统中，可以看到如何使相同的圆形和方形的人物成为各种蚂蚁，一部分火烈鸟、直升机、猫头鹰、沙发甚至油漆刷。通过使用各种不同的模型来训练不同的对象，设计师可以探索创造性的方法来向观众传达有意义的视觉信息。这些模型还会带来许多令人兴奋的，应用在各种不同的方向的新创意。同时也还可以作为一种工具，帮助我们提高对自己创造性思维过程的理解。

     > Google Creative Lab进行的一个互动的网络实验——让人们跟一个名叫sketch-rnn的神经网络模型一起画画。在这之前通过从[Quick，draw!](https://quickdraw.withgoogle.com/data/)收集的数百个涂鸦对这个神经网络进行了训练。一旦用户开始绘制一个对象，sketch-rnn将提供许多可能的方法来继续绘制这个对象，可以在这里尝试[sketch_rnn_demo](https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html).
     > 1. 因为该神经网络是基于其他人绘制的内容进行训练的，所以也可以在这种演示环境下看到机器预测下你的图形的未来样貌，可以用来满足自己的好奇心，探索不同的可能性。[ Multi Predict](https://magenta.tensorflow.org/assets/sketch_rnn_demo/multi_predict.html)
     > 2. 除了预测不完整的图形之外，sketch-rnn也可以从一个图形变换到另一个图形。在插值演示中，你可以使用屏幕两侧的按钮来随机生成两个图像。模型将绘出多种新的绘图，它被认为是两个原始图纸之间的插值。[ Interpolation Demo](https://magenta.tensorflow.org/assets/sketch_rnn_demo/interp.html)    
     > 3. 该模型还可以模仿你的风格并生产类似的涂鸦。在Variational Autoencoder演示中，你将绘制一个指定对象的完整图形。在左侧区域绘制完草图后，点击自动编码按钮，模型将在右侧较小的框中绘制类似的草图。神经网络将尝试模仿你的绘图。您可以尝试不是您应该绘制的类别的绘图对象，并查看模型如何解释您的绘图。例如，尝试画一只猫，并有一个模型训练来绘制螃蟹，生成类似猫的螃蟹。[ Variational Autoencoder](https://magenta.tensorflow.org/assets/sketch_rnn_demo/multi_vae.html)

      * Project List
         * 跟神经网络一起画画  [Draw Together with a Neural Network](https://magenta.tensorflow.org/sketch-rnn-demo) Thursday, April 13, 2017  Posted by David Ha, Google Brain Resident  
         * [Sketch-RNN Demos - Draw together with a neural network](https://aiexperiments.withgoogle.com/sketch-rnn-demo)
         * [Sketch-RNN Demos](https://magenta.tensorflow.org/assets/sketch_rnn_demo/multi_vae.html)
         * [Google Creative Lab](https://experiments.withgoogle.com/ai?tag=TensorFlow) 
     
      * 延伸阅读
         * [Google Creative Lab](https://experiments.withgoogle.com/ai?tag=TensorFlow)
         * [ai-duet](https://experiments.withgoogle.com/ai/ai-duet/view/)
         * 机器学习你如何弹钢琴[sound-maker](https://experiments.withgoogle.com/ai/sound-maker/view/)用机器学习的各种乐器声音的混合体来创作音乐（将声音转化为更加抽象的数字表达之后再进行组合)
         * [handwriting](https://distill.pub/2016/handwriting/)
        
*  [Webs of Influence: The Psychology of Online Persuasion, 2nd Edition](https://www.safaribooksonline.com/library/view/webs-of-influence/9781292134628/?imm_mid=0f4ac0&cmp=em-design-na-na-newsltr_20170725_test)

* 谷歌AutoDraw 让每个人都是设计师 [Google AutoDraw uses machine learning to make a designer out of anyone](http://www.androidpolice.com/2017/04/11/google-autodraw-uses-machine-learning-make-designer-anyone/)by Scott Scrivens

* 将机器学习应用到设计上将会怎样？[What Happens When You Apply Machine Learning To Logo Design](https://www.fastcodesign.com/3058852/what-happens-when-you-apply-machine-learning-to-logo-design)
* 将机器学习应用于设计  [Designing with Machine Learning](https://www.wework.com/zh-CN/blog/posts/designing-with-machine-learning)   by Nicole Phelan
* Adobe将AI应用于网页自动设计，你感受到危机感了吗？  BY NEAL UNGERLEIDER  [Adobe Is Building An AI To Automate Web Design. Should You Worry?](https://www.fastcodesign.com/3068884/adobe-is-building-an-ai-to-automate-web-design-should-you-worry)


* 机器学习将为设计带来什么 [What Machine Learning Will Do For Design](https://medium.com/emergent-future/what-machine-learning-will-do-for-design-42661096f21) by Eve Weinberg

     > 这是智能设计团队的ITP计划（ITP是一个为期两年的,设在艺术学院的研究生课程：课程使命是通过探索通信技术的使用来探索如何利用技术让艺术更好地融入人们的生活。）：如何利用有才华的设计师和机器学习设计工具的协同来探索设计的案例。 智能设计团队由 [《Machine Learning forDesigners》](https://www.oreilly.com/learning/machine-learning-for-designers)的作者[Patrick Hebron](http://www.patrickhebron.com/)和[《Programming Design Systems》](https://programmingdesignsystems.com/)作者[Rune Madsen](https://runemadsen.com/)领头。 Patrick进行关于机器学习的指导，Rune进行关于设计系统的指导，引导着小组的表述和思考过程。

     > 项目的设计挑战：设计一个logo, 围绕一个具体的logo设计项目展开，展示了在有无机器学习系统合作情况下的整个设计流程的差异。机器学习在收集资料，排版，设计调整的过程中都为设计师提供了帮助。
     
     > 1. 收集资料
     
     > 您首先在客户简要介绍表中键入，告诉它您希望看到多少参考资料，花费多长时间查找每个参考，并让计算机处理这些信息。它搜索的数据库包括Dribbble和Pinterest的。 会产生一个可供选择的参考网格。 把参考数限制在40，但是其中30个不太好，所以你选择你喜欢的只有10，再运行一次。可以向电脑解释为什么你喜欢你选择的10个？ 您有几种选择，从离散到非离散。 在离散的一边，你有一些像单选按钮：
     > ◎我喜欢排版。 ◎我喜欢对比。 ◎我喜欢玩耍
     > 在非离散的会话方面，你有自然语言处理。你可以谈论每一个选择。你选择完反馈方法之后，可以等待更多的参考。在几分钟的时间，你收到100多张参考图片。你喜欢其中的20个，所以现在你有一个更具体的30个图像的数据集来完善你的资料库。你可以进一步描述为什么你喜欢这些图像，冗长或简略。多次重复来让机器更好的理解你的选择。

     > 2. 排版
     
     > 电脑会显示一些字体，全部都应用在客户的名称上，并根据需要选择您喜欢的字体，并进行多轮修订。

     > 3. 设计调整
     
     > 你设计好之后，现在，由于这是您与计算机的第一个项目，它不知道您的风格或倾向，在未来的项目中将根据你曾经的设计对不同审美维度对你的设计风格进行加权。 它是审美的维度。设计师可以滑动样式参数（在左上方），并可以实时更新标志（右下方）。 设计师可以手工挑选图标和字体。 这3个类别中的任何一个需要被锁定，也是可以的。 例如，您有一种喜欢的字体，但您想将样式从“男性”更改为“女性”，不希望更改字体，就可以将字体锁定。
     
     > ![shejitiaozheng](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/7-What%20Machine%20Learning%20Will%20Do%20For%20Design/7-gDJM4PkGDrxogklI7m2cLg.png)
设计调整界面

     > 总结：机器学习不是好的设计的灵丹妙药，也不是工作的破坏者。它仅仅是一种新工具。设计人员可以通过这个新的工作流程更舒适，在设计过程中，他们会更多的时间享受认知和创造性的过程，更少的时间待在设计创作的沉闷中。



      * Project List
         * 演示视频 [Video of ‘99designs.com’ onboarding](https://vimeo.com/185045206)
        
        
        
* 在机器学习的时代重新思考设计工具 [Rethinking Design Tools in the Age of Machine Learning](https://medium.com/artists-and-machine-intelligence/rethinking-design-tools-in-the-age-of-machine-learning-369f3f07ab6c)

* 机器学习：AI和设计的光速发展  [Machine Learning: The Speed-of-Light Evolution of AI and Design](https://redshift.autodesk.com/machine-learning/) by JEFF WALSH  
*  以人为中心的机器学习——聚焦用户的重要7点  [Human-Centered Machine Learning - 7 steps to stay focused on the user when designing with ML](https://medium.com/google-design/human-centered-machine-learning-a770d10562cd?imm_mid=0f4f22&cmp=em-design-na-na-newsltr_20170801)   By Josh Lovejoy and Jess Holbrook
*  是时候进行机器学习中的设计演化了！——为何最好的时代还没到来。 [It’s Time for a Design Evolution in Machine Learning - Why the Best is Yet to Come](https://uxdesign.cc/its-time-for-a-design-evolution-in-machine-learning-6bfe7da3dcef). by Florian Oefner
*  Sensei：Adobe将机器学习和设计工具添加到 Creative Cloud [Bow to your Sensei! Adobe adds machine learning and design tool to Creative Cloud](https://www.theregister.co.uk/2016/11/02/adobe_updates_creative_cloud_with_sensei_machine_learning_and_new_3d_design_tool/) By Tim Anderson 2 Nov 2016 at 14:30
*  IntuiFace：如何使用机器学习来帮助创建交互式和连接的数字体验  [Machine Learning and Design in IntuiFace - How IntuiFace uses machine learning to aid the creation of interactive and connected digital experiences](https://www.intuilab.com/machine-learning)
*  自动化将淘汰平面设计师？未来该选择什么职业？[Automation Threatens to Make Graphic Designers Obsolete - So what kind of career should you expect to have in future?](https://eyeondesign.aiga.org/automation-threatens-to-make-graphic-designers-obsolete/) by Rob Peart
*  机器学习如何加速设计周期 [HOW MACHINE LEARNING CAN SPEED UP YOUR DESIGN CYCLE](https://www.maximintegrated.com/en/design/blog/machine-learning-can-speed-up-design-cycle.html) by Christine Young
*  [设计与AI的现在Ⅰ：设计了1.7 亿个 banner的阿里鲁班](https://zhuanlan.zhihu.com/p/26563244) 














-------------------------------------------------------------------



## Design Products & Services with AI & Machine Learning Embedded in

### Reference List
* 机器学习和交互设计 [Machine Learning and UX](https://medium.com/designer-hangout/machine-learning-and-ux-c28725b5f3a)

     > 与目标群体相对立的个人概念，它定义了用户体验与机器学习的必然联姻。
   
     > 设计师应该与机器学习一起通力合作服务用户————目前，设计师可以创造出引人注目的群体体验，但不考虑个人。针对个体的体验设计，需要机器学习来协助。![1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/9-machine%20learning%20and%20ux/2.png)可以将聚类，用于分组数据的无监督机器学习过程。在未来我们会看到专门为设计师洞察数据生成的工具，现在的好的解决方法就是设计师与团队和公司的数据科学家合作将双方的发现和能力融入设计中。
   
     > 设计师和数据科学家生活在一个意想不到的维恩图中。我认为这些团体的凝聚力会产生有趣的和令人惊喜的用户体验，当然在不久的将来（看不见的设计，由Amber Cartwright提出的一个概念，[进一步的页面]，似乎沿着这些线路的想法）。
     
     > 对设计师而言的机会点:很明显，我认为机器学习只会增加未来设计师的工作量，可以使用机器学习来帮助我们理解这一切。基于用户数据提取和提出见解的系统将变得正常和必要，特别是当数据集变得更大细粒度更高时。智慧的界面对于人类来说是很自然的：对数据集的自然语言查询是我们想看到的，甚至可能以识别语音的机器人（如Jarvis）的形式出现。![1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/9-machine%20learning%20and%20ux/3.jpg)我希望看到这些机器人是专门设计和推理设计者关心的东西，比如用户反馈的情绪和可用性测试中特定疼痛点的提取，因为SQL查询和Python脚本的能力有限。
   
     > 我们需要像人类那样能自然互动，但像机器一样思考的系统。这将有助于消除许多设计师在面对代码墙时所体验到的交互的心理障碍，同时还为我们提供了专门针对我们需要的代码的功能。在大多数人直接打开Google去搜索答案的时候，对于设计师而言，现在是有机会定义这种关系将如何发展的时机。这是一个未经探索的边界正在等待着，不是被发现，而是由你和我去创造。  
   
      > 案例：迪士尼通过[腕带来为用户提供定制化的服务](https://www.wired.com/2015/03/disney-magicband/)。腕带通过收集大量主题公园游客的信息，再将相关的数据传送给员工，例如你的名字或者桌号，没有任何的物理接触和语言交流，通过设计让公园的参与感更强。![1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/9-machine%20learning%20and%20ux/1.jpg)主题公园的设计者Dave Cobb 称未来可能会生成一个基于长时间记录的系统，，预期设计创造出每个人一个完全不同的体验。如果数据具体到一个人的地理、社会、历史甚至遗传背景 - 然后机器可以创建一个完全独特的和个人的经验。
      

* 关于机器学习的好的产品设计案例有哪些？ [Any good Product Design case studies that involve Machine Learning?](https://www.designernews.co/stories/75495-any-good-product-design-case-studies-that-involve-machine-learning)
    * [用可视化介绍机器学习](http://www.r2d3.us/%E5%9B%BE%E8%A7%A3%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/)

    * [Google CEO technical assistant on building AI products](https://vimeo.com/181330432)

    * [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471)

    * [Designing Machine Learning Models](https://medium.com/airbnb-engineering/designing-machine-learning-models-7d0048249e69)
    
* 机器学习在产品设计领域有多大影响力？ [How influential is machine learning in the field of product design?](https://www.quora.com/How-influential-is-machine-learning-in-the-field-of-product-design)
* 设计师需要了解的机器学习内容 [What designers need to know about machine learning](https://hackernoon.com/what-designers-need-to-know-about-machine-learning-109a12fdd3af)

* 对设计师有帮助的机器学习的应用 [Applications Of Machine Learning For Designers](https://www.smashingmagazine.com/2017/04/applications-machine-learning-designers/) By Lassi Liikkanen


* 将机器学习应用到设计上将会怎样？[What Happens When You Apply Machine Learning To Logo Design](https://www.fastcodesign.com/3058852/what-happens-when-you-apply-machine-learning-to-logo-design)

     > 神经网络的兴起和生成式设计为设计师创造了新的机会。在[Mark Maker](http://emblemmatic.org/markmaker/#/about)（一个自动化生成logo系统）中，输入一个词。该系统然后使用遗传算法genetic algorithm，一种模仿自然选择的程序，以产生无止境的连续的标志。 当你喜欢一个标志，你点击一个爱心，它告诉系统生成更多的标志。通过喜欢足够的标志，概念里Mark Maker可以最终生成一个适合您需求的产品，而无需使用人类设计师。Mark Maker通过将每个设计打破一半来创建其标志，使其包含基本设计和特色元素。

     ![gif1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/23-what%20happens%20when%20you%20apply%20ml%20to%20logo%20design/3058852-inline-i-1-this-bot-will-generate-millions-of-logos-until-you-find-the-perfect-one-copy.gif)
     ![p1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/23-what%20happens%20when%20you%20apply%20ml%20to%20logo%20design/屏幕快照%202017-08-29%20上午10.51.30.png)

* 为什么设计师和产品经理需要懂一点机器学习 [Why Should Designers And Product Managers Know About Machine Learning?](https://www.forbes.com/sites/quora/2017/04/07/why-should-designers-and-product-managers-know-about-machine-learning/#72cde9e07b28)
* 对机器学习系统的用户体验进行设计[Designing the User Experience of Machine Learning Systems](https://mikek-parc.github.io/AAAI-UX-ML/)

* [为男人们提供个性化服饰搭配，英国电商 Thread 获 800 万美金 A 轮融资](https://36kr.com/p/5036946.html)

     > 电商平台 Thread 试图采用造型顾问+机器算法的方式，来为想要穿得得体一些，却又不爱逛街的男士提供个性化的商品建议。

     > 网站首先会让用户填写一个问卷，问卷内容包括：你平时会出现在哪些场合？你钟爱的品牌和风格？尺码，价格，色彩？ 随后，Thread 的造型师通过了解问卷获得的数据和上传的照片，来得出适合顾客的大致搭配方案，随后机器算法将按照造型师给出的方案导出顾客所选价格范围内最合适的商品。Thread 在购买评价上设置了多个具体的选项，比如”我不喜欢领子的设计”、“我不喜欢衣服的面料”。目的是通过这些反馈信息，进一步优化下次的商品推荐结果，让平台变得越来越“懂”你。每周，Thread 都会发送一批新的个性化商品促销信息给用户，同时网站的造型师也在线上随时待命、提供一对一的咨询服务。

     > 由于涉及SKU众多，且多为非标品，Thread 并未采用自营“重”模式，而是多品牌达成合作关系，由官网直接发货。

![thread](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/37--%20Thread/屏幕快照%202017-09-19%20上午12.26.11.png)







-------------------------------------------------------------------


## Other Topics related to ML and Design 

### Reference List
* [Machine Learning for Designers](http://www.oreilly.com/design/free/machine-learning-for-designers.csp)

    * [Machine Learning for Designers](http://pan.baidu.com/s/1eSOUudW)

    * [Machine Learning for Designers 解构脑图](https://zhuanlan.zhihu.com/p/27045885)

* John Whalen应用脑科学进行设计   [John Whalen on using brain science in design](https://www.oreilly.com/ideas/john-whalen-on-using-brain-science-in-design?imm_mid=0f4f22&cmp=em-design-na-na-newsltr_20170801)By Nikki McDonald. July 27, 2017 
    
    -  主题：人类经验背后的“六感”／为什么设计师要理解脑科学／以及人们真正需要的是什么？为什么设计师要理解脑科学?

      > 通过了解什么吸引大脑的注意力，如何把握事物的记忆，如何做出决策，以及情感如何控制决定…来确保设计师们真正的以用户为中心，探索用户在挑选产品和如何使用上的思维框架。

    - 每个人类经验背后的“六感”

      1- Vision,Attention视觉和注意力 
      2- 记忆和你所有先入为主的想法和你认为的世界的工作方式 
      3- 方向感 ，是你在空间中移动的能力，例如在虚拟世界的方向感 
      4- 语言，掌握不同语言术语的能力 
      5- 情感内容。 
      最后，所有一切都是为了帮助你做出决定和解决你的世界的问题。

    - 我们在语音的助手身上寻找什么？

      > 通过研究不同人群对使用Siri,Cortana，Alexa和Google Assistant时的感觉：“你最想买哪款回家？你个人倾向于哪款？”Google Assistan第一，因为它在回答问题方面做得最好，，亚马逊echo的Alexa第二受欢迎，但是它在回答问题上是所有语音助手中最不成功的。事实证明，选择Google Assistant的人“只是想快速知道答案”。而喜欢Alexa的人则说：“它回答问题的方式跟我问它的方式一样 ”或者，“我喜欢可以来回交谈，这让我觉得我正在和一个人说话。”所以，Alexa对他们来说真的有人性化的品质。所以对于产品测试，并不仅仅是要“百分比正确”，还需要考虑人的组成部分，这种人文素质的重要性有多大呢？

    - AI系统应该如何预测……什么时候会变得令人恐惧？

      > 研究中，我们提出了一些问题：“你希望机器在多大的程度上了解你？”例如，亚马逊知道您多久购买牙膏，所以可能预测牙膏有没有用完。它可以在星期二随机问“天哪，尼基，你想要更多的牙膏吗？设备可以有各种各样的方式来增强你的认知 ;在某些方面，我们已经在使用电脑，每次使用Google地图，或者用Google价格来选择某些东西。我们习惯机器有这样的功能但并不习惯它预测我们的行为。我们习惯于问一个问题，然后收到答案，而不是让机器预期我可能需要的一个答案。

* 只需5步，以设计师思维看待机器学习 [5 Steps to Thinking Like a Designer in Machine Learning](http://machinelearningmastery.com/5-steps-to-thinking-like-a-designer-in-machine-learning/)  by Jason Brownlee on March 26, 2014 in Machine Learning Resources

   > 好的数据科学家不仅是统计学家、领域专家和机器学习黑客，还需要是一名优秀的设计师。设计的第一要义：人。设计师是以人为本的，需要从用户的角度去考虑实际项目。
     > 1. 第一步：问问自己为谁设计？设计什么？如何设计？为什么用机器学习？
         这一点的灵感来源来自[Max Shron](http://www.maxshron.com)————[OkCupid](https://www.okcupid.com)令人尊敬的，具有魅力的前数据科学家。在Max的会议上，他大力强调了上下文在任何数据科学或机器学习项目中的重要性。对数据没有足够的了解是无法从A点到一个有效的模型的方法。
     > - 在今天的机器学习中，你需要花时间去理解请求背后的人——他们的动机、奋斗、观点和价值观。所以，要问自己几个问题在你开始之前：
     > - 谁需要我帮忙？他们在组织中的角色是什么？他们个人需要完成什么才能成功地发挥作用？
     > - 他们通常使用什么数据，更重要的是，他们目前在数据中寻找什么含义？机器学习应用可能提供什么额外的见解？
     > - 我如何能可靠地访问和清洁我需要的应用程序的数据？一旦我有一个稳定的数据供应，我怎样才能确保我的模型的发展以满足不断变化的需求？
     > - 为什么我在这里？为什么这个项目是要求的人的优先事项？如果我成功了，对请求者的日常生活会产生什么变化？

       机器学习者的目标是为用户提供超人性化的数据处理能力，虽然我们是机器学习方面的专家，我们的利益相关者和客户是真正的领域专家。

     > 2. 为透明性和理解力而设计

     > 机器学习是一项技术性很强的工作，一般人难以掌握。因此，一个机器学习应用程序通常会让终端用户感觉像一个黑盒，而缺乏透明性和理解力将使普通用户很难信任和依赖机器学习算法。当你像一名设计师一样处理机器学习项目时，这个挑战很容易克服。在设计机器学习应用程序时，花些时间记录和解释所选择的输入、用于清理数据的方法以及驱动应用程序的基本概念。

     > 另外，谨慎选择易于理解的方法，例如决策树和基于规则的方法。很有可能你的发现或者见解将挑战或直接反驳一些长期持有的信念，所以重要的是，你有可能使最终用户能够理解这些知识的驱动过程。这样，您的用户能更了解程序，能够解释程序的输出。所以，当你开始考虑最终产品时，要这样做，用户才能更容易和直观地深入到底层的数据和信息中去。

     > 3. 考虑用户将如何你的机器学习程序进行互动

     > - 在什么情况下会使用这些信息？
     > - 这些信息将在外部共享吗？
     > - 用户希望改变或帮助引导分类或识别集群吗？
     > 当你选定某一模型或者方案之后，你需要考虑传递这些信息的页面会给用户带来什么样的感受。当你仔细考虑上面的问题时，你不仅要满足期望，而且要设计一个易于学习的应用程序和界面，使之易于融入用户的工作流程中。例如，如果你的机器学习应用将提供见解与外部客户共享，你可以主动设计一个输出报告和批准共享的报告。使用这种方法来理解用户体验将有助于设计一种增强而不是增加用户日常事务的工具。

     > 4. 画出你的最终产品的线框草图

     > 从一个完全粗略的草图开始，看看界面可能是什么样子，然后用这个草图开始UI设计对话。当你用一个仅仅是纸上的草图来接近终端用户的时候，他们会感到更舒服地提供反馈和要求改变。您还帮助终端用户成为了项目贡献者。这意味着他们在机器学习项目中会感到更强的所有权，将更容易受益，其中包括你的同事和客户。

     > 5. 让提供反馈变得更简单
     
     > 希望你对待任何开发项目都当作一个正在进行的对话。首先从你的草图和概念上寻求反馈，允许用户提供输入和指导，说明什么是错误的，哪些还不够。把这个反馈的记在心里和脑袋里，再重新开发。一定要让你的客户保持在线状态，确保在开发还在进行时能随时得到反馈。这种来回会产生更多的洞察力，确保您的产品与用户的需求相匹配。即使当你的项目刚刚完成时，我建议你总是建立简单的方式让终端用户提出建议或调整意见。无论这是一个建立在界面上的小的“建议”字段还是仅仅是一个电子邮件地址，许多用户都会提供有见地的指导和想法。从这些反馈模式就出现了，你就可以锁定需要作出的最重要的和有影响力的变化。
     
     
* [A Machine-Learning Framework for Design for Manufacturability](https://arxiv.org/abs/1703.01499)

* 关于设计中的机器学习多维度的讨论[Dimensions of Machine Learning in Design](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.32.5541&rep=rep1&type=pdf)
     > 1.0介绍
     > 设计代表了人工智能能解决的最复杂的问题领域之一。尽管在过去十年中，AI技术在设计领域中取得进展，但是现有系统难以应对所需知识的多样性和数量以及所涉及的各种推理问题。
     >      > 一般来说：
     > -  设计问题需要来自各个领域的知识，并使用广泛的表示。
     > -  设计解决问题是基于执行诸如分析，抽象，评估和解释等各种各样的推理能力的许多专门任务的能力。

     > 一些设计领域已经被分析过和正式化，为搜索解决方案提供了坚实的支持。然而，很多设计仍然依赖于良好的知识和启发。维护设计质量和生产效率需要持续评估和改进设计知识和方法，包括启发式。

     > 对于设计师来说，这样的改进是基于在设计开发期间发生的显着事件和属性的记录和学习。 从设计中学习和在设计中学习，与设计活动本身一样古老。适应设计系统是显而易见的。 即使学习并不总是达到最佳解决方案，经验最终将在初始设计和设计过程中带来明显而有价值的改进。 这些都是以更高的质量，更短的设计时间和更低的成本来衡量的。

     > 知识获取和机器学习是支持设计系统变革过程的主要工具。知识获取强调将知识从外部世界转移到系统中，而不依赖于系统内部的转换。知识获取的主要目标是通过增加新知识来扩展系统的运作。

     >      > 学习虽然是基于对事件和反馈的洞察，但着重于影响表现的变革。 “表现”的含义包括系统提供的解决方案的质量以及生成该设计（或设计）的过程的效率。

     > 近年来开发的许多设计系统都纳入了一些学习。它们说明了设计对自适应技术开放的不同方式。通过学习，设计系统可以尝试应对日益复杂的问题。已经提供的适应性设计系统的例子数量以及慢慢被揭示的大量设计学习机会表明，尝试将这些发展置于系统框架的时机已经成熟。

     > 2.0多尺度的需求

     > 本文不是在设计系统中审查机器学习的使用意图（最近的评论见[Duffy 1997]）。但是，我们认为现在这个领域已经足够重要，足够活跃，试图对其进行描述，并为未来的工作提供一个框架。

     > 因此，在本文中，我们提出了一套研究设计中的机器学习的维度。我们希望可以将其作为比较现有工作的指导手段，并提出新的探索方向。

     > 所选择的一套尺寸主要受到现有试图应用机器学习设计的启发。这绝对不是完整的，也许不是唯一可能的研究文献分析。它代表一个讨论的假设。我们期望未来的作者（包括在这个特殊问题上回答我们这些想法的草案[Grecu＆Brown 1997]）会有不同的意见，特别是当这个领域的新进展发生时。

     >      > 我们不声称每个维度内的坐标之间不存在重叠，或者它们耗尽了该维度内的可能性。 定义坐标的目的是确定每个类别中的主要重点。 一些坐标“流动”到彼此之间，并且很难在它们之间定义清晰的界限线。 他们的代表性和独特性已被同时考虑，单挑出来包括在内。

     > 最后，我们想注意到设计系统的潜在分布式性质。 维度的描述尽可能地保持一致，以便包含分布式和非分布式的范式。 除了明确提及设计系统的分布式或非分布式类型的情况外，假定在两种情况下都是有效的。我们现在介绍在设计中的机器学习的建议维度：

     > - 学习的触发因素。
     > - 支持学习的元素。
     > - 学到什么
     > - 学习知识的可用性。
     > - 学习方法
     > - 本地与全球学习。
     > - 学习的后果
     
* [Teaching Machine Learning to Design Students](https://link.springer.com/chapter/10.1007/978-3-540-69736-7_23)
* [设计与人工智能报告](https://zhuanlan.zhihu.com/p/26610724)



-------------------------------------------------------------------

## General Design Tools

### Reference List

最常见的用户体验设计的方法和技巧 [Most Common UX Design Methods and Techniques](https://uxplanet.org/most-common-ux-design-methods-and-techniques-c9a9fdc25a1e)介绍UX设计师为用户创造出极好的体验最常用的方法和技术。 对于列表中的每个项目，有一些最佳实践的链接。

   * Value Proposition 核心价值主张
      ![value](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/屏幕快照%202017-09-08%20下午5.45.55.png)

      一个考虑成熟的价值主张帮助UX设计师把焦点集中在重要的事情上图片来源：uxmag
      描述产品关键方面的声明：它是什么，它为谁设计，以及它将如何使用。价值主张有助于团队围绕产品的内容达成共识。

      * 拓展阅读：
         * [Value_proposition](https://en.wikipedia.org/wiki/Value_proposition)
         * [Communicating the UX Value Proposition](http://uxmag.com/articles/communicating-the-ux-value-proposition)
         * [Strategyzer’s Value Proposition Canvas Explained](https://youtu.be/ReM1uqmVfP0)


   * Product Strategy 产品战略
   
      产品战略是产品生命周期和进一步发展的执行计划的基础。它允许用户体验设计师瞄准特定目标受众,关注产品和消费属性。

      * 拓展阅读：
         * [XD Essentials: How to Develop a Product Strategy](https://blogs.adobe.com/creativecloud/xd-essentials-how-to-develop-a-product-strategy/)
         * [What is Good Product Strategy?](https://articles.uie.com/what-is-good-product-strategy/)
         * [HOW TO DEVELOP A FOCUSED PRODUCT STRATEGY TO BACK UP YOUR UI/UX DECISIONS](https://www.invisionapp.com/blog/how-to-develop-a-product-strategy/)

   * Competitive Audit竞争审计

      竞争审计是对竞争对手产品进行综合分析，以比较的方式描绘出它们的现有特征。竞争审计的目标是发现你所在行业中其他公司的工作情况，这样你就可以使这些战略为你工作，从而获得竞争优势。


     * 拓展阅读：
         * [Competitive Analysis: Understanding the Market Context](http://boxesandarrows.com/competitive-analysis-understanding-the-market-context/)
         * [Conducting a Solid UX Competitive Analysis](http://danforth.co/pages/2014/03/01/conducting-a-solid-ux-competitive-analysis/)

   * Cultural Probes文化探索

      文化探索是一种在设计过程中激发灵感的技术。它是收集关于人们生活、价值观和思想数据的一种手段。在极少的干扰的情况下，研究人员可以收集参与者的环境，帮助识别问题陈述，发现新的机会，并启发设计师提出新的想法和新的解决方案。
      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/culture.png)
      文化探索使用一系列工具、工件和任务来激发用户以新的方式看待和思考他们的环境。
      
      视频资料:[Cultural Probes - Qualitative Contextual Design Research](https://youtu.be/EJqpUG4pJIE)


     * 拓展阅读：
         * [Cultural Probes](http://designresearchtechniques.com/casestudies/cultural-probes/)
         * [Inside Your Users’ Minds: The Cultural Probe](https://alistapart.com/article/culturalprobe)
         
   * Stakeholders Interviews 利益相关者

      利益相关者访谈中UX设计师对话他们的关键利益相关者：客户、上司、下属或同事。这个采访让UX设计师充分了解他们的相关利益者。它也有助于优化的特点和定义关键绩效指标（KPI）。

     * 拓展阅读：
         * [Preparing for UX Stakeholder Interviews](https://www.interaction-design.org/literature/article/preparing-for-ux-stakeholder-interviews)
         * [Better Stakeholder Interviews](http://cognition.happycog.com/article/better-stakeholder-interviews)
         * [A Stakeholder Interview Checklist](http://boxesandarrows.com/a-stakeholder-interview-checklist/)

   * User Interview 用户访谈
   
      用户访谈是一种常见的用户研究技术，通常用于从现有用户获取定性信息。用户访谈帮助UX设计师更好地了解他们的用户（用户的情感和意见）。当目标受众是新的或未知的团队时，这种技术尤其有用。

      通常，研究人员与参与者进行一对一的讨论，深入讨论参与者对所讨论问题的看法。

     * 拓展阅读：
         * [Interviewing Users](https://www.nngroup.com/articles/interviewing-users/)
         * [How to Conduct User Interviews](https://www.interaction-design.org/literature/article/how-to-conduct-user-interviews)


   * Kickoff Meeting 开幕会议

      开幕会议涵盖了产品目的的高级大纲，谁参与设计和开发产品，如何共同合作，保持最新进展，以及预期成果或成功指标。 开幕会议为您的产品的成功奠定了基础。开幕会议是与项目团队和项目客户的第一次会议。

     * 拓展阅读：
         * [Hold A Kickoff Meeting Before Diving Into The Design](https://www.smashingmagazine.com/2015/01/hold-a-kickoff-meeting-before-diving-into-the-design/)
         * [How To Take Charge Of A UX Kickoff Meeting](https://www.smashingmagazine.com/2016/04/how-to-take-charge-of-a-ux-kickoff-meeting/)


   * Heuristic Evaluation 启发式评价

      启发式评价是对产品的详细分析，它突出了现有产品中好的和坏的设计实践。它有助于用户体验设计师在可用性、可访问性可视化产品的现状、经验和效果。

      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/2.png)

      视频资料：[How to evaluating the usability of your own website or product](https://youtu.be/3Zp6qzzCqeY)

      一个雷达图显示了一个在所有启发式类别中表现良好的网站。

     * 拓展阅读：
         * [What is a Heuristic Evaluation in UX?](https://careerfoundry.com/en/blog/ux-design/what-is-a-heuristic-evaluation-in-ux/)
         * [What You Really Get From a Heuristic Evaluation](https://uxmag.com/articles/what-you-really-get-from-a-heuristic-evaluation)
         * [How to run an heuristic evaluation](https://uxmastery.com/how-to-run-an-heuristic-evaluation/)
         * [A Guide To Heuristic Website Reviews](https://www.smashingmagazine.com/2011/12/a-guide-to-heuristic-website-reviews/)

   * Brainstorming 头脑风暴

      头脑风暴作为一种产生想法和解决问题的方法被团队广泛使用。头脑风暴允许团队在决定要坚持哪一个方案之前，可视化一系列广泛的设计方案。

      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/3.jpg)

      头脑风暴是通过密集和自由的小组讨论产生创意和解决方案的过程。

     * 拓展阅读：
         * [A Framework For Brainstorming Products](https://www.smashingmagazine.com/2016/06/a-framework-for-brainstorming-products/)
         * [Tips for Structuring Better Brainstorming Sessions](http://www.inspireux.com/2013/07/18/tips-for-structuring-better-brainstorming-sessions/)
         * [Learn How to Use the Best Ideation Methods: Brainstorming, Braindumping, Brainwriting, and Brainwalking](https://www.interaction-design.org/literature/article/learn-how-to-use-the-best-ideation-methods-brainstorming-braindumping-brainwriting-and-brainwalking)

   * Task Analysis  任务分析

      为完成给定任务所需的操作的研究。当设计人员和开发人员试图理解当前系统及其信息流时，任务分析是有帮助的。它使得在新系统中适当分配任务成为可能。

      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/4.jpg)

      任务分析是从用户的角度来布置任务的一个简单有效的过程。

     * 拓展阅读：
         * [What is the difference between “Task Analysis” and “User Journey”?](https://ux.stackexchange.com/questions/18683/what-is-the-difference-between-task-analysis-and-user-journey)
         * [Task Analysis a UX Designer’s Best Friend](https://www.interaction-design.org/literature/article/task-analysis-a-ux-designer-s-best-friend)


   * Product Roadmap 产品路线图

      产品路线图是一种具有优先级特性的产品进化计划。它可能是一个电子表格，一张图表，甚至是一堆便签。UX设计师与团队和道路，要实现其愿景的产品策略。
      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/5.png)

     * 拓展阅读：
         * [UX in Product Roadmaps: How to plan your design activities?](https://uxstudioteam.com/ux-blog/ux-roadmap/)
         * [5 Tips from 5 PMs to Improve Your Team’s Product Roadmap](https://www.uxpin.com/studio/blog/5-tips-from-5-pms-to-improve-your-product-roadmap/)


   * Focus Groups 焦点小组

      焦点小组是一个中等强度的讨论，通常涉及5到10个参与者。带领人们讨论问题和关注用户界面的特性。通常持续约2小时，由一名维持该小组重点的版主主持。
      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/6.jpg)

      5-10位参与者的小组讨论一系列主题，通过讨论和练习提供口头和书面的反馈。

     * 拓展阅读：
         * [The Use and Misuse of Focus Groups](https://www.nngroup.com/articles/focus-groups/)
         * [How to Conduct Focus Groups](https://www.interaction-design.org/literature/article/how-to-conduct-focus-groups)
         * [Myth #26: Usability testing = focus groups](http://uxmyths.com/post/1319999199/myth-26-usability-testing-focus-groups)


   * Card Sorting 卡片分类

      卡片分类是用来帮助设计或评估产品信息架构的一种方法。UX设计师要求用户组的内容和功能的开放或封闭的类。结果用来帮助UX设计师决定输入内容的层次结构，组织和流程。

      卡片分类是一种成熟的研究技术，用于发现人们如何理解和分类信息。

      视频资料：[Card Sorting](https://www.youtube.com/watch?v=PmioMessMbY)

     * 拓展阅读：
         * [Card Sorting Beginner’s Guide – Improving Your Information Architecture](https://www.smashingmagazine.com/2014/10/improving-information-architecture-card-sorting-beginners-guide/)
         * [The Pros and Cons of Card Sorting in UX Research](https://www.interaction-design.org/literature/article/the-pros-and-cons-of-card-sorting-in-ux-research)


   * Usability Testing  可用性分析

      可用性测试是观察用户试图用产品执行任务的过程。测试可以集中在一个单一的过程，或者更为广泛。

     * 拓展阅读：
         * [Usability Testing: Don’t Guess, Test.](http://www.uxbooth.com/articles/usability-testing-dont-guess-test/)
         * [How to Conduct Usability Testing from Start to Finish](https://uxmastery.com/beginners-guide-to-usability-testing/)
         * Concept Testing 概念测试

   * Concept Testing 概念测试

      用户体验研究员参与提出产品的一个新概念的价值主张以决定是否符合目标受众的需求。概念测试可以是一对一的，也可以面向大量参与者，可以是面对面的，也可以是在线的。

     * 拓展阅读：
         * [Testing Content Concepts](https://www.uxmatters.com/mt/archives/2009/12/testing-content-concepts.php)
         * [5 myths of concept testing: What clients need to know](https://effectiveinc.com/thought-leadership/blogs/5-myths-concept-testing-clients-need-know/)


   * A/B Test
   
      A / B测试向不同的用户提供产品的替代版本，并比较结果，以便找出哪一个效果更好。 这是一个优化渠道和着陆页的好方法。

      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/8.png)

     * 拓展阅读：
         * [A/B AND SEE: A BEGINNER’S GUIDE TO A/B TESTING](https://www.invisionapp.com/blog/ab-testing-beginners-guide/)
         * [The Ultimate Guide To A/B Testing](https://www.smashingmagazine.com/2010/06/the-ultimate-guide-to-a-b-testing/)


   * Guerrilla Testing 游击队测试

      游击队测试是用户测试中最简单（最便宜）的形式之一。 使用游击测试通常意味着进入咖啡店或另一个公共场所，向有关您的产品或原型的人员询问。 它可以在咖啡馆，图书馆，火车站等的任何地方进行，在任何可以找到相关观众的地方。
      
      视频资料：[Guerilla Testing with Usability Cafe](https://youtu.be/0YL0xoSmyZI)

     * 拓展阅读：
         * [The Art of Guerrilla Usability Testing](http://www.uxbooth.com/articles/the-art-of-guerrilla-usability-testing/)
         * [7 Step Guide to Guerrilla Usability Testing: DIY Usability Testing Method](https://userbrain.net/blog/7-step-guide-guerrilla-usability-testing-diy-usability-testing-method)


   * Field Studies 田野调研

      田野调研是用于观察用户在野外的行为，以便在实际使用产品的情况下衡量行为。这种技术可以包括人种学研究，访谈和观察，加上上下文调查。
      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/9.png)

     * 拓展阅读：
         * [Field Studies](https://www.nngroup.com/articles/field-studies/)
         * [Field Studies Done Right: Fast and Observational](https://www.nngroup.com/articles/field-studies-done-right-fast-and-observational/)


   * Eye Movement Tracking 眼动追踪

      一种通过界面布局分析用户眼球运动的技术（即网页）。眼动研究提供的数据，让用户在屏幕上的兴趣和他们的阅读流量可优化设计。

      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/10.jpg)

     * 拓展阅读：
         * [Eye Tracking: Best Way to Test Rich App Usability](https://uxmag.com/articles/eye-tracking-the-best-way-to-test-rich-app-usability)
         * [Eye Tracking: What Is It For And When To Use It](http://usabilitygeek.com/what-is-eye-tracking-when-to-use-it/)


   * SWOT Analysis  SWOT分析
   
      评估影响产品用户体验的优势、劣势、机会和威胁。
      ![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/11.png)
      UX用于着陆页的SWOT分析。

     * 拓展阅读：
         * [Digital SWOT analysis: What is it and why you should care?](https://boagworld.com/digital-strategy/swot-analysis/)



   * Accessibility Audit 可访问性审查
   
      衡量是否每个人都可以使用网站的研究，包括有特殊需求的用户。它应该遵循W3C指南，以确保所有用户都满意。
![culture probes](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/5-most%20common%20ux%20design%20methods%20and%20techniques/12.jpg)
      在可用性和可访问性方面的最终目标是发现人们如何轻松地使用产品，并将信息反馈到改进未来的设计和实施中。
            
     * 拓展阅读：
         * [Accessibility testing](https://www.w3.org/wiki/Accessibility_testing)
         * [Myth #5: Accessibility is expensive and difficult](http://uxmyths.com/post/654091803/myth-5-accessibility-is-expensive-and-difficult)
         * [A Complete List Of UX Deliverables](https://uxplanet.org/a-complete-list-of-ux-deliverables-d62ccf1de434)








