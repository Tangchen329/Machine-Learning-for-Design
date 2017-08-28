## Literature Review of Machine Learning for Design


-------------------------------------------------------------------


## Machine Learning Application in Design Process & Tools

### Reference List


#### :sparkles: John Whalen应用脑科学进行设计   By Nikki McDonald. July 27, 2017
[John Whalen on using brain science in design](https://www.oreilly.com/ideas/john-whalen-on-using-brain-science-in-design?imm_mid=0f4f22&cmp=em-design-na-na-newsltr_20170801)

 O’Reilly设计播客：为“六感”设计，像人类一样交流的重要性，以及可预见的AI的未来。
 ![pic1](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/1-John%20Whalen%20on%20using%20brain%20science%20in%20design/屏幕快照%202017-08-24%20下午3.12.35.png)DTI brain tractogram lateral view (source: Aaron Filler, MD, Ph.D., on Wikimedia Commons)
#### 主题：人类经验背后的“六感”／为什么设计师要理解脑科学／以及人们真正需要的是什么？
- 为什么设计师要理解脑科学?

> 通过了解什么吸引大脑的注意力，如何把握事物的记忆，如何做出决策，以及情感如何控制决定…来确保设计师们真正的以用户为中心，探索用户在挑选产品和如何使用上的思维框架。

- 每个人类经验背后的“六感”

> 1-Vision,Attention视觉和注意力 2-记忆和你所有先入为主的想法和你认为的世界的工作方式 3-方向感 ，是你在空间中移动的能力，例如在虚拟世界的方向感 4-> 语言，掌握不同语言术语的能力 5-情感内容。 最后，所有一切都是为了帮助你做出决定和解决你的世界的问题。

- 我们在语音的助手身上寻找什么？

> 通过研究不同人群对使用Siri，Cortana，Alexa和Google Assistant时的感觉：“你最想买哪款回家？你个人倾向于哪款？”Google助手第一，因为它确实在回答问题 方面做得最好，而亚马逊echo的Alexa第二受欢迎，尽管它在回答问题上是所有语音助手中最不成功的。
事实证明，选择Google助手的人将在这些系统里寻找的内容描述为“我只是想快速知道答案，只想知道发生了什么”。而喜欢Alexa的人则说：“它回答问题的方式跟我问它的方式一样 ”或者，“我喜欢可以来回交谈，这让我觉得我正在和一个人说话。”所以，Alexa对他们来说真的有人性化的品质。

> 所以对于产品测试，并不仅仅是要“百分比正确”，还需要考虑人的组成部分。我们对这种人文素质感到好奇，好奇它的重要性有多大。

- AI系统应该如何预测……什么时候会变得令人恐惧？

> 在我们的研究中，我们提出了一些问题：“你希望机器在多大的程度上了解你？”例如，亚马逊知道您多久购买牙膏，所以可能预测牙膏有没有用完。它可以在星期二随机问“天哪，尼基，你想要更多的牙膏吗？”你在想，“它是怎么知道的，它在哪里看起来？它有相机吗？还有谁在房间里？”其实有数学模型可以很好地预测这些事情。

> 设备可以有各种各样的方式来增强你的认知 - 我们已经做到了这一点;在某些方面，我们已经在使用电脑，每次使用Google地图，或者Google价格来选择某些东西。很多方法奏效了，我们也对这些技术很习惯。例如：提前发现天气增加了我们的认知，帮助我们做出更好的决定。

> 机器可以继续这样做，这只是我们在空间和时间上使用这项功能，但我们并不习惯它预测我们的行为。我们习惯于问一个问题，然后收到答案，而不是让机器预期我可能需要一个答案。

 
#### :sparkles: 教机器画画   Thursday, April 13, 2017  Posted by David Ha, Google Brain Resident
[Teaching Machines to Draw](https://research.googleblog.com/2017/04/teaching-machines-to-draw.html)
#### :sparkles: 跟神经网络一起画画   Thursday, April 13, 2017  Posted by David Ha, Google Brain Resident
[Draw Together with a Neural Network](https://magenta.tensorflow.org/sketch-rnn-demo)

Google Creative Lab进行了一个互动的网络实验，让人们可以跟一个名叫sketch-rnn的神经网络模型一起画画。通过从[Quick，draw!](https://quickdraw.withgoogle.com/data/)收集的数百个涂鸦对这个神经网进行了训练。一旦你开始绘制一个对象，sketch-rnn将提供许多可能的方法来继续绘制这个对象，可以在这里尝试[sketch_rnn_demo](https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html).
1. 因为该神经网络是基于其他人绘制的内容进行训练的，所以也可以在这种演示环境下看到机器预测下你的图形的未来样貌，可以用来满足自己的好奇心，探索不同的可能性。[ Multi Predict](https://magenta.tensorflow.org/assets/sketch_rnn_demo/multi_predict.html)
2. 除了预测不完整的图形之外，sketch-rnn也可以从一个图形变换到另一个图形。在插值演示中，你可以使用屏幕两侧的按钮来随机生成两个图像。模型将绘出多种新的绘图，它被认为是两个原始图纸之间的插值。[ Interpolation Demo](https://magenta.tensorflow.org/assets/sketch_rnn_demo/interp.html)
3. 该模型还可以模仿你的风格并生产类似的涂鸦。在VariationalAutoencoder演示中，你将绘制一个指定对象的完整图形。在左侧区域绘制完草图后，点击自动编码按钮，模型将在右侧较小的框中绘制类似的草图。神经网络将尝试模仿你的绘图。您可以尝试不是您应该绘制的类别的绘图对象，并查看模型如何解释您的绘图。例如，尝试画一只猫，并有一个模型训练来绘制螃蟹，生成类似猫的螃蟹。[ Variational Autoencoder](https://magenta.tensorflow.org/assets/sketch_rnn_demo/multi_vae.html)

抽象的视觉传达是人们传达彼此想法的关键部分。 从小时候开始，孩子们培养了用少量笔画来描绘物体甚至是情感的能力。 这些简单的绘画可能不像照片所捕获的现实那样，但它们告诉我们一些关于人们如何表现和重建周围世界的图像的方式。
在论文《草图的神经表示》（《A Neural Representation of Sketch Drawings》）中，提出了一个生成递归神经网络(recurrent neural network)，能够产生普通物体的草图，目的是训练机器以类似于人类的方式绘制和概括抽象概念。我们在手绘草图的数据集上训练我们的模型，每一个草图代表一系列控制钢笔的动作：哪个方向移动，什么时候提起钢笔，何时停止画画。在这样做的过程中，创建了一个潜在的应用模型，从帮助艺术家的创作过程到帮助学生如何绘画。除此之外，即使在最简单的用例，图案设计师可以通过sketch--RNN产生大量相似但独特的设计，用于纺织品或墙纸版画。如果给一辆卡车的输入草图，可以训练一个能画猪的模型来画猪一样的卡车。
我们可以将这一结果推广到应用程序中，这些应用程序可能有助于创造性的设计师设计出能与目标受众产生更多共鸣的抽象设计。也可以利用该神经网络来训练它来预测不同可能的结局不完整的草图，这种技术可能会给艺术家的创作过程带来帮助，因为系统可以推荐多种可选择的其他方式来完成一个不完整的草图。该系统中，可以看到了如何使相同的圆形和方形的人物成为各种蚂蚁，一部分火烈鸟、直升机、猫头鹰、沙发甚至油漆刷。通过使用各种不同的模型来训练不同的对象，设计师可以探索创造性的方法来向观众传达有意义的视觉信息。这些模型还会带来许多令人兴奋的，应用在各种不同的方向的新创意。同时也还可以作为一种工具，帮助我们提高对自己创造性思维过程的理解。




[延伸阅读][Google Creative Lab](https://experiments.withgoogle.com/ai?tag=TensorFlow)
[ai-duet](https://experiments.withgoogle.com/ai/ai-duet/view/)机器学习你如何弹钢琴
[sound-maker](https://experiments.withgoogle.com/ai/sound-maker/view/)用机器学习的各种乐器声音的混合体来创作音乐（将声音转化为更加抽象的数字表达之后再进行组合)
[handwriting](https://distill.pub/2016/handwriting/)

### Project List

[Sketch-RNN Demos - Draw together with a neural network](https://aiexperiments.withgoogle.com/sketch-rnn-demo)

[Sketch-RNN Demos](https://magenta.tensorflow.org/assets/sketch_rnn_demo/multi_vae.html)

[Google Creative Lab](https://experiments.withgoogle.com/ai?tag=TensorFlow)

### General Design Tools

[Most Common UX Design Methods and Techniques](https://research.googleblog.com/2017/04/teaching-machines-to-draw.html)

### MachineLeaarning-based Design Process & Tools

[Webs of Influence: The Psychology of Online Persuasion, 2nd Edition](https://www.safaribooksonline.com/library/view/webs-of-influence/9781292134628/?imm_mid=0f4ac0&cmp=em-design-na-na-newsltr_20170725_test)

[What Machine Learning Will Do For Design](https://medium.com/emergent-future/what-machine-learning-will-do-for-design-42661096f21)

:sparkles: 机器学习将为设计带来什么   作者：Eve Weinberg 

这是智能设计团队的ITP计划（ITP是一个为期两年的设在艺术学院的研究生课程：课程使命是探索通信技术的想象力的使用来探索如何提高技术带来的喜悦和如何更好的让艺术融入人们的生活。）：如何利用有才华的设计师来探索和机器学习设计工具的协同功能的预期案例。 智能设计团队由 [《Machine Learning forDesigners》](https://www.oreilly.com/learning/machine-learning-for-designers)的作者[Patrick Hebron](http://www.patrickhebron.com/)和[《Programming Design Systems》](https://programmingdesignsystems.com/)作者[Rune Madsen](https://runemadsen.com/)领头。 Patrick进行关于机器学习的指导和Rune进行关于设计系统的指导，引导着小组的表述和思考过程。

项目的设计挑战：设计一个logo
全文围绕一个具体的logo设计项目展开，展示了在有无机器学习系统合作情况下的整个设计流程的差异。机器学习在收集资料，排版，设计调整的过程中都为设计师提供了帮助。
1. 收集资料
您首先在客户简要介绍表中键入，告诉它您希望看到多少参考资料，花费多长时间查找每个参考，并让计算机处理这些信息。它搜索的数据库包括Dribbble和Pinterest的。 会产生一个可供选择的参考网格。 你把参考数限制在40，但是其中30个不太好，所以你选择你喜欢的只有10，再运行一次。想要向电脑解释为什么你喜欢你选择的10个？ 您有几种选择，从离散到非离散。 在离散的一边，你有一些像单选按钮：
◎我喜欢排版。 ◎我喜欢对比。 ◎我喜欢玩耍

在非离散的会话方面，你有自然语言处理。你可以谈论每一个选择。你选择完反馈方法之后，可以等待更多的参考。在几分钟的时间，你收到100多张参考图片。你喜欢其中的20个，所以现在你有一个更具体的30个图像的数据集来完善你的资料库。你可以进一步描述为什么你喜欢这些图像，冗长或简略。多次重复来让机器更好的理解你的选择。

2. 排版
电脑会显示一些字体，全部都应用在客户的名称上，并根据需要选择您喜欢的字体，并进行多轮修订。

3. 设计调整
你设计好之后，现在，由于这是您与计算机的第一个项目，它不知道您的风格或倾向，在未来的项目中将根据你曾经的设计对不同审美维度对你的设计风格进行加权。 它是审美的维度。设计师可以滑动样式参数（在左上方），并可以实时更新标志（右下方）。 设计师可以手工挑选图标和字体。 这3个类别中的任何一个需要被锁定，也是可以的。 例如，您有一种喜欢的字体，但您想将样式从“男性”更改为“女性”，不希望更改字体，就可以将字体锁定。
![shejitiaozheng](https://github.com/Tangchen329/Machine-Learning-for-Design/blob/master/Session00_LiteratureReviewOfML4D/Pictures/7-What%20Machine%20Learning%20Will%20Do%20For%20Design/7-gDJM4PkGDrxogklI7m2cLg.png)设计调整界面


总结：机器学习不是好的设计的灵丹妙药，也不是工作的破坏者。它仅仅是一种新工具。
设计人员可以通过这个新的工作流程更舒适，在设计过程中，他们会更多的时间享受认知和创造性的过程，更少的时间待在设计创作的沉闷中。
[演示视频][Video of ‘99designs.com’ onboarding](https://vimeo.com/185045206)
[Rethinking Design Tools in the Age of Machine Learning](https://medium.com/artists-and-machine-intelligence/rethinking-design-tools-in-the-age-of-machine-learning-369f3f07ab6c)

[Machine Learning and UX](https://medium.com/designer-hangout/machine-learning-and-ux-c28725b5f3a5)

[Machine Learning: The Speed-of-Light Evolution of AI and Design](https://redshift.autodesk.com/machine-learning/)

-------------------------------------------------------------------



## Design Products & Services with AI & Machine Learning Embedded in

### Reference List

[Human-Centered Machine Learning - 7 steps to stay focused on the user when designing with ML](https://medium.com/google-design/human-centered-machine-learning-a770d10562cd?imm_mid=0f4f22&cmp=em-design-na-na-newsltr_20170801)

### Project List


-------------------------------------------------------------------


## Other Topics related to ML and Design

[Machine Learning for Designers](http://www.oreilly.com/design/free/machine-learning-for-designers.csp)

[Machine Learning for Designers](http://pan.baidu.com/s/1eSOUudW)

[Machine Learning for Designers 解构脑图](https://zhuanlan.zhihu.com/p/27045885)

[5 Steps to Thinking Like a Designer in Machine Learning](http://machinelearningmastery.com/5-steps-to-thinking-like-a-designer-in-machine-learning/)

[A Machine-Learning Framework for Design for Manufacturability](https://arxiv.org/abs/1703.01499)

[Any good Product Design case studies that involve Machine Learning?](https://www.designernews.co/stories/75495-any-good-product-design-case-studies-that-involve-machine-learning)

[How influential is machine learning in the field of product design?](https://www.quora.com/How-influential-is-machine-learning-in-the-field-of-product-design)

[What designers need to know about machine learning](https://hackernoon.com/what-designers-need-to-know-about-machine-learning-109a12fdd3af)

[Algorithms, Machine Learning, AI and us designers](https://www.meetup.com/IxDA-London/events/232094087/)

[Dimensions of Machine Learning in Design](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.32.5541&rep=rep1&type=pdf)

[Applications Of Machine Learning For Designers](https://www.smashingmagazine.com/2017/04/applications-machine-learning-designers/)

[What Happens When You Apply Machine Learning To Logo Design](https://www.fastcodesign.com/3058852/what-happens-when-you-apply-machine-learning-to-logo-design)

[It’s Time for a Design Evolution in Machine Learning - Why the Best is Yet to Come](https://uxdesign.cc/its-time-for-a-design-evolution-in-machine-learning-6bfe7da3dcef)

[Why Should Designers And Product Managers Know About Machine Learning?](https://www.forbes.com/sites/quora/2017/04/07/why-should-designers-and-product-managers-know-about-machine-learning/#72cde9e07b28)

[Designing with Machine Learning](https://www.wework.com/zh-CN/blog/posts/designing-with-machine-learning)

[Adobe Is Building An AI To Automate Web Design. Should You Worry?](https://www.fastcodesign.com/3068884/adobe-is-building-an-ai-to-automate-web-design-should-you-worry)

[Teaching Machine Learning to Design Students](https://link.springer.com/chapter/10.1007/978-3-540-69736-7_23)

[Designing the User Experience of Machine Learning Systems](https://mikek-parc.github.io/AAAI-UX-ML/)

[Bow to your Sensei! Adobe adds machine learning and design tool to Creative Cloud](https://www.theregister.co.uk/2016/11/02/adobe_updates_creative_cloud_with_sensei_machine_learning_and_new_3d_design_tool/)

[Machine Learning and Design in IntuiFace - How IntuiFace uses machine learning to aid the creation of interactive and connected digital experiences](https://www.intuilab.com/machine-learning)

[Google AutoDraw uses machine learning to make a designer out of anyone](http://www.androidpolice.com/2017/04/11/google-autodraw-uses-machine-learning-make-designer-anyone/)

[Automation Threatens to Make Graphic Designers Obsolete - So what kind of career should you expect to have in future?](https://eyeondesign.aiga.org/automation-threatens-to-make-graphic-designers-obsolete/)

[HOW MACHINE LEARNING CAN SPEED UP YOUR DESIGN CYCLE](https://www.maximintegrated.com/en/design/blog/machine-learning-can-speed-up-design-cycle.html)

[设计与人工智能报告](https://zhuanlan.zhihu.com/p/26610724)

[设计与AI的现在Ⅰ：设计了1.7 亿个 banner的阿里鲁班](https://zhuanlan.zhihu.com/p/26563244)

[为男人们提供个性化服饰搭配，英国电商 Thread 获 800 万美金 A 轮融资](https://36kr.com/p/5036946.html)
