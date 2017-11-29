<!-- https://guides.github.com/features/mastering-markdown/ for markdown guide --> 
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-110464159-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-110464159-1');
</script>


## Justin M. Turner
![](justinturn.github.io/headshot.png)

### :round_pushpin: Edmond, Oklahoma 
### :us: USA 
### :envelope: justinturn@gmail.com 


### About Me

* Twenty Five. Oklahoman. 
* MS in Agricultural Economics from Oklahoma State University. :mortar_board:
* Dabble in R, Python, SQL, and SAS. 
* Various Regression Models, Neural Nets, Forecasting Models, etc.
* Dayjob is spent at a fantastic organization developing Tableau Visuals, some SQL and R for data loading and manipulation, and designing data architecture. :office:
* Prefer numbers to words. 
* Dream job = Rancher. 

### What I'm Reading in 2017
 
* Tipping Point (M. Gladwell)
* Scaling Up Excellence
* Blink (M. Gladwell)
* Divine Direction (C. Groeschel)
* Inside the Magic Kingdom (T. Connellan)
* Triggerfish Twist (T. Dorsey)
* Forty Chances: Finding Hope in a Hungry World (H.G. Buffett)
* The Reality Based Rules of the Workplace
* YouVersion Bible App
* Bloomberg
* WSJ

### Code

Stayed tuned for some code to the projects I work on in my spare time...
-JT

### Connect

[Instagram: @justinturn](https://www.instagram.com/justinturn/)  

[Twitter: @turnerjustinm](https://twitter.com/turnerjustinm)  

[Visit my LinkedIn page](https://www.linkedin.com/in/justin-turner-b9012966/)  

<!-- LineChart generated in R 3.4.1 by googleVis 0.6.2 package -->
<!-- Sat Nov 25 10:34:08 2017 -->


<!-- jsHeader -->
<script type="text/javascript">


// jsData 
function gvisDataLineChartID16c03ac86151 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
1992,
91.67
],
[
1993,
97.54
],
[
1994,
88.83
],
[
1995,
73.54
],
[
1996,
62.8
],
[
1997,
86.8
],
[
1998,
82.08
],
[
1999,
87.28
],
[
2000,
98.77
],
[
2001,
101.32
],
[
2002,
91.45
],
[
2003,
100.47
],
[
2004,
120.46
],
[
2005,
129.27
],
[
2006,
126.11
],
[
2007,
121.72
],
[
2008,
115.55
],
[
2009,
108.51
],
[
2010,
123.08
],
[
2011,
147.06
],
[
2012,
169.6
],
[
2013,
173.07
],
[
2014,
245.25
],
[
2015,
249.92
],
[
2016,
163.98
] 
];
data.addColumn('number','year');
data.addColumn('number','price');
data.addRows(datajson);
return(data);
}


// jsDrawChart
function drawChartLineChartID16c03ac86151() {
var data = gvisDataLineChartID16c03ac86151();
var options = {};
options["allowHtml"] = true;


    chartLineChartID16c03ac86151 = new google.visualization.ChartWrapper({
    dataTable: data,       
    chartType: 'LineChart',
    containerId: 'LineChartID16c03ac86151',
    options: options
    });
    chartLineChartID16c03ac86151.draw();
    

}

  function openEditorLineChartID16c03ac86151() {
  var editor = new google.visualization.ChartEditor();
  google.visualization.events.addListener(editor, 'ok',
  function() { 
  chartLineChartID16c03ac86151 = editor.getChartWrapper();  
  chartLineChartID16c03ac86151.draw(document.getElementById('LineChartID16c03ac86151')); 
  }); 
  editor.openDialog(chartLineChartID16c03ac86151);
  }
    


// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "charteditor";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartLineChartID16c03ac86151);
})();
function displayChartLineChartID16c03ac86151() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}


// jsFooter
</script>


<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartLineChartID16c03ac86151"></script>


<!-- divChart -->
<input type='button' onclick='openEditorLineChartID16c03ac86151()' value='Edit me!'/>  
<div id="LineChartID16c03ac86151" 
  style="width: 500; height: automatic;">
</div>


