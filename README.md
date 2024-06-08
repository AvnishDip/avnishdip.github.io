<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Vélo</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            padding-top: 56px;
            background: #f1e5d1;
        }
        .footer {
            background: #f1e5d1;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
        <div class="container">
            background: #808836;
            <a class="navbar-brand" href="#">Le Vélo</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarResponsive">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#products">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about-us">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#locations">Locations</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#booking">Book Appointment</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header Section -->
    <header class="bg-primary text-white text-center py-5">
        <div class="container">
            <h1>Welcome to Le Vélo</h1>
            <p>Your solution for all bike, e-scooter, and e-bike repair and maintenance needs in Ottawa.</p>
            <a href="#booking" class="btn btn-light btn-lg">Book a Repair</a>
        </div>
    </header>

    <!-- About Us Section -->
    <section id="about-us" class="py-5">
        <div class="container">
            <h2 class="text-center">About Us</h2>
            <p class="text-center">Le Vélo is your trusted destination for all things cycling and e-mobility since 2005. Founded by avid cyclist and local entrepreneur, Alex Thompson, our shop began as a small garage operation dedicated to providing high-quality bike repair services to our community. Over the years, we've grown into a full-service repair center specializing in e-bikes, traditional bikes, and e-scooters. Our mission has always been to keep Ottawa moving safely and efficiently, combining expert craftsmanship with a passion for innovation. Whether you're an everyday commuter or a weekend warrior, we’re here to keep your ride in top condition.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Our Services</h2>
            <div class="row">
                <!-- Service 1 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">Full Inspection</h5>
                            <p class="card-text">24-hour Guarantee Fix, Professional Service.</p>
                            <p class="card-text">$95 + Tax</p>
                        </div>
                    </div>
                </div>
                <!-- Service 2 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">Segway Licensed Repair</h5>
                            <p class="card-text">Full Inspection, 24-hour Guarantee Fix, Professional Service.</p>
                            <p class="card-text">$80 + Tax</p>
                        </div>
                    </div>
                </div>
                <!-- Service 3 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">Premium Repair</h5>
                            <p class="card-text">Full Inspection, 24-hour Guarantee Fix, Professional Service, Repairs under $100 are free.</p>
                            <p class="card-text">$120 + Tax</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-5">
        <div class="container">
            <h2 class="text-center">Our Products</h2>
            <div class="row">
                <!-- Product 1 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/150" class="card-img-top" alt="Product 1">
                        <div class="card-body">
                            <h5 class="card-title">Mountain Bike Accessories</h5>
                            <p class="card-text">$5.99</p>
                            <p class="card-text">Pick up available</p>
                        </div>
                    </div>
                </div>
                <!-- Product 2 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/150" class="card-img-top" alt="Product 2">
                        <div class="card-body">
                            <h5 class="card-title">Bike Fenders Adjustable</h5>
                            <p class="card-text">$12.99</p>
                            <p class="card-text">Delivery-only</p>
                        </div>
                    </div>
                </div>
                <!-- Product 3 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="https://via.placeholder.com/150" class="card-img-top" alt="Product 3">
                        <div class="card-body">
                            <h5 class="card-title">Ergonomic Design Bike Grips</h5>
                            <p class="card-text">$21.99</p>
                            <p class="card-text">Pick up available</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experts Section -->
    <section id="experts" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">Our Experts</h2>
            <div class="row">
                <!-- Expert 1 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">John Doe</h5>
                            <p class="card-text">Bike Mechanic Specialist</p>
                        </div>
                    </div>
                </div>
                <!-- Expert 2 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">Jane Smith</h5>
                            <p class="card-text">E-Bike Repair Specialist</p>
                        </div>
                    </div>
                </div>
                <!-- Expert 3 -->
                <div class="col-md-4">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">Alex Thompson</h5>
                            <p class="card-text">Founder and Chief Technician</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Booking Form Section -->
    <section id="booking" class="py-5">
        <div class="container">
            <h2 class="text-center">Book an Appointment</h2>
            <form id="bookingForm">
                <div class="form-row">
                    <div class="form-group col-md-6">
                        <label for="firstName">First Name</label>
                        <input type="text" class="form-control" id="firstName" placeholder="Jane">
                    </div>
                    <div class="form-group col-md-6">
                        <label for="lastName">Last Name</label>
                        <input type="text" class="form-control" id="lastName" placeholder="Smitherton">
                    </div>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="email@domain.com">
                </div>
                <div class="form-group">
                    <label for="service">Select Service</label>
                    <select class="form-control" id="service">
                        <option>Full Inspection - $95 + Tax</option>
                        <option>Segway Licensed Repair - $80 + Tax</option>
                        <option>Premium Repair - $120 + Tax</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="expert">Select Expert</label>
                    <select class="form-control" id="expert">
                        <option>John Doe - Bike Mechanic Specialist</option>
                        <option>Jane Smith - E-Bike Repair Specialist</option>
                        <option>Alex Thompson - Chief Technician</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="bookingTime">Time of Booking</label>
                    <input type="datetime-local" class="form-control" id="bookingTime">
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </form>
            <div id="confirmation" class="mt-3" style="display: none;">
                <div class="alert alert-success" role="alert">
                    Your booking has been confirmed!
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer text-center">
        <div class="container">
            <p>© 2024 Le Vélo. All Rights Reserved.</p>
            <p>123 Fake Lane, K1N 7D4, Ottawa, ON, Canada | (613) 4583 586</p>
            <p>4757 Not Real Lane, K3J 6Z7, Ottawa, ON, Canada | (343) 6875 498</p>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script>
        document.getElementById('bookingForm').addEventListener('submit', function(event) {
            event.preventDefault();
            document.getElementById('confirmation').style.display = 'block';
        });
    </script>
</body>
</html>
