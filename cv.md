# Kristaps Tunnis

## About me
   I'm a student. I'm 21 years old. I love programming. I started this relatively recently. For a very long time I couldn't find a programming language that 
   I would fall in love. And surprisingly became JS. And now, with fire in my eyes, I am ready to plunge into the world of programming with my head.

***

## Contacts:
* +375255451321 (My phone)
* @Kriforce (GitHub account and nickname in Discord)
* kriforce7@gmail.com (google email)
* @ktunnis (telegram)

***

## Skiils:
* HTML/CSS
* Bootstrap
* JS
* Git
* React +Redux (I'm new to this, just starting learning)
* Figma and Tilda 
* Linux (VM with Debian)
* C/C#
* PHP (a little)

***

## Education:
 1.  Secondary School №19 in Gomel (2010-2017)
 2.  Gomel city lyceum №1 (2017-2019)
 3.  Francisk Skorina Gomel State University
>> * Faculty of Physics and IT
>>> * Computer physics

***

## Languages:
1.  Russian (native)
2.  English (B1)
3.  Belorussian (native)
4.  Latvian (A2)

***

## Example of code:
<script type="text/javascript">
        function toggleText() {
            let listImg = ['<img src="img/765LT.jpg" alt="#" />',
                            '<img src="img/bmw.jpg" alt="#" />',
                            '<img src="img/ferrari.jpg" alt="#" />',
                            '<img src="img/huracan.jpg" alt="#" />',
                            '<img src="img/mercedes.jpg" alt="#" />',
                            '<img src="img/nisan.jpg" alt="#" />',
                            '<img src="img/taycan.jpg" alt="#" />',
                            '<img src="img/tesla.jpg" alt="#" />',
                            '<img src="img/viper.jpg" alt="#" />',
                            '<img src="img/ford.jpg" alt="#" />'];

            let img_arr = [];
    
            while(img_arr.length < 3){
                var r = Math.floor(Math.random() * listImg.length);
                if(img_arr.indexOf(r) === -1) img_arr.push(r);
            }

            document.getElementById('img1').innerHTML = listImg[img_arr[0]];
            document.getElementById('img2').innerHTML = listImg[img_arr[1]];
            document.getElementById('img3').innerHTML = listImg[img_arr[2]];
        }

        window.onload = randomImg;
    </script> 
