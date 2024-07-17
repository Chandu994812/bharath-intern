# bharath-intern
bharath internship projects code

HTML CODE::

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Netflix</title>
    
    <link rel="stylesheet" href="stylechandu.css">
    <link rel="stylesheet" href="mediaquery.css">
    <link rel="stylesheet" href="https://maxst.icons8.com/vue-static/landings/line-awesome/line-awesome/1.3.0/css/line-awesome.min.css">
    <script src="https://kit.fontawesome.com/bc3a1796c2.js" crossorigin="anonymous"></script>
    <link rel="shortcut icon" href="https://image.flaticon.com/icons/png/512/870/870910.ico'/> 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.css" />
  </head>
  <body>

    <div class="navbar">
<li class="logo"><img src="https://www.searchpng.com/wp-content/uploads/2019/02/Netflix-Logo-PNG-image-200x200.png" alt="Netflix Logo"></li>
<li class="buttons">Sign In</a>

    </div>
    <div class="main">
<div class="area">
  <h1>Unlimited movies, TV <br>shows, and more.</h1>
  <h3>Watch anywhere. Cancel anytime.
    </h3>

    <div class="search">
      <input type="text" class="box" placeholder="Email">
      <span class="try">
Try 30 days free <i class="fas fa-chevron-right"></i>


      </span>
</div>
<h4>Ready to watch? Enter your email to create or access your account
  </h4>
    </div>
   
    </div>
    <div class="container1">
        <div class="text">
          <h1>Enjoy on your TV.
            </h1>
            <p>
                Watchx on Smart TVs, Playstation, Xbox, <br>
                Chromecast, Apple TV, Blu-ray players, and<br>
                 more.
            </p>
        </div>
        <div class="image">
  <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/tv.png">
        </div>
      </div>
      <div class="container1">
          
          <div class="image">
    <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/mobile.png">
          </div>
          <div class="text">
              <h1>Download your shows to watch on the go.
                </h1>
                <p>
                    Save your data and watch all your favorites offline.
                </p>
            </div>
            
        </div>
        <div class="container1">
            <div class="text">
              <h1>Watch everywhere.

                </h1>
                <p>
                    Stream unlimited movies and TV shows on <br>your phone, tablet, laptop, and TV without paying more.

                </p>
            </div>
            <div class="image">
      <img src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/device-pile.png">
            </div>
          </div>
          <div class="question">
            <h1>Frequently Asked Questions
              </h1>
              <div class="quest">
                <div class="textbox">What is Netflix?</div>
                <i class="las la-plus"></i>
              </div>
              <div class="quest">
                  <div class="textbox">How much does Netflix cost?</div>
                  <i class="las la-plus"></i>
                </div>             
                <div class="quest">
                    <div class="textbox">Where can I watch?</div>
                    <i class="las la-plus"></i>
                  </div>                 <div class="quest">
                    <div class="textbox">How do I cancel?</div>
                    <i class="las la-plus"></i>
                  </div>               
                  <div class="quest">
                      <div class="textbox">What can I watch on Netflix??</div>
                      <i class="las la-plus"></i>
                    </div>
                    <div class="quest">
                        <div class="textbox">What is Netflix?</div>
                        <i class="las la-plus"></i>                   
                      </div>    
                      <div class="search1">
                          <input type="text" class="box1" placeholder="Email">
                          <span class="try1">
                    Try 30 days free <i class="fas fa-chevron-right"></i>
                    
                    
                          </span>
                          
                    </div>      
                    <h4>Ready to watch? Enter your email to create or access your account
                      </h4>
                    </div>
                    <div class="footer">


                        <div class="footercon">
                          <div class="flex1">
                                                    <h5>Questions? Call 1-866-579-7172
                            </h5>
                            <h5>
    </h5>
                          </div>
                          
               <ul class="list1">
                 
                        <li><a href="">FAQ</a></li>
                        <li><a href="">Investor Relation</a></li>
                        <li><a href="">Ways to Watch</a></li>

                        <li><a href="">Corporate Information</a></li>
                        <li><a href="">Netflix Originals</a></li>
                        </ul>
                        <ul class="list1">
                        <li><a href="">Home</a></li>
                            <li><a href="">Jobs</a></li>
                            <li><a href="">Terms of Use</a></li>
                            <li><a href="">Contact Us</a></li>
                            <li><a href="">#</a></li>
                            </ul>
                            <ul class="list1">
                                <li><a href="">Account</a></li>
                                <li><a href="">Redeem Gift Cards</a></li>
                                <li><a href="">Privacy</a></li>
                                <li><a href="">Speed Test</a></li>
                                <li><a href="">#</a></li>

                                </ul>
                                <ul class="list1">
                                    <li><a href="">Media Center<</a></li>
                                    <li><a href="">Buy Gift Cards</a></li>
                                    <li><a href="">Cookie Preferences</a></li>
                                    <li><a href="">Legal Notices</a></li>
                                    <li><a href="">#</a></li>

                                    </ul>
                                 
                    </div>

                  </div>
                  <div class="end">
<h2>
Netflix US
</h2> 
<h2>
  </h2>                    </div>
  </body>
</html>

CSS CODE::

@import url("https://fonts.googleapis.com/css?family=IBM+Plex+Sans&display=swap");
@import url("https://fonts.googleapis.com/css?family=Martel+Sans&display=swap");
@import url("https://fonts.googleapis.com/css?family=Roboto&display=swap");

body {
  margin: 0;
  padding: 0;
  flex-wrap: wrap;
  display: flex;
  font-family: "Roboto", sans-serif;
  background-color: rgba(8, 8, 8, 0.89);
}

.navbar {
  display: flex;
  flex-direction: row;
  position: relative;
  align-items: center;
  width: 100%;
  height: 50px;
  min-height: 100px;
  align-items: center;
  justify-content: space-between;
  background-color: transparent;
  align-self: center;
}

.navbar li {
  margin: 0 50px;
  list-style-type: none;
  display: flex;
  flex-direction: row;
}

.navbar li:nth-child(2) {
  margin-top: -10px;
  margin-right: 70px;
}

.logo img {
  width: 180px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  align-self: center;
}

.logo {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  align-self: center;
}

.buttons {
  background-color: #e50914;
  padding: 7px 17px;
  color: white;
  display: flex;
  flex-direction: row;
  border-radius: 3px;
}

.main {
  width: 100%;
  margin-top: -100px;
  background-size: cover;
  align-items: center;
  overflow-x: hidden;
  justify-content: center;
  display: flex;
  background-position: center;
  min-height: 710px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)),
    url(https://assets.nflxext.com/ffe/siteui/vlv3/a1dc92ca-091d-4ca9-a05b-8cd44bbfce6a/f9368347-e982-4856-a5a4-396796381f28/RS-en-20191230-popsignuptwoweeks-perspective_alpha_website_large.jpg);
}

.area {
  color: white;
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  margin-top: 70px;
}

.area h1 {
  font-size: 60px;
  word-spacing: 15px;
  line-height: 75px;
}

.area h3 {
  margin-top: -30px;
  font-size: 27px;
  font-weight: normal;
}

.search {
  width: 150%;
  background-color: none;
  min-height: 80px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  text-align: left;
  margin-top: 10px;
}

.box {
  width: 100%;
  min-height: 65px;
}

.try {
  display: inline-flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  background-color: #e50914;
  min-height: 70px;
  width: 70%;
  font-size: 30px;
  text-transform: uppercase;
}

.area h4 {
  margin-top: 10px;
  font-weight: normal;
}

.container1 {
  width: 100%;
  min-height: 460px;
  background-color: black;
  margin-top: 10px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-evenly;
  text-align: left;
}

.container1 img {
  display: flex;
  justify-content: center;
  flex-direction: row;
  object-fit: contain;
  object-position: center;
  align-self: center;
  max-width: 100%;
  height: 350px;
}

.container1.image {
  display: flex;
  justify-content: center;
  flex-direction: row;
  align-items: center;
  align-self: center;
  object-fit: contain;
}

.text {
  color: white;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
  align-self: center;
  align-content: center;
}

.text p {
  font-size: 1.5rem;
  margin-top: 5px;
}

.text h1 {
  font-size: 3.125rem;
}

.question {
  width: 100%;
  min-height: 950px;
  background-color: #000;
  margin-top: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-end;
  text-align: center;
}

.question h1 {
  text-align: center;
  color: white;
  margin-bottom: 50px;
  text-align: center;
  font-size: 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.quest {
  width: 51%;
  min-height: 75px;
  background-color: #303030;
  color: white;
  align-items: center;
  justify-content: space-between;
  display: flex;
  text-align: left;
  flex-direction: row;
  margin: 5px 0;
}

.quest.textbox {
  display: flex;
  text-align: left;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  justify-items: center;
  align-self: center;
  font-size: 25px;
  margin: 0 30px;
  word-spacing: 5px;
  text-align: left;
}

.quest i {
  margin: 0 30px;
  font-size: 40px;
  color: rgb(255, 255, 255);
}

.quest:focus {
  background-color: red;
}

.search1 {
  width: 50%;
  background-color: none;
  min-height: 80px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  text-align: left;
  margin-top: 10px;
}

.box1 {
  width: 100%;
  min-height: 65px;
}

.try1 {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  background-color: #e50914;
  min-height: 70px;
  width: 70%;
  color: white;
  font-size: 30px;
  margin: 50px 0;
  text-transform: uppercase;
}

.question h4 {
  color: white;
  margin-top: -20px;
  padding-bottom: 40px;
}

.footer {
  display: flex;
  flex-direction: column;
  width: 100%;
  min-height: 375px;
  background-color: black;
  margin-top: 10px;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
}

.footercon {
  display: flex;
  flex-direction: row;
  width: 100%;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  min-height: 50px;
  background-color: transparent;
}

.footer.flex1 {
  color: #999;
  justify-content: space-around;
  align-items: flex-start;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
  font-size: 17px;
  min-height: 30px;
}

.footer.flex1 h5 {
  align-self: flex-start;
}

.list1 {
  color: white;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  align-items: flex-start;
  justify-items: flex-start;
  align-self: center;
  justify-content: center;
  min-height: 50px;
  font-size: 13px;
  padding: 0px 70px;
  text-align: left;
}

.list1 li {
  font-size: 13px;
  margin: 7px -10px;
  list-style-type: none;
  text-align: left;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  align-items: flex-start;
  justify-items: center;
  align-self: flex-start;
  justify-content: center;
}

.list1 li a {
  color: #999;
  text-decoration: none;
  font-size: 14px;
}

li a {
  font-size: 13px;
  text-align: center;
  color: #999;
}

.footertxt {
  color: white;
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  justify-content: flex-end;
}

.end {
  width: 100%;
  min-height: 50px;
  background-color: black;
  justify-content: space-around;
  align-items: flex-start;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  color: #999;
  margin-top: -60px;
}

.end h2 {
  display: flex;
  flex-direction: row;
  font-size: 16px;
}

@media (min-width: 250px) and (max-width: 980px) {
  body {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
  }

  .container1 {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
    align-self: center;
  }

  .area h1 {
    font-size: 40px;
    line-height: 60px;
  }

  .area h3 {
    margin-top: 10px;
  }

  .container1 img {
    width: 60%;
  }

  .navbar {
    display: flex;
    flex-direction: column;
    background-color: black;
    align-items: center;
    justify-content: center;
    padding: 0;
    min-height: 250px;
    margin-bottom: 30px;
  }

  .search {
    display: flex;
    flex-direction: column;
    margin: 30px;
    width: 50%;
    margin: 0 10px;
  }

  .box {
    width: 100%;
    margin-bottom: 20px;
    margin: 30px;
  }

  .try {
    width: 200px;
    margin: 0 10px;
    font-size: 17px;
    min-height: 50px;
  }

  .search1 {
    display: flex;
    flex-direction: column;
    margin: 30px;
    width: 50%;
    margin: 0 10px;
    margin-bottom: 40px;
  }

  h4 {
    color: white;
  }

  .box1 {
    width: 100%;
    margin-bottom: 20px;
    margin: 30px;
  }

  .try1 {
    width: 200px;
    margin: 0 10px;
    font-size: 17px;
    min-height: 50px;
  }

  .text {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    align-self: center;
    text-align: center;
    margin-left: 10px;
    margin-right: 10px;
  }

  .text h1 {
    font-size: 2rem;
    margin-left: 10px;
    margin-right: 10px;
  }

  .text p {
    font-size: 1.2rem;
    margin-left: 10px;
    margin-right: 10px;
  }

  .quest.textbox {
    font-size: 20px;
    margin-left: 10px;
    margin-right: 10px;
  }

  .quest {
    width: 80%;
    min-height: 75px;
    margin-left: 10px;
    margin-right: 10px;
  }
}






2ND TASK IS WHEATHER WEBSITE:

HTML CODE IS::
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="weather__header">
            <form class="weather__search">
                <input type="text" placeholder="Search for a city..." class="weather__searchform">
                <i class="fa-solid fa-magnifying-glass"></i>
            </form> 
            <div class="weather__units">
                <span class="weather_unit_celsius">&#176C</span>
                <span class="weather_unit_farenheit">&#176F</span>
            </div>
        </div>
        <div class="weather__body">
            <h1 class="weather__city"></h1>
            <div class="weather__datetime">
            </div>
            <div class="weather__forecast"></div>
            <div class="weather__icon">
            </div>
            <p class="weather__temperature">
            </p>
            <div class="weather__minmax">
                <p>Min: 12&#176</p>
                <p>Max: 16&#176</p>
            </div>
        </div>

        <div class="weather__info">
            <div class="weather__card">
                <i class="fa-solid fa-temperature-full"></i>
                <div>
                    <p>Real Feel</p>
                    <p class="weather__realfeel">18&#176</p>
                </div>
            </div>
            <div class="weather__card">
                <i class="fa-solid fa-droplet"></i>
                <div>
                    <p>Humidity</p>
                    <p class="weather__humidity">18&#176</p>
                </div>
            </div>
            <div class="weather__card">
                <i class="fa-solid fa-wind"></i>
                <div>
                    <p>Wind</p>
                    <p class="weather__wind">18&#176</p>
                </div>
            </div>
            <div class="weather__card">
                <i class="fa-solid fa-gauge-high"></i>
                <div>
                    <p>Pressure</p>
                    <p class="weather__pressure">18&#176</p>
                </div>
            </div>
        </div>
    </div>
    <script src="https://kit.fontawesome.com/a692e1c39f.js" crossorigin="anonymous"></script>
    <script src="script.js"></script>
</body>
</html>


CSS CODE IS::

@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

.container {
    background: #171717;
    color: #fff;
    padding: 2rem;
    width: 40%;
    margin: 4rem auto;
    border-radius: 10px;
}

.weather__header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

input {
    border: none;
    background: #1e1e1e;
    outline: none;
    color: #fff;
    padding: 0.5rem 2.5rem;
    border-radius: 5px;
}

input::placeholder {
    color: #fff;
}

.weather__search {
    position: relative;
}

.weather__search i {
    position: absolute;
    left: 10px;
    top: 10px;
    font-size: 15px;
    color: #fff;
}

.weather__units {
    font-size: 1.5rem;
}

.weather__units span {
    cursor: pointer;
}

.weather__units span:first-child {
    margin-right: 0.5rem;
}

.weather__body {
    text-align: center;
    margin-top: 3rem;
}

.weather__datetime {
    margin-bottom: 2rem;
    font-size: 14px;
}

.weather__forecast {
    background: #1e1e1e;
    display: inline-block;
    padding: 0.5rem 1rem;
    border-radius: 30px;
}

.weather__icon img {
    width: 100px;
}

.weather__temperature {
    font-size: 1.75rem;
}

.weather__minmax {
    display: flex;
    justify-content: center;
}

.weather__minmax p {
    font-size: 14px;
    margin: 0.5rem;
}

.weather__info {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 1rem;
    margin-top: 3rem;
}

.weather__card {
    display: flex;
    align-items: center;
    background: #1e1e1e;
    padding: 1rem;
    border-radius: 10px;
}

.weather__card i {
    font-size: 1.5rem;
    margin-right: 1rem;
}

.weather__card p {
    font-size: 14px;
}

@media(max-width: 936px){
    .container {
        width: 90%;
    }

    .weather__header {
        flex-direction: column;
    }

    .weather__units {
        margin-top: 1rem;
    }
}


@media(max-width: 400px){
    .weather__info {
        grid-template-columns: none;
    }
}


JAVASCRIPT ODE IS ::

// state
let currCity = "London";
let units = "metric";

// Selectors
let city = document.querySelector(".weather__city");
let datetime = document.querySelector(".weather__datetime");
let weather__forecast = document.querySelector('.weather__forecast');
let weather__temperature = document.querySelector(".weather__temperature");
let weather__icon = document.querySelector(".weather__icon");
let weather__minmax = document.querySelector(".weather__minmax")
let weather__realfeel = document.querySelector('.weather__realfeel');
let weather__humidity = document.querySelector('.weather__humidity');
let weather__wind = document.querySelector('.weather__wind');
let weather__pressure = document.querySelector('.weather__pressure');

// search
document.querySelector(".weather__search").addEventListener('submit', e => {
    let search = document.querySelector(".weather__searchform");
    // prevent default action
    e.preventDefault();
    // change current city
    currCity = search.value;
    // get weather forecast 
    getWeather();
    // clear form
    search.value = ""
})

// units
document.querySelector(".weather_unit_celsius").addEventListener('click', () => {
    if(units !== "metric"){
        // change to metric
        units = "metric"
        // get weather forecast 
        getWeather()
    }
})

document.querySelector(".weather_unit_farenheit").addEventListener('click', () => {
    if(units !== "imperial"){
        // change to imperial
        units = "imperial"
        // get weather forecast 
        getWeather()
    }
})

function convertTimeStamp(timestamp, timezone){
     const convertTimezone = timezone / 3600; // convert seconds to hours 

    const date = new Date(timestamp * 1000);
    
    const options = {
        weekday: "long",
        day: "numeric",
        month: "long",
        year: "numeric",
        hour: "numeric",
        minute: "numeric",
        timeZone: `Etc/GMT${convertTimezone >= 0 ? "-" : "+"}${Math.abs(convertTimezone)}`,
        hour12: true,
    }
    return date.toLocaleString("en-US", options)
   
}

 

// convert country code to name
function convertCountryCode(country){
    let regionNames = new Intl.DisplayNames(["en"], {type: "region"});
    return regionNames.of(country)
}

function getWeather(){
    const API_KEY = '64f60853740a1ee3ba20d0fb595c97d5'

fetch(`https://api.openweathermap.org/data/2.5/weather?q=${currCity}&appid=${API_KEY}&units=${units}`).then(res => res.json()).then(data => {
    console.log(data)
    city.innerHTML = `${data.name}, ${convertCountryCode(data.sys.country)}`
    datetime.innerHTML = convertTimeStamp(data.dt, data.timezone); 
    weather__forecast.innerHTML = `<p>${data.weather[0].main}`
    weather__temperature.innerHTML = `${data.main.temp.toFixed()}&#176`
    weather__icon.innerHTML = `   <img src="http://openweathermap.org/img/wn/${data.weather[0].icon}@4x.png" />`
    weather__minmax.innerHTML = `<p>Min: ${data.main.temp_min.toFixed()}&#176</p><p>Max: ${data.main.temp_max.toFixed()}&#176</p>`
    weather__realfeel.innerHTML = `${data.main.feels_like.toFixed()}&#176`
    weather__humidity.innerHTML = `${data.main.humidity}%`
    weather__wind.innerHTML = `${data.wind.speed} ${units === "imperial" ? "mph": "m/s"}` 
    weather__pressure.innerHTML = `${data.main.pressure} hPa`
})
}

document.body.addEventListener('load', getWeather())
