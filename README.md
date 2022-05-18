<!-- PROJECT LOGO -->

<p align="center">
  <a href="https://github.com/mahlaNasr/nao_robot_project">
    <img src="nao_logo.png" alt="Logo" width="150" height="150">
  </a>
  <h3 align="center">FreeCodeCamp Projects</h3>
  <p align="center">
    Full Stack Development Projects
  </p>
</p>


<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-projects">About The Projects</a></li>
    <li>
      <a href="#legacy_responsive_web_design_projects">Legacy Responsive Web Design Projects</a>
      <ul>
        <li><a href="#tribute_page_project">Tribute Page</a></li>
        <li><a href="#landing_page_project">Landing Page</a></li>
        <li><a href="#survey-form-project">Survey Form</a></li>
        <li><a href="#tech_doc_page_project">Tech Doc Page</a></li>
        <li><a href="#personal_portfolio_webpage">Personal Portfolio Webpage</a></li>
      </ul>
    </li>
    <li>
      <a href="#Front_End_Dev_Libraries_Projects">Front End Dev Libraries Projects</a>
      <ul>
        <li><a href="#demo-video-for-section-b">Demo Video for Section (b)</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Projects

<!-- 
This project proposes a system where humanoid robot, NAO, uses scanned QR code ticket information to form simple conversations with the visitors at the [**the National Portrait Gallery**](https://www.nationalgallery.org.uk/whats-on/national-gallery-x) art museum. -->

There are two folders that are in this repository:
* Legacy Responsive Web Design Projects
* Front End Dev Libraries Projects



<!-- Legacy Responsive Web Design Projects -->
## Legacy Responsive Web Design Projects 

### [(1)](https://github.com/mahlaNasr/nao_robot_project/tree/master/booking_website) Tribute Page
To book a ticket for one of the gallery's events, I made a webpage where it generates a QR code with all the input parameters that you enter. This QR code then gets scanned by the robot to read the JSON file information inside the code. To run the scripts in this folder, [XAMPP](https://www.apachefriends.org/index.html) needs to be set up to run a local server. Write the IP address of your local server along with the directory of where the scripts are saved in the search bar of any search engine. In my case it was: `http://192.168.64.2/booking_website/index.php`.
Make sure that this folder (a) gets saved inside `htdocs` folder in XAMPP.

### [(2)]() Landing Page

### [(3)]() Survey Form

### [(4)]() Tech Doc Page

### [(5)]() Personal Portfolio Webpage










<!-- 
### [(b)](https://github.com/mahlaNasr/nao_robot_project/tree/master/scripts_enu) Scripts (English) folder 
This folder consists of all the codes that were written for the robot to scan QR codes and interact with the visitors.
To run the whole system, write 
    `
    python nao_project.py
    `
command in the terminal. A few libraries are needed to be installed in order to run the scripts which are listed below. 
Make sure that you are in the same directory as the python file (i.e. `nao_robot_project/scripts_enu`).

#### Demo Video for Section (b)
[Retrieving QR code Data to Form Personalised Speeches](https://youtu.be/nI8LN00qGhE)


### [(c)](https://github.com/mahlaNasr/nao_robot_project/tree/master/scripts_frf) Scripts (French) folder
These sets of scripts were added to show future possibilities that can be done with the built system. NAO retrieves  the language parameter within a pre-generated JSON file from a pre-scanned QR code that is inside the folder. It then asks the visitors to ask if NAO can speak in French or not. This program is very small and it is recorded below to show how it works. To run this program write
    `
    python nao_french_project.py
    `
command in the terminal. Make sure that you are in the same directory as the python file (i.e. `nao_robot_project/scripts_frf`).

#### Demo Video for Section (c)
[Personalised Speech Based on the 'Language' Parameter of a QR Code](https://youtu.be/HNX2OmFoa7k)

 -->



<!-- Front End Dev Libraries Projects -->
## Front End Dev Libraries Projects








<!-- 
To be able to run folders (2) and (3), follow these steps below to set up the neccessary applications. 

#### Prerequisites 

The older version of python is needed in order to run the software.
1. Get Python 2.7 from [python official website](https://www.python.org/about/)
2. Get Choregraphe installed from [ALDebaran documentations](http://doc.aldebaran.com/2-4/software/choregraphe/installing.html)
3. Get python SDK from [ALDebaran documentations](http://doc.aldebaran.com/2-4/dev/python/install_guide.html)

#### Installation 

A few libraries are also needed.

1. Install Computer Vision tools for OpenCV
    ```sh
    pip install opencv-python
    ```
2. If your python package does not have TKinter pre-installed for the Graphical User Interface (GUI), run this command to install for python 2.7 on Linux
   ```sh
   sudo apt-get install python-tk
   ```
3. Install pyzbar for reading barcodes using zbar library
   ```sh
   pip install pyzbar
   ```
Other libraries such as JSON, time, os, argparse, random and qi were imported.




### [(d)](https://github.com/mahlaNasr/nao_robot_project/tree/master/analyse_qrcode) Analysing Qr Codes folder 
This folder was added to show how the images were analysed and decoded using a few other libraries. The results were then stored onto an Excel sheet.

There was two ways:
1. [Real-time scanning](https://github.com/mahlaNasr/nao_robot_project/tree/master/analyse_qrcode/take_process_img) -> `take_process_img` folder
2. [Analysing images that are already taken](https://github.com/mahlaNasr/nao_robot_project/tree/master/analyse_qrcode/opencv_image_analyse) -> `opencv_image_analyse` folder
 
 

<!-- GETTING STARTED -->
## Getting Started for Analysing QR Codes

#### Prerequisites 
These files in this folder were run and tested using python 3.8. 
1. Get Python 3.8 from [python official website](https://www.python.org/about/)


#### Installation 
Extra libraries are needed to run this section of scripts as well as comparing the obtained results of images from Excel file.

1. Install Anaconda which comes with a lot of pre-installed libraries. Instruction found in [Anadonda Documentations](https://docs.continuum.io/anaconda/install/).

  Alternative method can be found here [through miniconda](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).
2. We also need ZBar and OpenCV tools here as well.


 -->

<!-- CONTRIBUTING -->
## Contributing 
This project was a contributed to help the National Gallery in order to make their ticket scan system automated through using a humanoid robot, NAO.



<!-- LICENSE -->
## License 

For distribution, please reference my [code](https://github.com/mahlaNasr/nao_robot_project) and cite my [report](https://drive.google.com/file/d/1tI2FzyNm9XHmyPpshxGPi-ilAd05Y5fe/view?usp=sharing) :)





<!-- CONTACT -->
## Contact 

Links to: 
* [My LinkedIn](https://www.linkedin.com/in/mahla-nasrollahi-0bb679163)
* [My GitHub](https://github.com/mahlaNasr/) 
* [My Carrd](https://mahla-nasrollahi.carrd.co/)

