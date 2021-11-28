---
date: "2017-11-27T00:00:00Z"
external_link: https://textmining-infopros.github.io/
image:
  caption: ''
  focal_point: Smart
summary: I identified the core topics of full-text LIS Electronic Theses and Dissertations (ETDs) using Topic-Modeling-Toolkit for the period of 2013-2017 and visualized it using Tableau.
categories:
- topic modeling
- ETDs
- visualization
title: Visualizing Topic Models of Indian LIS Research
links:
- icon: book
  icon_pack: fas
  name: Article
  url: https://zenodo.org/record/1475795#.X-YrudgzYuE
- icon: disease
  icon_pack: fas
  name: Dashboard
  url: https://public.tableau.com/views/Shodhganga/Dashboard?:display_count=n&:origin=viz_share_link
---
![](1.jpg)

## Introduction

I performed a [study](https://zenodo.org/record/1475795#.X-YrudgzYuE) in 2018 to identify the core topics in 98 full-text library and information science Electronic Theses and Dissertations (ETDs) using [Topic-Modeling-Toolkit](https://code.google.com/archive/p/topic-modeling-tool/) for the period of 2013-2017.

The dashboard helps to visualize the topic modeling results of the above study. It was prepared using [Tableau](https://www.tableau.com/) on 25 December 2020 and was updated on 13 June 2021. The data used to prepare the dashboard is available for download and can be searched using the publication year, topics, and keywords for title.

<video class="video-shortcode" preload="auto" autoplay loop>
          <source src="https://manika-lamba.github.io/media/shodhganga.MOV" type="video/mp4" width="640" height="360" >
        There should have been a video here but your browser does not seem
        to support it.
</video>


## Problems Faced
The major caveats in Shodhganga repository that holds back text mining or any kind of analyses are:

1. No API
2. Individual Chapter PDFs for each ETD
3. No Abstract for ETDs in the metadata
4. No option to download the metadata

The above issues will be the major reason for me to not able to update the dashboard frequently as it take months to just download the data! And the above issues do not include the other uncertainties related to metadata! There are many instances where there is no “year” or “advisor” in the metadata of the ETDs. Some ETDs are submitted in Word, some are submitted in PDFs. Again all these issues were covered in my small study which I faced when I analysed this repository. If someone wants to do any analysis, one has to go through each ETD manually which is not possible for analyses that depend on large corpus of data. Until and unless INFLIBNET works on fixing on all the above issues, user experience of using Shodhganga will never be competitive to databases like ProQuest.

PS: This study was conducted in 2018 and all these issues have not been fixed till now.

## Dashboard


<div class='tableauPlaceholder' id='viz1638054644340' style='position: relative'><noscript><a href='https:&#47;&#47;manika-lamba.github.io&#47;project&#47;shodhganga&#47;'><img alt='Visualization of Topic Modeling Result for ETDs in Shodhganga (2013-2017) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sh&#47;Shodhganga&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Shodhganga&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sh&#47;Shodhganga&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1638054644340');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1027px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
