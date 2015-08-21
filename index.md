---
title       : Testosterone as a Drug
subtitle    : Overmarketed for Off-Label Use?
author      : Nick Switzer with inspiration from Tim from the Digital Apothecary
job         : Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Testosterone Marketing

Testosterone drugs are often marketed by capitalizing on aging male insecurity. 

Ads often include attractive women and compel the target audience to increase their testosterone. 



--- &radio 

## Quick Quiz

What is the only indication for AndroGel, a popular testosterone product? 

1. Feelings of Insecurity
2. Muscle Atrophy
3. _Hypogonadism_
4. Erectile Dysfunction

*** .hint
Which one is the most unknown?


*** .explanation
Hypogonadism is the only approved indication for AndroGel. Why are erectile dysfunction, muscle atrophy and feelings of insecurity used as the primary marketing tools then?

----

## The Downsides of Testosterone as a Drug

According to the OpenFDA Adverse Effects Database, the top 5 adverse effects of testosterone are:


```
## Fetching: https://api.fda.gov/drug/event.json?search=patient.drug.openfda.generic_name:testosterone&count=patient.reaction.reactionmeddrapt.exact
```
<br>
term, count<br>
DRUG INEFFECTIVE, 1318<br>
BLOOD TESTOSTERONE DECREASED, 1016<br>
PAIN, 808<br>
FATIGUE, 687<br>
ASTHENIA, 525<br>


<br>

Does this look like a drug worth taking? 

---

## The Dangers of Testosterone as a Drug

Among the more serious adverse effects are:

Heart Attacks (Myocardial Infarctions)<br>
Strokes (Cerebrovascular Accidents)<br>
Blood Clots in the Lungs (Pulmonary Embolism)<br>

<a href="https://nswitzer.shinyapps.io/shinyApp">How is this trending over time?</a>


---

## What can I do??

This is far from a complete study. 

A doctor and a pharmacist had a hunch
They got together with an emerging data scientist
OpenFDA gave them the API and the data
They did a preliminary study.

Next steps:

*Examine if those adverse events rates are higher than expected for their demographics
*Gather data on prescription volume over time
*Gather data on the marketing timeline 
*Make a recommendations on how to combat ill-advised use. 

How can you help?

<a href="https://twitter.com/intent/tweet?button_hashtag=OpenFDAChallenge&text=I%20support%20Testosterone%20drug%20adverse%20effects%20research" class="twitter-hashtag-button" data-related="NickSwitzer1,TDAungst" data-url="http://rpubs.com/nswitzer/Testosterone">Tweet #OpenFDAChallenge</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>

If we get more than 1,000 Tweets / Retweets, we will take this study to the next level. 

find.package("RCurl")
.libPaths( "")
publish(title = 'mytitle2', 'index.html', host = 'rpubs')
