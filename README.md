<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Simple Calculator</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="calculator" role="application" aria-label="Simple calculator">
    <div class="display" id="display" aria-live="polite">0</div>

    <div class="buttons" role="group" aria-label="Calculator keys">
      <!-- Row 1 -->
      <button class="btn control" data-action="clear" aria-label="All clear">AC</button>
      <button class="btn control" data-action="delete" aria-label="Delete">DEL</button>
      <button class="btn control" data-value="%" aria-label="Percent">%</button>
      <button class="btn operator" data-value="÷" aria-label="Divide">÷</button>

      <!-- Row 2 -->
      <button class="btn" data-value="7" aria-label="Seven">7</button>
      <button class="btn" data-value="8" aria-label="Eight">8</button>
      <button class="btn" data-value="9" aria-label="Nine">9</button>
      <button class="btn operator" data-value="×" aria-label="Multiply">×</button>

      <!-- Row 3 -->
      <button class="btn" data-value="4" aria-label="Four">4</button>
      <button class="btn" data-value="5" aria-label="Five">5</button>
      <button class="btn" data-value="6" aria-label="Six">6</button>
      <button class="btn operator" data-value="-" aria-label="Subtract">−</button>

      <!-- Row 4 -->
      <button class="btn" data-value="1" aria-label="One">1</button>
      <button class="btn" data-value="2" aria-label="Two">2</button>
      <button class="btn" data-value="3" aria-label="Three">3</button>
      <button class="btn operator" data-value="+" aria-label="Add">+</button>

      <!-- Row 5 -->
      <button class="btn zero" data-value="0" aria-label="Zero">0</button>
      <button class="btn" data-value="." aria-label="Decimal point">.</button>
      <button class="btn equals" data-action="equals" aria-label="Equals">=</button>
    </div>
  </main>

  <script src="script.js" defer></script>
</body>
</html>
