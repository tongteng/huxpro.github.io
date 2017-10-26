---
layout:     post
title:      "CSS总结"
date:       2017-10-25 23:00:00
author:     "HandSomeTT"
header-img: "img/post-bg-css.jpg"
tags:
    - CSS
    - 面试总结
---

> 在这个收割offer的季节，我在干嘛？专注玩蛇二十余年。

# 题目和答案

<br>

<div>
	<ul>
		<li>
			<strong><em>如何引入CSS？</em></strong><br>
			<blockquote>
				<p>(1): 行间样式 &lt;div style="..."&gt;&lt;/div&gt;</p><br>
				<p>(2): 通过style标签</p><br>
				<p>(3): 引入外部css文件</p><br>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em>CSS有哪些选择器？</em></strong><br>
			<blockquote>
				<p>(1): id选择器(#id)</p><br>
				<p>(2): class选择器(.class)</p><br>
				<p>(3): 标签选择器(div,p,h1)</p><br>
				<p>(4): 相邻选择器(div+p)</p><br>
				<p>(5): 父子选择器(ul>li)</p><br>
				<p>(6): 后代选择器(li a)</p><br>
				<p>(7): 通配符选择器(*)</p><br>
				<p>(8): 伪类选择器(a:hover)</p><br>		
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em>CSS选择器的权重? </em></strong><br>
			<blockquote>
				<p>!important		正无穷</p><br>
				<p>行间样式		      1000</p><br>
				<p>id选择器		   100</p><br>
				<p>class|伪类|属性	   10</p><br>
				<p>标签|伪元素		   1</p><br>
				<p>通配符*				 0</p><br>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em>盒模型？</em></strong><br>
			<blockquote>
				<p>分为W3C盒模型，还有IE盒模型，两者的区别就是给的盒子的宽高包括什么。</p><br>
				<p>W3C盒模型中，盒子大小 = 给的大小(content) + padding + border。 content为给的宽高。box-sizing: content-box</p><br>
				<p>IE盒模型中，盒子大小 = 给的大小。 而content = 盒子大小 - padding - border。 box-sizing: border-box</p><br>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em>如何居中一个div? </em></strong><br>
			<blockquote>
				<p>如果给定宽高水平居中的话：margin: 0 auto;</p><br>
				<p>如果给定宽高水平垂直居中：<br>
					&nbsp;&nbsp;&nbsp;&nbsp;width: 100px;<br>
					&nbsp;&nbsp;&nbsp;&nbsp;height: 100px;<br>
					&nbsp;&nbsp;&nbsp;&nbsp;position: absolute;<br>
					&nbsp;&nbsp;&nbsp;&nbsp;left: 50%;<br>
					&nbsp;&nbsp;&nbsp;&nbsp;top: 50%;<br>
					&nbsp;&nbsp;&nbsp;&nbsp;margin-left: -50px;<br>
					&nbsp;&nbsp;&nbsp;&nbsp;margin-top: -50px;
				</p><br>
				<p>
					如果未给定宽高：
					<ul>
						<li>
							<p>使用CSS3中的translate进行平移</p>
							&nbsp;&nbsp;&nbsp;&nbsp;position: absolute;<br>
							&nbsp;&nbsp;&nbsp;&nbsp;left: 50%;<br>
							&nbsp;&nbsp;&nbsp;&nbsp;top: 50%;<br>
							&nbsp;&nbsp;&nbsp;&nbsp;transform: translate(-50%, -50%);<br>
						</li><br>
						<li>
							<p>Flex布局</p>
							在父级元素中<br>
							.container {<br>
								&nbsp;&nbsp;&nbsp;&nbsp;display: flex;<br>
								&nbsp;&nbsp;&nbsp;&nbsp;align-items: center;<br>
								&nbsp;&nbsp;&nbsp;&nbsp;justify-content: center;<br>
							}
						</li>
					</ul>
				</p>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em>三栏布局？</em></strong><br>
			<blockquote>
				<p>
					通过float方法：
					&nbsp;&nbsp;.left.right{<br>
						&nbsp;&nbsp;&nbsp;&nbsp;width: 100px;<br>
						&nbsp;&nbsp;&nbsp;&nbsp;height: 100px;<br>
					}<br>
					&nbsp;&nbsp;.left{<br>
						&nbsp;&nbsp;&nbsp;&nbsp;float: left;<br>
					}<br>
					&nbsp;&nbsp;.right{<br>
						&nbsp;&nbsp;&nbsp;&nbsp;float: right;<br>
					}<br>
					&nbsp;&nbsp;.mid{<br>
						&nbsp;&nbsp;&nbsp;&nbsp;width: 100%;<br>
						&nbsp;&nbsp;&nbsp;&nbsp;height: 100%;<br>
						&nbsp;&nbsp;&nbsp;&nbsp;margin-left: 100px;<br>
						&nbsp;&nbsp;&nbsp;&nbsp;margin-right: 100px;<br>
					}
				</p><br>
				<p>
					通过绝对定位方法：
				</p><br>
				<p>
					通过flex布局方法：
				</p><br>				
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em></em></strong><br>
			<blockquote>
				<p></p><br>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em></em></strong><br>
			<blockquote>
				<p></p><br>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em></em></strong><br>
			<blockquote>
				<p></p><br>
			</blockquote>
		</li>
		<br>
		<li>
			<strong><em></em></strong><br>
			<blockquote>
				<p></p><br>
			</blockquote>
		</li>
		<br>
	</ul>
</div>
