# Ex04 Places Around Me
## Date: 28/04/2025

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
```
map.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IMAGE MAPPING</title>
</head>
<body>
    <h1>Explore Locations Around My House</h1>
    <p>Click on the marked locations to learn more about each place.</p>
    
    <img src="mapvellore2.png" usemap="#image-map" alt="Map Image">
    
    <map name="image-map">
        <area target="" alt="Katpadi" title="katpadi railway station" href="index1.html" coords="1358,782,1344,1014,1792,779" shape="poly"></area>
        <area target="" alt="Bagayam" title="Bagayam" href="index2.html"coords="961,387,939,604,1326,447,1285,438" shape="poly"></area> 
        <area target="" alt="Adukamparai" title="Adukamparai" href="index3.html"coords="140,505,86,682,538,605" shape="poly"></area> 
        <area target="" alt="Anaicut" title="Anaicut" href="index4.html" coords="1353,323,1442,520,1765,284" shape="poly"></area>
        <area target="" alt="Pallikonda" title="pakkionda" href="index5.html"coords="945,807,1172,794,1176,952,942,945" shape="poly"></area> 
    </map>
    </body>
</html>

index1.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name=""viewport" content="width=device-width,initial-scale=1.0">
        <title>Katpadi</title>
    </head>
    <body>
        <h1>Katpadi</h1>
        <img src="katpadi.avif"usemap="#image-map"style="1000px;height:500px;">
        <p>
            Katpadi junction is the railway station in Tamil Nadu, where highest number of trains stop. Major commuters to Katpadi station are people who travel to Vellore Golden Temple, CMC Hospital and VIT University. On an average it serves approximately 18,000 passengers daily, with 11 originating trains and 67 passing.
        </p>
    </body>
</html>

index2.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name=""viewport" content=""width=device-width,initial-scale=1.0">
        <title>Bagayam</title>
    </head>
    <body>
        <h1>Bagayam</h1>
        <img src="bagayam.png" usemap="#image-map" style="width:1000px;height:500px;">
        <p>
            Bagayam is a small Village/hamlet in Kaniyambadi Block in Vellore District of Tamil Nadu State, India. It comes under Palavansathu Panchayath. It is located 4 KM towards South from District head quarters Vellore. 6 KM from Kaniyambadi. 144 KM from State capital ChennaiBagayam Hospital in Vellore is a well-established facility known for its dedicated team of healthcare professionals and high-quality services. It offers a wide range of treatments, surgeries, and procedures, catering to the diverse needs of its patients, including those in the surrounding cities and towns

        </p>
</body>
</html>

index3.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name=""viewport" content=""width=device-width,initial-scale=1.0">
        <title>Adukamparai</title>
    </head>
    <body>
        <h1>Adukamparai</h1>
        <img src="adukamparai.png"usemap="#image-map"style="width:1000px;height:500px;">
        <p>
            Adukkamparai is a small town located within Vellore City in the Vellore district of Tamil Nadu, India. It's situated on the Vellore to Cuddalore highway, about 8.9 km from Vellore. A notable feature of Adukkamparai is the presence of a government hospital and medical college, Government Vellore Medical College Hospital. 
        </p>
</body>
</html>

index4.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name=""viewport" content=""width=device-width,initial-scale=1.0">
        <title>Thalapureeswarar Temple</title>
    </head>
    <body>
        <h1>Anaicut</h1>
        <img src="anaicut.png"usemap="#image-map"style="width:1000px;height:500px;">
       <p>
        An anaicut is a type of dam or check dam built across a stream or river, primarily for irrigation. It's derived from the Tamil words "aṇai" (dam) and "kaṭṭu" (to build), and it's used to control the flow of water and regulate irrigation systems. 
       </p>
</body>
</html>

index5.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name=""viewport" content=""width=device-width,initial-scale=1.0">
        <title>Pallioknda</title>
    </head>
    <body>
        <h1>Pallikonda</h1>
        <img src="pallikonda.png"usemap="#image-map"style="width:1000px;height:500px;">
        <p>
            Pallikonda is a town panchayat located in the Vellore district of Tamil Nadu, India. It's known for its megalithic assembly, a large non-sepulchral structure, and the nearby Sri Uthara Ranganathar Temple, where Lord Ranganathar is depicted in a reclining posture, which is believed to be the origin of the town's name
        </p>

        </body>
</html>
```


## OUTPUT
![WhatsApp Image 2025-04-28 at 21 58 23_d04a28e6](https://github.com/user-attachments/assets/19613a0b-002c-427b-9538-a28fbc92cd47)

![WhatsApp Image 2025-04-28 at 21 58 30_2f054319](https://github.com/user-attachments/assets/ef58f819-cfff-4a9b-906e-a3305d6085f6)

![WhatsApp Image 2025-04-28 at 21 58 39_768dff08](https://github.com/user-attachments/assets/a6414e6b-68f7-41b4-836c-04e4d6216e4b)










## RESULT
The program for implementing image maps using HTML is executed successfully.
