
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />

    <!-- bootstrap icon -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">
<!-- font -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Merriweather+Sans:ital@1&display=swap" rel="stylesheet">
<link rel="stylesheet" href="fontawesome/fontawesome-free-6.0.0-beta3-web/css/all.min.css">

<!-- my css -->
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="img/projects/logo.jpeg" type="image/x-icon">
    <title>Agro Indo Jaya</title> 
  
  #products {
  background-color: #73cef1;
}

h1 {
  text-align: center;
}

#collapse {
  font-family: "Merriweather Sans", sans-serif;
}

.section {
  padding-top: 6rem;
}

.carousel-item {
  height: 500px;
  width: 1200px;
}

.nama-tim {
  font-size: 20px;
}

.new-tim {
  background-color: #73cef1;
}

.nav-item :hover {
  transform: scale(1.2);
  transition: 0, 2s;
}

.img-title {
  position: absolute;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(to bottom, rgba(5, 5, 5, 0), rgba(5, 5, 5, 1));
  top: 400px;
  transition: all 0.2s ease-in;
}

.img-title p,
h3 {
  text-align: center;
  color: rgb(255, 255, 255);
  line-height: 20px;
  position: relative;
  top: 100px;
  text-shadow: rgba(5, 5, 5, 0.5);
}

.card:hover .img-title {
  top: 0;
  transition: all 0.2s ease-out;
}

.container1 {
  width: 1056px;
  height: 980px;
  background-color: #73cef1;
  margin: auto;
  display: flex;
  flex-wrap: wrap;
}

.card {
  display: flex;
  position: relative;
  overflow: hidden;
  border: 10px;
}

.card img {
  transform: scale(1);
  transition: all 0.3s ease-out;
}

.card:hover img {
  transform: scale(1.1);
  transition: all 0.3s ease-in;
}

@media screen and (max-width: 1056px) {
  .container1 {
    width: 100%;
    height: 100%;
  }
  .card {
    width: 30%;
    height: 15%;
  }

  .img-title {
    position: absolute;
  }
  .img-title p,
  h3 {
    top: 10px;
    font-size: 8pt;
    line-height: 10px;
  }
}
  
  </head>
  <!-- header -->
    <div class="container-fluid p-5 border-bottom" id="collapse" style="background-color: #566ef8">
      <div class="text-center text-white">
        <h1>AGRO INDO JAYA</h1>
      </div>
    </div>
  <!-- akhir header -->

  <body id="home">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark shadow-sm Text-bold" style="background-color:#566ef8">
      <div class="container fs-4">
        <a class="navbar-brand" data-bs-toggle="collapse" data-bs-target="#collapse" aria-expanded="false" aria-controls="collapseExample" href="#">
          <img src="img/projects/logo.jpeg" alt="" width="50" height="50" class="rounded-circle" class="d-inline-block align-text-top">
        </a>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#products">Our products</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- Akhir Navbar -->

    <!-- carousel -->
    <div class="container mt-5 mb-5">
    <div id="carouselExampleIndicators" class="carousel slide mx-0" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="img/projects/2.jpeg" class="d-block img-fluid w-100" alt="mango">
    </div>
    <div class="carousel-item">
      <img src="img/projects/manggaiki.jpg" class="d-block img-fluid w-100" alt="mango">
    </div>
    <div class="carousel-item">
      <img src="img/projects/New folder/salak.jpg" class="d-block img-fluid w-100" alt="mangosteen">
    </div>
    <div class="carousel-item">
      <img src="img/projects/m1.jpg" class="d-block img-fluid w-100" alt="mango">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>
    <!-- akhir carousel -->
    <!-- about -->
    <section id="about">
        <div class="container">
            <div class="row text-center mb-3">
                <div class="col">
                <h1>About Us</h1>
                </div>
            </div>
            <div class="row justify-content-center fs-5">
                <div class="col-8 text-center">
                  Since 2017 our company has collaborated with registered local farmers to produce fresh fruit and market it to local and modern markets. <br> our company is starting to expand to provide our products to the international market
                </div>
            </div>
            <div class="row text-center fs-5">
              <div class="col justify-content-center">
                <br><br><i class="bi bi-gem fs-1"></i>
                <br><h2>Our Quality</h2>
                <p>our company is committed to serve customers with the best possible to get the best products. our team directly supervises the production system, grading system, and packing strictly</p>
              </div>
            </div>
            <div class="row text-center fs-5">
              <div class="col justify-content-center">
                <br><br><i class="fas fa-handshake fs-1"></i>
                <br><h2>Commitment and Integrity</h2>
                <p>Integrity means doing business honestly, speaking the truth, treating our partner with good services and respectfully. <br>
                  we are committed to have a positive impact on farmers as our suppliers to be more prosperous</p>
              </div>
            </div>
            <div class="row text-center fs-5">
              <div class="col justify-content-center">
                <br><br><i class="bi bi-box-seam fs-1"></i>
                <br><h2>Production and Packaging</h2>
                <p>In our production warehouse, we work with experienced team and keep learning with new technology. <br>
                  our packaging uses various types of packaging according to the market needed (Cardboard, Wood, Plastic, Europool, Esteco)</p>
              </div>
            </div>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#73cef1" fill-opacity="1" d="M0,256L48,240C96,224,192,192,288,170.7C384,149,480,139,576,165.3C672,192,768,256,864,240C960,224,1056,128,1152,122.7C1248,117,1344,203,1392,245.3L1440,288L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
    </section>
    <!-- akhir about -->

    <!-- Product -->
    <section id="products">
        <div class="container">
            <div class="row text-center mb-3 p-3">
                <div class="col">
                    <h1>Our Product</h1>
                </div>
            </div>
        </div>
            <div class="container1 justify-content-center">
                    <div class="card">
                        <img src="img/projects/New folder/mangga3.jpg" class="img-fluid" alt="Mango">
                          <div class="img-title">
                            <h3>Mango</h3>
                            <p>Harum Manis Mango <br>
                            Harvest time : June-December <br>
                          weight avg 400 gram up <br> color : green <br> Maturity : 80% <br> Packing with cardboard box 12 pcs 5 kg </p>
                          </div>
                    </div>    
                
                    <div class="card">
                        <img src="img/projects/New folder/buahnaga.jpg" class="img-fluid" alt="Dragon fruit">
                        <div class="img-title">
                          <h3>Dragonfruit</h3>
                          <p> Harvest time : September-March <br> Size : 3/4 fruits/kg <br> Red or white flesh of fruits <br> Fin : green leaves
                            Maturity : 70% <br> Color : pink to red well covered </p>
                          </div>
                    </div>

                    <div class="card">
                      <img src="img/projects/New folder/maanggis.jpg" class="img-fluid" alt="Mangosteen">
                        <div class="img-title">
                          <h3>Mangosteen</h3>
                          <p> Harvest time : November-March <br> Size : 8-10 fruits/kg <br>
                          Maturity : 80% <br> Color : pink/light purple with 4 green ear </p>
                    </div>
                  </div>

                    <div class="card">
                        <img src="img/projects/New folder/salak1.jpg" class="img-fluid" alt="Snake fruit">
                        <div class="img-title">
                          <h3>Salacca (snakefruits)</h3>
                          <p> Harvest time : November-July <br> Size : 10-14 fruits /kg <br> free from thom (no spike) <br> Maturity : 70% <br> color : shiny black brown </p>
                          </div>
                    </div>

                  <div class="card">
                      <img src="img/projects/New folder/keffir.jpg" class="img-fluid" alt="kefirlime">
                        <div class="img-title">
                          <h3>Kefir lime</h3>
                          <p> Harvest every mounth <br> Size : 15-20 fruits/kg <br>
                          Maturity : ripe well <br> color : Dark green </p>
                          </div>
                  </div>

                  <div class="card">
                    <img src="img/projects/New folder/nnas.jpg" class="img-fluid" alt="Pineaple">
                    <div class="img-title">
                      <h3>Pineaple</h3>
                      <p> Harvest time : August-October <br> Size : 800 gram <br> Maturity : 75% <br> color : yellow to green </p>
                      </div>
                </div>

                <div class="card">
                  <img src="img/projects/New folder/jahe.jpeg" class="img-fluid" alt="ginger">
                    <div class="img-title">
                    <h3>Ginger</h3>
                    <p> Fresh or dried <br> sun dried proccess <br> Moisture : 10% <br> color : red or white <br>Approved as organic farm </p>
                    </div>
                </div>
                    
                    <div class="card">
                      <img src="img/projects/sweetpotato.jpg" class="img-fluid" alt="sweetpotato">
                        <div class="img-title">
                        <h3>Sweet Potato</h3>
                        <p> Harvest every mounth <br> Size : 15-20 fruits/kg <br> Maturity : ripe well <br> color : Dark green </p>
                        </div>
                    </div>

                    <div class="card">
                      <img src="img/projects/New folder/lengkuas.jpg" class="img-fluid" alt="galangal">
                        <div class="img-title">
                        <h3>Galangal</h3>
                        <p> Fresh or dried <br> sun dried proccess <br> Moisture : 15% <br> Approved as organic farm </p>
                        </div>
                    </div>
            </div>
          </section>
    <!-- akhir products -->

    <!-- Contact -->
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#73cef1" fill-opacity="1" d="M0,160L48,170.7C96,181,192,203,288,213.3C384,224,480,224,576,218.7C672,213,768,203,864,186.7C960,171,1056,149,1152,144C1248,139,1344,149,1392,154.7L1440,160L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>
    <section id="contact">
        <div class="container">
            <div class="row text-center mb-3">
                <div class="col">
                    <h1>Contact Us</h1>
                </div>
            </div>
            <div class="row justify-content-center">
                <div class="col-md-8">
                  <div class="alert alert-success alert-dismissible fade show d-none my-alert" role="alert">
                    <strong>Thank you!</strong> your message has been send.
                    <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>
                  </div>
                    <form name="submit-to-google-sheet"> 
                      <div class="mb-3">
                        <label for="name" class="form-label">Full Name</label>
                        <input type="Text" class="form-control" id="exampleInputEmail1" aria-describedby="name" name="nama">
                         
                      </div>
                      <div class="mb-3">
                        <label for="email" class="form-label">Email Address</label>
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="email" name="email">
                          
                      </div>
                      <div class="mb-3">
                        <label for="pesan" class="form-label">Message</label>
                        <textarea class="form-control" id="Pesan" rows="3" name="pesan"></textarea>
                      </div>  
                        <button type="submit" class="btn btn-primary btn-kirim">Submit</button>
                        <button class="btn btn-primary btn-loading d-none" type="button" disabled>
                          <span class="spinner-grow spinner-grow-sm" role="status" aria-hidden="true"></span>
                          Loading...
                        </button>
                      </form>
                      </div>
                </div>
          </div>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#73cef1" fill-opacity="1" d="M0,128L48,149.3C96,171,192,213,288,229.3C384,245,480,235,576,218.7C672,203,768,181,864,176C960,171,1056,181,1152,192C1248,203,1344,213,1392,218.7L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>
    </section>
    <!-- akhir contact -->
  <!-- Team -->
  <div class="container-fluid" style="background-color: #73cef1;">
    <div class="container">
      <div class="row text-center justify-content-center">
          <h1>Our Team</h1>
        <div class="col-4 text-center my-3">
          <img src="img/team/foto 1.jpeg" alt="tim2" width="100" class="rounded-circle img-thumbnail">
          <h1 class="nama-tim">Irawan Wicaksono S,P</h1>
          <p>Sales Marketing</p>
        </div>
        <div class="col-4 text-center my-3">
          <img src="img/team/foto 2.jpeg" alt="tim3" width="100" class="rounded-circle img-thumbnail">
          <h1 class="nama-tim">Dany Setyawan S,E</h1>
          <p>Manager</p>
        </div>
        <div class="col-4 text-center my-3">
          <img src="img/new.jpg" alt="tim3" width="100" class="rounded-circle img-thumbnail">
          <h1 class="nama-tim">Ridlo Imagine S,T</h1>
          <p>Front end Developer</p>
        </div>
      </div>
    </div>
  </div>
  
  <!-- akhir Team -->

  <!-- Partner -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#73cef1" fill-opacity="1" d="M0,256L48,229.3C96,203,192,149,288,133.3C384,117,480,139,576,176C672,213,768,267,864,256C960,245,1056,171,1152,160C1248,149,1344,203,1392,229.3L1440,256L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>
  <div class="container-fluid">
    <div class="row text-center">
        <div class="col">
          <h1 class="mb-3">Our Partner</h1>
            <div class="col mt-5">
              <img src="img/projects/logo.jpeg" class="rounded-circle mx-auto mb-3" width="100" height="100" alt="Logo">
            </div>
        </div>
    </div>
  </div>
  <!-- Akhir partner -->

  <!-- medsos -->
  <div class="container-fluid mt-5" style="background-color: #504646;">
    <div class="container p-5">  
    <div class="row">
      <div class="col pt-5">
        <H1 class="text-center fs-4 text-white">PT Agro Indo Jaya</H1><br><br>
        <p class="text-center fs-5 text-white">Jl. Perumahan Sukodono Permai <br>
        Telp. (0334) 882228</p><br>
        <div class="col text-center fs-1">
          <a href="https://www.instagram.com/ptagroindonusantara/"><i class="bi bi-instagram"></i></a>
          <a href="#"><i class="bi bi-facebook"></i></a>
          <a href="https://www.linkedin.com/in/irawan-wicaksono-a988b1228/"><i class="bi bi-linkedin"></i></a>
          <a href="https://wa.me/6281232205878/?text=Hi Agro Indo Jaya, i want to ask question and get more information from your company's products"><i class="bi bi-whatsapp"></i></a>
        </div>
      </div>
    </div>
  </div>
  <!-- Akhir medsos -->

    <!-- footer -->
    <div class="text-white text-center border-top" style="background-color: #504646;">
      <footer>&copy; 2021 Agro Indo Jaya. All right reserved
    </div>
    <!-- akhir footer -->

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <script>
      const scriptURL = 'https://script.google.com/macros/s/AKfycbzeV4C7vg_uZY-9qAFHqAqrMTDyLL-uxIA4FU3w7dM4QKri1VAMGbfQd_b4PpLKKOzl/exec'
      const form = document.forms['submit-to-google-sheet']
      const btnKirim = document.querySelector('.btn-kirim')
      const btnLoading = document.querySelector('.btn-loading')
      const myAlert = document.querySelector('.my-alert')

      form.addEventListener('submit', e => {
        e.preventDefault()
            // ketika tombol submit diklik
            // tampilkan tombol loading, hilangkan tombol kirim
        btnLoading.classList.toggle('d-none');
        btnKirim.classList.toggle('d-none');
          // tampilkan tombol loading, hilangkan tombol kirim
        fetch(scriptURL, { method: 'POST', body: new FormData(form)})
          .then(response => {
            btnLoading.classList.toggle('d-none');
            btnKirim.classList.toggle('d-none');
          // Tampilkan alert
          myAlert.classList.toggle('d-none');
          //reset formnya
          form.reset();  
            console.log('Success!', response)
          
          })
          .catch(error => console.error('Error!', error.message))
      })
    </script>
  </body>
</html>
