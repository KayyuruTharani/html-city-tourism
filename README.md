# html-city-tourism
# Aim: To impement a web page for city Tourism
## Program:
### home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism</title>
    <style>
        body {
            background-color: #f0f0f0; 
        }
        .header {
            text-align: center;
        }
        .navbar {
            text-align: center;
            margin: 20px;
        }
        .navbar a {
            margin: 0 15px;
            text-decoration: none;
        }
        .content {
            text-align: center;
            margin: 20px;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Welcome to Hyberabad Tourism</h1>
    </div>
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </div>
    <div class="content">
        <p>Welcome to SEC - Saveetha Engineering College (Autonomous), a distinguished institution established in 2001 under the visionary leadership of Dr. N. M. Veeraiyan— a committed medical professional and philanthropist par excellence. </p>
           <p> With over 35 years of unwavering commitment to excellence in education, our college has emerged as the forefront of engineering education and research.</p>
    </div>
</body>
</html>
```
### heritage.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage</title>
</head>
<body>
    <div class="header">
        <img src="images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Sites of Hydearbad</h1>
    </div>
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </div>
    <div class="content">
      
            <a href="heritage-sites/site1.html"><img src="images/heritage1.jpeg" alt="Heritage Site 1" width="200"></a>
            <a href="heritage-sites/site2.html"><img src="images/heritage2.jpeg" alt="Heritage Site 2" width="200"></a>
            <a href="heritage-sites/site3.html"><img src="images/heritage3.jpeg" alt="Heritage Site 3" width="200"></a>
            <a href="heritage-sites/site4.html"><img src="images/heritage4.jpeg" alt="Heritage Site 4" width="200"></a>
            <a href="heritage-sites/site5.html"><img src="images/heritage5.jpeg" alt="Heritage Site 5" width="200"></a>
            <a href="heritage-sites/site6.html"><img src="images/heritage6.jpeg" alt="Heritage Site 6" width="200"></a>
            <a href="heritage-sites/site7.html"><img src="images/heritage7.jpeg" alt="Heritage Site 7" width="200"></a>
            <a href="heritage-sites/site8.html"><img src="images/heritage8.jpeg" alt="Heritage Site 8" width="200"></a>
            <a href="heritage-sites/site9.html"><img src="images/heritage9.jpeg" alt="Heritage Site 9" width="200"></a>
            <a href="heritage-sites/site10.html"><img src="images/heritage10.jpeg" alt="Heritage Site 10" width="200"></a>
        
    </div>
</body>
</html>
```
### hotel-booking.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Hotel Booking</title>
</head>
<body>
    <div class="header">
        <img src="images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Book Your Stay in Hyberabad</h1>
    </div>
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </div>
    <div class="content">
        <form action="submit-booking.html" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone"><br><br>
            <label for="checkin">Check-in Date:</label>
            <input type="date" id="checkin" name="checkin"><br><br>
            <label for="checkout">Check-out Date:</label>
            <input type="date" id="checkout" name="checkout"><br><br>
            <label for="roomtype">Room Type:</label>
            <select id="roomtype" name="roomtype">
                <option value="single">Single</option>
                <option value="double">Double</option>
                <option value="suite">Suite</option>
            </select><br><br>
            <input type="submit" value="Book Now">
        </form>
    </div>
</body>
</html>
```
### gallery.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Gallery</title>
</head>
<body>
    <div class="header">
        <img src="images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Gallery of Hyberabad</h1>
    </div>
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="images/gallery1.jpeg" alt="Gallery Image 1" width="300">
        <img src="images/gallery2.jpeg" alt="Gallery Image 2" width="300">
        <img src="images/gallery3.jpeg" alt="Gallery Image 3" width="250">
        <img src="images/gallery4.jpeg" alt="Gallery Image 4" width="250">
    </div>
</body>
</html>
```
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Home</title>
</head>
<body>
    <div class="header">
        <img src="images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Welcome to Hyberabad Tourism</h1>
    </div>
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="heritage.html">Heritage</a>
        <a href="hotel-booking.html">Hotel Booking</a>
        <a href="gallery.html">Gallery</a>
    </div>
    <div class="content">
        <p>Hyberabad is a beautiful city with a rich history and vibrant culture.</p>
        <p>Explore our heritage sites, book a comfortable stay, and view our gallery to see the stunning landmarks we have to offer.</p>
    </div>
</body>
</html>
```
### site1.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 1</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 1</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage1.jpeg" alt="Heritage Site 1" width="300">
        <p>Description and history of Heritage Site 1.</p>
    </div>
</body>
</html>
```

### site2.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 2</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 2</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage2.jpeg" alt="Heritage Site 2" width="300">
        <p>Description and history of Heritage Site 2.</p>
    </div>
</body>
</html>
```
### site3.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 3</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 3</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage3.jpeg" alt="Heritage Site 3" width="300">
        <p>Description and history of Heritage Site 3.</p>
    </div>
</body>
</html>
```
### site4.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 4</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 4</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage4.jpeg" alt="Heritage Site 4" width="300">
        <p>Description and history of Heritage Site 4.</p>
    </div>
</body>
</html>
```
### site5.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 5</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 5</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage5.jpeg" alt="Heritage Site 5" width="300">
        <p>Description and history of Heritage Site 5.</p>
    </div>
</body>
</html>

```
### site6.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 6</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 6</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage6.jpeg" alt="Heritage Site 6" width="300">
        <p>Description and history of Heritage Site 6.</p>
    </div>
</body>
</html>

```
### site7.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 7</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 7</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage7.jpeg" alt="Heritage Site 7" width="300">
        <p>Description and history of Heritage Site 7.</p>
    </div>
</body>
</html>

```
### site8.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 8</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 8</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage8.jpeg" alt="Heritage Site 8" width="300">
        <p>Description and history of Heritage Site 8.</p>
    </div>
</body>
</html>

```
### site9.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 9</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 9</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage1.jpeg" alt="Heritage Site 9" width="300">
        <p>Description and history of Heritage Site 9.</p>
    </div>
</body>
</html>

```
### site10.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>City Tourism - Heritage Site 10</title>
</head>
<body>
    <div class="header">
        <img src="../images/logo.jpeg" alt="City Logo" width="1200" height="100">
        <h1>Heritage Site 10</h1>
    </div>
    <div class="navbar">
        <a href="../index.html">Home</a>
        <a href="../heritage.html">Heritage</a>
        <a href="../hotel-booking.html">Hotel Booking</a>
        <a href="../gallery.html">Gallery</a>
    </div>
    <div class="content">
        <img src="../images/heritage10.jpeg" alt="Heritage Site 10" width="300">
        <p>Description and history of Heritage Site 10.</p>
    </div>
</body>
</html>

```
## Output
![Screenshot (436)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/5c04061d-c071-4652-b433-78b1807e8f53)
![Screenshot (437)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/6bc42fcd-aa1e-4200-b503-c10a0c4d2c0d)
![Screenshot (443)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/4c1df70c-0b44-4167-944d-9fd174bbf446)
![Screenshot (444)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/cef8d794-a1e1-453c-b9c9-138cc614c0e8)

![Screenshot (445)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/5ad7dac7-4714-4b75-88ee-45aae156febc)

![Screenshot (446)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/18e50ef8-4d5c-46fa-af46-54f83e33d0ef)
![Screenshot (447)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/f85d0f1e-2604-4765-af78-75434f975d6e)
![Screenshot (448)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/9c9c6a18-7a25-49bd-92cb-22b15fca8f93)

![Screenshot (449)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/d4b5ac4c-6075-4ed9-9250-70c108d6bb68)
![Screenshot (450)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/ee449ac5-d39b-4eb4-8996-1eb557d03105)
![Screenshot (451)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/9d305a44-c4e8-4748-b51b-0d27132806ac)
![Screenshot (452)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/6f6017a7-78dd-4eb6-bf74-1675bb71ac52)

![Screenshot (439)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/d7a7fdb5-158c-40ea-bfaf-7510d75ec0b2)
![Screenshot (440)](https://github.com/KayyuruTharani/html-city-tourism/assets/142209319/45d16edd-10d6-46af-a066-ceab453f1f27)


