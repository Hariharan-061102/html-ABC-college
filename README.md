# html-ABC-college

One Home page that leads to other pages. The Home page should contain the name of the City as heading along with a logo. There should be a tab with the following links:
 Home;
 Heritage;
 Hotel Booking;
 Gallery.
There should be an appropriate description of the college on the home page.

## Index.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="./images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <hr>
        <nav align="center">
            <a href="college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <h2 align="center">Description</h2>
        <p align="center" style="margin-top: 2%;margin-bottom: 2%;margin-left: 5%;margin-right: 5%;">Saveetha Engineering College (SEC), established in 2001 and located in Chennai, Tamil Nadu, is a part of the Saveetha Institute of Medical and Technical Sciences (SIMATS). Affiliated with Anna University and approved by the AICTE, SEC offers a range of undergraduate and postgraduate programs in various engineering disciplines, including Computer Science, Electronics and Communication, Electrical and Electronics, Mechanical, and Civil Engineering. Known for its high academic standards and modern infrastructure, SEC features state-of-the-art laboratories, modern classrooms, a comprehensive library, and extensive facilities for sports and extracurricular activities. The college boasts impressive placement records, with a 97% placement rate in 2023, and companies offering packages as high as Rs. 34 lakhs per annum. Additionally, SEC emphasizes research and innovation, encouraging students and faculty to engage in cutting-edge projects. The institution is also involved in significant community service activities, reflecting its commitment to societal welfare. SEC has received notable rankings, including being placed 16th among private engineering colleges in Tamil Nadu by the NIRF in 2021.</p>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## academics.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="./images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <hr>
        <nav align="center">
            <a href="college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <font size="3" >List of Departmennts and Courses offered by Saveetha Engineering College,</font>
        <main>
        <ol type="1">
            <li> ARTS
                <UL type="circle">
                    <li><a href="./Courses/english.html">English</a></li>
                    <li><a href="./Courses/sociology.html">Sociology</a></li>
                </UL>
            </li>
            <li> SCIENCE
                <UL type="circle">
                    <li><a href="./Courses/computer-science.html">Computer Science</a></li>
                    <li><a href="./Courses/mathematics.html">Mathematics</a></li>
                </UL>
            </li>
            <li> COMMERCE
                <UL type="circle">
                    <li><a href="./Courses/economics.html">Economics</a></li>
                    <li><a href="./Courses/business-management.html">Bussiness Management</a></li>
                </UL>
            </li>
        </ol>
        </main>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## admission.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="./images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            label{
                padding: 10px;
                text-align: left;
            }
            input{
                padding: 10px;
                text-align: center;
                width: 300px;
            }
            select{
                padding: 10px;
                width: 40%;
                text-align: center;
                margin-left: 6px;

            }
            button{
                padding:10px;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <form>
            <label>Enter Name:</label>
            <input type="text" placeholder="Fname" style="margin-left: 100px;"> <input type="text" placeholder="Lname"><br><br>
            <label>Choose Your Departmennt: </label>
            <select>
                <option>Computer Science</option>
                <option>Business Management</option>
                <option>Economics</option>
                <option>English</option>
                <option>Mathematics</option>
                <option>Sociology</option>
                </select>
            <br><br>
            <label>Date-of-Birth:</label>                        <input type="date" style="margin-left: 88px;"><br><br>
            <label>Email:</label>                                <input type="email" placeholder="sample@gmail.com" style="margin-left: 136px;"><br><br>
            <label>Father's Name:</label> <input type="text" style="margin-left: 81px;"> <br><br>
            <label>Mother's Name:</label> <input type="text" style="margin-left: 74px;"><br><br>
            <label align="top">Address:</label>

            <textarea rows="7" cols="80" style="margin-left: 120px;">Enter your Address here</textarea> <br><br>
            <label>Upload 12th Marksheet:</label> <input type="file" style="margin-left: 12px;"><br><br>
            <button style="margin-left: 100px;">Submit</button> <button style="margin-left: 20px;">Cancel</button>
            </form>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## gallary.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="./images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <hr>
        <nav align="center">
            <a href="college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <img src="./images/Gallary1.jpeg" height="500px" width="738px">
        <img src="./images/Gallary2.png" height="500px" width="900px">
        <img src="./images/gallary3.jpeg">
        <img src="./images/gallary4.png" height="314px">
        <img src="./images/gallary5.jpg" height="314px">
        <img src="./images/gallary6.png" height="314px">
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## computer-science.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="../images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            th,td{
                text-align: center;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="../college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="../academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="../admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="../gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <p>Computer Science at Saveetha Engineering College equips students with a robust understanding of computational theory and practical application. The curriculum covers essential areas such as programming, data structures, algorithms, and software engineering. Advanced courses delve into artificial intelligence, machine learning, cybersecurity, and network systems, ensuring students are well-versed in contemporary technological advancements. Hands-on projects and lab sessions enable students to apply theoretical knowledge to real-world problems, fostering innovation and problem-solving skills. Collaboration on group projects and participation in hackathons and coding competitions further enhance their technical expertise. Graduates are prepared for various roles in the tech industry, including software development, data analysis, system administration, and research.</p>
        <font size="3" ><b>Available Faculties for Computer Science,</b></font>
        <ul>
            <li>Maddala Joel Manoj Tej</li>
            <li>Gowthami M</li>
        </ul>
        <font size="3" ><b>Time table for Computer Science,</b></font>
        <table border="double">
        <tr>
            <th colspan="5" align="center"> TIME TABLE </th>
        </tr>
        <tr>
            <th>DAY</th>
            <th>Period 1(8 to 10 AM)</th>
            <th>Period 2(10 AM to 12 PM)</th>
            <th>Period 3(1 to 3 PM)</th>
            <th>Period 4(3 to 5 PM)</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>Class 1</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>Xlass 2</td>
            <td>-</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>Ckass 3</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        <tr>
            <td>SUNDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        </table>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## business-management.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="../images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            th,td{
                text-align: center;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="../college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="../academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="../admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="../gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <p>The Business Management program at Saveetha Engineering College prepares students for leadership roles in various organizational settings. The curriculum includes courses in marketing, finance, human resources, operations, and strategic management, providing a well-rounded understanding of business operations. Students learn to develop business plans, manage projects, and make data-driven decisions. Emphasis is placed on developing critical thinking, leadership, and communication skills. Case studies, internships, and industry projects offer practical experience, enabling students to apply theoretical knowledge in real-world contexts. The program also addresses global business trends and ethical considerations, preparing graduates to navigate the complexities of modern business environments. Career opportunities for graduates include roles in management, consulting, entrepreneurship, and corporate leadership.</p>
        <font size="3" ><b>Available Faculties for Bussiness Management,</b></font>
        <ul>
            <li>Megala J</li>
            <li>Evangelin Helen</li>
        </ul>
        <font size="3" ><b>Time table for Bussiness Management,</b></font>
        <table border="double">
        <tr>
            <th colspan="5" align="center"> TIME TABLE </th>
        </tr>
        <tr>
            <th>DAY</th>
            <th>Period 1(8 to 10 AM)</th>
            <th>Period 2(10 AM to 12 PM)</th>
            <th>Period 3(1 to 3 PM)</th>
            <th>Period 4(3 to 5 PM)</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>-</td>
            <td>Class 1</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>Class 2</td>
            <td>-</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>Class 3</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        <tr>
            <td>SUNDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        </table>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## english.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="../images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            th,td{
                text-align: center;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="../college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="../academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="../admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="../gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <p>The study of English at Saveetha Engineering College focuses on developing advanced communication skills and a deep appreciation for literature. Students engage in reading and analyzing various literary forms, including novels, plays, and poetry, which helps them understand different cultural and historical contexts. The curriculum also emphasizes critical thinking and interpretive skills, enabling students to articulate their ideas effectively. Writing assignments range from creative compositions to analytical essays, enhancing their ability to express complex thoughts clearly and coherently. Additionally, courses in linguistics and technical writing prepare students for diverse career paths that require strong language proficiency. Overall, the English program fosters a comprehensive understanding of the language, promoting both academic and professional growth.</p>
        <font size="3" ><b>Available Faculties for English,</b></font>
        <ul>
            <li>Rajesh Emmanuel</li>
            <li>Pandiyan R</li>
        </ul>
        <font size="3" ><b>Time table for English,</b></font>
        <table border="double">
        <tr>
            <th colspan="5" align="center"> TIME TABLE </th>
        </tr>
        <tr>
            <th>DAY</th>
            <th>Period 1(8 to 10 AM)</th>
            <th>Period 2(10 AM to 12 PM)</th>
            <th>Period 3(1 to 3 PM)</th>
            <th>Period 4(3 to 5 PM)</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>Class 1</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>Class 2</td>
            <td>-</td>
            <td>-</td>
            <td>Class 3</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        <tr>
            <td>SUNDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        </table>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## mathematics.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="../images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            th,td{
                text-align: center;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="../college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="../academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="../admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="../gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <p>The Mathematics program at Saveetha Engineering College focuses on developing analytical and problem-solving skills through a comprehensive study of mathematical principles. Students engage with subjects such as calculus, linear algebra, differential equations, and statistics, which form the foundation for advanced mathematical concepts. The curriculum also includes discrete mathematics, numerical methods, and mathematical modeling, providing students with the tools to tackle complex problems in engineering and science. Emphasis is placed on logical reasoning and precision, preparing students for rigorous analytical work. Practical applications of mathematics in real-world scenarios are explored, helping students understand the relevance of mathematical theory in various fields. Graduates are well-equipped for careers in academia, research, finance, engineering, and technology.</p>
        <font size="3" ><b>Available Faculties for Mathematics,</b></font>
        <ul>
            <li>Manoj Kumar S</li>
            <li>Ezhilarasan I</li>
        </ul>
        <font size="3" ><b>Time table for Mathematics,</b></font>
        <table border="double">
        <tr>
            <th colspan="5" align="center"> TIME TABLE </th>
        </tr>
        <tr>
            <th>DAY</th>
            <th>Period 1(8 to 10 AM)</th>
            <th>Period 2(10 AM to 12 PM)</th>
            <th>Period 3(1 to 3 PM)</th>
            <th>Period 4(3 to 5 PM)</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>-</td>
            <td>Class 1</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>Class 2</td>
            <td>-</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>Class 2</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>Class 3</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        <tr>
            <td>SUNDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        </table>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## economics.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="../images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            th,td{
                text-align: center;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="../college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="../academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="../admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="../gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
        <p>Economics at Saveetha Engineering College provides a thorough understanding of economic principles and their application in the real world. The curriculum covers microeconomics, which focuses on individual and firm behavior, and macroeconomics, which examines national and global economic systems. Students learn about market dynamics, resource allocation, and economic policy-making. Courses in econometrics and statistical analysis equip students with the skills to analyze economic data and make informed decisions. The program also explores development economics, international trade, and public finance, broadening students' perspectives on economic issues. Through case studies and projects, students apply theoretical knowledge to practical situations, preparing them for careers in finance, government, consulting, and academia.</p>
        <font size="3" ><b>Available Faculties for Economics,</b></font>
        <ul>
            <li>Saranya V</li>
            <li>David Raj V</li>
        </ul>
        <font size="3" ><b>Time table for Economics,</b></font>
        <table border="double">
        <tr>
            <th colspan="5" align="center"> TIME TABLE </th>
        </tr>
        <tr>
            <th>DAY</th>
            <th>Period 1(8 to 10 AM)</th>
            <th>Period 2(10 AM to 12 PM)</th>
            <th>Period 3(1 to 3 PM)</th>
            <th>Period 4(3 to 5 PM)</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>Class 1</td>
            <td>-</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>Class 2</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>Class 3</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        <tr>
            <td>SUNDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        </table>
    </body>
    <hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```
## sociology.html
```
<!Doctype html>
<html>
    <head >
        <title>College Name</title>
        <header align="center">
            <img src="../images/logo.png" width="10%" height="10%"  alt="logo" style="vertical-align: middle;"> 
            <font size="7"  style="display:inline; vertical-align:middle">Saveetha Engineering College</font>
        </header>
        <style>
            th,td{
                text-align: center;
            }
        </style>
        <hr>
        <nav align="center">
            <a href="../college.html" style="margin-left: 6%; margin-right: 1%;">INDEX</a>
            <a href="../academics.html" style="margin-left: 1%; margin-right: 1%;">ACADEMICS</a>
            <a href="../admission.html" style="margin-left: 1%; margin-right: 1%;">ADMISSION</a>
            <a href="../gallary.html" style="margin-left: 1%; margin-right: 1%;">GALLARY</a>
        </nav>
        <hr>
    </head>
    <body>
    <p>Sociology at Saveetha Engineering College explores the intricate dynamics of societies and human interactions. Students study key sociological theories and concepts, examining how social structures, institutions, and relationships influence individual and group behavior. Topics such as social stratification, race and ethnicity, gender, and globalization are thoroughly investigated, providing insights into the complexities of modern societies. The program encourages students to engage in qualitative and quantitative research, developing skills in data collection and analysis. Through case studies and fieldwork, students gain practical experience in understanding and addressing social issues. This discipline prepares graduates for careers in social services, community development, policy analysis, and more, emphasizing a holistic approach to understanding social phenomena.</p>
    <font size="3" ><b>Available Faculties for Sociology,</b></font>
    <ul>
        <li>Dhevishathya M S R</li>
        <li>Naresh G</li>   
    </ul>
    <font size="3" ><b>Time table for Sociology,</b></font>
        <table border="double">
        <tr>
            <th colspan="5" align="center"> TIME TABLE </th>
        </tr>
        <tr>
            <th>DAY</th>
            <th>Period 1(8 to 10 AM)</th>
            <th>Period 2(10 AM to 12 PM)</th>
            <th>Period 3(1 to 3 PM)</th>
            <th>Period 4(3 to 5 PM)</th>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>Class 1</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>Class 2</td>
            <td>-</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>-</td>
            <td>-</td>
            <td>Class 3</td>
            <td>-</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
            <td>-</td>
        </tr>
        <tr>
            <td>SATURDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        <tr>
            <td>SUNDAY</td>
            <td colspan="4"> LEAVE</td>
        </tr>
        </table>
    </body>
<hr>
    <p align="center">&copy; Saveetha Engineering College</p>
</html>
```


## OUTPUT:
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/b67f5d47-f199-40f7-9acf-deac5c8adb0d)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/93fa50bb-9a39-4fee-843f-bfd4a10c6de0)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/a85d11d9-cac3-4765-8a19-24ad74a87ee5)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/322b8d28-fd11-4dee-a6a2-d895be0333bc)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/1cab3f9d-df1e-42e9-a142-2a401c35896d)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/e0e58137-f222-43f6-bac9-07578027458a)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/aefdd3dc-e8a8-4262-8274-7130375a8d0a)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/77496952-d99d-43d0-a917-8aa3c605bd91)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/df16ef43-6a78-44d9-a12d-66f9f652f15e)
![image](https://github.com/Hariharan-061102/html-ABC-college/assets/93427270/3d3dcc9d-6934-4969-8e41-226e20612923)
