# Website-
This is the government polytechnic jamnager website 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Government Polytechnic, Jamnagar</title>
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
          rel="stylesheet"/>  
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #34495e;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position:auto;
            width: 100%;
            bottom: 0;
        }
        .courses, .contact-info {
            display: flex;
            justify-content:center;
        }
        .course-item, .contact-item {
            background-color: white;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 45%;
            margin: 10px 0;
            justify-content:center;
        }
        form {
            background-color: white;
            padding: 20px;
            margin: 20px auto;
            width: 50%;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
        form input, form select, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            background-color: #2c3e50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #34495e;
        }
    </style>
    </head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Government Polytechnic, Jamnagar</h1>
        <p>Empowering Future Technocrats</p>
    </header>

    <!-- Navigation Section -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#courses">Courses</a>
        <a href="#registration">Registration</a>
        <a href="#contact">Contact</a>
        <a href="Details">Details</a>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to Government Polytechnic, Jamnagar</h2>
        <p>Your pathway to a bright technical career starts here!</p>
    </section>
    <div class="container mt-5">  
    <div id="gpJamnagarCarousel" class="carousel slide" data-bs-ride="carousel">  <!-- Indicators/dots -->  
  <div class="carousel-indicators">  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="0" class="active"></button>  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="1"></button>  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="2"></button>  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="3"></button>  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="4"></button>  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="5"></button>  
    <button type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide-to="6"></button>  
  </div>  

  <!-- Slides / Items -->  
  <div class="carousel-inner">  
    <!-- Slide 1 -->  
    <div class="carousel-item active">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQc0mjFgKxB0Afz16nUQ0PvyHng9itPEFHaRNfjqLD9VQ&s=10" class="d-block w-100" alt="Entrance Building">  
      <div class="carousel-caption d-none d-md-block">  
      </div>  
    </div>  
    <!-- Slide 2 -->  
    <div class="carousel-item">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRcPxQSglmBnE8X3BoU3ZBo05m_LOEXmRpxu4UNQyRGCQ&s=10" class="d-block w-100" alt="Academic Block">  
      <div class="carousel-caption d-none d-md-block">    
      </div>  
    </div>  
    <!-- Slide 3 -->  
    <div class="carousel-item">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJeEWWX6t8pJumldyJTuyNg6rfensGgU1m6p8BYEllSg&s=10" class="d-block w-100" alt="Lab / Workshop">  
      <div class="carousel-caption d-none d-md-block">  
      </div>  
    </div>  
    <!-- Slide 4 -->  
    <div class="carousel-item">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQyONa3KVynpbctvKonlRP71rNqo9NUDr7SmLqJ8qCNjw&s=10" class="d-block w-100" alt="Hostel Building">  
      <div class="carousel-caption d-none d-md-block">   
      </div>  
    </div>  
    <!-- Slide 5 -->  
    <div class="carousel-item">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRG2b1fVHEoGD7Ruvy81SdHYMHZDuzRJaa13hP3-tksWg&s=10" class="d-block w-100" alt="Ground / Open Area">  
      <div class="carousel-caption d-none d-md-block"> 
      </div>  
    </div>  
    <!-- Slide 6 -->  
    <div class="carousel-item">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjY59PcDp9VQFTBhX95Z2hx12eempyqVZ4Dp4pjqTCrg&s=10" class="d-block w-100" alt="Computer Department">  
      <div class="carousel-caption d-none d-md-block">   
      </div>  
    </div>  
    <!-- Slide 7 -->  
    <div class="carousel-item">  
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREkPSulIJaNdG8hVX0wPNxG3RvnViq2juAJzL9KNBe2g&s=10" class="d-block w-100" alt="Event / Celebration">  
      <div class="carousel-caption d-none d-md-block">   
      </div>  
    </div>  
  </div>  
        <!-- Controls: Previous / Next arrows -->  
  <button class="carousel-control-prev" type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide="prev">  
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>  
    <span class="visually-hidden">Previous</span>  
  </button>  
  <button class="carousel-control-next" type="button" data-bs-target="#gpJamnagarCarousel" data-bs-slide="next">  
    <span class="carousel-control-next-icon" aria-hidden="true"></span>  
    <span class="visually-hidden">Next</span>  
  </button>  
    </div>
    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>
            Government Polytechnic, Jamnagar was established in August 1983 by the Government of Gujarat under the Directorate of Technical Education to promote technical education. 
            Initially, two programmes were launched: Diploma in Civil Engineering and Diploma in Mechanical Engineering, each with an intake of 30 students.
        </p>
        <p>
            Over the years, the institute expanded with Diploma in Electrical Engineering (1989), Electronics & Communication and Computer Engineering (2007), 
            and infrastructure such as hostels, residential quarters, and dedicated academic buildings.
        </p>
        <p>
            The institute is located at Valsura Road, Jamnagar — 6 km from the bus stand, 2 km from the railway station, and 15 km from the airport. 
            Jamnagar is an industrial hub with Reliance Industries Ltd., Essar Industries Ltd., and many brass factories in the vicinity, offering excellent career opportunities for students.
        </p>
    </section>
    <!-- Courses Section -->
    <section id="courses">
        <h2>Our Courses</h2>
        <div class="courses">
            <div class="course-item justify-contect-center">
                <h3>Diploma in Mechanical Engineering</h3>
                <p>Duration: 3 Years</p>
                <p>This course offers in-depth knowledge in the field of mechanical engineering.</p>
            </div>
            <div class="course-item">
                <h3>Diploma in Civil Engineering</h3>
                <p>Duration: 3 Years</p>
                <p>A comprehensive course in civil engineering principles and practices.</p>
            </div>
            <div class="course-item">
                <h3>Diploma in Electrical Engineering</h3>
                <p>Duration: 3 Years</p>
                <p>Explore the dynamic field of electrical engineering with this diploma.</p>
            </div>
            <div class="course-item">
             <h3>Diploma in computer Engineering </h3> 
             <p>Duration: 3 years</p>
             <p>computer Engineering is degin a hardware and software</p>
             </div>
        </div>
    </section>
    
     <!-- Details Section -->
    <section id="details">
        <h2>Facilities & Details</h2>
        <p>
            Our campus offers modern classrooms, fully equipped laboratories, hostels for boys and girls, and a well-stocked library. 
            Students benefit from industrial exposure due to proximity to major industries in Jamnagar.
        </p>
    </section>
    

    <!-- Registration Section -->
    <section id="registration">
        <h2>Student Registration</h2>
        <form action="submit_registration.php" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

            <label for="course">Select Course:</label>
            <select id="course" name="course" required>
                <option value="mechanical">Diploma in Mechanical Engineering</option>
                <option value="civil">Diploma in Civil Engineering</option>
                <option value="electrical">Diploma in Electrical Engineering</option>
                <option value="computer">Diploma in computer Engineering</option>
            </select>

            
            <button type="submit">Register Now</button>
        </form>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <div class="contact-info">
            <div class="contact-item">
                <h3>Address</h3>
                <p>Government Polytechnic, P.O Box 25, Jamnagar, Gujarat - 361001, India</p>
            </div>
            <div class="contact-item">
                <h3>Contact Details</h3>
                <p>Phone: +91 288 267 6500</p>
                <p>Email: info@gpjamnagar.ac.in</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Government Polytechnic, Jamnagar. All rights reserved.</p>
    </footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>