---
layout: home
---

<div class="index-content project">
    <div class="section">
        <ul class="artical-cate">
            <li><a href="/"><span>团队介绍</span></a></li>
            <li style="text-align:center"><a href="/dump"><span>学习交流</span></a></li>
            <li class="on" style="text-align:right"><a href="/project"><span>工作剪影</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.project %}
            <li>
                <h2>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
    <div class="friend-site-list">
            Friend Site:
            <a class="friend-site" href="https://www.baidu.com">Group1</a> 
            <a class="friend-site" href="https://www.zhihu.com">Group2</a>
            <a class="friend-site" href="https://www.163.com">Group3</a>            
    </div>
</div>
