<marquee behavior="scroll" direction="right" bgcolor="antiquewhite">打地鼠</marquee>
onMouseOut="this.start()" ：用来设置鼠标移出该区域时继续滚动
onMouseOver="this.stop()"：用来设置鼠标移入该区域时停止滚动
<marquee id="affiche" align="left" behavior="scroll" bgcolor="#FF0000" direction="up" height="300" width="200" hspace="50" vspace="20" loop="-1" scrollamount="10" scrolldelay="100" onMouseOut="this.start()" onMouseOver="this.stop()">
这是一个完整的例子
</marquee>//该标签支持的属性多达11个
align=""对齐方式
absbottom：绝对底部对齐（与g、p等字母的最下端对齐）
absmiddle：绝对中央对齐
baseline：底线对齐
bottom：底部对齐（默认）
left：左对齐
middle：中间对齐
right：右对齐
texttop：顶线对齐
top：顶部对齐
——————————————————————————————————————————————————————
behavior设定滚动的方式：
alternate： 表示在两端之间来回滚动。
scroll：表示由一端滚动到另一端，会重复。
slide：表示由一端滚动到另一端，不会重复。
————————————————————————————————————————————————————————
direction设定活动字幕的滚动方向
direction="down"：向下
direction="left"：向左
direction="right"：向右
direction="up"：向上
