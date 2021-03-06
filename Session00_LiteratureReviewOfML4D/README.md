# Literature Review of Machine Learning for Design


-------------------------------------------------------------------


## Machine Learning Application in Design Process & Tools

### Reference List

* 教机器画画  [Teaching Machines to Draw](https://research.googleblog.com/2017/04/teaching-machines-to-draw.html)  Thursday, April 13, 2017  Posted by David Ha, Google Brain Resident  :page_facing_up:
   
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
 

*  [Webs of Influence: The Psychology of Online Persuasion, 2nd Edition](https://www.safaribooksonline.com/library/view/webs-of-influence/9781292134628/?imm_mid=0f4ac0&cmp=em-design-na-na-newsltr_20170725_test)  :page_facing_up:



* 谷歌AutoDraw 让每个人都是设计师 [Google AutoDraw uses machine learning to make a designer out of anyone](http://www.androidpolice.com/2017/04/11/google-autodraw-uses-machine-learning-make-designer-anyone/)by Scott Scrivens  :page_facing_up:

     > AutoDraw是Google Creative Lab创造的一款使用机器学习帮助你实现设计需求的工具。如果你需要完成多个生日卡或活动海报的快速设计，AutoDraw可以帮你。AutoDraw使用简单的画图程序的界面风格，用户需要做的就是画出任何自己喜欢的基本轮廓，AutoDraw就会猜测用户在画什么，并提供更专业的选择。点击一个AutoDraw建议的图案，系统将自动用来自不同的，有才华的艺术家，设计师和插图画家的作品来替换用户粗糙的草稿。用户可以添加文本，形状，并给自己的杰作填充颜色。一旦完成，用户可以以PNG格式下载自己的作品。

     > AutoDraw和[QuickDraw](https://quickdraw.withgoogle.com/)使用相同的技术，Google Creative Lab 人工智能实验用神经网络从去年大众画的涂鸦中尝试找到相对应的图案。对于任何机器学习项目，被越多的用户使用的系统会变得更好，现在，学习机制已被纳入到AutoDraw中。
![32-1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/32-Google%20autodraw%20uses%20machine%20learning%20to%20make%20a%20designer%20out%20of%20anyone/屏幕快照%202017-09-04%20下午3.46.23.png)



* 将机器学习应用到设计上将会怎样？[What Happens When You Apply Machine Learning To Logo Design](https://www.fastcodesign.com/3058852/what-happens-when-you-apply-machine-learning-to-logo-design)  :page_facing_up:


     > 神经网络的兴起和生成式设计为设计师创造了新的机会。在[Mark Maker](http://emblemmatic.org/markmaker/#/about)（一个自动化生成logo系统）中，输入一个词。该系统然后使用遗传算法genetic algorithm，一种模仿自然选择的程序，以产生无止境的连续的标志。 当你喜欢一个标志，你点击一个爱心，它告诉系统生成更多的标志。通过喜欢足够的标志，概念里Mark Maker可以最终生成一个适合您需求的产品，而无需使用人类设计师。Mark Maker通过将每个设计打破一半来创建其标志，使其包含基本设计和特色元素。

     ![gif1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/23-what%20happens%20when%20you%20apply%20ml%20to%20logo%20design/3058852-inline-i-1-this-bot-will-generate-millions-of-logos-until-you-find-the-perfect-one-copy.gif)
     ![p1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/23-what%20happens%20when%20you%20apply%20ml%20to%20logo%20design/屏幕快照%202017-08-29%20上午10.51.30.png)




* 将机器学习应用于设计  [Designing with Machine Learning](https://www.wework.com/zh-CN/blog/posts/designing-with-machine-learning)   by Nicole Phelan  :page_facing_up:

    > 将机器学习用于评价建筑布局，这在设计产业上是非常新颖的。使用技术：ANN（Artificial Neural Network）人工神经网络。神经网络收集有关建筑物布局的数据（左），(提供的数据包括：办公室数量；办公室空间尺寸；会议室数量；会议室里的设备；)并将这些数据提供给一系列已经训练过，能够识别建筑物布局中的差异的人工神经元（中间）。基于神经元已经接触到的其他布局，神经网络作出预测得到会议室的利用率（右）。提供的数据包括：办公室数量；办公室空间尺寸；会议室数量；会议室里的设备；![p2](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/26-Designing%20with%20machine%20learning/屏幕快照%202017-09-19%20上午10.06.01.png)

    > 这项研究最强有力的含义是，在开始建造之前，可以计划一个适合需要的空间。使用机器学习揭示人与空间交互的模式是可以做出更好的设计和规划决策的信息。没有什么能够取代架构师的专业知识，而机器生成的新指标可以帮助指导设计师，提高他们创作效率。
    
    
* Adobe将AI应用于网页自动设计，你感受到危机感了吗？  BY NEAL UNGERLEIDER  [Adobe Is Building An AI To Automate Web Design. Should You Worry?](https://www.fastcodesign.com/3068884/adobe-is-building-an-ai-to-automate-web-design-should-you-worry)  :page_facing_up:

    > Adobe正在尝试将机器学习和人工智能应用到图形和网页设计上，一个未透露名字的实验项目正在创造工具来自动完成设计师的任务，例如剪裁图片，设计网站页面等。这项研究采用[ Adobe’s AI and machine learning program Sensei]（http://www.adobe.com/sensei.html#x），融合进Adobe Experience Manager CMS，这项功能在Adobe2016年3月的Sneaks（https://blogs.adobe.com/conversations/2016/11/lets-get-experimental-behind-the-adobe-max-sneaks.html） 大赛上亮相。虽然Adobe还没有宣称将这项技术融合进任何产品中，但这是将机器学习应用于平面设计的尝试中最有野心的一种。在设计领域里，已经有过将AI引入的案例，例如Wix的 [Advance Design Intelligence](https://www.fastcodesign.com/3060934/can-you-teach-ai-to-design-wix-is-trying)和自动化项目 [Mark Maker] (https://www.fastcodesign.com/3058852/what-happens-when-you-apply-machine-learning-to-logo-design)

    > 将机器学习用于网页设计 
    
    > 该平台的核心目标是更方便地为大型企业客户定制网站。 演示时是用机器学习和AI技术来编辑Food Network的网页。平台不由设计者决定布局，颜色，照片和照片大小，而是自动分析所有的输入，并向用户推荐设计元素。 使用图像识别技术，自动化进行裁剪照片等基础操作，用AI推荐页面设计。 使用客户端数据库中已经存在的照片（以及附加在这些照片上的元数据），AI再次分层到Adobe的CMS中，就可以为设计人员在设计要素和自定义设置上提出建议。
    > 据Adobe Marketing Cloud的产品管理总监Cedric Huesler介绍，该项目旨在提供所谓的“增强人性化”的设计。 AI提供建议，设计人员可以手动覆盖。“问题显然是个性化的规模，”Huesle称“我们可以通过提供不同的输入来重复相同的过程” - 一旦实施，机器学习工具可以在让大型企业用户快速生成定制的内容。 在像食品网络这样的大型企业客户的情况下，Adobe表示，部分自动化使他们能够为客户创造更自定义的网络和移动体验，比其他方式更快速，更经济实惠。

    > 基于模式和行为发现观众
    
    > AI旨在使大型项目的设计更容易。 它包括自动裁剪或以其他方式编辑照片的图像识别组件和依赖于文本元数据进行设计决策的更常规组件。Huesler指出，在食品网络示例中，内容可以立即为用户定制。 例如，活动行为表明是乳糖不耐受或不耐麸质的用户将会看到不同的食谱和图像。 机器学习平台实际上不会处理重新绘制界面并进行复杂的UI或UX决策等重大决定。 但是，例如，它可以帮助快速确定将哪些照片和文本内容移植到专为非常小的用户段设计的页面上。
    > Adobe Marketing Cloud产品高级总监Steve Hammond表示：“每个品牌都想做个性化设计。” “他们希望使内容与个人和观众相关，但是当您扩展您创建内容的受众时，您将面临两个瓶颈：您如何创建内容的变体，以及如何为他们创建图像？”他说，这些瓶颈是机器学习可以帮助解决的问题。机器学习世界的一个旧主题在这里被拾起。 在网页设计和图形设计的情况下，机器学习有助于自动化繁琐乏味的任务。[机器学习完成繁琐]（https://www.fastcodesign.com/3067411/technology-forces-us-to-do-things-were-bad-at-time-to-change-how-design-is-done） 

    > 平面设计师绝大多数都不用担心算法很快就会窃取他们的工作，因为机器学习仅是对于了解大数据集和提出建议是非常有用的，但分析诸如品味等主观事物是非常糟糕的。 尽管如此，重要的是要注意，繁琐乏味的任务包含了设计界进行的大部分入门级工作。 可以肯定的是，在未来几年里，机器学习工具将被用于入门级员工现在所做的许多任务。

    > ai驱动的设计的未来
    
    > Sensei已经在慢慢地在Adobe的Creative Cloud平台和其他产品上工作; 例如，在Creative Cloud中，它帮助进行图像识别和编辑面部表情。Hammond指出Adobe面临的一个重大问题是为客户提供不同平台的统一体验，例如桌面网站，移动网站，智能家居设备，广告，呼叫中心和触摸屏信息亭。 他补充说，自动化设计细节使这些更容易。


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
        
        
        
* 在机器学习的时代重新思考设计工具 [Rethinking Design Tools in the Age of Machine Learning](https://medium.com/artists-and-machine-intelligence/rethinking-design-tools-in-the-age-of-machine-learning-369f3f07ab6c)  :page_facing_up:

* 机器学习：AI和设计的光速发展  [Machine Learning: The Speed-of-Light Evolution of AI and Design](https://redshift.autodesk.com/machine-learning/) by JEFF WALSH  :page_facing_up:

   > Autodesk CTO杰夫·科瓦尔斯基（Jeff Kowalski）追求创新思想，他设想了一个对人类和人工智能（AI）来说更积极的结果。 他谈到机器学习如何加速机器人，生物设计和物联网的进步，改变了事物的设计和制作方式。
   > AI和机器学习的演变如何？ 六十年前，一位程序员教了一台机器，用tic-tac-toe击败人类。 此后，电脑变得更聪明。 到1997年，在国际象棋比赛中，深蓝击败了卡斯帕罗夫。 令人印象深刻的是无比强大的计算力。2011年，Big Blue的后裔沃森（Watson）利用推理力克对手Jeopardy！。 最近，AlphaGo在Go（世界上最复杂的游戏）中击败了人类最强者，它具有比宇宙中的原子更多的可能的动作。通过开发一种直觉，AlphaGo能够击败其对手。 而通过发展这个特质，有时候，甚至程序员也不明白为什么它这么做。在过去60年的里程碑中有一些指数级的转变：在不到一个人的一生的时间中，电脑已经从学习孩子的游戏到掌握被认为是战略思想的顶峰的游戏。
   > 一个例子是Atari视频游戏Breakout：通过仅查看分数和控制器输入，DeepMind的AI通过学习如何玩游戏的效果比任何人类整个夜晚玩数百万场游戏的效果要好。所以，它的自我学习速度比人类快得多，也可以快速将其新发现的知识传播到其他计算机。换句话说，只是因为你擅长Breakout，无法帮你的朋友也变得擅长。但是当一台电脑掌握Breakout时，所有这些电脑都掌握了，因为它们都是连接的。
   > 设计中机器学习的快速发展将如何有利于商业？ 一是加快生成式设计（generative design）。 一个例子就是设计一个四足直升机：设计师希望它能够很好地飞行并支持其有效载荷，这意味着需要使底盘重量轻，气动阻力低。通过给计算机这些约束，它可以探索每一个可能的解决方案，并回想出设计师们永远无法想象的想法。 电脑可以自己完全创造这些想法，而不用人超凡的绘画力量。
   > Autodesk已经在Airbus公司的一个项目上使用这项技术来重新设计一个比原来更牢固但重量是原先一半的新型飞机舱隔墙。 3D打印的隔墙将在今年晚些时候在A320飞行。
   > 与此同时，机器学习将会推进机器人的发展。 这里的一个例子是Autodesk与艺术家Joris Laarman及其团队在MX3D上的合作，以生成设计和机器人打印世界上第一个自动制造的桥梁。 今年夏天，我们会按下一个按钮，机器人将在阿姆斯特丹的运河上以不锈钢打印，无需人为干预。
   > 机器学习还会影响传感器和物联网的进步吗？绝对。 为了探索更先进的物联网，我们一直在与设计和制造研究组织Hack Rod和一家名为Bandito Brothers的电影制片厂合作，搭建一辆具有神经系统的疯狂车。 我们搭了一辆传统的赛车，配备了几十个传感器，然后把一个世界级的车手放在车轮的后面，把车停在沙漠里。使用其新的神经系统，汽车记录了在该驱动期间发生的一切，包括其受到的力量。 然后我们把现实世界的数据字面上数十亿的数据点插入到我们的生成设计工具Project Dreamcatcher中。结果得到的最终的底盘，是人类不可能设计的。 但是，在生成式设计，先进机器人和数字神经系统的帮助下，它成为现实。
   > 这一切听起来都很科幻。 那么下一步呢 随着机器学习的发展，它将通过注意设计师对其建议的反应以及将他们的不言而喻的偏好纳入设计过程来加速生成设计。 机器学习还将使机器人能够完成任务而不依赖于设计人员进行明确的指示。 机器学习将使用其新的数字神经系统（也称为物联网）的输入，对现实世界进行智能化的认知和反应。
   > 直到最近，设计师都用电脑来解决左脑，逻辑问题。 但电脑正开始进入人类创造力的领域。 例如，一旦电脑了解椅子的基本要素，他们可以帮助人们更好地设计，因为设计师和计算机之间有着共同的意义，这使计算机更好的创意合作伙伴。那么当电脑能够自己创造洞察力并像人类一样创造性的飞跃时，会是什么样的呢？ 这将从根本上改变设计师在创作过程中的角色。 在未来，设计师将更多地通过提供他们的指导和经验来指导电脑。纵观历史，人类塑造了世界。 展望未来，他们将塑造塑造世界的东西。 这与人类以前见过的不一样; 这将是前所未有的技术和人性的融合。 这是一个令人兴奋的未来，期待。



*  以人为中心的机器学习——聚焦用户的重要7点  [Human-Centered Machine Learning - 7 steps to stay focused on the user when designing with ML](https://medium.com/google-design/human-centered-machine-learning-a770d10562cd?imm_mid=0f4f22&cmp=em-design-na-na-newsltr_20170801)   By Josh Lovejoy and Jess Holbrook  :page_facing_up:


*  是时候进行机器学习中的设计演化了！——为何最好的时代还没到来。 [It’s Time for a Design Evolution in Machine Learning - Why the Best is Yet to Come](https://uxdesign.cc/its-time-for-a-design-evolution-in-machine-learning-6bfe7da3dcef). by Florian Oefner  :page_facing_up:


*  Sensei：Adobe将机器学习和设计工具添加到 Creative Cloud [Bow to your Sensei! Adobe adds machine learning and design tool to Creative Cloud](https://www.theregister.co.uk/2016/11/02/adobe_updates_creative_cloud_with_sensei_machine_learning_and_new_3d_design_tool/) By Tim Anderson 2 Nov 2016 at 14:30  :page_facing_up:

     > 最有趣的领域是机器学习。 虽然Creative Cloud长期以来受到机器学习驱动的功能，如内容感知填充Photoshop，但Sensei将启用新功能，例如以前在Adobe Stock图像库中进行的视觉搜索。Sharma谈到分析使用数据来推动新功能 “因为我们可以看到云中有什么资料，而且由于协作是支持云的，所以我们可以了解客户所具有的联系，了解他们拥有的移动设备，可以在新的层面上实现机器学习。” 

*  IntuiFace：如何使用机器学习来帮助创建交互式和连接的数字体验  [Machine Learning and Design in IntuiFace - How IntuiFace uses machine learning to aid the creation of interactive and connected digital experiences](https://www.intuilab.com/machine-learning)  :page_facing_up:

     > 三大理念：

     > 1.创作过程的民主化（The democratization of the creation process）
     > IntuiFace的一个基本原则是对互动内容的创作同等对待，不仅论在技术和非技术性的层面，对专业和业余设计师都一视同仁。实质上是创作过程的民主化。唯一的先决条件：设计理念，灵感，视觉理念。 

     > 2.基于机器学习的辅助（Machine Learning-based assistance）
     > 设计过程本身可以通过机器学习算法变得民主化。该系统的愿景是提出一个基于人群来源和个人喜好的设计方案系统，使intuiface用户能轻松根据上下文，个人需求和历史调整结果，带来一个好玩又有增强性的，系统的，具有创造力的发现过程。


     > 3.通过智能自动化进行简化（Simplification through smart automation）
     > 人工智能系统可以随着时间的推移了解每个用户的喜好，动态生成建议，编码用户和他人的DNA，同时继续调整，完善和打破传统，以保证设计是时下新鲜并且流行的。通过自动化和预过滤，用户将得到一系列实用的、独特的和个人的自定义选项，而不是在一个主题上的一些小变化。

     > 对熟练的或新手的设计师来说，好处是什么？
     > Rob Girling: 在未来的10年里，所有视觉设计工作都将通过算法可视化的方法得到加强。

      > 1.让各种技能基础的用户都能创作出结构完整的，有吸引力的设计作品。
      > 2.大规模扩大实验的能力
      > 3.通过促进学习引导新技能习得
 
      > intuiface和机器学习# 1：API消费
 
      > 现代设计工具应该很方便地能收集外部数据。从天气，货币兑换率，到NASA的照片，博物馆的艺术收藏，推特反馈，Spotify的专辑和专有的内部系统，在云端有大量有用的内容和服务，-又名Web服务，等待着设计师利用他们的价值。使用真实数据进行设计意味着我们可以更快地解决表面问题和附加约束，最终为用户创造更好的体验。
 
     > 一个人的技术能力不重要。它应该像粘贴URL或拖放文件一样简单。不幸的是，这些Web服务（它们的应用程序编程接口或API）所使用的语言需要技术技能去理解和使用。由此产生的“巨大的API墙”只能由软件开发人员控制，给特权少数人带来不公平的优势，限制了可用内容和信息的全部潜力。

     > intuilab创建API Explorer解决这个有关公平的挑战。 API Explorer将Web服务API的请求URL作为输入，并生成一个非技术的、用户友好的显示，通取代了通常提供的难懂的响应。同时，API Explorer自动预选返回的API特性（云上的内容和服务）认为，最有可能在一个互动的经验是有用的（例如图像、视频、网站、文本等）。
所有这些都是由API Explorer中的机器学习引擎所推动的，它通过观察世界各地的用户识别他们首选的API属性而变得“更聪明”。

     > intuiface和机器学习# 2：辅助设计

     > 显示内容的最佳方式是什么？即使是经验丰富的设计师也会在无数选择的压力下挣扎。设计辅助将有助于减少噪音和突出适合于数据和个性化的用户的历史偏好的选择，避免又复杂又冗长的方法。这种帮助的关键是具有避免低水平的特点，具有可调节的特性，而不是提供无穷无尽的没有方向，只有无尽的、麻木的主题变化。辅助应该呈现可行的“最终”选项，简化使用并且避免长学习曲线。

     > intuiface设计助理，一个API Explorer的配套功能，是我们实现辅助设计的第一步。

     > 在API Explorer 中，绑定了用户选择的属性的可视化布局是“智能”生成的，这要归功于适应性的机器学习——在有针对性的交互体验中，总体布局可以重新排列，需要结合其他intuiface设计能力来生产现代的、多点触控体验的适用于Windows、iPad、Android、Chrome OS和三星SSP的设备。在运行时，可视化显示始终保持不断更新，通过API不断刷新获取的信息。在这整个过程中，intuiface用户不用写一行代码，没有额外的成本即获得可用的成千上万的Web服务。
![pic31-1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/31-ml%20and%20design%20in%20intuiface/595f94c41a3a79706d6d7cf6_Design-assistant%202.gif)

     > 该系统的目标：

     > 1. 通过探索进行设计
     > 2. 赋能设计者领导工具，而不是反过来。
     > 3. 促进创造性协作，设计师与算法合作，以解决产品任务。
     > 4. 授权设计师制定和打破规则


 


*  自动化将淘汰平面设计师？未来该选择什么职业？[Automation Threatens to Make Graphic Designers Obsolete - So what kind of career should you expect to have in future?](https://eyeondesign.aiga.org/automation-threatens-to-make-graphic-designers-obsolete/) by Rob Peart  :page_facing_up:

     > 设计师做的很多事情都是依托规范的。 我们在设定的屏幕尺寸和分辨率下工作，使用按比例计算的网格标准化纸张格式。 我们使用数字序列化和索引的颜色，并可以通过数学计算开发成色系。 我们可以从在线访问的字体创建类型样式的调色板，可以根据历史发展和类型进行分类，并根据基础单位进行布局。 这些部件是模块化和机械的，可以完美实现自动化的。 而且我们目前的工作流程很多都是非常自动化的 - 比如排版。

     > 20世纪50年代以来，随着每个技术大规模的发展，随之而来的是设计师的角色的演变。严格定义的任务可以通过编码生成的严格定义的程序输出来自动实现。 这些算法已经在设计和创作中被使用了一段时间。

     > 伦敦的[Field](https://www.field.io/)工作室将这种自动化方法应用于高度创造性的领域，其工作将艺术，技术天赋和敏锐的美学结合在一起。 该工作室[为纸张公司GF史密斯的设计](https://www.field.io/project/digital-paintings/)是一个有趣的例子，是在一个商业图形设计环境中应用的算法增强过程。 Field通过一种算法创建了一个数字3D结构，从各种角度和优势点渲染了超过10,000个这样的结构图像。 该过程的最后部分是手动编辑程序的输出，确保每个图像都足够令人惊叹，以便商业使用。 真正实现了的设计师和算法的协作。

     > 设计师Jon Gold 一直在研究将机器学习技术应用于标准图形设计程序。 机器学习是开发机器智能的一种方法，百度研究首席科学家Andrew Ng和Google Brain项目的创始人将机器学习定义为“在不需要明确编程的情况下，用科学让计算机学习。“Gold使用这种方法分析字体和排版趋势，并根据计算机学到的内容生成不太可能的类型配对。 他在他的文章[《让机器人进入设计学校》](http://www.jon.gold/2016/05/robot-design-school/)中描述了他的探索。虽然Gold的工作可能看起来很好，并适用于狭窄的AI频谱，但它给了我们一个可以期待的未来工作流的样子。 很容易忘记的是一旦通过掌握特定区域创建了模型，它就可以嵌入并与其他可能已经在非常不同的问题类型的颜色理论或组合上进行了训练的模型相结合。

     > 他写道，“瞥一眼未来后再看现在的设计工具是令人沮丧的。 在我们的软件中完全缺乏语境和工业意识。 工具操纵字符串，向量和布尔值而不是设计 。但是，工具是影响变革的最重要的地方。

     > “我正在构建将智能算法与设计过程相结合的设计工具; 这种设计工具通过了解设计师在做什么从而让他们更好。 助力设计师而不是取代他们。”




*  机器学习如何加速设计周期 [HOW MACHINE LEARNING CAN SPEED UP YOUR DESIGN CYCLE](https://www.maximintegrated.com/en/design/blog/machine-learning-can-speed-up-design-cycle.html) by Christine Young  :page_facing_up:



*  [设计与AI的现在Ⅰ：设计了1.7 亿个 banner的阿里鲁班](https://zhuanlan.zhihu.com/p/26563244) by 阿里巴巴AI设计项目负责人乐乘（吴春松） :page_facing_up:

     > ![36](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/36-luban/1.png)
随着人工智能时代的到来，设计与人工智能的纠葛，艺术与科技的博弈，越来越频繁地现身热门话题榜。而在设计人工智能领域，阿里巴巴已经开始加速探索。

     > 15 年“双11”，是阿里第一次基于算法和大数据，为用户做大规模的、个性化的商品推荐，叫做“千人千面”，是阿里流量分发模式很大的升级和转型。双11”结束后，（设计、工程和算法团队）就聚在一起，商量下一年要做些什么。我们当时想，我们已经做到的个性化推荐，但都是基于白底图商品推荐，能不能往前迈一步，让强营销导向的广告资源位的设计也“千人千面”呢？从纯商品个性化跨到广告资源位个性化，中间几个关键的技术点打通之后，我们就着手做了。

     > Q: 都是哪几个关键技术点？

     > A: 一是图像算法“抠图”。因为高质量的广告设计需要把商品图片抠出来，放到精美的设计主题里。以前都是设计师给商品抠图后再做设计，现在我们用机器做海量设计，就得让机器来做这个事情。我们跟阿里搜索部门做图像切割的算法团队合作，处理海量的商品自动抠图。

     > 第二点是把设计变成“数据”。一张广告设计图片是像素组成的“信息”，不是“数据”。我们利用机器把商品、文字和设计主题进行在线合成，这样每张广告图片就带上了商品信息，可以根据消费者偏好进行个性化投放。所以鲁班产品上线初期，我们请设计师根据活动主题做了大批量风格确定的模板，证明了这种模式投放效果可以大幅提升点击率。

     > 第三点就是让机器学习设计。靠“人肉设计模板”度过了第一个阶段，但长远发展角度我们必须让机器来做设计。大概是 16 年 8 月份开始的，有一位之前负责淘宝“拍立淘”（在淘宝内通过图片搜索找同款，随拍随找）产品开发的图像算法专家加入进来，主导整个智能设计的算法框架。建立了一套数据体系去管理设计数据，让机器生产出更匹配的结果。AI 目前有几个主要方向，一个是“识别”，像语音识别、图像识别；另一个是“生成”，也就是我们在做的，从无到有创造东西，让机器能根据请求生成符合特定要求的结果。我们把我们的智能设计定位为：可控的图像生成技术。我们可以结合技术框架和原理来理解。

     > 在整个生成过程中，有4个核心步骤。

     > 第一步，让机器理解设计是什么构成的：我们通过人工数据标注，对设计的原始文件中的图层做分类，对元素做标注。设计专家团队也会提炼设计手法和风格。通过数据的方式告诉机器这些元素为什么可以放在一起，我们把专家的经验和知识通过数据输入。这部分核心是深度序列学习的算法模型。

     > 第二步，建立元素中心：当机器学习到设计框架后，需要大量的生产资料。我们会建立元素库，通过机器做图像特征提取，然后分类，再通过人工控制图像质量以及版权问题。

     > 第三步，生成的系统：原理有点像 Alpha Go 下围棋。在设计框架上构建起虚拟画布，类似棋盘，生成的系统把元素中心的元素往棋盘放，在这里我们采用了“强化学习”，就好像你在家里放一台扫地机器人，让它自己跑，跑个几圈，它自己会知道哪里有障碍要避开。在强化学习的过程中，机器参考原始样本，通过不断尝试，得到一些反馈，然后从中学习到什么样的设计是对的、好的。

     > 第四步，评估的系统：我们会抓取大量设计的成品，从“美学”和“商业”两个方面进行评估。美学上的评估由人来进行，这方面有专业众包公司；商业上的评估就是看投放出去的点击率浏览量等等。

     > Q:“鲁班”的最大优势是什么？

     > A: 是商业和技术两方面的比较好的结合产物。首先在技术深度方面，它有门槛很高的一套系统，另外在商业方面，它的确能通过“智能化”和“个性化”，实现商业价值最大化，颠覆传统方式。

     > Q: 听说去年“双11”，“鲁班”设计了 1.7 亿个 banner，你怎么看这个“历史事件”？

     > A: 其实这 1.7 亿个 banner 是有设计强干预的，因为“双11”的风格是比较确定而且需要严格执行，所以设计师制作了很多“双11”特定风格的固定模板。机器在这个基础上，把调整尺寸这些行为进行优化，节省了尺寸拓版的人力。用机器生成亿级设计从而带来商业效果提升，总体来说也是一次非常成功的应用实践。我想未来的“双11”仍然会是设计师带着机器做设计的模式，重大活动中设计机器是提升效率的助理角色。

     > 内部如何评价“鲁班”呢？

     > A: 引用阿里 CEO 的话——“鲁班是数据业务化的代表”，之前我们有很多数据，但都是闲置的或者利用效率不高的，比如海量的商品图，而“鲁班”把数据变成了业务，通过大规模设计加精准投放，提高每个广告位的资源效率，带动了流量的效率和业务价值，点击率是翻倍的，收益也接近翻倍。人员倒没有出现缩减，只是做的事情有调整了，要学习这套系统，学习如何训练机器，同时在美学方面做把控。












-------------------------------------------------------------------



## Design Products & Services with AI & Machine Learning Embedded in

### Reference List
* 机器学习和交互设计 [Machine Learning and UX](https://medium.com/designer-hangout/machine-learning-and-ux-c28725b5f3a)  :page_facing_up:

     > 与目标群体相对立的个人概念，它定义了用户体验与机器学习的必然联姻。
   
     > 设计师应该与机器学习一起通力合作服务用户————目前，设计师可以创造出引人注目的群体体验，但不考虑个人。针对个体的体验设计，需要机器学习来协助。![1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/9-machine%20learning%20and%20ux/2.png)可以将聚类，用于分组数据的无监督机器学习过程。在未来我们会看到专门为设计师洞察数据生成的工具，现在的好的解决方法就是设计师与团队和公司的数据科学家合作将双方的发现和能力融入设计中。
   
     > 设计师和数据科学家生活在一个意想不到的维恩图中。我认为这些团体的凝聚力会产生有趣的和令人惊喜的用户体验，当然在不久的将来（看不见的设计，由Amber Cartwright提出的一个概念，[进一步的页面]，似乎沿着这些线路的想法）。
     
     > 对设计师而言的机会点:很明显，我认为机器学习只会增加未来设计师的工作量，可以使用机器学习来帮助我们理解这一切。基于用户数据提取和提出见解的系统将变得正常和必要，特别是当数据集变得更大细粒度更高时。智慧的界面对于人类来说是很自然的：对数据集的自然语言查询是我们想看到的，甚至可能以识别语音的机器人（如Jarvis）的形式出现。![1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/9-machine%20learning%20and%20ux/3.jpg)我希望看到这些机器人是专门设计和推理设计者关心的东西，比如用户反馈的情绪和可用性测试中特定疼痛点的提取，因为SQL查询和Python脚本的能力有限。
   
     > 我们需要像人类那样能自然互动，但像机器一样思考的系统。这将有助于消除许多设计师在面对代码墙时所体验到的交互的心理障碍，同时还为我们提供了专门针对我们需要的代码的功能。在大多数人直接打开Google去搜索答案的时候，对于设计师而言，现在是有机会定义这种关系将如何发展的时机。这是一个未经探索的边界正在等待着，不是被发现，而是由你和我去创造。  
   
      > 案例：迪士尼通过[腕带来为用户提供定制化的服务](https://www.wired.com/2015/03/disney-magicband/)。腕带通过收集大量主题公园游客的信息，再将相关的数据传送给员工，例如你的名字或者桌号，没有任何的物理接触和语言交流，通过设计让公园的参与感更强。![1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/9-machine%20learning%20and%20ux/1.jpg)主题公园的设计者Dave Cobb 称未来可能会生成一个基于长时间记录的系统，，预期设计创造出每个人一个完全不同的体验。如果数据具体到一个人的地理、社会、历史甚至遗传背景 - 然后机器可以创建一个完全独特的和个人的经验。
      

* 关于机器学习的好的产品设计案例有哪些？ [Any good Product Design case studies that involve Machine Learning?](https://www.designernews.co/stories/75495-any-good-product-design-case-studies-that-involve-machine-learning) :page_facing_up:
    * [用可视化介绍机器学习](http://www.r2d3.us/%E5%9B%BE%E8%A7%A3%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/)

    * [Google CEO technical assistant on building AI products](https://vimeo.com/181330432)

    * [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471)

    * [Designing Machine Learning Models](https://medium.com/airbnb-engineering/designing-machine-learning-models-7d0048249e69)
    
* 机器学习在产品设计领域有多大影响力？ [How influential is machine learning in the field of product design?](https://www.quora.com/How-influential-is-machine-learning-in-the-field-of-product-design) :page_facing_up:




* 设计师需要了解的机器学习内容 [What designers need to know about machine learning](https://hackernoon.com/what-designers-need-to-know-about-machine-learning-109a12fdd3af)  :page_facing_up:





* 对设计师有帮助的机器学习的应用 [Applications Of Machine Learning For Designers](https://www.smashingmagazine.com/2017/04/applications-machine-learning-designers/) By Lassi Liikkanen  :page_facing_up:






* 为什么设计师和产品经理需要懂一点机器学习 [Why Should Designers And Product Managers Know About Machine Learning?](https://www.forbes.com/sites/quora/2017/04/07/why-should-designers-and-product-managers-know-about-machine-learning/#72cde9e07b28)  :page_facing_up:




* 对机器学习系统的用户体验进行设计[Designing the User Experience of Machine Learning Systems](https://mikek-parc.github.io/AAAI-UX-ML/)  :page_facing_up:
     > 设计机器学习系统的用户体验是AAAI会议在斯坦福大学举行，斯坦福，加利福尼亚从3月27日–29, 2017。讨论主题：探索，实验和在系统间的合作仿真和解决冲突需要更好工具的需求；更好的模式和围绕着数据清洗，维护，管理，和源审计的实践；并建议如何加深合作。

     > 报告
     > 机器学习只是更广泛的人工智能工具箱中的一个子区域，但它是最近获得了大量公众想象力的一部分。本次研讨会汇集了一个多方面的小组探讨什么机器学习意味着用户体验：我们面临什么样的挑战，创造理想的，有用的，可用的，可靠的用户体验，包括机器学习技术？我们邀请与会者考虑在机器学习和用户体验的交叉点上存在的问题。问题包括如何面对机器学习的挑战，例如对机器学习和预测建模工作的专家有什么应用和特定领域的挑战？以及那些研究这些系统和服务对人们和他们的实践，以及最终对社会结构的影响的人的意见。
     > 专题讨论会的参加者是不同的，我们所涵盖的主题，从工业界和学术界，从社会和技术科学，从设计。与会者来自人工智能的许多领域工程；计算机科学；人机交互；交互设计；用户体验和产品、社会学和人类学。他们在不同的职业阶段，在不同的组织中扮演着不同的角色和级别。

     > 论文介绍了机器学习对一系列主题的影响，从哲学到批判，再到实用：
     > 技术与设计交叉的新方法（范艾伦）
     > 时尚推荐系统的改造（瓦卡罗和库玛；Seshadri等人）
     > 鉴定专家谁使用机器学习的关键需求（塞特勒和保守党；Girardin和lathia）
     > 探索最终用户体验与使用（或不使用）机器学习系统的心理学（春等人）
     > 隐私问题（维塔利等人）。

     > 主题：沟通与协作
     > 我们讨论了如何开发支持系统、交互、产品和服务设计者之间的通信和协作的工具。我们如何支持应用机器学习技术的人和那些理解开发人员和设计者在设计这些系统时所做出的选择的人之间更有效率的对话？我们研究了如何超越黑箱，在模型训练中进行更好的实验，以及对数据进行修剪和修剪。
互惠知识共享将推动这两个领域向前发展，并将使我们能够创造更值得信任和值得信赖的用户体验。提供反映各种不同用例的相关和包容性案例研究是更好地制定设计机会的一种方法。 

     > 自动化和控制机构
     > 在自主车辆小组的推动下，我们讨论了为多设备、多服务、相互连接或有时断开的复杂生态系统设计的困难。他们都利用他们自己的学习和预测建模的形式，使得相当大的设计和用户体验的复杂性，需要在技术、物理和社会层之间工作。

     > 偏差、信任与权力
     > 哲学和政治问题，讨论了系统透明性，呼吁明确出处模型，明确在机器学习数据集，源和交互的潜在偏差。基本的要求是始终提供多个观点，以减轻与偏见有关的问题，并使偏见成为调查本身的明确主题。
     > 信任和权力的关键问题的研讨会关闭对话框应该系统与他们的用户，并且什么它意味系统要“风度”，有“个性”，而“社会责任”？




* [为男人们提供个性化服饰搭配，英国电商 Thread 获 800 万美金 A 轮融资](https://36kr.com/p/5036946.html)  :page_facing_up:



     > 电商平台 Thread 试图采用造型顾问+机器算法的方式，来为想要穿得得体一些，却又不爱逛街的男士提供个性化的商品建议。

     > 网站首先会让用户填写一个问卷，问卷内容包括：你平时会出现在哪些场合？你钟爱的品牌和风格？尺码，价格，色彩？ 随后，Thread 的造型师通过了解问卷获得的数据和上传的照片，来得出适合顾客的大致搭配方案，随后机器算法将按照造型师给出的方案导出顾客所选价格范围内最合适的商品。Thread 在购买评价上设置了多个具体的选项，比如”我不喜欢领子的设计”、“我不喜欢衣服的面料”。目的是通过这些反馈信息，进一步优化下次的商品推荐结果，让平台变得越来越“懂”你。每周，Thread 都会发送一批新的个性化商品促销信息给用户，同时网站的造型师也在线上随时待命、提供一对一的咨询服务。

     > 由于涉及SKU众多，且多为非标品，Thread 并未采用自营“重”模式，而是多品牌达成合作关系，由官网直接发货。

![thread](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/37--%20Thread/屏幕快照%202017-09-19%20上午12.26.11.png)







-------------------------------------------------------------------


## Other Topics related to ML and Design 

### Reference List
* [Machine Learning for Designers](http://www.oreilly.com/design/free/machine-learning-for-designers.csp)  :book:

    * [Machine Learning for Designers](http://pan.baidu.com/s/1eSOUudW)

    * [Machine Learning for Designers 解构脑图](https://zhuanlan.zhihu.com/p/27045885)

* John Whalen应用脑科学进行设计   [John Whalen on using brain science in design](https://www.oreilly.com/ideas/john-whalen-on-using-brain-science-in-design?imm_mid=0f4f22&cmp=em-design-na-na-newsltr_20170801)By Nikki McDonald. July 27, 2017  :page_facing_up:
    
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

* 只需5步，以设计师思维看待机器学习 [5 Steps to Thinking Like a Designer in Machine Learning](http://machinelearningmastery.com/5-steps-to-thinking-like-a-designer-in-machine-learning/)  by Jason Brownlee on March 26, 2014 in Machine Learning Resources :page_facing_up:

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
     
     
* [A Machine-Learning Framework for Design for Manufacturability](https://arxiv.org/abs/1703.01499) :page_facing_up:

* 关于设计中的机器学习多维度的讨论[Dimensions of Machine Learning in Design](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.32.5541&rep=rep1&type=pdf) :page_facing_up:
     > 1.0介绍
     > 设计代表了人工智能能解决的最复杂的问题领域之一。尽管在过去十年中，AI技术在设计领域中取得进展，但是现有系统难以应对所需知识的多样性和数量以及所涉及的各种推理问题。
     >      > 一般来说：
     > -  设计问题需要来自各个领域的知识，并使用广泛的表示。
     > -  设计解决问题是基于执行诸如分析，抽象，评估和解释等各种各样的推理能力的许多专门任务的能力。

     > 一些设计领域已经被分析过和正式化，为搜索解决方案提供了坚实的支持。然而，很多设计仍然依赖于良好的知识和启发。维护设计质量和生产效率需要持续评估和改进设计知识和方法，包括启发式。

     > 对于设计师来说，这样的改进是基于在设计开发期间发生的显着事件和属性的记录和学习。 从设计中学习和在设计中学习，与设计活动本身一样古老。适应设计系统是显而易见的。 即使学习并不总是达到最佳解决方案，经验最终将在初始设计和设计过程中带来明显而有价值的改进。 这些都是以更高的质量，更短的设计时间和更低的成本来衡量的。

     > 知识获取和机器学习是支持设计系统变革过程的主要工具。知识获取强调将知识从外部世界转移到系统中，而不依赖于系统内部的转换。知识获取的主要目标是通过增加新知识来扩展系统的运作。

     > 学习虽然是基于对事件和反馈的洞察，但着重于影响表现的变革。 “表现”的含义包括系统提供的解决方案的质量以及生成该设计（或设计）的过程的效率。

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
     
* [Teaching Machine Learning to Design Students](https://link.springer.com/chapter/10.1007/978-3-540-69736-7_23) :page_facing_up:

     > 机器学习是设计和制造智能系统，产品和相关服务的关键技术。像许多其他设计部门一样，我们面临着挑战，教授机器学习给设计学生，他们通常对技术不太有兴趣。我们成功地运用了实体智能方法来教机器学习。通过将学习系统体现在乐高Mindstorm NXT平台中，我们为学生提供了一个有用的工具来了解和与学习系统进行互动的过程。有形机器与乐高系统积极联系的结果激发了所有的学生。具有更多技术兴趣的学生优秀地解决了先进的问题。我们相信，我们的经验可能会指导打算学习机器学习或其他计算机科学相关话题的其他教师来指导设计的学生。
     
* [设计与人工智能报告](https://zhuanlan.zhihu.com/p/26610724) :page_facing_up:

* [Logojoy：用人工智能完成标志设计](http://techcrunch.cn/2016/12/02/logojoy-makes-designers-unemployed/)

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








