+++
# Project title.
title = "Undergraduate Course Projects"

# Date this page was created.
date = 2016-04-27T00:00:00

# Project summary to display on homepage.
summary = "All the major computer science projects done for my undergraduate (B.Tech) courses."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["undergraduate","web","android","arduino" ,"networks","data-viz", "academic"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
# Associate this project with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. `slides = "example-slides"` references 
# `content/slides/example-slides.md`.
# Otherwise, set `slides = ""`.
slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/PrasannaNatara1"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""

# Focal point (optional)
# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"

+++
# Projects (Computer Science) - Under Graduate course work

## 1. Self-Service Portal for Mobile Application development (RMADP)

**Description**: A rapid mobile application development platform where users can drag and drop components into a mobile screen on the portal and build a complete android/ios application.

**Technology Stack**: HTML, CSS, JS, Vue.js for View layer, which is hosted on an Apache server. STS server for controller layer. MySQL for model layer. Node.js and bash scripts for build server layer.

**Demo Video**:

<iframe src="https://player.vimeo.com/video/267376074" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

<br>
**Presentation**: [pdf](./SSP_presentation.pdf)

**Report**: [pdf](./SSP_report.pdf)

**Team Members**: [Shourya Pratap Singh](https://www.linkedin.com/in/shouryaps/), [Sneha Agarwal](https://www.linkedin.com/in/sneha-agarwal-b75032138/), [Harshit Anand](https://www.linkedin.com/in/harshit-anand-40a077101/), Sneha Reddy

## 2. IOYou - Debt Manager

**Description**: An android application that could act as a debt manager. 

**Course**: DBMS

**Technology Stack**: Android and SQLite for front end, PHP and MySQL for backend.

**Presentation**: [ppt](./IOU.pptx)

**Repo**: [IOYou](https://github.com/PrasannaNatarajan/IOU_dbms-)

**Team Members**: [Vedant Chakravarthy](https://www.linkedin.com/in/vedant-chakravarthy/)

**My Contribution**: Built and hosted the backend system. Made the SQLite connection in android. Also wrote the sync functionality.

## 3. Symphonia - Sync your music

**Description**: A synchronous music player for everyone. Music listeners encounter the problem that the volume of any individual device they own is often too low. Although the combined volume that can be obtained on all the devices available is adequate for their needs, this is under utilized due to a lack of the ability to play the music synchronously across all the devices.

**Course**: Software Engineering

**Technology Stack**: Android 

**Presentation**: [pdf](./Symphonia.pdf)

**Repo**: [Symphonia](https://github.com/PrasannaNatarajan/Symphonia) 

**Team Members**: [Anirudh Badri](https://www.linkedin.com/in/anirudh-badri-419390a7/), [Hari Prasath](be.net/hariiprasath), [Vedant Chakravarthy](https://www.linkedin.com/in/vedant-chakravarthy/)

**My Contribution**: Made the basic music player in android. Worked on formulating a custom protocol for synchronized playing and implemented parts of it.

## 4. Internet TV/radio - a collge wide multicast

**Description**: An Internet TV/radio application that uses any source multicast (ASM). The first part of this project focuses on socket programming and the next part on making a GUI for the player. We used cvlc/ffplay for playing the received music and for GUI.  

**Course**: Computer Networks

**Technology Stack**: C

**Report**: [pdf](./Internet_Radio.pdf)

**Repo**: [InternetRadio/TV](https://github.com/PrasannaNatarajan/NetworksAssignment) 

**Team Members**: [Siddhart Mitra](//github.com/sm515), [Sridhar R Ramanujam](//github.com/sridhar1896), [Vedant Chakravarthy](https://www.linkedin.com/in/vedant-chakravarthy/)

**My Contribution**: Worked on serializing and sending a multimedia stream.

## 5. US-Pollution data analysis and visualization

**Description**: A complete cleaning and visualization of us-pollution data.

**Course**: Data mining and warehousing

**Technology Stack**: R, Shiny

**Report**: [pdf](./R_pollution.pdf)

**Repo**: [US_Pollution_data_analysis](https://github.com/PrasannaNatarajan/CSD342-Data-Mining/tree/master/R/graded%20lab) 

**Data Source**: https://aqs.epa.gov/aqsweb/documents/data_mart_welcome.html

**Demo**: [live_demo](https://prasanna-dm-vis.shinyapps.io/us-pollution/)

**Team Members**: [Atish Majumdar](//github.com/atish-maj), [Vishal Gauba](//github.com/FlameFractal)

**My Contribution**: Made functions in R to read cleaned data and visualize (choropleth, donut chart) the data. Also hosted the shiny app in shiny-apps.io.

## 6. CatNap - Sleep Analyzer

**Description**: This project lies in the domain of smart homes, as it monitors disturbances in light and sound
while one is sleeping and provides relevant information. When sound increases, the system’s volume of white noise also increases aiding in one's sleep as validated by many research communities. This works best with bluetooth earphones.

**Course**: Wireless Sensor Networks

**Technology Stack**: Arduino code (C++) for getting values from sensors and processing for GUI. Python for analyzing and plotting the received data.

**Report**: [pdf](./WSN_CatNap.pdf)

**Repo**: [CatNap](https://github.com/PrasannaNatarajan/CSD_337_WSN/tree/master/Catnap%20-%20Project) 

**Team Members**: [Atish Majumdar](//github.com/atish-maj), [Vedant Chakravarthy](https://www.linkedin.com/in/vedant-chakravarthy/)

**My Contribution**: Wrote arduino code for reading the sensor values (LDR and Sound Sensor). Wrote a python script for plotting the received data from sensors.

## 7. SNU-Dashboard

**Description**: An online portal where users can know all the happenings around Shiv Nadar University. Club activities to cab pool and lost and found all at this one place.

**Technology Stack**: HTML, CSS, jquery for front end. MongoDB as our database. Node.js for backend server.

**Repo**:[snudashboard](https://github.com/FlameFractal/SNU-Dashboard)

**Demo**: [link](https://snu-dashboardd.herokuapp.com/)

**Team Members**: [Hari Prasath](be.net/hariiprasath), [Vedant Chakravarthy](https://www.linkedin.com/in/vedant-chakravarthy/), [Vishal Gauba](//github.com/FlameFractal) 

**My Contribution**: Set up and hosted Mongo DB database instance for the forums. Customized nodebb forum to suite our theme.

## 8. Bookbuy Website

**Description**: An e-commerce website for selling and buying books.

**Technology Stack**: HTML, CSS, jquery for front end. MySQL as our database. PHP for backend server.

**Demo**: [link](https://bookbuy.hol.es/)

**Team Members**: Pranjal Mathur, Prerna, Pulkit Gupta.

**My Contribution**: Wrote backend PHP, especially connected it to MySQL database. 