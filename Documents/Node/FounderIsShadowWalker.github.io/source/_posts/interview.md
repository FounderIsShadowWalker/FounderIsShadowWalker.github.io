---
title: 面试阿里有感
date: 2017-03-15 21:19:52
tags: [生活, 工作]
---

##  <b>第一次面试阿里</b>

   <p style='text-indent: 2em'>第一次面试阿里的时候大约是去年暑假的时候，受豪情老师鼓励，第一次尝试面试阿里，这里感谢何幻老师投递了简历，让我有机会能感受一下阿里的选拔，一面是何幻老师亲自问的，闭包，原型链，bfc直接跳过吧，问了一些react相关的，坦白说那个时候自己刚接触react，停留在知识点很朦胧的问题，问了react diff算法的问题，和key的作用，很不幸，两个都没答上。
   总结一下阿里一面：js基础 css基础。基础的学习没有捷径的，无非就是实打实啃一些原理的书，高程，js面向对象编程都是不错的选择。

<!--more-->
   一个月后，阿里二面了，二面的主考官语气很威严，面试的时候很担心是自己的学校不好让对方不满意，加上这是自己第一次面试，说一句瑟瑟发抖真的不为过。二面先问有没有做过什么项目，我说没有，坦白说垃圾学校跟老师做的项目说了还不如不说，当时是这样想的。然后问我懂不懂跨域，我说知道iframe和jsonp。然后简单描述了一下jsonp的原理，之前写一个原生的ajax库，属性是支持jsonp，这个问题答得很好，然后主考官问了，页面有多个jsonp 怎么区别各个callback，没答上，很紧张。其实不难，在库的入口绑个id，在闭包外，每次调用＋1，类似uuid。然后和前端约定好，callback就用这个uuid，可以挂在window下。面完之后，气的在床上打滚。第二个问题，是怎么能在一个固定长宽的容器内正常显示长宽不定的图片。我的回答是按照容器的长宽对图片进行等比例缩放。很遗憾，这个回答，主考官也不是很满意。然后这场面试以失败告终。
   总结一下阿里二面：有项目经验是最棒的，不然不知道聊什么，这个时候大多拼应急能力了，然后一定要冷静。

   </p> 


 ##  <b>第二次面试阿里</b>  

   <p style='text-indent: 2em'> 
    2017年7.17 这个日子给的准确是因为某一位好心的阿里系员工帮我查看了一下，事毕业前校招的最后一次机会了。一面还是老生长谈，基础云云就跳过了。
    二面的时候是canvas 方向的，问的是一些具体的问题，在我github上的repo下，有一些3d球，和环形的demo，主考官对这些很感兴趣，回答的差强人意吧，这些repo已经是很早的demo了，经历了武汉2个月的java，和美团的react学习，canvas很多细节真的记不住了，就把自己的思路简单的过了一遍，然后全部说出来了，主考官沉了一下，感觉还算满意把。然后问了一个canvas 视频帧的问题，问的是如何用少数的帧尽可能播放流畅的视频，当时蒙了，着什么问题啊？想了一回，回答了：对不同的视频帧diff把，弄个相似度做阈值。在做个阈值内的不播放。主考官说：一帧的diff的单位是像素点，你确定做diff会比播放节省性能吗？ 然后就不说话了，确实没做过性能优化，也不好随便给答案，补充了一句，diff的canvas 可以放在离屏canvas里做，感觉尽力了，显然，主考官不是很满意。
    第二次二面：比第一次面试的冷静了，可以正常的思考了，还是缺乏深度的思考，不得不说 阿里对学习深度的考察是深的，最好有一些扩展性。
   </p>


## <b>总结</b>  
   <p style='text-indent: 2em'> 
    学习不是一蹴而就的过程，多半是磕磕绊绊的过程，遇到困难，解决困难，总结困难。 学习的过程中失败在所难免，希望自己能从失败中吸取教训，成为更优秀的自己。
    <img src='http://oymaq4uai.bkt.clouddn.com/922281957.jpg'/>
   </p>
