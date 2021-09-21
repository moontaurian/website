# website
trial
<!DOCTYPE html>
<html>
<head>
<style>
header { grid-area: header; }
nav { grid-area: menu; }
main { grid-area: main; }
aside { grid-area: right; }
footer { grid-area: footer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'menu header header header header header'
    'menu main main main right right'
    'footer footer footer footer footer footer';
  grid-gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}

.grid-container * {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}
</style>
</head>
<body>

<h1>Grid Layout</h1>

<p>This grid layout contains six columns and three rows:</p>

<div class="grid-container">
  <header>Header</header>
  <nav>Menu</nav>
  <main>Price 0 &yen</main>  
  <aside>Right</aside>
  <footer>&copy; w3school</footer>
</div>

</body>
</html>
