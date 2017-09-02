#TMUX 快捷键
<table class="inline " style="padding:0px; margin:0px 0px 1em; font-size:13px; border-spacing:0px; border-collapse:collapse">
<tbody style="padding:0px; margin:0px">
<tr class="row0" style="padding:0px; margin:0px">
<td class="col0 centeralign" colspan="2" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Ctrl&#43;b</td>
<td class="col2" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
激活控制台；此时以下按键生效</td>
</tr>
<tr class="row1" style="padding:0px; margin:0px">
<td class="col0" rowspan="9" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
系统操作</td>
<td class="col1 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
?</td>
<td class="col2" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
列出所有快捷键；按q返回</td>
</tr>
<tr class="row2" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
d</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
脱离当前会话；这样可以暂时返回Shell界面，输入tmux attach能够重新进入之前的会话</td>
</tr>
<tr class="row3" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
D</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
选择要脱离的会话；在同时开启了多个会话时使用</td>
</tr>
<tr class="row4" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Ctrl&#43;z</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
挂起当前会话</td>
</tr>
<tr class="row5" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
r</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
强制重绘未脱离的会话</td>
</tr>
<tr class="row6" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
s</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
选择并切换会话；在同时开启了多个会话时使用</td>
</tr>
<tr class="row7" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
:</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
进入命令行模式；此时可以输入支持的命令，例如kill-server可以关闭服务器</td>
</tr>
<tr class="row8" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
[</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
进入复制模式；此时的操作与vi/emacs相同，按q/Esc退出</td>
</tr>
<tr class="row9" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
~</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
列出提示信息缓存；其中包含了之前tmux返回的各种提示信息</td>
</tr>
<tr class="row10" style="padding:0px; margin:0px">
<td class="col0" rowspan="10" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
窗口操作</td>
<td class="col1 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
c</td>
<td class="col2" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
创建新窗口</td>
</tr>
<tr class="row11" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
&amp;</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
关闭当前窗口</td>
</tr>
<tr class="row12" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
数字键</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
切换至指定窗口</td>
</tr>
<tr class="row13" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
p</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
切换至上一窗口</td>
</tr>
<tr class="row14" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
n</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
切换至下一窗口</td>
</tr>
<tr class="row15" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
l</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
在前后两个窗口间互相切换</td>
</tr>
<tr class="row16" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
w</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
通过窗口列表切换窗口</td>
</tr>
<tr class="row17" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
,</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
重命名当前窗口；这样便于识别</td>
</tr>
<tr class="row18" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
.</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
修改当前窗口编号；相当于窗口重新排序</td>
</tr>
<tr class="row19" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
f</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
在所有窗口中查找指定文本</td>
</tr>
<tr class="row20" style="padding:0px; margin:0px">
<td class="col0" rowspan="14" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
面板操作</td>
<td class="col1 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
”</td>
<td class="col2" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
将当前面板平分为上下两块</td>
</tr>
<tr class="row21" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
%</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
将当前面板平分为左右两块</td>
</tr>
<tr class="row22" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
x</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
关闭当前面板</td>
</tr>
<tr class="row23" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
!</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
将当前面板置于新窗口；即新建一个窗口，其中仅包含当前面板</td>
</tr>
<tr class="row24" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Ctrl&#43;方向键</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
以1个单元&#26684;为单位移动边缘以调整当前面板大小</td>
</tr>
<tr class="row25" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Alt&#43;方向键</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
以5个单元&#26684;为单位移动边缘以调整当前面板大小</td>
</tr>
<tr class="row26" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Space</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
在预置的面板布局中循环切换；依次包括even-horizontal、even-vertical、main-horizontal、main-vertical、tiled</td>
</tr>
<tr class="row27" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
q</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
显示面板编号</td>
</tr>
<tr class="row28" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
o</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
在当前窗口中选择下一面板</td>
</tr>
<tr class="row29" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
方向键</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
移动光标以选择面板</td>
</tr>
<tr class="row30" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
{</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
向前置换当前面板</td>
</tr>
<tr class="row31" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
}</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
向后置换当前面板</td>
</tr>
<tr class="row32" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Alt&#43;o</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
逆时针旋转当前窗口的面板</td>
</tr>
<tr class="row33" style="padding:0px; margin:0px">
<td class="col0 centeralign" style="padding:3px; margin:0px; text-align:center; border:1px solid rgb(140,172,187)">
Ctrl&#43;o</td>
<td class="col1" style="padding:3px; margin:0px; border:1px solid rgb(140,172,187)">
顺时针旋转当前窗口的面板<br>
</td>
</tr>
</tbody>
</table>
<div>
我已经尝试了在~/.tmux.conf中添加set -g default-terminal "screen-256color",但还是不行，也尝试了在.bashrc中添加alias tmux="tmux -2"
</div>
<div>
  set -g mouse-resize-pane on
set -g mouse-select-pane on
set -g mouse-select-window on

set -g mode-mouse on

bind S setw synchronize-panes on
bind F setw synchronize-panes off
</div>

