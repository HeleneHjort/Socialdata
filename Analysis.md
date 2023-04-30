---
layout: page
title: Startup Environment in US
permalink: /Analysis/
---

<style>
    body {
        font-family: Arial, sans-serif;
    }
    h1 {
        font-family: Arial, sans-serif;
       }
    h2 {
        font-family: Arial, sans-serif;
       }
    figcaption {
        font-size: 1.2em;
        font-style: Arial, sans-serif;
    }
</style>



# Introduction 
The startup ecosystem is rapidly growing worldwide, and many countries are becoming hotspots for new businesses and innovation. Every year, about 305 million startups are created, and according to 2019 statistics, about 90% of these startups fail [[1]](https://websitebuilder.org/blog/how-many-startups-are-there/){:target="_blank"}{:rel="noopener noreferrer"} [[2]](https://www.demandsage.com/startup-statistics/){:target="_blank"}{:rel="noopener noreferrer"}. As seen below, the US has the highest number of startups; therefore, the US cities are the focus of this article. 
<figure>
    <embed
        type="text/html" 
        src="/plot/country.html"
        width="900"
        height="500"
    />
    <figcaption>Fig 1: Hover over the map to see the number of startups per country. </figcaption>
</figure>
Did you know that statistics show 3 million new jobs were created in the United States through less than one year old businesses from March 1994 to March 2021? This means that during the Internet-driven boom from 1990 to 2000, startup firms accounted for about 70% of all new jobs in the US economy [[3]](https://www.statista.com/statistics/235515/jobs-created-by-start-ups-in-the-us/#statisticContainer){:target="_blank"}{:rel="noopener noreferrer"}. The data for this article also shows a growing trend of startups in the US over the years. 
<figure>
    <embed
       type="text/html" 
       src="/plot/year_count.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 2: There is a growing trend in startup companies.</figcaption>
</figure>
Although there is an increase in new business startups, not all of them survive. 80% of all startups in the US fail, with health tech and e-commerce being some of the most challenging industries to succeed in [[4]](https://www.demandsage.com/startup-failure-rate/){:target="_blank"}{:rel="noopener noreferrer"}. This article mainly looks at companies that are still open, as 86.5% of companies are operating. 
<figure>
    <embed
       type="text/html" 
       src="/plot/circle.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 3: This article focuses mainly on companies that still operate.</figcaption>
</figure>
Startup companies create new jobs and economic growth and contribute to local communities development. Overall, the relationship between startups and cities is complex and multifaceted. Startups have the potential to drive economic growth, create jobs, and transform industries, but the question remains, is it the city that gives birth to startups, or do startups move to the city? And can we find the explanation of which factors the company's success depends on?

This article will explore this by analyzing educational background data, location, founding dates, investments, and more. Using data analysis and visualization, we will investigate the factors contributing to startup growth and success in cities. Our dataset comes from various sources, including US public data, background information about founders, placement, venture capital investments, etc. By the end of this article, we hope to provide readers with a deeper understanding of the startup ecosystem in cities and unveil the patterns and possibilities within.

# General trends across US
Looking at a map showing the location of startups across the US, you see that California and New York are two of the biggest states for startup companies in the US. California, in particular, stands out as the epicenter of the startup world. 

<figure>
    <embed
       type="text/html" 
       src="/plot/cities.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 4: Hover over the map to see the number of startups per state in US.</figcaption>
</figure>
The type of startup companies can vary significantly from state to state. For example, California has a high concentration of tech, biotech and enterprise startups. On the other hand, there are few companies in these fields in New York, but there is a higher concentration of startups in ecommerce and advertising. This already shows that there are differences between states and startups. States like California and New York tend to have a higher concentration of startups. And as a new founder, there may be advantages to researching the type of environment in a city before deciding where to start your business.
<figure>
    <embed
       type="text/html" 
       src="/plot/CategoryStartups.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 5: Tech is the biggest industry within the startup environment.</figcaption>
</figure>
In general big cities in the states also tend to be the place to go. The majority of the top cities are from the two coastal states, California and New York. There are two primary hubs of activity in California: Silicon Valley and Los Angeles. These regions are known for being home to many new and innovative companies driving the state's economy and shaping the future of technology and business. These areas are also characterized by a dense concentration of venture capital firms, incubators, and accelerators providing the resources and support startups need to grow and thrive.
<figure>
    <embed
       type="text/html" 
       src="/plot/cities2.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 6: New York City and San Francisco are market leaders.</figcaption>
</figure>

The map below shows the exact locations of the companies' offices and the industries they operate in. The two hubs in Los Angeles and San Francisco are clearly shown. Silicon Valley in San Fransico is the birthplace of many of the world's most successful tech companies, including Apple, Google, and Facebook. Los Angeles, located in southern California, is known for having its unique startup ecosystem focused on entertainment, media, and e-commerce. In addition, the map highlights many companies in the field of biotech.  

<figure>
    <embed
       type="text/html" 
       src="/plot/CA.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 7: Companies and their branches in California.</figcaption>
</figure>
If you look at New York, it is unsurprising that the biggest hub is in New York City. NYC is characterised by its vibrant city life, diversity and business. Finance and management consulting are buzzwords for NYC, and many of the world's largest companies call the city home. McKinsey & Company, Chartis Group and Bain & Company are among these firms [[5]](https://www.consultancy.uk/news/13677/the-top-10-management-consulting-firms-to-work-for-in-new-york){:target="_blank"}{:rel="noopener noreferrer"}. Not all firms were founded in NYC, but their city location is among the factors attracting start-up consultancies. Beyond consulting, NYC also rivals San Francisco regarding tech start-ups, with companies such as IBM, Etsy and E*Trade all born in NYC [[6]](https://theculturetrip.com/north-america/usa/new-york/new-york-city/articles/the-history-of-new-yorks-silicon-alley/){:target="_blank"}{:rel="noopener noreferrer"}. Pfizer and Goldman Sachs are other examples of companies founded in NYC. The city continues attracting bright minds, with new companies popping up daily in a wide range of sectors, as seen in the NYC companies map.
<figure>
    <embed
       type="text/html" 
       src="/plot/NY.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 8: Companies and their branches in New York.</figcaption>
</figure>

# Starting a Business is Expensive
There are many advantages of having offices in the city. The possibilities are plentiful, and the entrepreneurial environment is more established and dynamic. Deepening on the startup's size, there is also a bigger pool of talent to recruit from. The networking opportunities a more frequent, with elegant events every weekend and conferences every week with the possibility for learning and sparing with bright heads within a given industry. The list goes on with easy access to funding and higher visibility. Looking at the average wage by state, there may be a reason that coast states and cities are hubs for startups. It turns out that the popular states and cities for startups are also states with a high average wage.
<figure>
    <embed
       type="text/html" 
       src="/plot/wage.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 9: Average wage per state.</figcaption>
</figure>
It seems reasonable to assume that the higher the state's average wage, the stronger the possibility of finding someone in the city with deep pockets to help you along your startup journey. Looking at the distribution of funding, the assumption is correct. 
<figure>
    <embed
       type="text/html" 
       src="/plot/heatmap.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 10: Heatmap of the amount of funding a company has received between 1998 and 2013.</figcaption>
</figure>
Funding is centered around the big city areas and distributed in many States with a high average wage. Additionally, large cities are often hubs for specialized industries, as we saw at the beginning of the article. The distribution of funding has changed over the years, and there are significant differences across the middle states. Still, big hubs around the coast cities are apparent throughout all years. Diving into these coast states, the familiar NY and CA, the founding amount over the years can be seen below. 
<figure>
    <embed
       type="text/html" 
       src="/plot/funds.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 11: There are many clear spikes in the amount of funding over the years, indicating specific events that are happening.</figcaption>
</figure>
The largest spike, seen in mid-2008, is investments made in the company 'Clearwire' the day before the announcement of a big merger between the company and 'Sprint Nextel [[7]](https://en.wikipedia.org/wiki/Clearwire){:target="_blank"}{:rel="noopener noreferrer"}. A guess as to why the investment size is so significant is Sprint Nextel's investment in the company. In general, all spikes show a significant amount of money and how much money flows in startups daily, underlining the importance of startups for economic growth in a country. Funnily enough, there were also some spikes in 2010 and 2011, despite only a few short years after the financial crisis in 2008. But the standard advice is to buy when the market is down, and someone seems to have taken that seriously, keeping the internet boom alive with big investments in Tesla, AOL, Facebook, Wave Broadband, and Clearwire. So now the big question is, besides timing in terms of the market, crisis, and other external factors, are there periods in a year when a company should invest more time in promoting and seeking investments? 
<figure>
    <embed
       type="text/html" 
       src="/plot/month_week.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 12: Click on month and weeks respectively to get an overview of the amount of fundings broken down by these for CA and NY.</figcaption>
</figure>
There are no clear trends across months. There is not any season that is more popular than others. However, January has the most investment, indicating that budget years and deadlines have a say in when investment occurs. In terms of weekdays, there is no apparent reason as to why, but Tuesday is the most popular day, so if you waiting on the final found approval or transfer, it is recommended that you put your money on Tuesdays. But it would be even wiser to put your money into education because there seems to be some correlation between startup founders and education. 

# Founders and Their Background
 It is clear from the data that most founders have an education, but not just any. The same universities appear again and again. But which educational institutions are the best at opening the door to the startup world?
<figure>
    <embed
       type="text/html" 
       src="/plot/FoundersUni.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 13: People involved in startups typically have a high-level degree from an Ivy League university.</figcaption>
</figure>
Common for startup employees is an educational background within an Ivy League school. The state of New York and its surrounding cities are over-represented in the number of universities. In contrast, the number of degrees awarded by universities in California is the highest. For both CA and NY, we see that the roots are torn up or moved, but the exciting find is Harvard Business School, where the normalized count is almost identical for the two states. It is no surprise that Stanford is the institution from which most startups are hatched. It is a statistical fact that the majority of entrepreneurs in the US are graduates of Stanford University [[8]](https://www.demandsage.com/startup-statistics/){:target="_blank"}{:rel="noopener noreferrer"} . Is it, therefore, a requirement to be well-educated to enter the startup scene?
<figure>
    <embed
       type="text/html" 
       src="/plot/e_level.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 14: Most people have a Bachelor of Arts og Bachelor of Science, not everyone takes a Master's degree.</figcaption>
</figure>

As a founder, the answer must be no. It can be seen that most founders have only a bachelor's degree. To be a founder, you don't necessarily need a Ph.D. in finance but rather a good idea and the right competencies in the area the idea spans. As the company grows, hiring different people with different backgrounds can be advantageous. For example, it is seen that more Directors and CEOs have an MBA education, which is consistent with their role in the companies. 
# Conclusion 
