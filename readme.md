
<p><img src="/documents/osirix-logo.svg" alt="ColorMRI Logo"></p>
<h1 id="osirix-color-mri-plugin">Osirix Color MRI Plugin</h1>
<p>An RGB Image Composer Plugin developed for Osirix. The plugin lets users to choose 2 or 3 image sets from the same locations of a patient, and composes them into a single rgb Image Set</p>
<p><img src="/documents/1280px-Beyoglu_4671_tricolor.jpg" alt="Tricolor Composing"></p>
<p>you can find much more detailed information from <strong>Dr. Nevit Dilmen</strong>’s documentation : <a href="/documents/Three%20color%20vision%20and%20Color%20MRI.pdf">Three color vision and Color MRI</a></p>
<h2 id="getting-started">Getting Started</h2>
<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.</p>
<h3 id="prerequisites">Prerequisites</h3>
<p>In order to run this plugin, you must have at least OSX 10.6 and  Osirix installed in your system.</p>
<h3 id="installing">Installing</h3>
<h4 id="install-by-downloaded-the-precompiled-binary-recommended">Install by downloaded the precompiled binary (recommended)</h4>
<ul>
<li>Download “ColorMRI.osirixplugin.zip” the latest release from the <a href="https://github.com/dreampowder/Osirix-ColorMRI/releases">Releases</a> tab.</li>
<li>Double click on the extracted “ColorMRI.osirixplugin” file. Osirix will launch automatically and add the plugin to the application.</li>
</ul>
<h4 id="rebuilding-the-project-from-the-source-code-and-install">Rebuilding the project from the source code and install</h4>
<ul>
<li>Clone the repository by typing “git clone <a href="https://github.com/dreampowder/Osirix-ColorMRI">https://github.com/dreampowder/Osirix-ColorMRI</a>”</li>
<li>open terminal and navigate to the project path.</li>
<li>run “pod install” inside the project path. If you do not have cocoapods installed in your system, you can install it by typing “sudo gem install cocoapods” in the terminal window. ( you can also find further instuctions about installing cocoapods at <a href="https://guides.cocoapods.org/using/getting-started.html">https://guides.cocoapods.org/using/getting-started.html</a> )</li>
<li>Open the project by typing “open Osirix\ ColorMRI.xcworkspace/” from the terminal  or double click on the “Osirix ColorMRI.xcworkspace” file form the finder.</li>
<li>From the XCode, click on ‘Build’ from Product menu from the top to build.</li>
<li>Once the build process is completed, right click on the  “ColorMRI.osirixplugin” and show in finder to open the file from finder.</li>
<li>double click on the file to launch Osirix and Install the plugin.</li>
</ul>
<h2 id="minimum">Minimum image requirements</h2>
<ul>
<li>In order to make a trichromatic color MRI you need:</li>
<li>Three series with same Field of view (FOV) and resolution.</li> 
<li>Recommended series are T1 for red channel, T2 for green channel and STIR or T2 Fat sat for blue channel.</li><br>  
<img src="/documents/MR_Ornekler1a.jpg" alt=""><br>  
</ul>
<h2 id="usage">Usage</h2>
<ul>
<li>Double click and load the patient:</li>
<li>Select plugins:Image plugins:Color MRI.</li> 
<li>From possible groupings select one by clicking on a series name.</li>
<li>Assign series to colors from dropdown menu.</li>
<li>Click compose.</li><br>  
<img src="/documents/photo5850293469665406159.jpg" alt=""><br>  
</ul> 
<h2 id="contributing">Contributing</h2>
<p>Please read [<a href="http://CONTRIBUTING.md">CONTRIBUTING.md</a>](<a href="https://gist.github.com/PurpleBooth/b24679402957c63ec426">https://gist.github.com/PurpleBooth/b24679402957c63ec426</a>) for details on our code of conduct, and the process for submitting pull requests to us.</p>
<h2 id="authors">Authors</h2>
<ul>
<li>Dr. Nevit Dilmen - Project Manager</li>
<li>Serdar Coskun - Developer</li>
</ul>
<h2 id="license">License</h2>
<p>This project is licensed under the MIT License - see the [<a href="LICENSE">LICENSE</a>] file for details</p>
<h2 id="example-outputs-from-the-plugin">Example Outputs from the plugin</h2>
<p>

<img src="/documents/Orbita_MRI_02-0009a.jpg" alt=""><br>
<img src="/documents/Ornek3.jpg" alt=""><br>
<img src="/documents/photo5812225993404951649.jpg" alt=""><br>
<img src="/documents/photo5812225993404951653.jpg" alt=""><br>

<img src="/documents/photo5850293469665406160.jpg" alt=""><br>
<img src="/documents/photo5850293469665406161.jpg" alt=""><br>
<img src="/documents/photo5850293469665406162.jpg" alt=""></p>

<img src="/documents/photo5850293469665406158.jpg" alt=""><br>

<img src="/documents/IM-0001-0001_cra.jpg" alt=""><br>
Color MRA
