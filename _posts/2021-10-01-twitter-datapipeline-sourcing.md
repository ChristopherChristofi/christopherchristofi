---
category: Programming
topic: Shell scripting
title: Building a Twitter Data pipeline using twarc and jq
---

TODO: full write-up....
For a standalone, full script written in bash for both accessing the twitter API and wrangling the initial raw dataset, please view: [GitHub Script](https://github.com/ChristopherChristofi/raw-tweets-to-csv-script)...
For script functionality as a component of a full NLP project (which diagram is most relevant to), please view: [GitHub Script](https://github.com/ChristopherChristofi/tweet-nlp-text-analyser/tree/main/scripts)

***A diagram depicting bash script processes - the initial transformation workflow used on the gathered raw datasets: tweet property parametrization; character pattern matching replacing newline escape characters; format conversions from JSONL to CSV; removal of duplicate tweet entries; and text lowercasing. De-duplication removed an extensive 37000 unwanted data records.***

<br>

![Diagram of process workflow of the raw data processing script](/assets/img/projects/twitterpipeline/tweetdatapipelinesourcing.png)

<br>
