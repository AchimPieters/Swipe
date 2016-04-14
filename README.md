Add Finger-Swipe Support to Webpages

One of the more interesting and fun aspects of iPad usage is the ability to effect change in a webpage by swiping a finger across the screen of the iPad. For example, swiping to the left to navigate to the next page in a series of pages, or swiping to display the next image in a series of images. For iPad users, these actions are intuitive and natural.
However, for those who compose webpages, adding touch detection to a page can be a challenging and difficult process. No more. The information presented on these pages will make it easy to add touch sensing to your pages, requiring only a minimum of JavaScript coding on your part.

Add the JavaScript Script

The first step in implementing swipe support for specific page elements is to copy and add this script to the HEAD section of the webpage. Copy the entire script, including opening and closing <script> tags, and paste it into the webpage code after the title tag, but within the head section:

<!-- Include stylesheets -->
<link href="css/style.css" rel="stylesheet" type="text/css">
<link href="css/Font.css" rel="stylesheet" type="text/css">

<!-- Get jQuery from CDN -->
<script src="scripts/jquery-1.10.1.min.js"></script>
<script src="scripts/jquery-migrate-1.2.1.min.js"></script>

<!-- Include the slider scripts -->
<script type="text/javascript" src="scripts/jquery.slider.js"></script>
<script type="text/javascript" src="scripts/backstretch.js"></script>
      
<!-- Include the Settings scripts -->
<script type="text/javascript" src="scripts/Settings.js"></script>

Tag the Page Element

Once you’ve added the script to the head section, you need to add some parameters to the tag declaration of the page element you want to respond to swipe events, for example, a <div> page Element.

 <!-- START - Logo Area-->
    <header id="top">
      <div id="logo"><h2>Studio Pieters˙</h2></div>
    </header>
        <!-- START - Logo Area-->


    <!-- START - Slide Area-->
      <div class='pageblock' id='fullscreen'>
        <div class='slider'>
                    
                    
                    <!-- START - The First Slide -->
          <div class='slide' id="first"> <!-- Change the ID to Firts, second, thirth, fourth......  as you add more you'll need to add it also to custom.js -->
            <div class='slidecontent'>
                            
                            
                            <!-- START - Add Your content code here-->
              <p>Responsive Design and the slider works perfectly fine on mobile devices, tablets etc.</p> <!-- Add a heading text-->
              <h1>Slide one.</h1> 
                            <!-- Add Your content code here - STOP-->
                            
                            
            </div>
          </div>
                    <!--The Second Slide - STOP -->
                    
                    <!-- START - The Second Slide -->
          <div class='slide' id="second"> <!-- Change the ID to Firts, second, thirth, fourth......  as you add more you'll need to add it also to custom.js -->
            <div class='slidecontent'>
                            
                            
                            <!-- START - Add Your content code here-->
              <p>You Need some Knowledge of PHP, HTML5 or CSS3.</p> <!-- Add a heading text-->
              <h1>Slide two.</h1> 
                            <!-- Add Your content code here - STOP-->
                            
                            
            </div>
          </div>
                    <!--The Second Slide - STOP -->
                    
                    <!-- START - The Thirth Slide -->
          <div class='slide' id="thirth"> <!-- Change the ID to Firts, second, thirth, fourth......  as you add more you'll need to add it also to Settings.js -->
            <div class='slidecontent'>
                            
                            
                            <!-- START - Add Your content code here-->
              <p>Creating a new slider is simple – add your image, add your slide and the script will do the rest.</p> <!-- Add a heading text-->
              <h1>Slide Three.</h1> 
                            <!-- Add Your content code here - STOP-->
                            
                            
            </div>
          </div>
                    <!--The Thirth Slide - STOP -->
                    
                    
                   
        </div>
      </div>
        <!-- Slide Area - STOP -->

Add Your content Code between the tag’s  <!– START – Add Your content code here–>  and  <!– Add Your content code here – STOP–>.

                            <!-- START - Add Your content code here-->
              <p>You Need some Knowledge of PHP, HTML5 or CSS3.</p> <!-- Add a heading text-->
              <h1>Slide two.</h1> 
                            <!-- Add Your content code here - STOP-->

