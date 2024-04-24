# Ex04 Places Around Me
## Date: 26/03/2024

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
### map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ImageApp</title>
</head>
<body bgcolor="cyan">
    <h1>Arani - The Silk City</h1>
    <h2>212223230133</h2>
    <img src="Screenshot 2024-03-21 142017.png" usemap="#image-map">
    
    <map name="image-map">
        <area target="" alt="Kottai Ground" title="Kottai Ground" href="kottai.html" coords="754,250,905,292" shape="rect">
        <area target="" alt="Paary Sweet" title="Paary Sweet" href="paary.html" coords="930,368,757,371,759,416,932,421" shape="poly">
        <area target="" alt="Rajeshwari Th." title="Rajeshwari Th." href="raja.html" coords="1135,528,66" shape="circle">
        <area target="" alt="GK Hospital" title="GK Hospital" href="hosp.html" coords="822,16,817,46,925,44,924,11" shape="poly">
        <area target="" alt="Eco Air" title="Eco Air" href="eco.html" coords="675,649,601,607" shape="rect">
    </map>
    
</body>
</html>
```
### eco.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eco Air</title>
</head>
<body bgcolor="grey">
    <center>
        <h1>Arani - The Silk City</h1>
        <hr>
        <h2>ECO AIR</h2>
        <h3>1) Eco Air refers to an environmentally friendly approach to air quality management and air conditioning systems. As concerns about climate change and environmental sustainability grow, the demand for eco-friendly solutions in various sectors, including air conditioning, has increased.
        </h3>
        <h3>2) Eco Air systems typically utilize energy-efficient technologies that reduce electricity consumption and minimize greenhouse gas emissions. These systems may incorporate features such as advanced filtration to improve indoor air quality, use of natural refrigerants with lower global warming potential, and smart controls for optimized operation.
        </h3>
        </center>    
</body>
</html>
```
### hosp.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GK Hospital</title>
</head>
<body bgcolor="sandel">
    <center>
        <h1>Arani - The Silk City</h1>
        <hr>
        <h2>GK HOSPITAL</h2>
        <h3>1) A hospital is a specialized medical facility designed to provide diagnosis, treatment, and care for patients with various illnesses, injuries, and medical conditions. It serves as a crucial component of the healthcare system, offering a range of medical services to individuals of all ages and backgrounds.
        </h3>
        <h3>2) Medical Staff: Hospitals are staffed by a diverse team of healthcare professionals, including doctors, nurses, surgeons, specialists, therapists, and support staff. These professionals work collaboratively to deliver comprehensive medical care to patients.
        </h3>
        <h3>
            3) Medical Services: Hospitals offer a wide array of medical services, including emergency care, surgery, intensive care, diagnostic imaging, laboratory testing, maternity care, pediatrics, rehabilitation, and specialized treatments for specific diseases and conditions.</h3>
        </center>
</body>
</html>
```
### raja.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajeshwari The.</title>
</head>
<body bgcolor="violet">
    <center>
        <h1>Arani - The Silk City</h1>
        <hr>
        <h2>RAJESHWARI TH.</h2>
        <h3>1) Theatre is a dynamic art form that encompasses live performances, storytelling, and creative expression, often presented on stage for an audience. It is a multifaceted medium that combines elements of literature, music, visual arts, and performance to convey narratives, emotions, and ideas.
        </h3>
        <h3>2)Theatre involves live performances by actors who portray characters and convey stories through dialogue, movement, and expression. Performances can range from scripted plays and musicals to improvisational theater and experimental performances.
        </h3>
    </center>
</body>
</html>
```
### paary.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parry Sweets nd Backery</title>
</head>
<body bgcolor="">
    <center>
        <h1>Arani - The Silk City</h1>
        <hr>
        <h2>PAARY SWEETS</h2>
        <h3>1) A sweets and bakery shop is a delightful establishment that specializes in the creation and sale of a wide variety of sweet treats, baked goods, and confections. These shops offer a tempting array of pastries, cakes, cookies, bread, chocolates, and other delectable items that satisfy customers' cravings for delicious desserts.
        </h3>
        <h3>2) Sweets and bakery shops pride themselves on offering freshly baked goods made with high-quality ingredients. From flaky croissants to decadent cakes, customers can enjoy a wide range of treats that are prepared with care and attention to detail.
        </h3>
        <h3>3) Sweets and bakery shops typically offer a diverse selection of sweet treats to cater to different tastes and preferences. This may include traditional pastries and desserts from various culinary traditions, as well as innovative creations and seasonal specialties.</h3>
    </center>
</body>
</html>
```
### kottai.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kottai Ground</title>
</head>
<body>
    <center>
    <h1>Arani - The Silk City</h1>
    <hr>
    <h2>KOTTAI GROUND</h2>
    <h3>1) In many cultures, especially indigenous ones, the concept of "ground" extends far beyond mere physical terrain. It embodies a deep spiritual connection to one's ancestral lands, the earth, and all living beings therein. This connection is often rooted in traditions, myths, and rituals passed down through generations.
        For indigenous peoples, the ground represents not only a physical space but also a source of identity, sustenance, and spirituality.
    </h3>
    <h3>2) It holds the memories of their ancestors, the wisdom of their traditions, and the essence of their cultural heritage. The ground is a living entity, deserving of respect, reciprocity, and protection.The relationship with the ground is reciprocal, as indigenous communities understand the importance of living in harmony with nature. They practice sustainable land stewardship, honoring the interconnectedness of all life forms. The ground provides nourishment, shelter, and healing, while humans are entrusted with the responsibility to preserve its integrity for future generations.
        However, indigenous peoples often face challenges to their connection with the ground, including land dispossession, environmental degradation, and cultural erosion. 
    </h3>
    <h3>3) Despite these obstacles, many continue to fight for their rights to their ancestral lands, advocating for environmental conservation and cultural revitalization.
        In essence, the ground in one's native place represents much more than physical geography; it embodies the heart and soul of indigenous cultures, serving as a testament to the enduring bond between people, land, and spirit.
    </h3>
    </center>
</body>
</html> 
```
## OUTPUT
![Screenshot 2024-03-22 101329](https://github.com/Narasimhan05/NearMe/assets/132819871/9c5ba0f4-733e-4943-9230-08775698187d)

![Screenshot 2024-03-22 101436](https://github.com/Narasimhan05/NearMe/assets/132819871/b9cb953d-8faa-4e56-aed5-21af87b1df0c)

![raja png](https://github.com/Narasimhan05/NearMe/assets/132819871/245008c6-9ab5-48ea-85a0-54ced70675f3)

![Screenshot 2024-03-22 101600](https://github.com/Narasimhan05/NearMe/assets/132819871/e73e1ee8-728a-49fa-8ef4-4eb567b3e3db)

![Screenshot 2024-03-22 101614](https://github.com/Narasimhan05/NearMe/assets/132819871/99820bb4-a12c-48b7-9d18-bad768c9e7ec)

![Screenshot 2024-03-22 101419](https://github.com/Narasimhan05/NearMe/assets/132819871/73515cd4-74cd-4754-b123-46ad71debd36)


## RESULT
The program for implementing image maps using HTML is executed successfully.
