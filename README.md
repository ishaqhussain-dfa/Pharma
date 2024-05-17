# Project Responsive Web Design using Bootstrap
## Date:15.05.2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
home.html

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy - Home</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">IH Pharmaceuticals ⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="product.html" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="product.html" >Ayurveda</a>
                                <a class="dropdown-item" href="product.html">IH in Care</a>
                                <a class="dropdown-item" href="product.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about_us.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <div class="container mt-5">
        <center>
            <div class="col-md-6">
                <br>
                <h2>Welcome to IH Pharmaceuticals</h2>
                <img src="HOMe.png" alt="" class="img-fluid">
            </div>
            
            <div >
                <p  style="font-weight: bold;"> <br> <strong> IH Pharmaceuticals is one of the world's leading pharmacy chains, committed to providing accessible healthcare solutions to communities worldwide. Established in 1980 by Dr. ISHAQ HUSSAIN, a visionary pharmacist with a passion for patient care, MedicoCare has grown exponentially over the decades, expanding its reach and services to cater to diverse healthcare needs.</strong> 
                </p>
                <p style="font-weight: bold" align="left"> <br><strong>MISSION:  </strong>Our mission at IH Pharmaceuticals is to enhance the quality of life for individuals by delivering comprehensive and personalized pharmacy services. We strive to empower our customers with knowledge, convenience, and affordable healthcare solutions, while fostering a culture of compassion and integrity in everything we do.</p>
                <p style="font-weight: bold" align="left"> <br><strong>COMMUNITY ENGAGEMENT:  </strong>At IH Pharmaceuticals, we believe in giving back to the communities we serve. Through initiatives such as health fairs, educational workshops, and partnerships with local organizations, we strive to promote health literacy, disease prevention, and access to healthcare resources for underserved populations.</p>
                <p style="font-weight: bold" align="left"> <br><strong>CORPORATE RESPONSIBILITY:  </strong>We are committed to upholding the highest standards of corporate responsibility, ethical business practices, and environmental sustainability. From reducing our carbon footprint through eco-friendly initiatives to supporting charitable causes that align with our mission, ISHAQ Pharmaceuticals aims to make a positive impact on society and the planet.</p>
                <p style="font-weight: bold" align="left"> <br><strong>GLOBAL PRESENCE:  </strong>Headquartered in New York City, IH Pharmaceuticals operates across North America, Europe, Asia, and beyond, with a dedicated workforce of over 100,000 employees united by a common goal: to make healthcare accessible and affordable for all.</p>
            </div>
            <body style="background-image: url('medical_bg.png'); background-size: cover; background-repeat: no-repeat;">

            </center>
    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; IH Pharmaceuticals. Designed By ISHAQ HUSSAIN A </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>


product.html


<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pharmacy - Products</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<style>
     .product-card {
    height: 850px; 
    border: 5px solid black; 
    margin-bottom: 40px;
    background-color: transparent;
}

</style>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">IH Pharmaceuticals ⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="product.html" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="product.html" >Ayurveda</a>
                                <a class="dropdown-item" href="product.html">IH in Care</a>
                                <a class="dropdown-item" href="product.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about_us.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
        <br> <br> <br> <br>
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="s1.jpg" class="card-img-top product-image" alt="Medicine 1">
                    <div class="card-body">
                        <h5 class="card-title">Zolgensma</h5>
                        <p class="card-text">Zolgensma is given a one-time, single-dose, intravenous (IV) infusion therapy with a total cost at approval of $2.125 million. It works by replacing the defective or missing survival motor neuron 1 (SMN1) gene to treat the root cause of SMA and halt disease progression. It is considered potentially curative.
                        </p>
                        <p class="card-text" align="center"> <b>Rate: $2.125/- </b></p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="s2.jpg" class="card-img-top product-image" alt="Medicine 2">
                    <div class="card-body">
                        <h5 class="card-title">Myalept</h5>
                        <p class="card-text">Myalept (metreleptin for injection) was FDA-approved as a replacement therapy to treat the complications of leptin deficiency, in addition to diet, in patients with congenital or acquired generalized lipodystrophy. Lipodystrophy can be inherited through the genes or acquired without a known cause.</p>
                        <p class="card-text" align="center"> <b>Rate: $1.375/- </b></p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card product-card">
                    <img src="s3.jpg" class="card-img-top product-image" alt="Medicine 3">
                    <div class="card-body">
                        <h5 class="card-title">Danyelza</h5>
                        <p class="card-text">Danyelza (naxitamab-gqgk) 40 mg/10 mL is approved to treat adults and children 1 year of age and older with high-risk neuroblastoma in the bone or bone marrow, in combination with granulocyte-macrophage colony-stimulating factor (GM-CSF), who have demonstrated a partial response, minor response, or stable disease to prior therapy</p>
                        <p class="card-text" align="center"> <b>Rate: $1.225 /- </b></p>
                    </div>
                </div>
            </div>
        </div>
        <body style="background-image: url('medical_bg.png'); background-size: cover; background-repeat: no-repeat;">
    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; IH Pharmaceuticals. Designed By ISHAQ HUSSIAN A </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>


about_us.html

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - IH Pharmaceuticals</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        .product-card {
            height: 680px;
            border: 5px solid black;
            margin-bottom: 40px;
        }
    </style>
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="#">IH Pharmaceuticals⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="product.html" id="navbarDropdown" role="button"
                                data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="product.html">Ayurveda</a>
                                <a class="dropdown-item" href="product.html">IH in Care</a>
                                <a class="dropdown-item" href="product.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about_us.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <br> <br> <br> <br>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-12">
                <h2 class="text-center">About IH Pharmaceuticals</h2>
                <img src="sk.png" alt="IH Pharmaceuticals Logo" style="display: block; margin: auto; width: 200px; height: auto;">
                <p class="text-center">IH Pharmaceuticals is a trusted provider of high-quality pharmaceutical products
                    since 1980. We are committed to improving the health and well-being of our customers by offering a
                    wide range of medicines, supplements, and healthcare products.</p>
                <p class="text-center">Our team of experienced pharmacists and healthcare professionals ensures that
                    every product we offer meets the highest standards of safety and efficacy. We strive to provide
                    exceptional customer service and personalized care to all our clients.</p>
                <p class="text-center">At IH Pharmaceuticals, your health is our priority. We are dedicated to helping you
                    lead a healthier and happier life.</p>
            </div>
        </div>
        <body style="background-image: url('medical_bg.png'); background-size: cover; background-repeat: no-repeat;">

    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy; IH Pharmaceuticals. Designed By ISHAQ HUSSAIN A </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>



contact.html


<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - IH Pharmaceuticals</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>

<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
            <div class="container">
                <a class="navbar-brand" href="home.html">IH Pharmaceuticals⚕️</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="home.html">Home</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="product.html" id="navbarDropdown" role="button"
                                data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Products
                            </a>
                            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                                <a class="dropdown-item" href="product.html">Ayurveda</a>
                                <a class="dropdown-item" href="product.html">IH in Care</a>
                                <a class="dropdown-item" href="product.html">Multivitamins</a>
                            </div>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="about_us.html">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="contact.html">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
    <br> <br> <br> <br>
    <div class="container mt-5">
        <div class="row">
            <div class="col-md-6 offset-md-3">
                <h2 class="text-center">Contact Us</h2>
                <form>
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" class="form-control" id="name" placeholder="Enter your name">
                    </div>
                    <div class="form-group">
                        <label for="email">Email address</label>
                        <input type="email" class="form-control" id="email" aria-describedby="emailHelp"
                            placeholder="Enter email">
                        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone
                            else.</small>
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea class="form-control" id="message" rows="5"
                            placeholder="Enter your message"></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary btn-block">Submit</button>
                    <br>

                   <b>IH Pharmaceuticals <br> Poonamallee ,Chennai - 600056 <br> Tamil Nadu
                </form>
            </div>
        </div>
        <body style="background-image: url('medical_bg.png'); background-size: cover; background-repeat: no-repeat;">


    </div>

    <footer class="bg-dark text-white text-center py-3 fixed-bottom">
        <div class="container">
            <p>&copy;  IH Pharmaceuticals. Designed By ISHAQ HUSSAIN A </p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>

</html>

```


## OUTPUT:

![out1](https://github.com/KGSatheeshKumar/Pharma/assets/128453421/ea40628a-1210-42b3-9372-73a6f0d53fa8)
![out2](https://github.com/KGSatheeshKumar/Pharma/assets/128453421/8e54f0af-e82a-4259-b135-62f92bc6f56a)
![out3](https://github.com/KGSatheeshKumar/Pharma/assets/128453421/9d192ca7-3201-468b-b520-5b75804190ed)
![out4](https://github.com/KGSatheeshKumar/Pharma/assets/128453421/80da4e51-4a46-45de-b635-5c9208523bbb)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
