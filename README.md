# js实现圆形动画
###
可调参数的圆形动画
```
//参数设置
Obj = {
        showFlag: false,//显示隐藏
        timer: null,//定时器
        _timer: null,//定时器
        position: 't',//组件所处页面位置
        radius: 250, //大圆半径
        cell_r: 10,//小圆半径r
        centerX: 250,//组件圆心坐标x
        centerY: 250,//组件圆心坐标y
        totalTime: 100,//动画持续时间(改为速率是否更恰当？)
        part: 1 ,//占圆的几分之几
        transNum: 0,//起始偏移角度值设置
    }
```
