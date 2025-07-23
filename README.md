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

#  card - section 

```html
 <main>
    <section class="card-section">
    <h2>Our Products</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis pariatur sapiente reiciendis.</p>
    <div class="card-container">
      <div class="card">
        <img src="camera.png" alt="">
        <h3>Canon camera 2.5</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste, porro voluptas qui fugit inventore doloribus animi architecto saepe, culpa, omnis quam quos sunt delectus veniam?</p>
        <button>Buy now</button>
      </div>
      <div class="card">
        <img src="camera.png" alt="">
        <h3>Canon camera 2.5</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iste, porro voluptas qui fugit inventore doloribus animi architecto saepe, culpa, omnis quam quos sunt delectus veniam?</p>
        <button>Buy now</button>
      </div>

    </div>
    </section>
  </main>
```

- css part 

```css
body{
  max-width: 1170px;
  /* background-color: bisque; */
  margin: 0 auto;
}
.card-container{
  display: flex;
  gap: 50px;
  flex-wrap: wrap;
  margin: 0 auto;
  justify-content: center;

}
.card {
  width: 300px;
  border: 2px solid sandybrown;
  border-radius: 10px;
  padding: 10px;
  text-align: left;
  box-shadow: 5px 5px rgba(0, 0, 0, 0.037);
}
.card h3 {
  font-size: 1.25em;
  font-weight: 700;
}
.card img {
  width: 100%;
  border-radius: 10px;
}

.card button {
    background-color: aqua;
  padding: 10px 30px;
  font-size: 1.25em;
  border-radius: 10px;
  cursor: pointer;
}
.card:hover {
  background-color: rgba(255, 239, 213, 0.363);
} 
```

# Relative absolute 

```html 
<div class="holiday_img">
      <img id="discount" src="images/Group 44.png" alt="">
      <img id="box" src="images/Group 75.png" alt="">
      <img id="ractangle" src="images/Rectangle 2.png" alt="">
    </div>
```

```css
.holiday_img {
  position: relative;
  margin-top: 50px;
  width: 100%;
  height: 300px;
  overflow: hidden;
}

#rectangle {
  width: 100%;
  position: absolute;
  bottom: 0;
  left: 0;
  z-index: 1;
}


#box {
  position: absolute;
  bottom: 40px;
  left: 50px;
  z-index: 2;
  height: 200px; 
}


#discount {
  position: absolute;
  top: 40px;
  right: 50px;
  z-index: 3;
  height: 100px; 
}
```

# Two column flex and use media query with flex direction 

```html
<body>
  <div class="container">
    <div>
   <img src="tiger.png" alt="">
    </div>
    <div>
 <img src="vegetable.png" alt="">
    </div>
  </div>
</body>
```

```css
 <style>
    body {
      max-width: 1280px;
      margin: 1 auto;
    }
    .container{
      display: flex;
    }
    .container div{
      width: 50%;
    }
    .container img {
      width: 100%;
    }
    @media  screen and (max-width:576px) {
        .container {
          flex-direction: column-reverse;
        }
        .container div {
          width: 100%;
        }
    }
  </style>
  ```


  ## Complex layout with grid 

  - repo link: https://github.com/shohan12727/Raw-projects/blob/main/tasks/task_two.html 


  # complex layout with grid 

  - repo link: https://github.com/shohan12727/Raw-projects/tree/main/layout