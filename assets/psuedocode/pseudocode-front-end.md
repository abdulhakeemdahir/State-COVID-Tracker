##PSUEDOCODE for Frontend



======
##Old code

```
=======

  <section class="hero is-danger has-text-centered">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">
          COVID 19 TRACKER
        </h1>
        <h2 class="subtitle">
          Latest U.S. Data on the Corona Virus
        </h2>
      </div>
    </div>
  </section>

  
   
  

<div class="container">

 <div class="container is is-widescreen is-flex is-justify-content-center mb-3 mt-3 ">
   <!-- Add media query to change size for smaller and largest size screen -->
    <span class="tag is-link is-medium">Click to view newest stories on Corona Virus</span>
  </div>
</div>

<div class= "container2 ">
  
    <div class="notification mt-0 mb-3 is-flex is-justify-content-space-between  is-flex-direction-row is-justify-content-center  ">
      <input class="input" type="text" placeholder="Search State">
      <!-- Add wrap on media query for small screens -->
      <button class="button" id="currentBtn">CURRENT</button>
      <input class="input" type="text" placeholder="YYYY/MM/DD">
      <button class="button" id="historicBtn">HISTORIC</button>

    </div>
  

</div>
<!-- Columns automatically stack on top of eachother on small screen sizes -->
<div class="columns is-vcentered ">
  <div class="column has-background-info has-text-white has-text-centered">
   <h2>Current Data</h2>
  Tesing how this works <br>
  when I add content.
  
  </div>
  <div class="column has-background-grey-light has-text-white has-text-centered">
   <h2>Historic Data</h2>

   <!-- Add hide class until user clicks on view articles link -->
  </div>
  <div class="column has-background-info has-text-white has-text-centered">
   <h2> Latest Covid News Articles</h2>
  </div>
  
</div>
```