# frenchmen
frenchmen  art market test

this is hopefully where the new website can take off!
I will add more stuff about how to edit and change things later.

Maintenance:
    Since I will be busy with school, I've designed the website so that there's as little maintenance as possible.
    However, there are a few things that can be done that don't require too much work.
    
    EDITING ART PAGES:
    This is a block of code:
      <div class="responsive"> # refers to the responsive class - allows the image to be clicked
         <div class="gallery"> # refers to the gallery class - this makes the photo appear in a "gallery" box instead of just on the page 
            <a target="_blank" href="example.jpg"> # when the image is clicked, it opens the image on another page
              <img src="example.jpg" alt="333" width="600" height="400"> # sources the image, gives an alt name, and defines width and    height by pixels
            </a>
        <div class="desc"></div> # adds a blank space below the image for space reasons.
      </div>
    The code above will add an image for an artist.
    
    <button class="accordion">A. R. Tiste</button>
       <div class="panel">
          <p>Example description about a person, place, or thing.</p>
       </div>
    This block of code adds a drop down button for an artist   
    
<div class="clearfix"></div>
The code above adds a "clearfix"--a way to clear things up with spacing so that the button shows up nicely on desktop and mobile.
