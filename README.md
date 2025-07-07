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
```

# Banner section hard code 

```html
 <section class="hero-container">
       <div>
      <h1>Welcome to my website</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur eos porro saepe, quibusdam possimus quia?</p>
      <button>Explore me</button>
       </div>
       <div>
   <img src="dev.png" alt="">
       </div>

       
     </section>
```

```css
body {
  max-width: 1270px;
  background-color: bisque;
  margin: 0 auto;
  padding: 25px;
  font-size: 1.25em;
}

.hero-container {
  display: flex;
  align-items: center;
  gap: 40px;
  background-color: antiquewhite;
  border-radius: 25px;
}
.hero-container button {
  background-color: aqua;
  padding: 10px 30px;
  font-size: 1.25em;
  border-radius: 10px;
  cursor: pointer;
  
}
.hero-container img {
  width: 100%;
  height: 400px;
  border-radius: 25px;
}
```