<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .navbar-brand {
            font-weight: bold;
        }
        .carousel-caption {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 10px;
        }
        footer {
            background-color: #f8f9fa;
        }
        footer ul {
            list-style-type: none;
            padding: 0;
        }
    </style>
	<title></title>
</head>
<body>
  <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="#">Edureka</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Courses</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Blog</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Contact Us</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Carousel -->
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://upload.wikimedia.org/wikipedia/commons/3/3d/DevOps-toolchain.svg" class="d-block w-100" alt="DevOps Program">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Post Graduate Program in DevOps</h5>
                    <p>Apply now and grow your career.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://www.enterprisenetworkingplanet.com/wp-content/uploads/2023/01/cloud-architect-scaled.jpg" class="d-block w-100" alt="Cloud Architect">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Become a Cloud Architect</h5>
                    <p>Learn from industry experts.</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://media.istockphoto.com/id/1303805276/photo/data-science-concept-illustration-in-blue-with-cube-shape-arranged-in-the-background.jpg?b=1&s=170667a&w=0&k=20&c=whxU6dH06SYpmhQRmVFGPHSsNDATpQPC2oeOFPWAd38=" class="d-block w-100" alt="Data Science Master">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Master in Data Science</h5>
                    <p>Get certified and advance your career.</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
    </div>

    <!-- Latest Blog Posts Section -->
    <section class="container my-5">
        <h2 class="text-center">Latest Blog Posts</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="https://images.techopedia.com/images/uploads/2023/05/DevOps-Interview.jpg" class="card-img-top" alt="DevOps Interview Questions">
                    <div class="card-body">
                        <h5 class="card-title">120+ DevOps Interview Questions</h5>
                        <p class="card-text">Prepare for 2024 with the top DevOps interview questions.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://1.bp.blogspot.com/-lQzqjAV4xS8/YRI3W6NnWLI/AAAAAAAAAQ0/pM7womZ59E02IZM2PXLwvEXomQ9yzTGWQCLcBGAsYHQ/w680/java-interview-questions-1.jpg" class="card-img-top" alt="Java Interview Questions">
                    <div class="card-body">
                        <h5 class="card-title">Java Interview Questions</h5>
                        <p class="card-text">Get ready with the most commonly asked Java interview questions.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="https://cdn.ttgtmedia.com/rms/onlineimages/hadoop_platform_and_cloud_analytice_final_desktop.jpg" class="card-img-top" alt="Hadoop Installation">
                    <div class="card-body">
                        <h5 class="card-title">Hadoop Installation Guide</h5>
                        <p class="card-text">Learn how to set up a multi-node Hadoop cluster.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Trending Courses Section -->
    <section class="container my-5">
        <h2 class="text-center">Trending Courses</h2>
        <div class="row">
            <div class="col-md-3">
                <div class="card">
                    <img src="https://st2.depositphotos.com/5653638/9449/v/600/depositphotos_94492866-stock-illustration-devops-concept.jpg" class="card-img-top" alt="DevOps Certification">
                    <div class="card-body">
                        <h5 class="card-title">DevOps Certification Training</h5>
                        <p class="card-text">Learn DevOps and get certified by top instructors.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="https://www.edureka.co/blog/wp-content/uploads/2019/05/aws.jpg" class="card-img-top" alt="AWS Certification">
                    <div class="card-body">
                        <h5 class="card-title">AWS Certification Training</h5>
                        <p class="card-text">Prepare for AWS Certification with industry experts.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="https://cdn.ttgtmedia.com/ITKE/cwblog/fundamentally-flawed/files/2018/07/cyber-security.jpg" class="card-img-top" alt="Cyber Security">
                    <div class="card-body">
                        <h5 class="card-title">Cyber Security Course</h5>
                        <p class="card-text">Become a certified cybersecurity professional.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/full_stack_developer_skills.jpg" class="card-img-top" alt="Web Development">
                    <div class="card-body">
                        <h5 class="card-title">Full Stack Web Development</h5>
                        <p class="card-text">Master full-stack development with hands-on projects.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-light text-center text-lg-start">
        <div class="container p-4">
            <div class="row">
                <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
                    <h5 class="text-uppercase">About Edureka</h5>
                    <p>Edureka offers online courses to help you grow your career in tech and business.</p>
                </div>
                <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
                    <h5 class="text-uppercase">Courses</h5>
                    <ul class="list-unstyled mb-0">
                        <li><a href="#!" class="text-dark">DevOps</a></li>
                        <li><a href="#!" class="text-dark">Cloud Computing</a></li>
                        <li><a href="#!" class="text-dark">Cyber Security</a></li>
                        <li><a href="#!" class="text-dark">Data Science</a></li>
                    </ul>
                </div>
                <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
                    <h5 class="text-uppercase">Follow Us</h5>
                    <ul class="list-unstyled mb-0">
                        <li><a href="#!" class="text-dark">LinkedIn</a></li>
                        <li><a href="#!" class="text-dark">Twitter</a></li>
                        <li><a href="#!" class="text-dark">Facebook</a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2024 Edureka | All rights reserved
        </div>
    </footer>

    <!-- JavaScript -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</body>
</html>
