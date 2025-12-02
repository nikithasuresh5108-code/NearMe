# Ex03 Places Around Me
## Date: 01.12.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
map.html
```
<html>
    <head>
        <title>CITY</title>
    </head>
    <body>
        <h1>VARKALA</h1>
        <h2>NIKITHA(25003017)</h2>
        <img src="Screenshot 2025-11-28 112352.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="clafouti beach resort" title="clafouti beach resort" href="resort.html" coords="210,360,396,429" shape="rect">
    <area target="" alt="mantraa villa" title="mantraa villa" href="villas.html" coords="758,377,71" shape="circle">
    <area target="" alt="varakala beach" title="varakala beach" href="beach.html" coords="421,661,534,631,580,683,550,751,487,762,423,727" shape="poly">
    <area target="" alt="varkala cliff" title="varkala cliff" href="cliff.html" coords="271,481,448,466,477,578,389,581" shape="poly">
    <area target="" alt="aadhi homestay" title="aadhi homestay" href="homestay.html" coords="658,74,67" shape="circle">
</map>
    </body>
</html>
```

beach.html
```
<html>
    <head>
        <title>beach</title>
    </head>
    <body bgcolor="blanchedalmond">
        <h1>varakala</h1>
        <h2>KAPPIL BEACH</h2>
        <h3>Kappil Beach is one of the most beautiful and peaceful beaches near Varkala, located about 7 km north of Varkala town in Kerala. It is famous for its unique natural beauty, where the Arabian Sea and the Edava–Nadayara Backwaters run parallel to each other. This creates a stunning landscape that you won't find in many other places in Kerala.</h3>
    </body>
</html>
```

homestay.html
```
<html>
    <head>
        <title> homestay</title>
    </head>
    <body bgcolor="cyan">
        <h1>VARKALA</h1>
        <h2>AADHI HOMESTAY</h2>
       <h3>Aadhi Villa is a homestay / apartment-style accommodation located in the Kurakkanni / Punnamoodu Road area of Varkala. The property offers a villa / apartment layout: 2 bedrooms (plus living/sitting area), private bathrooms, kitchen facilities. It provides amenities often expected by travellers: free WiFi, private parking, garden/terrace or balcony, kitchen access. </h3>
    </body>
</html>
```

cliff.html
```
<html>
    <head>
        <title>cliff</title>
    </head>
    <body bgcolor="mouse grey">
        <h1>VARKALA</h1>
        <h2>NORTH CLIFF</h2>
        <h3>Varkala Cliff is one of the most unique and beautiful coastal formations in Kerala. It rises sharply above the Arabian Sea, creating a stunning viewpoint for visitors. The cliff is made of red laterite rock, which gives it a striking look, especially during sunrise and sunset.</h3>
        
    </body>
</html>
```

resort.html
```
<html>
    <head>
        <title>resort </title>
    </head>
    <body bgcolor="violet">
        <h1>VARKALA </h1>
        <h2>CLAFOUTI RESORT</h2>
        <h3>Clafouti Beach Resort is located on the north-cliff / north-middle cliff area of Varkala Cliff, making it one of the cliff-side resorts with easy access to beaches and cliff-top views. Rooms / cottages range from heritage cottages, sea-view villas, deluxe villas, to standard AC / non-AC rooms depending on your budget and preferences.</h3>
    </body>
</html>
```

villas.html
```
<html>
    <head>
        <title>villa</title>
    </head>
    <body bgcolor="pink">
        <h1>VARKALA</h1>
        <h2>MANTRAA VILLAS</h2>
        <h3>It’s on Kurakkanni / Odayam Road, Varkala (PIN 695141). Offers rooms with AC, private bathrooms; there’s garden/terrace, parking, and reasonably good amenities. Breakfast is provided; property is described as clean, peaceful, and fairly close to beach/cliff (about a short walk or ~1 km)</h3>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-12-01 114038.png>)
![alt text](<Screenshot 2025-12-01 114022.png>)
![alt text](<Screenshot 2025-12-01 114006.png>)
![alt text](<Screenshot 2025-12-01 113949.png>)
![alt text](<Screenshot 2025-12-01 113937.png>)
![alt text](<Screenshot 2025-12-01 113920.png>)







## RESULT
The program for implementing image maps using HTML is executed successfully.
