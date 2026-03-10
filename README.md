# h-kgetaways<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>H&K Getaways</title>

<style>

body{
font-family: Arial, sans-serif;
margin:0;
background:#f5f7fb;
color:#333;
}

header{
background:#1e90ff;
color:white;
padding:40px 20px;
text-align:center;
}

header h1{
margin:0;
font-size:40px;
}

header p{
font-size:18px;
}

.btn{
display:inline-block;
margin-top:15px;
padding:12px 25px;
background:white;
color:#1e90ff;
text-decoration:none;
font-weight:bold;
border-radius:6px;
}

section{
padding:60px 20px;
max-width:1000px;
margin:auto;
}

.services{
display:flex;
flex-wrap:wrap;
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
flex:1;
min-width:250px;
}

form{
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

input, textarea{
width:100%;
padding:10px;
margin:10px 0;
border:1px solid #ccc;
border-radius:5px;
}

button{
background:#1e90ff;
color:white;
padding:12px 20px;
border:none;
border-radius:6px;
font-size:16px;
cursor:pointer;
}

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<header>
<h1>H&K Getaways</h1>
<p>Disney Vacations & Cruise Specialists</p>
<a class="btn" href="#quote">Get a Free Quote</a>
</header>

<section>
<h2>Plan Your Dream Vacation</h2>
<p>
At H&K Getaways, we specialize in helping families plan unforgettable Disney vacations
and incredible cruise adventures. We handle the planning so you can focus on making memories.
</p>
</section>

<section>
<h2>Our Specialties</h2>

<div class="services">

<div class="card">
<h3>🏰 Disney Vacations</h3>
<p>
Planning trips to Walt Disney World, Disneyland, and Disney Cruises.
We help with resorts, park tickets, dining reservations, and tips to make
your vacation magical.
</p>
</div>

<div class="card">
<h3>🚢 Cruise Vacations</h3>
<p>
Caribbean cruises, family cruises, and first-time cruise planning.
We help you find the best cruise line and itinerary.
</p>
</div>

<div class="card">
<h3>✨ Stress-Free Planning</h3>
<p>
From the moment you book to the day you return home, we help make
your trip smooth and stress-free.
</p>
</div>

</div>
</section>

<section id="about">
<h2>About Us</h2>

<p>
H&K Getaways was created by Kenneth and Haley to help families plan
stress-free vacations. Our passion is helping travelers experience the magic
of Disney destinations and the adventure of cruising.
</p>

</section>

<section id="quote">

<h2>Start Planning Your Trip</h2>

<form>
<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Email Address" required>

<input type="text" placeholder="Destination (Disney, Cruise, etc)">

<input type="text" placeholder="Travel Dates">

<input type="number" placeholder="Number of Travelers">

<textarea placeholder="Tell us about your dream trip"></textarea>

<button type="submit">Request Free Quote</button>

</form>

</section>

<footer>

<p>H&K Getaways</p>
<p>Disney & Cruise Vacation Planning</p>

</footer>

</body>
</html>
