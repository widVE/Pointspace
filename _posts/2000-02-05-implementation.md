---
title: "Implementation"
bg: white
color: black
style: center

---

# Our method


We build a way to store and render data, through the use of volumetric cubes.

![standard-method](images/standardmethod.gif)
![our-method](images/ourmethod.gif)

Our method captures and stores data using volumes as opposed to points.  This enables data to be stored and visualized at the detail at which it was captured.

![istandard-render](images/standardrender.gif)
![our-render](images/ourrender.gif)

Our novel rendering methods utilize the power of the graphics processor to draw many volumes in parallel ultra fast.
    
<style type="text/css">
#wrapper {
  display: flex;
  

}

#left {
  flex: 0 0 50%;
  padding: 15px;
}

#right {
  flex: 1;
   padding: 15px;
}
</style>




<div id="wrapper">
  <div id="left">
  <h2> Standard Approach </h2>
  <img src="images/Screenshot.jpg">

  </div>
  <div id="right">
  <h2>
   Our Approach
  </h2>
   <img src="images/ourmethod.jpg">

  
  </div>
      
</div>

<div id="wrapper">
  <div id="left">
  
  <img src="images/Screenshot4.jpg">

  </div>
  <div id="right">
   <img src="images/ourmethod.jpg">

  
  </div>
      
</div>


