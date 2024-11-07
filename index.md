---
title: "My Tech Blog"
layout: default
---

# Welcome to My Tech Blog! 🚀

I’m excited to share my journey through topics like kernel development, cybersecurity, and other tech projects. Below, you’ll find a collection of my blog posts. Feel free to explore and let me know what you think!

---

## 📖 Recent Blog Posts

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** <br>
  <small>Published on {{ post.date | date: "%B %d, %Y" }}</small>  
  {{ post.excerpt | strip_html | truncatewords: 30 }}
  <br><br>
{% endfor %}

---

Thanks for stopping by! Feel free to reach out if you'd like to connect.  
📬 [GitHub](https://github.com/yourusername) | [LinkedIn](https://www.linkedin.com/in/yourusername) | [Email Me](mailto:youremail@example.com)

*Made with ❤️ by [Your Name](https://github.com/yourusername)*
