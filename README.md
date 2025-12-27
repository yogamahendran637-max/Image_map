# Ex03 Places Around Me
# Date:25/11/25
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE

```
map.html

<!DOCTYPE html>
<html>
   
    <title>MY TOWN</title>
    <h1><b>MANGADU</b></h1>
        
    <h2>PRIYARITHANYA M(25007623)</h2>    
    <style>
        h1{
            text-align: center;
            color: rgb(9, 9, 207);
            
        }
        h2{
            background-color: brown;
            font-family: 'Times New Roman', Times, serif;
            text-align: center;
        }
        

    </style>    
    <body bgcolor="grey">
        <img src="Screenshot (25).png" usemap="#MY CITY" height="600" width="1400">
        <map name="MY CITY">
        <area shape="rect" coords="429,166,788,365"title="mycity" href="mycity.html" >
        <area shape="rect" coords="546,89,871,249" title="kamakshiamman temple" href="temple.html">
        <area shape="rect" coords="947,179,1230,319" title="sakthi palace" href="palace.html">
        <area shape="rect" coords="135,553,585,760" title="Madha engineering college" href="college.html">
        <area shape="rect" coords="553,409,859,579" title="Kundrathur" href="nearby.html">
        </map>

    </body>
</html>

mycity.html

<!DOCTYPE html>
<html>
    <head>
        <h1><b>MANGADU</b></h1>
    <style>
        p{
            background-color: rgb(164, 157, 232);
            text-align: justify;
            font-style: initial;
            font-family: Georgia, 'Times New Roman', Times, serif;
            color: black;
            font-size:x-large;

        }
        h1{
            text-align: center;
            color: blue;
        }
        body{
            color: rgb(159, 210, 233);
        }
    </style>
    </head>
    <body>
        <p>Mangadu's charm lies in its seamless blend of spirituality, nature, and urban growth. The locality is anchored by the Mangadu Kamakshi Amman Temple, where devotees believe Goddess Kamakshi performed penance before marrying Lord Shiva. This temple, along with nearby shrines like Velleswarar and Vaikunta Perumal, makes Mangadu a spiritual hub, especially during festivals when the area comes alive with rituals and celebrations.
Beyond its religious significance, Mangadu is witnessing a surge in residential and commercial development. The expansion of roads, improved public transport, and upcoming metro stations are transforming it into a well-connected suburb. Real estate projects are flourishing, offering affordable housing options for middle-class families and retirees seeking peace without sacrificing convenience.
Educational institutions and healthcare facilities are also growing steadily. Schools like Velammal Vidyalaya and RISHS International cater to diverse academic needs, while hospitals such as Muthukumaran Medical College Hospital and Saveetha Dental College ensure access to quality medical care. With clean groundwater, abundant greenery, and a relatively low cost of living, Mangadu is becoming a preferred destination for those looking to settle in Chennai's outskirts.
Mangadu is a tranquil and spiritually rich suburb located in the western part of Chennai, Tamil Nadu. The name "Mangadu" translates to "Mango Forest," reflecting its lush, green heritage. It is best known for the revered Mangadu Kamakshi Amman Temple, a significant pilgrimage site dedicated to Goddess Kamakshi, which draws devotees from across the region. Over the years, Mangadu has evolved from a quiet village into a rapidly developing residential area, thanks to its proximity to key hubs like Porur, Kundrathur, and the Chennai-Bangalore Highway. The locality offers a blend of tradition and modernity, with well-established schools, hospitals, and growing infrastructure, including upcoming metro connectivity. Despite urbanization, Mangadu retains its peaceful charm, making it a desirable place for families seeking both spiritual solace and urban convenience.</p>

    </body>
   
</html>

temple.html

<!DOCTYPE html>
<html>
    <head>
    <h1><b>Kamakshiamman Temple</b></h1>
    <style>
        h1{
            color: coral;
            text-align: center;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-style: oblique;
        }
        p{
            text-align: justify;
            color: darkmagenta;
            font-size:x-large;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        body{
            background-color: bisque;
        }
    </style>
    </head>
    <body>
        <p>The Kamakshi Amman Temple in Mangadu, located near Chennai in Tamil Nadu, is a revered shrine dedicated to Goddess Kamakshi, a powerful manifestation of Parvati. This temple holds deep spiritual significance as it marks the site where the goddess is believed to have performed intense penance to reunite with Lord Shiva. According to legend, after playfully closing Shiva's eyes and plunging the universe into darkness, Parvati was instructed to undertake austerities to atone for her actions. She chose Mangadu—then a forest of mango trees—as the place for her penance, meditating amidst five sacred fires in a unique posture with one leg folded and the other resting on the flames, holding a rosary in her hand. The temple enshrines this form of Kamakshi, known as Tapas Kamakshi, and is one of the few temples where she is depicted in such a meditative state. To calm the intense energy of her penance, Adi Shankaracharya is said to have installed a Sri Ardhameru Chakra here, which remains a central focus of worship. The temple's architecture reflects classic Dravidian style, with a towering gopuram and shrines dedicated to Shiva, Vishnu, and Ganesha. Devotees often bring lemons as offerings, believing they carry divine blessings when returned as prasadam. The temple is especially vibrant during festivals like Navaratri and attracts thousands of pilgrims seeking spiritual solace and divine grace.
            The Kamakshi Amman Temple in Mangadu is not only a spiritual sanctuary but also a symbol of divine feminine energy and devotion. The temple's ambiance is serene, with the scent of incense and the rhythmic chants of mantras creating a deeply meditative atmosphere. Pilgrims from across Tamil Nadu and beyond visit Mangadu to seek blessings for marriage, fertility, and personal well-being, believing that the goddess's penance here grants powerful boons. The temple's rituals are steeped in tradition, with daily abhishekams (ritual bathing of the deity), alankarams (decorations), and deepa aradhanas (lamp offerings) performed with great reverence. Fridays are especially auspicious, drawing large crowds who come to offer prayers and participate in special poojas. The temple also plays a vital role in the local community, hosting cultural events, spiritual discourses, and charitable activities. Its proximity to Chennai makes it a popular destination for both casual visitors and devout worshippers, blending urban accessibility with ancient sanctity. Over the years, the temple has undergone renovations to preserve its heritage while accommodating the growing number of devotees. Despite its modest size compared to larger temple complexes, Mangadu's Kamakshi Amman Temple radiates a unique spiritual intensity that continues to inspire faith and devotion in all who visit.

        </p>
    </body>

</html>

palace.html

<!DOCTYPE html>
<html>
    <head>
        <h1><b>SAKTHI PALACE</b></h1>
        <style>
            h1{
                color: deeppink;
                text-align: center;
                font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
                font-style: unset;
            }
            body{
                background-color: indianred;
            }
            p{
                text-align: justify;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: deepskyblue;
                font-size:x-large
            }
        </style>
    </head>
    <body>
        <p>
            Sakthi Palace in Mangadu, Chennai, is a popular and well-regarded marriage and banquet hall known for hosting weddings, receptions, and other celebratory events. Located near the Bharat Petrol Bunk on Mangadu Road in Paraniputhur, it offers a blend of modern amenities and traditional ambiance, making it a preferred venue for families across Chennai.

Established in 2019, Sakthi Palace features AC banquet halls, spacious dining areas, and ample car parking facilities. The interiors are tastefully designed with elegant décor and lighting, creating a festive atmosphere for special occasions. The venue is especially appreciated for its **well-maintained infrastructure**,cleanliness, and professional service staff who help ensure smooth event execution.

Sakthi Palace also offers customizable packages to suit different budgets and event sizes, from intimate gatherings to large-scale weddings. It's equipped with backup power systems, although some reviews mention occasional power interruptions during peak moments, so it's advisable to confirm arrangements in advance. While the location is slightly away from central Chennai, it remains accessible for guests traveling by private transport.

Overall, Sakthi Palace in Mangadu stands out as a reliable and elegant choice for hosting memorable events, combining comfort, style, and value.
In addition to weddings, Sakthi Palace is also used for cultural programs, religious ceremonies, and milestone celebrations like birthdays and anniversaries. The management is known for being cooperative and responsive, helping clients plan their events with attention to detail. Some packages include stage decoration, seating arrangements, and dining setup, which reduces the hassle for hosts. While the venue doesn't offer in-house catering, it allows clients to bring their preferred vendors, giving flexibility in menu choices and pricing. Overall, Sakthi Palace stands out as a reliable and well-equipped venue that balances affordability with quality, making it a popular choice in the Mangadu area.
        </p>
    </body>
</html>

college.html

<!DOCTYPE html>
<html>
    <head>
        <h1>MADHA ENGINEERING COLLEGE</h1>
        <style>
            h1{
                text-align: center;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: mediumvioletred;
            }
            body{
                background-color: orchid;
            }
            p{
                text-align: justify;
                color: rebeccapurple;
                font-family: Verdana, Geneva, Tahoma, sans-serif;
                font-style: initial;
                font-size:larger;
            }
        </style>
    </head>
    <body>
        <p>
            Madha Engineering College, located in Kundrathur near Chennai, Tamil Nadu, is a prominent institution offering undergraduate and postgraduate programs in engineering and technology. Established in 1998 under the Madha Group of Academic Institutions, it is affiliated with Anna University and approved by AICTE (All India Council for Technical Education). The college is known for its commitment to academic excellence, industry-oriented training, and holistic development of students. With a sprawling campus equipped with modern laboratories, well-stocked libraries, and advanced computing facilities, Madha Engineering College provides a conducive environment for learning and innovation. The institution emphasizes practical exposure through internships, industrial visits, and workshops, helping students bridge the gap between theory and real-world application. It also hosts various technical and cultural events, encouraging students to showcase their talents and engage in collaborative learning. The college's placement cell actively works to connect students with leading companies, ensuring career opportunities across diverse engineering domains. Madha Engineering College continues to be a preferred choice for aspiring engineers in Tamil Nadu, blending tradition, technology, and transformation in its educational approach.

            Madha Engineering College places a strong emphasis on nurturing innovation and entrepreneurship among its students. Through its dedicated research centers and incubation programs, the college encourages students to explore cutting-edge technologies and develop solutions to real-world problems. Faculty members are not only academically qualified but also bring industry experience, which enriches classroom learning with practical insights. The college regularly organizes seminars, guest lectures, and technical symposiums, inviting experts from various engineering disciplines to share their knowledge and inspire students.

Beyond academics, Madha Engineering College fosters a vibrant campus life. Students actively participate in clubs and societies focused on robotics, coding, environmental sustainability, and cultural arts. Annual events like Madha Fest showcase student talent across music, dance, drama, and sports, creating a well-rounded educational experience. The college also emphasizes values like discipline, integrity, and social responsibility, often engaging students in community outreach and service initiatives. With a growing alumni network contributing to industries across India and abroad, Madha Engineering College continues to build a legacy of excellence, preparing students not just for jobs, but for leadership and lifelong learning.


        </p>
    </body>
</html>

nearby.html

<!DOCTYPE html>
<html>
    <head>
        <h1><b>KUNDRATHUR</b></h1>
        <style>
            h1{
                color: orangered;
                font-style: unset;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                text-align: center;
            }
            body{
                background-color: cadetblue;
            }
            p{
                text-align: justify;
                text-decoration: darkcyan;
                font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                font-style: italic;
                font-size: x-large;
            }

        </style>
    </head>
    <body>
        <p>
            Kundrathur is a historically rich and culturally vibrant suburb located in the southwestern part of Chennai, Tamil Nadu. Known for its serene atmosphere and spiritual significance, Kundrathur is home to the famous **Kundrathur Murugan Temple**, one of the few temples where Lord Murugan is seen in a standing posture facing north. This temple, believed to have been built by the Chola king Kulothunga Chola II in the 12th century, sits atop a small hill and offers panoramic views of the surrounding landscape. The area's religious heritage draws devotees from across the region, especially during festivals like Thaipusam and Panguni Uthiram.

Beyond its spiritual appeal, Kundrathur has evolved into a bustling residential and commercial hub. With its proximity to key areas like Porur, Mangadu, and Poonamallee, it has seen rapid urban development in recent years. The locality offers a mix of traditional homes and modern apartments, catering to a diverse population. Educational institutions, healthcare centers, and shopping complexes have sprung up, enhancing the quality of life for residents. Despite modernization, Kundrathur retains its old-world charm through its temples, local markets, and cultural events that reflect Tamil traditions. The blend of heritage and progress makes Kundrathur a unique and desirable place to live and visit.
Kundrathur's charm lies in its seamless blend of heritage and modernity. While the area is steeped in religious and historical significance, it has also embraced urban development, making it a sought-after residential locale for families and professionals alike. The presence of reputed educational institutions such as Madha Engineering College and several CBSE and matriculation schools has made Kundrathur a hub for academic growth. Healthcare facilities, including clinics and multi-specialty hospitals, ensure residents have access to quality medical care. The local economy thrives on a mix of traditional businesses, retail outlets, and service providers, contributing to a self-sustaining community.

Transport connectivity is another highlight of Kundrathur. Well-linked by road to major parts of Chennai, including Porur, Guindy, and Tambaram, it benefits from frequent bus services and proximity to the Chennai Outer Ring Road, which enhances accessibility. Real estate in Kundrathur has seen a steady rise, with new housing projects and gated communities offering modern amenities while preserving the area's peaceful vibe. Despite its growth, Kundrathur retains a close-knit community feel, where festivals are celebrated with enthusiasm and local traditions are upheld with pride. Whether you're visiting for its temples or considering it as a place to settle down, Kundrathur offers a unique blend of spiritual depth and contemporary living.

        </p>
    </body>
</html>
```

# OUTPUT
# RESULT

<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/79f29074-c756-4f34-b79a-971852537213" />
<img width="1920" height="1080" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/002be80b-f698-41af-8e3c-668d2151cfc2" />
<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/3a3b41fd-7f4f-41fe-bc5c-08db88ce6558" />
<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/093c3730-4a91-409a-b00a-18b56e0d1a15" />
<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/9c97644d-9327-41d6-8259-aa33590d4ba1" />







The program for implementing image maps using HTML is executed successfully.
