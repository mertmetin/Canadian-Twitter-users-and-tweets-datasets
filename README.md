# Canada---Twitter-users-dataset
Data is crucial part of research, but not always very easy to find, especially in huge volume. In order to facilitate the academic research, I share two datasets <i>Twitter-CAD-Users</i> and <i>Twitter-CAD-Tweets</i>; they were collected for my thesis in <a href="http://uottawa.ca" target="_blank">University of Ottawa</a>. The datasets can be downloaded from the public Dropbox folder <a href="https://www.dropbox.com/sh/a58ac7638cjrnv2/AABmbU-UUPM34kYo2YSjRIe4a?dl=0">here</a>.

Both datasets contain users — and tweets — from census metropolitan areas and agglomerations in Canada with population more than 100.000. The full list of CMAs and CAs can be found <a href="https://en.wikipedia.org/wiki/List_of_census_metropolitan_areas_and_agglomerations_in_Canada">here</a>.

<h2>Twitter-CAD-Users</h2>
Twitter-CAD-Users — as the name suggests – includes Canadian Twitter users with their tweets, up to last 100 friends and followers <sup>1</sup> and bunch of metadata information about users (e.g. tweets, friends and followers count and gender<sup>2</sup>). We collected this dataset to geolocate users from their tweets as well as their social graph (i.e. friends and followers). Furthermore, each user tagged with a location (i.e. groundtruth location) which is the user declared location in Twitter profile. 

<ul>
<li><b>Collection period:</b> January 10 and January 25, 2019</li>
<li><b>Total number of users:</b> 420
<li><b>Total number of tweets:</b> 935.512
<li><b>Total number of friends:</b> 50.252
<li><b>Total number of followers:</b> 50.122
<li><b>Size:</b> 218.2 MB</b></li>
<li><b>Format:</b> SQL</li>
</ul>

<h2>Twitter-CAD-Tweets</h2>
Twitter-CAD-Tweets includes tweets from Canadian Twitter users. We collected this dataset to geolocate tweets from their context. Each tweet is geotagged with a latitute and longitute pairs (i.e. bounding box).

<ul>
<li><b>Collection period:</b> March 25 and April 5, 2019</li>
<li><b>Total number of tweets:</b> 40.455
<li><b>Size:</b> 73.57 MB</b></li>
<li><b>Format:</b> SQL</li>
</ul>

<b>P.S: If you use any of these datasets for the academic purpose, please do not forget to cite/include this page's link in your paper.</b>

1) We could only get last 100 friends and followers of a user because of the strict <a href="https://developer.twitter.com/en/docs/basics/rate-limiting.html">API limits</a>.
2) Twitter does not expose users' gender information. We used API gender-api.com to get genders from names.
