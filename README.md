## Welcome to My GitHub Pages, Share Data together!

[阿里云python免费课程地址](https://edu.aliyun.com/roadmap/python?spm=5176.8764702.dnewclick.ddawen.153c4679L1uThU)

You can use the [editor on GitHub](https://github.com/renxiulong/renxiulong.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/renxiulong/renxiulong.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.  
学习Jekyll的[博客](http://ju.outofmemory.cn/entry/126281)
### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
{% for post in site.posts %}
  <li style="display:none">
    <a href="{{ post.url }}">{{ post.title }}</a>
    <a href="{{ post.url }}">{{ post.date }}</a>
  </li>
{% endfor %}
{% for post in site.posts %}
   > [{{ post.title }} {{ post.date }}]({{ post.url }})   
   >> {{ post.excerpt | remove: 'test' }}   
   ***
{% endfor %}
