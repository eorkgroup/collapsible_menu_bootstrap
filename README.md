collapsible menu on bootstrap
==========================

Working with bootstrap is wonderfull, fast development, easy to use, responsive for all devices. We are share about how to make collapsable menu using bootstrap. The source code is attatched below of the post, hope you will understand the code.
Step1:
Following is the code for the nav bar of bootstrap
<div class="nav-collapse collapse">
              <ul class="nav">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">Contact</a></li>
              </ul>
            </div>
In the main div of nav there are two class nav-collapse and collapse 
These two classes are main for the collapsable menu
data-toggle="collapse" and data-target=".classname"
Step2: 
What you need to show while the screen is small.
<a class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse">
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
			</a>

You need to put this code just above  <div class="nav-collapse collapse"> div.

Detail documentation is on http://eorkgroup.com/blog/2013/07/how-to-make-collapsible-menu-using-bootstrap-for-small-screen
