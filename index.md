---
layout: default
---
<!-- <p style='text-align: right;'> [ {{ page.last_modified_at | date: '%d  %B  %Y' }}] </p> -->
<h5 style="font-size:0.6vw"><i><p align='right'>[Last update: {{ page.last_modified_at | date: '%d  %B  %Y' }}]</p></i></h5>

## Who Am I?
I am currently assistant professor (Maitre de conference) at University of Rennes.  
I am member of the [Capsule](https://team.inria.fr/capsule/team-members/)
team, inside the IRISA laboratory. My research focus on side-channel analysis. 

I am involved in the ANR project [IDROMEL](https://projects.laas.fr/IDROMEL/): Improving the
Design of secure systems by a Reduction Of Micro-architectural Effects
on side-channeL Attacks (IRISA, LAAS-CNRS, LIP6, CEA-list, ARM, DGA).

I was previously:
- postdoc in [Capsule](https://team.inria.fr/capsule/team-members/)
    team on the ANR project [AHMA](https://anr.fr/Project-ANR-18-CE39-000): 
    Automated Hardware Malware Analysis,
- Postdoc in the [MAIS](https://www.mais.informatik.tu-darmstadt.de/)
    team, inside TU-Darmstadt. I was supervised by Heiko Mantel,
    involved in the DFG collaborative research center
    [CROSSING](https://www.crossing.tu-darmstadt.de/crc_1119/index.en.jsp)
    and created the [side-channel
    lab](https://www.mais.informatik.tu-darmstadt.de/side-channel-ss20.html).

I completed my PhD at [Secure-IC](https://www.secure-ic.com/) and
[COMELEC](https://www.comelec.telecom-paristech.fr/) supervised by
[Sylvain Guilley](https://perso.telecom-paristech.fr/guilley/):
{% bibliography -q @phdthesis %}

<!--  -->
<!-- ## Book Chapters -->

<!-- {% bibliography -q @inbook %} -->
<!-- ## Coming soon -->
<!-- {% bibliography -q @*[status=not-published] %} -->

## Last publications
{% bibliography -q @*[year >= 2021 && status=published] %}

## Conferences and Workshops
{% bibliography -q @inproceedings[year < 2021  && status=published] %}

## Journal Articles
{% bibliography -q @article[year < 2021  && status=published] %}

## Talks
{% bibliography -q @*[status=talk] %}
<!-- - Malwares revealed through EM at [EDUC (European Digital UniverCity) - Session III: AI & Security](https://www.educalliance.eu/). *November, 24, 2021.* -->
<!-- - Binary Data Analysis for Source Code Leakage Assessment at [CIDRE seminar](https://team.inria.fr/cidre/). *January 25, 2021.* -->


## Media Coverage
### Podcasts
- [Leveraging electromagnetic emanations for IoT malware classification](https://www.electronicspecifier.com/news/podcasts/series-9-episode-4-leveraging-electromagnetic-emanations-for-iot-malware-classification). *electronicspecifier, Series 9 – Episode 4, September 16th, 2022*.


### Articles
- [Detecting evasive malware on IOT devices using electromagnetic emanations](https://thehackernews.com/2022/01/detecting-evasive-malware-on-iot.html). *The Hacker News, January 3rd, 2022*.
- [Using EM Waves to Detect Malware](https://www.schneier.com/blog/archives/2022/01/using-em-waves-to-detect-malware.html). *Schneier on Security, January 14, 2022*.
- [Raspberry Pi Can Detect Malware Using Electromagnetic Waves, Say Researchers](https://www.indiatimes.com/technology/news/raspberry-pi-can-detect-malware-559086.html). *Indian Times, January 16th, 2022.*
- [On peut détecter des malwares avec précision grâce... aux ondes électromagnétiques ](https://www.01net.com/actualites/on-peut-detecter-des-malwares-avec-precision-grace-aux-ondes-electromagnetiques-2053625.html). *01 net, January 16th, 2022 (in French)*.
- [Identifying Malware By Sniffing Its EM Signature](https://hackaday.com/2022/01/19/identifying-malware-by-sniffing-its-em-signature/). *harckday, January 20th, 2022*.
- [Detect malware with electromagnetic waves and Raspberry Pi](https://www.raspberrypi.com/news/detect-malware-with-electromagnetic-waves-and-raspberry-pi/). *RasperryPi, February 1st, 2022.*

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~. -->

<!-- [Link to another page](./another-page.html). -->

<!-- There should be whitespace between paragraphs. -->

<!-- There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project. -->

<!-- # Header 1 -->

<!-- This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. -->

<!-- ## Header 2 -->

<!-- > This is a blockquote following a header. -->
<!-- > -->
<!-- > When something is important enough, you do it even if the odds are not in your favor. -->

<!-- ### Header 3 -->

<!-- ```js -->
<!-- // Javascript code with syntax highlighting. -->
<!-- var fun = function lang(l) { -->
<!--   dateformat.i18n = require('./lang/' + l) -->
<!--   return true; -->
<!-- } -->
<!-- ``` -->

<!-- ```ruby -->
<!-- # Ruby code with syntax highlighting -->
<!-- GitHubPages::Dependencies.gems.each do |gem, version| -->
<!--   s.add_dependency(gem, "= #{version}") -->
<!-- end -->
<!-- ``` -->

<!-- #### Header 4 -->

<!-- *   This is an unordered list following a header. -->
<!-- *   This is an unordered list following a header. -->
<!-- *   This is an unordered list following a header. -->

<!-- ##### Header 5 -->

<!-- 1.  This is an ordered list following a header. -->
<!-- 2.  This is an ordered list following a header. -->
<!-- 3.  This is an ordered list following a header. -->

<!-- ###### Header 6 -->

<!-- | head1        | head two          | three | -->
<!-- |:-------------|:------------------|:------| -->
<!-- | ok           | good swedish fish | nice  | -->
<!-- | out of stock | good and plenty   | nice  | -->
<!-- | ok           | good `oreos`      | hmm   | -->
<!-- | ok           | good `zoute` drop | yumm  | -->

<!-- ### There's a horizontal rule below this. -->

<!-- * * * -->

<!-- ### Here is an unordered list: -->

<!-- *   Item foo -->
<!-- *   Item bar -->
<!-- *   Item baz -->
<!-- *   Item zip -->

<!-- ### And an ordered list: -->

<!-- 1.  Item one -->
<!-- 1.  Item two -->
<!-- 1.  Item three -->
<!-- 1.  Item four -->

<!-- ### And a nested list: -->

<!-- - level 1 item -->
<!--   - level 2 item -->
<!--   - level 2 item -->
<!--     - level 3 item -->
<!--     - level 3 item -->
<!-- - level 1 item -->
<!--   - level 2 item -->
<!--   - level 2 item -->
<!--   - level 2 item -->
<!-- - level 1 item -->
<!--   - level 2 item -->
<!--   - level 2 item -->
<!-- - level 1 item -->

<!-- ### Small image -->

<!-- ![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png) -->

<!-- ### Large image -->

<!-- ![Branching](https://guides.github.com/activities/hello-world/branching.png) -->


<!-- ### Definition lists can be used with HTML syntax. -->

<!-- <dl> -->
<!-- <dt>Name</dt> -->
<!-- <dd>Godzilla</dd> -->
<!-- <dt>Born</dt> -->
<!-- <dd>1952</dd> -->
<!-- <dt>Birthplace</dt> -->
<!-- <dd>Japan</dd> -->
<!-- <dt>Color</dt> -->
<!-- <dd>Green</dd> -->
<!-- </dl> -->

<!-- ``` -->
<!-- Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this. -->
<!-- ``` -->

<!-- ``` -->
<!-- The final element. -->
<!-- ``` -->
