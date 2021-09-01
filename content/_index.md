---
date: "2017-06-26T18:27:58+01:00"
title: ""
toc: false
---
<div class="top-section-main">


<div class="splash-title">
<h2 style="font:3rem;font-weight: bold;">Whitman College & Northwest Archives</h2>
</div>

<div id="announcement">{{% announcement file="announcement.md" %}}</div>

</div>

<div class="second-section-main">
<div class="bootstrap-wrapper">
<div class="container-fluid">
<div class="row">
    <div class="col-lg-4 col-md-6 col-sm-12 col-xs-12">
    <div class="card"  style="font-size:0.8rem">
    <h3 class="center">Plan your visit</h3>
     <p>The Whitman College and Northwest Archives is currently closed to the public.</p>
     <p>We are open to Whitman students, faculty and staff who are approved to be on campus. For more details, see our <a href="/archives/access-policy">Fall 2021 Access Policy</a>.</p>
     
   For questions or to schedule an appointment, please email or call us.
  
  - ***Hours***: Monday-Friday, 9am-noon and 1-4pm
  - ***Email***: Archives@whitman.edu 
  - ***Phone number***: 509-527-5922
  - ***Location***: Ground floor of Penrose Library

 
    </div>
    </div>
    <div class="col-lg-4 col-md-6 col-sm-12 col-xs-12">
    <div class="card" style="font-size:0.8rem">
    <h3 class="center">Search Whitman College and Northwest Archives Finding Aids</h3>
     <form action="https://nwda-db.orbiscascade.org/nwda-search/results.aspx" method="get" target="_blank"><input id="searchValue" name="q" type="text" class="form-control no-up-margin"> <input id="searchSubmit" class="btn" type="submit" value="search"> <input id="t" name="t" type="hidden" value="k"> <input id="c" name="c" type="hidden" value="htm"></form>
     <p style="margin-top:0.5rem">To search Finding Aids for our archival and manuscript collections, visit Archives West. For more information about our collections, visit our <a href="/archives/collection/">Explore our Collections</a> page.</p>
    </div>
    </div>
   <div class="col-lg-4 col-md-6 col-sm-12 col-xs-12">
   <div class="card" style="padding:0">
      <div id="blog-jacket">
       <h3 class="center">Digital Collections</h3>
       <img class="responsive-img" src="" alt="Arminda Image" id="arminda-image" />
      </div>
      <div class="jacket-title">
       <a href="https://arminda.whitman.edu/collections/whitman-college-and-northwest-archives">ARMINDA: Digital Archives</a>
       <p>Explore digitized archival collections in ARMINDA, our Institutional Repository. Content includes College and regional publications, photographs, manuscripts, and more.</p>
      </div>
    </div>
   </div>
  </div>
</div>
</div>
</div>


<script>
var rad=Math.floor((Math.random() * 5) + 1); 
function getRandomInt(max) {
  return Math.floor(Math.random() * Math.floor(max))+1;
}

$(document).ready(function(){

	//background img
	$('#arminda-image').attr('src','/images/archive_web/img_0'+getRandomInt(6)+'.jfif');

});
</script>