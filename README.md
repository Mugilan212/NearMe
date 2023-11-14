# Ex:04 Places Around Me
## Date: 28/10/2023 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
## map.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="map1.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Kundrathur Murugan Temple" title="Kundrathur Murugan Temple" href="Temple.html" coords="928,834,723,775" shape="rect">
        <area target="_blank" alt="Venkateswara Cinemas" title="Venkateswara Cinemas" href="Theatre.html" coords="950,448,1149,530" shape="rect">
        <area target="_blank" alt="Outer Ring Road" title="Outer Ring Road" href="ORR.html" coords="569,428,754,489" shape="rect">
        <area target="_blank" alt="Chembrambakkam Lake Dam" title="Chembrambakkam Lake Dam" href="Dam.html" coords="273,282,504,364" shape="rect">
        <area target="_blank" alt="Poorvika Mobiles" title="Poorvika Mobiles" href="Mobileshop.html" coords="1041,286,1233,356" shape="rect">
    </map>
</body>
</html>
```
## Temple.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KUNDRATHUR MURUGAN TEMPLE</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:black;
        }
        p{
            text-align: justify;
            color:black;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>KUNDRATHUR MURUGAN TEMPLE</h1>
    <br>
    <hr color="black">
    <p>This is the only Murugan temple in Tamil Nadu where the God is standing in a north facing direction. This temple was constructed by King Kulothunga Chola II. I think it has around 100 steps but which is easily climbable comparing other hill temples. Vehicles (cars, bikes, autos) can also be driven up the hill.Once winning the demons in Thiruporur, Lord Muruga went to Thirutani in a joyous spirit. He placed a Siva Linga, performed pooja and meditated deep. The temple was subsequently constructed by the great Chola King Kulothunga Chola. Lord Siva, worshiped by Lord Muruga graces the worshipers in the name of Kandaleeswarar in a separate shrine.
        One of the famous Murugan temple in the outskirts of Chennai.This is the only Murugan temple in Tamil Nadu where the Moolavar ( main deity) is standing in a north facing direction. This temple was constructed by King Kulothunga Chola II. There are 84 steps to reach this hill temple. Vehicles (cars, bikes, autos) can also be driven up the hill right up to the front of the temple on the hill, for those that cannot walk up the 84 steps. The temple is very close to the outer ring road for those that need faster accessibility to the temple. Pallavaram to Kundrathur there are a lot of buses too but do not go all the way to the temple.
    </p>

</body>
</html>
```
## Theatre.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VENKATESWARA CINEMAS</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:black;
        }
        p{
            text-align: justify;
            color:black;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>VENKATESWARA CINEMAS</h1>
    <br>
    <hr color="black">
    <p>Venkateswara Theatre in Kundrathur, Chennai is known to satisfactorily cater to the demands of its customer base. The business came into existence in 2012 and has, since then, been a known name in its field. It stands located at Main Road, Kundrathur-600069.The business strives to make for a positive experience through its offerings.Customer centricity is at the core of Venkateswara Theatre in Kundrathur, Chennai and it is this belief that has led the business to build long-term relationships. Ensuring a positive customer experience, making available goods and/or services that are of top-notch quality is given prime importance.</p>
</body>
</html>
```
## Dam.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CHEMBRAMBAKKAM LAKE DAM</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:black;
        }
        p{
            text-align: justify;
            color:black;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>CHEMBRAMBAKKAM LAKE DAM</h1>
    <br>
    <hr color="black">
    <p>Chembarambakkam lake is a lake located in Chennai, Tamil Nadu, India, about 25 km from Chennai. It is one of the two rain-fed reservoirs from where water is drawn for supply to Chennai City, the other one being the Puzhal Lake. The Adyar River originates from this lake. A part of water supply of the metropolis of Chennai is drawn from this lake. This was the first Artificial lake built by Rajendra Chola I the son of Rajaraja Chola and Thiripuvana Madeviyar, prince of Kodumbalur.Chembarambakkam lake was known as Puliyur Kottam. It is one of the 24 kottams (villages) that existed even during the later Chola period in Thondai Mandalam which had Kanchipuram as its headquarters. The lake was built by Rajendra Chola, the son of Rajaraja Chola.The full tank level is 85.40 ft (26.03 m). The full capacity of the lake is 3,645 million ft3 (108 million m3). The level of the tank in feet is 75.60 ft (23.04 m).</p>

</body>
</html>
```
## ORR.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OUTER RING ROAD</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:black;
        }
        p{
            text-align: justify;
            color:black;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>OUTER RING ROAD</h1>
    <br>
    <hr color="black">
    <p>The Outer Ring Road, officially State Highway 234 (SH 234),is a major transport corridor along the periphery of Chennai Metropolitan Area (CMA) by the Chennai Metropolitan Development Authority (CMDA). It is 62 km long connecting GST Road at Perungalathur, GST Road at Vandalur, NH 48 (GWT Road) at Nazarethpettai, NH 716 (CTH Road) at Pattabiram to NH 16 (GNT Road) at Vijayanaallur and to TPP road at Minjur. On 29 August 2010, the then Tamil Nadu Deputy Chief Minister M. K. Stalin laid the foundation for the first phase of the project from Vandalur to Nemilichery covering a distance of 30 kilometres (19 mi). The Chennai ORR generally covers Avadi North, West and South, Redhills, Minjur and Tambaram neighbourhoods.</p>

</body>
</html>
```
## Mobileshop.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>POORVIKA MOBILES</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:black;
        }
        p{
            text-align: justify;
            color:black;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>POORVIKA MOBILES</h1>
    <br>
    <hr color="black">
    <p>Poorvika Mobiles Pvt Ltd in Kundrathur, Chennai is one of the leading businesses in the Data Card Dealers. Also known for Mobile Phone Dealers, Mobile Phone Dealers-Apple, Laptop Dealers, TV Dealers, Mobile Phone Dealers-Oneplus, Mobile Phone Dealers-Samsung, Wrist Watch Dealers, UPS Dealers and much more. Find Address, Contact Number, Reviews & Ratings, Photos, Maps of Poorvika Mobiles Pvt Ltd, Chennai.Poorvika Mobile is a dynamic and prominent player in the Indian mobile retail landscape, specializing in the distribution of an extensive range of smartphones, accessories, and electronic gadgets. With a rich history dating back to its inception in 2004, Poorvika Mobile has consistently strived to provide cutting-edge technology solutions to its customers, making it a household name in the Indian mobile market.</p>
</body>
</html>
```
## OUTPUT
![web ex 4](https://github.com/Mugilan212/NearMe/assets/144508901/3d5eda9b-b74a-4963-87d8-f5fd747fd2f2)
![map1](https://github.com/Mugilan212/NearMe/assets/144508901/f9f0d123-aff5-4884-803e-b3033e6b9bc8)
![web ex 4 1](https://github.com/Mugilan212/NearMe/assets/144508901/564262ec-2c2f-4780-9fa3-6952e1bde8af)
![web ex 4 2](https://github.com/Mugilan212/NearMe/assets/144508901/d9a179ec-c4ac-4958-97ed-f4f77eb6d07d)
![web ex 4 3](https://github.com/Mugilan212/NearMe/assets/144508901/66623934-a185-40e6-a005-c7e31a337713)
![web ex 4 4](https://github.com/Mugilan212/NearMe/assets/144508901/49765a98-80a5-440f-b672-b6f2f9a70737)
![web ex 4 5](https://github.com/Mugilan212/NearMe/assets/144508901/6ca20e72-5c6f-4fad-8d50-f37d3528ddd6)



## RESULT
The program for implementing image maps using HTML is executed successfully.
