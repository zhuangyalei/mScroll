# mScroll  移动端 滑动回弹事件封装

## 传参
### init: {
	wrap: el, 滑动区域
	scroll: el, 移动的元素 (一般移动的元素wrap.chilren[0])
	[dir:('x'|'y')] dir 滑动方向默认为Y默认y
	over: "ease","backOut","none" 超出之后，需要怎么处理(ease：平滑回来，backOut：回弹，none:不允许超出)
	showBar: (true||false) 是否显示滚动条,默认值为true
	start:fn 按下时的回调
	move: fn 移动时的回调
	up: fn 抬起时的回调
	end: fn 动画结束时的回调 
}

