# comp598-homework-7---data-scraping-solved
**TO GET THIS SOLUTION VISIT:** [COMP598 Homework 7 – Data Scraping Solved](https://www.ankitcodinghub.com/product/comp-598-homework-7-data-scraping-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118616&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP598 Homework 7 – Data Scraping Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Non-standard (i.e., built-in) python libraries you can use:

– pandas

– requests

– BeautifulSoup

Task 1: Scraping relationships (10 pts)

Write a script collect_relationships.py that collects the relationships for a set of celebrities provided in a JSON configuration file as follows:

python scripts/collect_relationships.py -c &lt;config-file.json&gt; -o &lt;output_file.json&gt;

where config-file.json contains a single JSON dictionary with the following structure (the exact path and list of celebrities can, obviously, change):

{

“cache_dir”: “.data/wdw_cache”,

“target_people”: [ “robert-downey-jr”, “justin-bieber” ]

}

The output format for the file is:

{

“robert-downey-jr”: [ “person-1”, “person-2”, “person-3” ],

“justin-bieber”: []

}

Where the identifiers in the list are the people the person had a relationship with. If the person has had no relationships, then they will have an empty list.

Task 2: Getting course information (20 pts)

python scripts/scrape_courses.py -c &lt;caching_dir&gt; &lt;page#&gt;

Your script must cache to the directory specified. The page# indiciates which URL will be loaded. The courses should be printed in CSV format to stdout with the following columns (header included): CourseID, Course Name, # of credits

You should assume that all courses will be delivered with structure like this:

Where “ACCT 626” is the CourseID, “Data Analytics in Accounting” is the course name, and “1.5” is the # of credits. If the course encountered does NOT have this structure, ignore it. (Note that the course # if the course ID can have letters in it as well, e.g., “ACCT 645D1”).

Submission Instructions

Your MyCourses submission must be a single zip file entiled HW7_&lt;studentid&gt;.zip. It should contain the following items:

– scripts/ o collect_relationships.py – script for Task 1 o scrape_courses.py – script for Task 2
