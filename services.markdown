---
layout: page
title: Services
permalink: /services/
---
<style type="text/css" media="screen">
  .title-container {
    margin: 10px auto;
    #max-width: 600px;
    text-align: center;
    color: white;
    text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;
    background-color: white;
    background-image: url("/images/circuit-board-3.jpg");
    background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Do not repeat the image */
    background-size: cover; /* Resize the background image to cover the entire container */
    #padding-bottom: 2px;
    #padding-top: 1px;
  }
  .header-img-shadow {
    box-shadow: inset 0px -20px 10px -5px rgba(0,0,0,0.5);
  }
  h1 {
    margin: 30px 0;
    font-size: 4em;
    line-height: 1;
    letter-spacing: -1px;
  }
  .page-content {
       background: rgb(2,0,36);
       background: linear-gradient(36deg, rgba(2,0,36,1) 0%, rgba(9,9,121,1) 25%, rgba(0,212,255,1) 100%); 
  }
  .wrapper {
      background-color: white;
      max-width: 80%;
      margin-right: auto;
      margin-left: auto;
      box-shadow: 0px 8px 15px 5px rgba(0,0,0,0.4);
  }
  .main-content {
    text-align: center;
    padding: 10px;
  }
  .column {
  float: left;
  width: 33%;
  padding-top: 10px;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;

</style>

<div class="background-img"></div>
<div class="title-container">
  <br>
  <h1>Our Services</h1>

  <h3><strong>Something missing on this list? Get in touch and we'll see what we can do!</strong></h3>
  <br>
  <br>
  <br>
  <br>
<div class="header-img-shadow"><br></div>
</div>

<div class="main-content">
<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'General Support')" id="defaultOpen">General Support</button>
  <button class="tablinks" onclick="openTab(event, 'Data Recovery')">Data Recovery</button>
  <button class="tablinks" onclick="openTab(event, 'Web Hosting')">Web Hosting</button>
  <button class="tablinks" onclick="openTab(event, 'MacBook Repair')">MacBook/iMac Repair</button>
</div>

<div id="General Support" class="tabcontent">
  <h3>General Support</h3>
  <p>Placeholder</p>
</div>

<div id="Data Recovery" class="tabcontent">
  <h3>Data Recovery</h3>
  <p>Placeholder</p> 
</div>

<div id="Web Hosting" class="tabcontent">
  <h3>Web Hosting</h3>
  <p>Placeholder</p>
</div>

<div id="MacBook Repair" class="tabcontent">
  <h3>MacBook / iMac Repair</h3>
  <p>Placeholder</p>
</div>

  <script>
    document.getElementById("defaultOpen").click();

    function openTab(evt, tabName) {
    // Declare all variables
    var i, tabcontent, tablinks;

    // Get all elements with class="tabcontent" and hide them
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }

    // Get all elements with class="tablinks" and remove the class "active"
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }

    // Show the current tab, and add an "active" class to the button that opened the tab
    document.getElementById(tabName).style.display = "block";
    evt.currentTarget.className += " active";
    }

    
</script>