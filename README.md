collapsible_menu_bootstrap
==========================

Working with bootstrap is wonderfull, fast development, easy to use, responsive for all devices. We are share about how to make collapsable menu using bootstrap. The source code is attatched below of the post, hope you will understand the code. Step1: Following is the code for the nav bar of bootstrap &lt;div class="nav-collapse collapse">               &lt;ul class="nav">                 &lt;li>&lt;a href="#" class="active">Home&lt;/a>&lt;/li>                 &lt;li>&lt;a href="#">Contact&lt;/a>&lt;/li>               &lt;/ul>             &lt;/div> In the main div of nav there are two class nav-collapse and collapse  These two classes are main for the collapsable menu data-toggle="collapse" and data-target=".classname" Step2:  What you need to show while the screen is small. &lt;a class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse"> 				&lt;span class="icon-bar">&lt;/span> 				&lt;span class="icon-bar">&lt;/span> 				&lt;span class="icon-bar">&lt;/span> 			&lt;/a>  You need to put this code just above  &lt;div class="nav-collapse collapse"> div. Step3: While we merge the code like this &lt;a class="btn btn-navbar" data-toggle="collapse" data-target=".nav-collapse"> 				&lt;span class="icon-bar">&lt;/span> 				&lt;span class="icon-bar">&lt;/span> 				&lt;span class="icon-bar">&lt;/span> 			&lt;/a>             &lt;div class="nav-collapse collapse">               &lt;ul class="nav">                 &lt;li>&lt;a href="#" class="active">Home&lt;/a>&lt;/li>                 &lt;li>&lt;a href="#">Contact&lt;/a>&lt;/li>               &lt;/ul>             &lt;/div> Hope this post will help to you.
