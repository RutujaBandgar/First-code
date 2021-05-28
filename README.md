# First-code
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  </head>
  <body>
    
<nav class="navbar sticky-top navbar-expand-lg navbar-dark bg-primary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">ShapeAI</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#Course">Course</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contact">Contact Us</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<main class="container mt-3">
  <section id=home class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row bg-primary p-4 rounded">
      <div class="d-flex justify-content-sm-center align-items-center flex-column justify-content-md-start align-items-md-start" >
        <h1 class="text-white">Industrial Trainings and Internships</h1>
        <p class="text-white">Learn Artificial Intelligence and Full-Stack Web Development from people at Google, Goldman Sachs, American Express, Jio and Microsoft</p>
        <button class="btn btn-light btn-sm">Explore Coursese</button>
      </div>
      <div class="w-50 w-50">
       <img src="https://www.impactbnd.com/hubfs/Inbound%20Success%20Podcast/Blog%20Images/web-developer-characteristics.jpg"  alt="..." class="w-100 h-100 shadow">
      </div>
   </section>
      
    <section class="mt-4"> 
       <h1 class="text-center">Our Instructors are from</h1>
       <p class="text-md-center">The only program where you are learning directly from people who have cracked the best companies</p>
       <div class="mt-4 d-flex justify-content-evenly">
         <img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/6091aa185404a61ff39523f5_1200px-American_Express_logo_(2018).svg.png" loading="lazy" width="125" alt="American Express" class="brand-image-2">
         <img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/6091aa0407157d9dbb9f1daa_1125px-Reliance_Jio_Logo_(October_2015).svg.png" loading="lazy" width="125" alt="Jio" class="brand-image-2">
         <img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/60798deca9b7d4fea3ab1620_Microsoft%20Logo.png" loading="lazy" width="185" alt="Microsoft" class="brand-image-2">
         <img src="https://uploads-ssl.webflow.com/60798d9b0b61160814b3d8c3/60798dc9d0cb6bb0b1aec7a0_Google%20Logo.png" loading="lazy" width="185" alt="Google" class="brand-image-2">
       </div>
    </section>
        
     <section id=Course class="mt-5">
         <h1 class="text-center ">Crack MNC's With Our Training and Internship Programsm</h1>
         <p class="text-md-left"">Build. Internship&Industrial-grade tech-projects</p>
         <p class="text-md-left">Learn. Full Stack or Data Science hands-on</p>
         <p class="text-md-left">Grow. your career with real work experience</p>
      <div class="d-flex flex-column flex-md-row justify-content-md-evenly">
       <div class="card" style="width: 18rem;">
         <img src="https://images.unsplash.com/photo-1565106430482-8f6e74349ca1?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
          <div class="card-body">
             <h5 class="card-title">Full-Stack Web Dev Training and Internship</h5>
            <p class="card-text">Join us for the 2.5 month-long intensive industrial training and internship. Get placed as a Full-Stack Web Developer or a Software Development Engineer in your Dream Company.</p>
            <a href="#" class="btn btn-primary">Web Dev</a>
          </div>
        </div>
        <div class="card mt-3" style="width: 18rem;">
         <img src="https://images.unsplash.com/photo-1565106430482-8f6e74349ca1?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" class="card-img-top" alt="...">
          <div class="card-body">
             <h5 class="card-title">Data Analyst Training And Internship</h5>
            <p class="card-text">Join us for the 2.5 month-long intensive industrial training and internship. Get placed as a Data Analyst or a Software Development Engineer in your Dream Company</p>
            <a href="#" class="btn btn-primary">Data science</a>
          </div>
        </div>
      </div>
    </section>
     

    <section id="contact" class="mt-4 py-4">
      <h1 class="text-center text-primary">Contact Form</h1>
      <div cclas="row">
        <div class="col-sm col-md-8">
       <form>
         <div class="mb-3">
          <label for="exampleFormControlInput1" class="form-label">Email address</label>
           <input type="email"  required class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
         </div>
        <div class="mb-3">
          <label for="exampleFormControlTextarea1" class="form-label">Text Area</label>
           <textarea class="form-control" id="exampleFormControlTextarea1" required placeholder="Enter your Comment" rows="3"></textarea>
        </div>
        <button type="submit" class="btn btn-primary">
          Submit
        </button>
       </form>
       </div>
       <div class=" col=sm col-md-4">
      <div class="mt-3">
        <h4><i class="fas fa-at"></i>
        shapeai@gmail.com</h4>
       <button type="button" class="btn btn-outline-primary mt-2">
       <a class="btn btn-primary" href="https://www.facebook.com/"><i class="fab fa-facebook"></i></a>
       </button>
      </div>
      </div>
      </div>
    </section>
    
</main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>
  </body>
  </html>
