---
layout: default
title: Dian Ji (吉点)
---

# Welcome
<h1 class="home-title">Welcome</h1>


<div class="carousel" style="float: right;">
  <div class="carousel-images" id="carouselImages">
    <div class="carousel-item">
      <div class="image-title">Large skipjack shad caught in the Tennessee River</div>
      <img src="https://dian01811.github.io/files/photo2.JPG" alt="Image 1">
    </div>
    <div class="carousel-item">
      <div class="image-title">Talk presentation at Lunar and Planetary Science Conference</div>
      <img src="https://dian01811.github.io/files/LPSC.jpg" alt="Image 2">
    </div>
    <div class="carousel-item">
      <div class="image-title">Field trip in North Carolina</div>
      <img src="https://dian01811.github.io/files/field trip.jpg" alt="Image 3">
    </div>
  </div>
  <div class="carousel-buttons">
    <button class="carousel-button" id="prevButton">◀</button>
    <button class="carousel-button" id="nextButton">▶</button>
  </div>
</div>

<script>
  const carouselImages = document.getElementById('carouselImages');
  const items = document.querySelectorAll('.carousel-item');
  const prevButton = document.getElementById('prevButton');
  const nextButton = document.getElementById('nextButton');

  let index = 0;

  function showImage(index) {
    const width = items[0].clientWidth;
    carouselImages.style.transform = `translateX(${-index * width}px)`;
  }

  function nextImage() {
    index = (index + 1) % items.length;
    showImage(index);
  }

  function prevImage() {
    index = (index - 1 + items.length) % items.length;
    showImage(index);
  }

  nextButton.addEventListener('click', nextImage);
  prevButton.addEventListener('click', prevImage);


  setInterval(nextImage, 5000);
</script>

<style>
  .carousel {
    position: relative;
    width: 350px;
    height: 450px; 
    margin: 20px;
    overflow: hidden;
    border: 2px solid #ddd;
    border-radius: 10px;
  }

  .carousel-images {
    display: flex;
    transition: transform 0.5s ease-in-out;
  }

  .carousel-item {
    position: relative;
    flex: 0 0 100%;
    width: 100%;
    height: 100%; 
  }

  .carousel-item img {
    width: 100%;
    height: 100%;
    object-fit: cover; 
  }

.image-title {
  position: absolute;
  top: 10px;
  left: 50%;
  transform: translateX(-50%);
  width: 80%; /* Adjust the width to your preference */
  background: rgba(0, 0, 0, 0.6);
  color: #fff;
  padding: 5px 10px;
  border-radius: 5px;
  font-size: 14px;
  z-index: 10;
  text-align: center;
  height: auto; /* Keeps height adaptive to content */
  overflow-wrap: break-word; /* Ensures text wraps within the box */
}

  .carousel-buttons {
    position: absolute;
    top: 50%;
    width: 100%;
    display: flex;
    justify-content: space-between;
    transform: translateY(-50%);
  }

  .carousel-button {
    background: rgba(0, 0, 0, 0.5);
    color: #fff;
    border: none;
    padding: 5px 10px;
    cursor: pointer;
    border-radius: 5px;
  }

  .carousel-button:hover {
    background: rgba(0, 0, 0, 0.8);
  }
</style>
  
&emsp;&emsp;I am currently a PhD candidate in the Department of Earth, Environmental and Planetary Sciences of Rice University, working with [Dr. Rajdeep Dasgupta](https://www.dasgupta.rice.edu). I got my Master's degree in Geology from University of Tennessee, Knoxville with [Dr. Nicholas Dygert](https://dygert.utk.edu), and my Bachelor of Engineering in Resource Exploration Engineering from China University of Petroleum in Beijing.<br>&emsp;&emsp;I am interested in experimental petrology and igneous geochemistry. My previous research involved: 1) [high temperature and pressure experiments on sulfide solubility of young lunar basalts](https://dian01811.github.io/files/Ji_GCA_2025.pdf), 2) [apatite-melt trace element partitioning experiments, and developing temperature and composition-dependent predictive partitioning model as well as Eu-in-apatite oxybarometers](https://dian01811.github.io/files/Ji_GCA_2024.pdf), 3) [physical evolution of the lunar anorthositic crust and cumulate mantle inferred from trace element geochemical modeling](https://dian01811.github.io/files/Ji_EPSL_2023.pdf), and 4) [the petrogenesis of the early Cretaceous adakities in northeast China by their distribution, petrological, geochronological and isotopic characteristics](https://dian01811.github.io/files/Ji_IGR_2020.pdf).<br>&emsp;&emsp;Outside of research, I go freshwater fishing at least once a week. Driving around in search of high-quality fishing spots and reservoirs to catch those strong bass, skipjack, catfish, trout and bluegill is my greatest interest.




<h2 class="section-title">News</h2>

<strong>Jul 10, 2025: Ji will supervise a high-school intern, Denim-Leenox Sasser, on high temperature experiments this Summer!</strong> Welcome, Denim!

<strong>May 9, 2025: Ji was awarded the [Torkild Reiber Award](https://eeps.rice.edu/news/2025/2025-faculty-staff-and-student-awards) by the Department of Earth, Environmental and Planetary Sciences, Rice University.</strong>

<strong>Apr 17, 2025: Ji passed his PhD Qualifying Exam!</strong>

<strong>Mar 10, 2025: Ji gave a talk presentation on [existence of garnet in the source of young lunar mare basalts](https://www.hou.usra.edu/meetings/lpsc2025/pdf/1332.pdf) at the 56th Lunar and Planetary Science Conference.</strong>

<strong>Feb 21, 2025: Ji gave a talk on the sulfur budget of the young lunar mantle and the origin of the Chang’e-5 mare basalts at the [Geochemistry/Minerology/Petrology (GMP) Lunch Bunch](https://events.brown.edu/earth-environmental-planetary/event/305456-gmp-lunch-bunch-dian-ji) at Brown University!</strong>

<strong>Feb 17, 2025: [Ji’s paper on sulfur budget of the young lunar mantle was accepted for publication in <em>Geochimica et Cosmochimia Acta</em>](https://doi.org/10.1016/j.gca.2025.02.019)!</strong>

<strong>Dec 16, 2024: Ji won the 2025 Rice Space Institute Center for Planetary Origins to Habitability (CPO2H) graduate fellowship!</strong>

<strong>Dec 13, 2024: Ji gave a poster presentation on [deep sulfur cycle in the young lunar mantle](https://agu.confex.com/agu/agu24/meetingapp.cgi/Paper/1517917) at the 2024 AGU Fall Meeting.</strong>

<strong>Jul 6, 2024: Ji will supervise a high-school intern, Aahan Roy, on sulfur solubility experiments of lunar basalt this Summer!</strong> Welcome, Aahan!

<strong>Apr 3, 2024: Ji passed his written Preliminary Exam!</strong>

<strong>Mar 12, 2024: Ji gave a talk presentation on [a new europium in apatite-plagioclase oxybarometer](https://www.hou.usra.edu/meetings/lpsc2024/pdf/1240.pdf) at the 55th Lunar and Planetary Science Conference.</strong>

<strong>Nov 3, 2023: [Ji’s paper on apatite-melt trace element partitioning was accepted for publication in <em>Geochimica et Cosmochimia Acta</em>](https://doi.org/10.1016/j.gca.2023.11.004)!</strong>

<strong>Oct 13, 2023: Ji participated in a field trip regarding igneous and metamorphic rocks in Valles Caldera, Los Alamos Surge Deposits, Bandelier National Monument, and Rio Grande Gorge.</strong>

<strong>Aug 15, 2023: Ji was awarded the Chair’s Fellowship by the Department of Earth, Environmental and Planetary Sciences, Rice University.</strong>

<strong>Aug 1, 2023: Ji moved on to the PhD program at Rice University.</strong> Bye, Tennessee!

<strong>Jul 6, 2023: Ji defended his MS Thesis!</strong>

<strong>May 4, 2023: Ji was awarded the Virginia & James Bibee Graduate Student Professional Promise Award and the Excellence in Teaching by GTA’s Award by Department of Earth, Environmental, and Planetary Sciences, University of Tennessee.</strong>

<strong>May 3, 2023: Ji was awarded a [MSA grant in Mineralogy-Petrology Research](https://msaweb.org/mineralogy-petrology-grant/)!</strong>

<strong>Mar 15, 2023: In the PhD program application, Ji received offers of admission from all applied programs</strong>, including Caltech, University of Chicago, University of Michigan, Rice University, UT Austin, and University of Minnesota!

<strong>Mar 13, 2023: Ji gave a talk presentation on [apatite-melt trace element partitioning](https://www.hou.usra.edu/meetings/lpsc2023/pdf/1255.pdf) at the 54th Lunar and Planetary Science Conference.</strong>

<strong>Dec 7, 2022: [Ji’s paper on lunar anorthositic crust was accepted in <em>Earth and Planetary Science Letters</em>](https://doi.org/10.1016/j.epsl.2022.117958)!</strong> 

<strong>Sep 30, 2022: Ji participated in the Rio Grande Rift xenolith sampling expedition in New Mexico, collecting mantle and crustal xenoliths.</strong>

<strong>May 5, 2022: Ji received the Jimmy Walls Colloquium Presentation Award from the Department of Earth, Environmental, and Planetary Sciences, University of Tennessee.</strong>

<strong>Mar 13, 2022: Ji gave a talk presentation on [lunar anorthositic crust](https://www.hou.usra.edu/meetings/lpsc2022/pdf/1229.pdf) at the 53rd Lunar and Planetary Science Conference.</strong>

<strong>Mar 13, 2022: Ji attended the McClung Blue Ridge Foothills Field Trip, studying the Appalachian foreland fold-thrust belt transition.</strong>

<strong>Jul 6, 2021: [Ji gave a talk presentation at the 2021 Goldschmidt meeting](https://conf.goldschmidt.info/goldschmidt/2021/meetingapp.cgi/Paper/3219)!</strong>

<strong>Jun 1, 2021: Ji arrived in Knoxville to begin his graduate adventure!</strong> 

<strong>Oct 19, 2020: Ji was awarded the Li Siguang Outstanding Student Award!</strong> This is the highest undergraduate geoscience award in China.

<strong>Nov 24, 2019: [Ji’s paper on Northeast China adakite was accepted in <em>International Geology Review</em>](https://doi.org/10.1080/00206814.2019.1697968).</strong>

<strong>Jul 1, 2019: Ji will be a visiting scholar at the University of Texas at Dallas working with Dr. Robert J. Stern for two months!</strong>
