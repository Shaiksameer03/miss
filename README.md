<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  <style>
    body {
      padding-top: 56px; /* Adjusted for the fixed navbar height */
    }
    .navbar {
      transition: background-color 0.3s;
    }
    .navbar-scrolled {
      background-color: #333; /* Change background color when scrolled */
    }
  </style>
</head>
<body>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
  <a class="navbar-brand" href="#">FOOD,LLC</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
    <ul class="navbar-nav"
    <ul class="navbar-nav ml-auto">
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Our Menu
        </a>
        <div class="dropdown-menu dropdown-menu-full" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Chicken</a>
          <p> <bold>Chicken generally includes low fat in the meat itself (castrated roosters excluded). The fat is highly concentrated on the skin. A 100g serving of baked chicken breast contains 4 grams of fat and 31 grams of protein, compared to 10 grams of fat and 27 grams of protein for the same portion of broiled, lean skirt steak.</bold></p>
          <a class="dropdown-item" href="#">Beef</a>
          <p>Along with other kinds of red meat, high consumption is associated with an increased risk of colorectal cancer and coronary heart disease, especially when processed. Beef has a high environmental impact, being a primary driver of deforestation with the highest greenhouse gas emissions of any agricultural product.</p>
          <a class="dropdown-item" href="#">Sushi</a>
          <p>Roast Beef Sushi is a delightful appetizer or delicious end to a meal in the Japanese manner of serving a rice dish as the last course. It can also be enjoyed as a meal in itself along with a salad and bowl of miso soup.</p>
        </div>
      </li>
    </ul>
  </div>
</nav>
<!-- Page Content -->
<div class="container">
  <h1 class="mt-5 text-center">Page Heading</h1>
  <!-- Add your content here -->
</div>
<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script>
  // Change navbar background on scroll
  $(window).scroll(function() {
    if ($(this).scrollTop() > 50) {
      $('.navbar').addClass('navbar-scrolled');
    } else {
      $('.navbar').removeClass('navbar-scrolled');
    }
  });
</script>

</body>
</html>

