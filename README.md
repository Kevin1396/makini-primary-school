<!DOCTYPE html>
<html>
<head>
    <title>MAKINI PRIMARY SCHOOL</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css"> <!-- External CSS file for custom styles -->
</head>
<body>
<!-- Navigation Menu -->
<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
        <a class="navbar-brand" href="#">MAKINI PRIMARY SCHOOL</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link" href="#home">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contacts">Contacts</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#gallery">Gallery</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#courses" onclick="toggleCourses()">Courses</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#registration">Registration</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Home Section -->
<section id="home">
    <div class="card">
        <div class="card-body">
            <h1 class="card-title">About Us</h1>
            <p class="card-text">Welcome to Makini primary school, a vibrant and inclusive school dedicated to nurturing a love for learning. Our experienced educators provide a well-rounded education that fosters curiosity, critical thinking, and creativity. With a student-centred curriculum tailored to individual needs, we blend traditional and innovative teaching methods. Our dynamic classrooms encourage active participation, collaboration, and a lifelong passion for learning. Through diverse extracurricular activities in sports, music, art, and more, we nurture well-rounded individuals who can confidently express themselves. Ensuring safety and well-being is our top priority, creating a secure environment where students thrive. Join our Makini primary school family, where we value and support each child's journey, inspiring them to become future leaders and changemakers.</p>
        </div>
    </div>
    <div class="card">
        <div class="card-body">
            <h1 class="card-title">Mission</h1>
            <p class="card-text">Makini will actively encourage and facilitate: The formation of each student's moral character, unique skills, capabilities, and talents, creating a solid communal ethos of social responsibility; and the achievement of the highest possible academic results.</p>
        </div>
    </div>
    <div class="card">
        <div class="card-body">
            <h1 class="card-title">Vision</h1>
            <p class="card-text">Makini's vision is to provide quality education at an affordable cost and to create centres of excellence in which each child will develop: the highest possible moral, academic, cultural, and sporting standards; a wide range of interests, capacities, and talents; a strong sense of social responsibility and carry these values into adult life.</p>
        </div>
    </div>
</section>

<!-- Contacts Section -->
<section id="contacts">
    <div class="container">
        <h2>Contacts</h2>
        <p>Phone: +254797255880</p>
        <p>Email: info@makinischool.com</p>
        <p>Address: P.O.BOX 57-50117, KOYONZO</p>
    </div>
</section>

<!-- Gallery Section -->
<section id="gallery">
    <div class="container">
        <h2>Gallery</h2>
        <div class="image-grid">
            <img src="E:\Makini primary school\Images\Image 1.jpg" alt="Image 1">
            <img src="E:\Makini primary school\Images\Image 2.jpg" alt="Image 2">
            <img src="E:\Makini primary school\Images\Image 3.jpeg" alt="Image 3">
        </div>
    </div>
</section>

<!-- Courses Section -->
<section id="courses">
    <div class="container">
        <h2>Courses</h2>
        <ul>
            <li>Mathematics</li>
            <li>English</li>
            <li>Kiswahili</li>
            <li>Science</li>
            <li>Social Studies</li>
            <li>CRE</li>
        </ul>
    </div>
</section>

<!-- Registration Section -->
<section id="registration">
    <div class="container">
        <h2>Student Admission</h2>
        <form id="registration-form">
            <div class="mb-3">
                <label for="name" class="form-label">Student Name:</label>
                <input type="text" class="form-control" id="name" name="name" autocomplete="name" required>
            </div>
            <div class="mb-3">
                <label for="admission" class="form-label">Admission Number:</label>
                <input type="text" class="form-control" id="admission" name="admission" autocomplete="off" required>
            </div>
            <div class="mb-3">
                <label for="date" class="form-label">Date of Admission:</label>
                <input type="date" class="form-control" id="date" name="date" autocomplete="off" required>
            </div>
            <button type="submit" class="btn btn-primary">Admit Student</button>
        </form>
    </div>
</section>

<!-- Search Section -->
<section id="search">
    <div class="container">
        <h2>Search Student Records</h2>
        <form id="search-form">
            <div class="mb-3">
                <label for="admission-search" class="form-label">Admission Number:</label>
                <input type="text" class="form-control" id="admission-search" name="admission-search" required>
            </div>
            <button type="submit" class="btn btn-primary">Search</button>
        </form>
    </div>
</section>

<!-- Student Record Section -->
<section id="student-record">
    <!-- Student records will be displayed here --> 
</section>

<!-- Academic Achievements Section -->
<section id="achievements">
    <div class="container">
        <h2>Academic Achievements</h2>
        <ul>
          <li>
            <h3>National Math Olympiad Champions</h3>
            <p>Our students showcased their exceptional math skills and emerged as champions in the prestigious National Math Olympiad. Their problem-solving abilities and dedication to academic excellence were commendable.</p>
          </li>
          <li>
            <h3>Outstanding Performance in Standardized Tests</h3>
            <p>We take immense pride in our students' outstanding performance in standardized tests. In the recent national exams, our students achieved remarkable scores, surpassing the national average and positioning our school among the top-performing institutions in the country.</p>
          </li>
          <li>
            <h3>High Graduation Rates</h3>
            <p>At Makini Primary School, we prioritize ensuring that our students succeed academically. We are delighted to share that our graduation rates have consistently been above 95% for the past five years, a testament to our commitment to providing quality education and supporting students to excel.</p>
          </li>
          <li>
            <h3>Scholarships and University Acceptances</h3>
            <p>Our students' exceptional academic performance has opened doors to prestigious scholarships and university acceptances. Numerous students have been awarded scholarships to renowned institutions, recognizing their hard work, dedication, and intellectual capabilities.</p>
          </li>
          <li>
            <h3>Recognition for Innovative Teaching Methods</h3>
            <p>Our dedicated faculty members continually explore innovative teaching methods to enhance the learning experience. Their efforts have been recognized at national conferences, where they have been invited to share their best practices and contribute to the advancement of education.</p>
          </li>
        </ul>
      </div>
</section>

<!-- Staff Section -->
<section id="staff">
    <div class="container">
      <h2>Our Dedicated Staff</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="E:\Makini primary school\Images\Image 4.jpg" alt="Staff Member 1" style="max-width: 10%; height: auto;">
            <div class="card-body">
              <h3 class="card-title">Agness Kubende</h3>
              <p class="card-text">Head Teacher</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    
  </section>  

<!-- Alumni Section -->
<section id="alumni">
    <div class="container">
        <h2>Our Dedicated Staff</h2>
        <div class="row">
          <div class="col-md-4">
            <div class="card">
              <img src="E:\Makini primary school\Images\Image 4.jpg" alt="Staff Member 1" style="max-width: 10%; height: auto;">
              <div class="card-body">
                <h3 class="card-title">Agness Kubende</h3>
                <p class="card-text">Head Teacher</p>
              </div>
            </div>
          </div>
</section>

<!-- Footer Section -->
<footer>
    <div class="container">
        <p>MAKINI PRIMARY SCHOOL &copy; 2023. All rights reserved.</p>
    </div>
</footer>

<script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/8.10.0/firebase-database.js"></script>
<script src="script.js"></script> <!-- External JS file for custom scripts -->
</body>
</html>
