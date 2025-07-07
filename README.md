# 📝 My Note

## ✅ Nav Bar with Raw CSS

This is a basic navigation bar implemented using raw HTML and CSS (no frameworks used).

---

## 📄 HTML Part

```html
<header>
  <nav>
    <ul>
      <li><a href="blogs.html">Blogs</a></li>
      <li><a href="center.html">Center</a></li>
      <li><a href="flex.html">Flex</a></li>
      <li><a href="table.html">Table</a></li>
      <li><a href="form.html">Blogs</a></li>
      <li><a href="auto.html">Margin auto</a></li>
    </ul>
  </nav>
</header>
``` 


- css part 



```css

nav ul {
  display: flex;
}

nav ul li {
  list-style: none;
  margin: 10px;
}

nav ul li a {
  text-decoration: none;
  color: black;
}

nav ul li a:hover {
  background-color: lightgray;
}
