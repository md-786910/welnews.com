<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Live Weather</title>
    <meta name="keywords" content="weather, world, openweathermap, weather, layer" />
    <meta name="description" content="A layer with current weather conditions in cities for world wide" />
    <meta name="domain" content="openweathermap.org" />
    <meta http-equiv="pragma" content="no-cache" />
    <meta http-equiv="Expires" content="-1" />
</head>
<style>
    * {
        padding: 0;
        margin: 0;
    }
    
    body {
        background-color: rgba(12, 107, 17, 1);
        width: 100%;
        height: 40em;
        background-repeat: no-repeat;
    }
    
    #container {
        display: flex;
        justify-content: center;
        color: rgb(231, 22, 22);
        font-family: sans-serif;
        flex-direction: column;
        align-items: center;
    }
    
    #report {
        margin-top: 0.5em;
    }
    
    .card {
        /* background-color: cyan; */
        width: 40%;
        height: 25em;
        margin-top: 2em;
        display: block;
        overflow-y: scroll;
        /* border: none; */
    }
    
    .card::after {
        content: "";
        position: absolute;
        top: 3.5em;
        z-index: -1;
        left: 20em;
        background-image: url("imgwea.png");
        width: 50%;
        height: 25em;
        background-position: center;
        border: 1em double black;
        background-size: cover;
        background-repeat: no-repeat;
        border-radius: 1em;
        opacity: 0.5;
    }
    
    #weather-form {
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        line-height: 1em;
    }
    
    #searchweather {
        outline: none;
        /* border: 0.2em solid red; */
        font-size: 1.5em;
        background-color: black;
        color: white;
        border-radius: 0.2em;
        font-family: 'Courier New', Courier, monospace;
    }
    
    #setweather {
        outline: none;
        border: none;
        font-size: 1.5em;
        color: red;
        font-family: 'Courier New', Courier, monospace;
    }
    
    #con,
    #weatherid {
        color: black;
        font-family: 'Courier New', Courier, monospace;
    }
    
    @media screen and (max-width: 1400px) {
        #con,
        #weatherid {
            margin-left: 3em;
            line-height: 1.5em;
        }
    }
    
    @media screen and (max-width: 1250px) {
        #con,
        #weatherid {
            margin-left: 5.5em;
            line-height: 1.5em;
        }
        #searchweather {
            /* border: 0.2em solid red; */
            font-size: 1.7em;
            margin-left: 3.5em;
        }
        #setweather {
            font-size: 1.7em;
            margin-left: 3.8em;
        }
    }
    
    @media screen and (max-width: 480px) {
        #con,
        #weatherid {
            margin-left: 6em;
            line-height: 1.5em;
            width: 100%;
        }
        .card {
            /* background-color: cyan; */
            width: 100%;
            height: 25em;
            margin-top: 2em;
            display: block;
            overflow-y: scroll;
            /* border: none; */
        }
        .card::after {
            content: "";
            position: absolute;
            top: 3.5em;
            left: 0em;
            width: 100%;
            height: 30em;
        }
        #searchweather {
            /* border: 0.2em solid red; */
            font-size: 1.7em;
            margin-left: 2em;
        }
        #setweather {
            font-size: 1.7em;
            margin-left: 2em;
        }
    }
    
    @media screen and (max-width: 480px) {
        #con,
        #weatherid {
            margin-left: 3em;
            line-height: 1.5em;
            width: 100%;
        }
    }
</style>

<body>
    <div id="container">
        <h2 id="report">Weather Report</h2>
        <div class="card">
            <form action="" id="weather-form">
                <input type="text" name="weather" id="setweather" placeholder="search city"><br>
                <input type="button" value="search" id="searchweather">
            </form>
            <h2 id="con"></h2>
            <h2 id="weatherid"></h2>
        </div>
    </div>
</body>
<script>
    // api=5cf004ad4cd179c105b2d1791dd1566b

    let searchweather = document.querySelector("#searchweather");
    let setweather = document.querySelector("#setweather");
    let con = document.querySelector("#con");
    let weatherid = document.querySelector("#weatherid");
    searchweather.addEventListener('click', function(e) {

        e.preventDefault();
        const weathervalue = setweather.value;
        if (weathervalue == '') {
            let defaultcity = 'delhi';
            url = `http://api.openweathermap.org/data/2.5/weather?q=${defaultcity}&appid=5cf004ad4cd179c105b2d1791dd1566b`
            fetch(url).then(Response => {
                return Response.json();
            }).then(data => {
                console.log(data)
                let sys = (data["sys"])
                let country = (sys.country)

                let sunrise = new Date(sys.sunrise).toLocaleTimeString("en-US")

                let sunset = new Date(sys.sunset).toLocaleTimeString('en-us')
                let coord = data["coord"];
                let lat = coord.lat;
                long = coord.lon;
                let temp = data["main"];
                let cel = Math.floor(temp.temp - 273.5);
                let feels = Math.floor(temp["feels_like"] - 273.5);
                let wind = data["wind"];
                let weather = data["weather"];
                weather.forEach(element => {
                    let weath = element.description;
                    weatherid.innerHTML = `WEATHER:${weath}`;

                });
                con.innerHTML = `CITY:${data.name} <br> COUNTRY:${country} <br> SUNSET:${sunset} <br> SUNRISE:${(sunrise)} <br>
        LONG:${long} <br> LAT:${lat} <br> TEMP:${cel}deg^C <br> FEELS-LIKE:${feels}deg^C <br> PRESSURE:${temp['pressure']}^hpa <br> 
        WINDSPEED:${wind["speed"]}m/s <br>
        `;
            });
        } else if (weathervalue != null) {
            url = `http://api.openweathermap.org/data/2.5/weather?q=${weathervalue}&appid=5cf004ad4cd179c105b2d1791dd1566b`
            fetch(url).then(Response => {
                return Response.json();
            }).then(data => {
                console.log(data)
                let sys = (data["sys"])
                let country = (sys.country)

                let sunrise = new Date(sys.sunrise).toLocaleTimeString("en-US")

                let sunset = new Date(sys.sunset).toLocaleTimeString("en-US")
                let coord = data["coord"];
                let lat = coord.lat;
                long = coord.lon;
                let temp = data["main"];
                let cel = Math.floor(temp.temp - 273.5);
                let feels = Math.floor(temp["feels_like"] - 273.5);
                let wind = data["wind"];
                let weather = data["weather"];
                weather.forEach(element => {
                    let weath = element.description;
                    weatherid.innerHTML = `WEATHER:${weath}`;

                });
                con.innerHTML = `CITY:${data.name} <br> COUNTRY:${country} <br> SUNSET:${sunset} <br> SUNRISE:${(sunrise)} <br>
        LONG:${long} <br> LAT:${lat} <br> TEMP:${cel}deg^C <br> FEELS-LIKE:${feels}deg^C <br> PRESSURE:${temp['pressure']}^hpa <br> 
        WINDSPEED:${wind["speed"]}m/s <br>
        `;
            });

        } else {
            // console.log("error city")optional
            // try {
            // fun()
            // } catch (e) {
            // console.log(e.massage)
            // }
        }
        // window.location = ""
        setweather.value = '';
    })
</script>

</html>