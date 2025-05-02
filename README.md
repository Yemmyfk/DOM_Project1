<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
    <div>
        <h1>Product</h1>
        <p>Price<span> $ 1000</span></p>
        <p>Quantity<span id="quantity"> 0</span></p>
        <button id="btn1">-</button>
        <button id="btn2">+</button>
    </div>

    <script>
        let btn = document.getElementById('btn2')

        let btn1 = document.getElementById('btn1')

        let qt = 0
        btn.addEventListener('click',  function(){
            document.getElementById('quantity').innerHTML = qt++
        })

        btn1.addEventListener('click',  function(){
            document.getElementById('quantity').innerHTML = qt--
        })

    </script>
</body>
</html>
