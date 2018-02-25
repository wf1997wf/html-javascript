做好的东西要和小伙伴连接了，很开心。
要在小伙伴的代码里加气泡，no problem~
no！！！小伙伴用的是d3，看不懂！！！
好吧，我又学会了用d3。

.append（）添加。。。
.attr（"A","B"或function（d）{
	return d.xx;//d代表data（）中的。。
}）把A的值改为B...
.transition()//启动过渡
.duration(2000)//过渡的持续时间，单位毫秒
.ease("bounce")//过渡的方式：linear：线性变化，circle：慢慢的到达终态，elastic：弹跳的到达，bounce：在终态处弹跳
.delay(500)//延迟一段时间再开始过渡，单位毫秒.500可换为function（）{。。。}使不同图形的时间不同

动作添加：
node.select("circle")
    .on('click',function(d){
        self.location.href="http://127.0.0.1:5000/hh";
    })