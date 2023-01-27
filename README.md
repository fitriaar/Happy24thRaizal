<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <title>Happy Birthday</title>
    <style type="text/css">
      .container-fluid {
  background: #f09433; 
  background: -moz-linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%); 
  background: -webkit-linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); 
  background: linear-gradient(45deg, #f09433 0%,#e6683c 25%,#dc2743 50%,#cc2366 75%,#bc1888 100%); 
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f09433', endColorstr='#bc1888',GradientType=1 );
  min-height: 120vh;
  display: inline-block;
}
.happy {
  margin-top: 14%;
  margin-bottom: 14%;
  text-align: center;
  color: white;
  font-weight: 600;
  font-size: 80px;
}
#lihat {
  border: 2px solid white;
  background: transparent;
  color: white;
  margin-top: -120px;
}
#lihat:hover {
  color: black;
  border: 2px solid black;
}
div.card {
  background: white;
  border-radius: 20px;
  padding: 10px;
}
    </style>
  </head>
  <body>
    <!-- Add Typewriter -->
    <div class="container-fluid">
      <div class="happy">
        <div id="app"></div><br>
        <a id="lihat" class="btn" href="#ucapan">Lihat Ucapan!</a>
      </div>
      <div id="ucapan" class="cardouter row row-cols-1 row-cols-md-2 g-4">
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">"selamat ulang tahun sayangku!"</h5>
              <p class="card-text">- mau peluk kamu huaaaaaa T-T </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">"Sayang, walaupun aku jauh, tapi doaku terbaik untuk kamu selalu"</h5>
              <p class="card-text">- i need you!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">"jangan nakal nakal disana, jangan aneh aneh disana, disini aku yang panik karna belum berani naik kapal kelampung :("</h5>
              <p class="card-text">- i miss you! </p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">"jaga diri baik-baik, harus tambah rajin minumnya gabole males males, rajin makannya biar semakin setrong, rajin solatnya ya mas ganteng dan berdoa semoga selalu dalam lindungan Allah serta diberikan segala kemudahan dan kelancaran atas apa yang kamu lakukan disana!"</h5>
              <p class="card-text">- i love you! </p>
            </div>
          </div>
        </div>
      </div>
    </div>


    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->
    <!-- Typewriter -->
    <script src="https://unpkg.com/typewriter-effect@latest/dist/core.js"></script>
    <script type="text/javascript">
      var app = document.getElementById('app');
      var typewriter = new Typewriter(app, {
        loop: true,
        delay: 75,
      });

      typewriter
        .pauseFor(2500)
        .typeString('HELLO RAIZAL!')
        .pauseFor(300)
        .deleteChars(6)
        .typeString('THIS IS YOUR DAY!')
        .deleteChars(15)
        .typeString('HAPPY B'DAY TO YOU!')
        .pauseFor(1000)
        .start();
    </script>
  </body>
</html>
