# deepEase
Deep-Ease基本动效库

use
    
    var box = document.getElementById('box')
    var change = {
        height : 400,
        width : 400,
        opacity : 0.3,
        left: 500
    } 

    deepEase(box , change , 500 , 'easeInBack') 
    
    // box - 需要动画的元素
    // change - 需要改变的属性
    // 500 - time，时间
    // 'easeInBack' 30+ ease动画可选