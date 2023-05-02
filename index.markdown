---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Startup Environment in US
authors:
  - Helene Hjort, s194665
  - Kathrine Sofie Rasmussen, s194654
  - Sascha Thorsgaard Jacobsen, s171281
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
The startup ecosystem is rapidly growing worldwide, and many countries are becoming hotspots for new businesses and innovation. Every year, about 305 million startups are created [[1]](https://websitebuilder.org/blog/how-many-startups-are-there/){:target="_blank"}{:rel="noopener noreferrer"} , and according to 2019 statistics, about 90% of these startups fail [[2]](https://www.demandsage.com/startup-statistics/){:target="_blank"}{:rel="noopener noreferrer"}. As seen below, the US has the highest number of startups; why, the US cities are the focus of this article.
<figure>
    <embed
        type="text/html" 
        src="/plot/country.html"
        width="900"
        height="500"
    />
    <figcaption>Fig 1: Hover over the map to see the number of startups per country. </figcaption>
</figure>
Did you know that statistics show 3 million new jobs were created in The United States, through less than one year old businesses, from March 1994 to March 2021? This means that during the Internet-driven boom from 1990 to 2000, startup firms accounted for about 70% of all new jobs in the US economy [[3]](https://www.statista.com/statistics/235515/jobs-created-by-start-ups-in-the-us/#statisticContainer){:target="_blank"}{:rel="noopener noreferrer"}. The data for this article also shows a growing trend of startups in the US over the years.

<figure>
    <embed
       type="text/html" 
       src="/plot/year_count.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 2: There is a growing trend in startup companies.</figcaption>
</figure>
Although there is an increase in new business startups, not all of them survive. 80% of all startups in the US fail, with health tech and e-commerce being some of the most challenging industries to succeed in [[4]](https://www.demandsage.com/startup-failure-rate/){:target="_blank"}{:rel="noopener noreferrer"}. This article mainly looks at companies that are still operating, as the data used have a distribution where 86.5% of companies are operating.  
<figure>
    <embed
       type="text/html" 
       src="/plot/circle.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 3: This article mainly focus on companies that are still operate.</figcaption>
</figure>
Startups are an interesting area to look into, as they are a big part of the business market. The startup companies create new jobs and contribute to economic growth and local communities development. Overall, the relationship between startups and cities is complex and multifaceted. Startups have the potential to drive economic growth, create jobs, and transform industries, but the question remains, is it the city that gives birth to startups, or do startups move to the city? And can we find the explanation of which factors the company's success depends on?

This article will explore these questions by analyzing educational background data, location, founding dates, investments, and more. Using data analysis and visualization, we will investigate the factors contributing to startup growth and success in cities. Our dataset comes from various sources, including US public data[[5]](https://datausa.io/){:target="_blank"}{:rel="noopener noreferrer"}, background information about founders, localization, venture capital investments, etc [[6]](https://www.kaggle.com/datasets/justinas/startup-investments?select=funds.csv){:target="_blank"}{:rel="noopener noreferrer"}. By the end of this article, we hope to provide readers with a deeper understanding of the startup ecosystem in cities and unveil the patterns and possibilities within.

# General trends across US
Looking at a map showing the location of startups across the US, you see that California and New York are two of the biggest states for startup companies in the US. California, in particular, stands out as the epicenter of the startup industry.   
<figure>
    <embed
       type="text/html" 
       src="/plot/cities.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 4: Hover over the map to see the number of startups per state in US.</figcaption>
</figure>
The nature of startup companies can vary significantly from state to state. For example, California has a high concentration of tech, biotech and enterprise startups. On the other hand, there are a few companies in these fields in New York, but there is a higher concentration of startups in e-commerce and advertising. This already shows that there are differences based on location and startup natures. States like California and New York tend to have a higher concentration of startups. And as a new founder, there may be advantages to researching the type of environment in a city before deciding where to start your business.
<figure>
    <embed
       type="text/html" 
       src="/plot/CategoryStartups.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 5: Tech is the biggest industry within the startup environment. Click states on and off to get the desired view.</figcaption>
</figure>
As a general trend big cities attract a greater number of startups. This is evident from the fact that the top ten cities for startup locations in the US are predominantly some of the largest cities in their state. Big cities do have special advantages as there are more opportunities than smaller cities. For example when it comes to expanding your network, the bigger the city, the better the chance of a greater network. Which can be vital for the survival of a startup, as it was said by Diana Helbig president of Helbig Enterprises “Networking is an investment in your business. It takes time and when done correctly can yield great results for years to come." [[7]](https://blog.hubspot.com/marketing/networking-quotes){:target="_blank"}{:rel="noopener noreferrer"} 
Taking a closer look the majority of the cities are from the two coastal states, California and New York. In California  there are two primary hubs of activity: Silicon Valley (San Francisco) and Los Angeles. These regions are known for being home to many new and innovative companies driving the state's economy and shaping the future of technology and business. These areas are also characterized by a dense concentration of venture capital firms, incubators, and accelerators providing the resources and support startups need to grow and thrive. 

<figure>
    <embed
       type="text/html" 
       src="/plot/cities2.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 6: New York City and San Francisco are market leaders. </figcaption>
</figure>

The support can be very different deeping on the industries your startup operates in. For example if a startup working with developing medical equipment is compared with a consultancy startup. The medicine startup may need money for equipment, knowledge or legal advice, whereas the consultancy may only need startup capital for office spaces or recruitment. The map below shows the exact locations of the companies' offices and the industries they operate in. The two hubs in Los Angeles and San Francisco are clearly shown. Silicon Valley in San Fransico is the birthplace of many of the world's most successful tech companies, including Apple, Google, and Facebook. Los Angeles, located in southern California, is known for having its unique startup ecosystem focused on entertainment, media, and e-commerce. In addition, the map highlights many companies in the field of biotech. Interesting enough, the map highlights a larger field of biotech companies. California has in the latest couple of years grown more into biotech, which already is represented at the map." [[8]](https://www.fiercebiotech.com/special-reports/top-biotech-hubs){:target="_blank"}{:rel="noopener noreferrer"}
 

<figure>
    <embed
       type="text/html" 
       src="/plot/CA.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 7: Companies and their branches in California. Hover over the map to see the specific company.</figcaption>
</figure>
If you look at industries in New York, it is unsurprising that the biggest hub is New York City (NYC). NYC is internationally known for its diversity and high paced business environment, where finance and management consulting are buzzwords. Many of the world's largest companies are located in this city including McKinsey & Company, Chartis Group, Bain & Company, Pfizer, and Goldman Sachs [[9]](https://www.consultancy.uk/news/13677/the-top-10-management-consulting-firms-to-work-for-in-new-york){:target="_blank"}{:rel="noopener noreferrer"}. Not all of these firms were founded in NYC, but the fact that they are present in the city is among the factors that attract startups, and as it can be seen from the map, especially startups working with consulting and  e-commerece are present in NY. Beyond consulting, NYC also has tech startups, with companies such as IBM, Etsy and E*Trade all founded in NYC [[10]](https://theculturetrip.com/north-america/usa/new-york/new-york-city/articles/the-history-of-new-yorks-silicon-alley/){:target="_blank"}{:rel="noopener noreferrer"}. It also a trend that is represented in the map where startups within software and video games are also some of the more common industries. 
<figure>
    <embed
       type="text/html" 
       src="/plot/NY.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 8: Companies and their branches in New York. Hover over the map to see the specific company.</figcaption>
</figure>
Overall, the hubs from both states show a diversity that supports the previously mentioned reasons for locating in large cities, as well as cities with an environment within one's industry. Startups unfortunately cannot survive on good ideas alone, often a significant amount of funding is also needed.

# The Need for Funding
Funding, and money in general can be hard to come by, and lack of it is one of the biggest reasons startups fail. [[11]](https://www.investopedia.com/articles/personal-finance/040915/how-many-startups-fail-and-why.asp){:target="_blank"}{:rel="noopener noreferrer"}. So where have the startups portrayed in this article acquired their funding? The map below portrays where and how much funding startups have received in the period from 1998 to 2013.
<figure>
    <embed
       type="text/html" 
       src="/plot/heatmap.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 9: Heatmap of the amount of funding a company has received between 1998 and 2013. Click play to play the time series or use the slider.</figcaption>
</figure>
The funding is not surprisingly following the same trends as the location for startups, and are centered around the big city areas. The distribution of funding has, however, changed over the years especially across the middle states where the amount of funding differs a lot. Still, big hubs around the coastal cities are apparent throughout all years. But why are the places for funding so stationary over time? Logically if you are looking for funding, you will also go to a place where you have an idea that money circulates. To investigate this theory data from DATA USA [[12]](https://datausa.io/){:target="_blank"}{:rel="noopener noreferrer"} is incorporated to compare the funding locations with the average wages on state level in 2013. The distribution can be seen from the map below. Looking at the average wage by state, it can be seen that the coastal states do have a high average, and that in general the states with high wages correspond to the areas with high amounts of funding. On that basis it seems reasonable to assume that the higher the state's average wage, the stronger the possibility of finding a company or private investor to provide funding.

<figure>
    <embed
       type="text/html" 
       src="/plot/wage.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 10: Average wage per state.</figcaption>
</figure>
Develing into the specific funding made comparing the two familiar states of CA and NY against all other states the following time series is depicted. The largest spike in investment is in mid-2008, which is somewhat unexpected as the financial crisis occured that same year. Upon closer examination it was discovered that the investments responsible for the spike was made in the company 'Clearwire' the day before the announcement of a big merger between them and 'Sprint Nextel’ [[13]](https://en.wikipedia.org/wiki/Clearwire){:target="_blank"}{:rel="noopener noreferrer"}. A guess is that the investment can be attributed to Sprint Nextel's investment in the company. The following years we continue to see some significant surges in investment despite a general low market the years after the crisis. There is a possibility that this can be attributed to large players making investments when the market is low, thereby taking advantage of the low valuations. Investigating the spikes support this as the investments in 2010 and in 2011 can be attributed to big investments in Tesla, AOL, Facebook, Wave Broadband, and Clearwire. All firms that when valued high boost investment values. In general, the plot is a good indicator for how much money flows through startups, underlining the importance of startups for economic growth in a country. So now the big question is, besides timing in terms of the market, crisis, and other external factors, are there periods in a year when a company should use more time in promoting and seeking investments?
<figure>
    <embed
       type="text/html" 
       src="/plot/funds.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 11: There are many clear spikes in the amount of funding over the years, indicating specific events that are happening.</figcaption>
</figure>
On average, the month with the most investments for both locations is September, the last month in the third quarter. The lowest funding months for CA are November and December during the final quarter of the year, where NY experiences their lowest funding months in February and August. For NY, those months could be lower, due to timing, as these months are typically used for major public holidays. It could also be that due to investor fatigue, as January is a high investment month, causing a low February. The reasons for lower investments in the final quarter could be connected to the fiscal year, meaning that the budget is being consolidated at the end of the year, downscaling investments. The opposite is the case for the beginning of the year, when all budgets have been finalized, potentially making room for new investments. Some studies have suggested that there is a "January effect" for startup funding, with a higher proportion of funding deals occurring in the first month of the year. This may be due to a variety of factors, including the fact that many investors may be more focused on new opportunities at the start of a new year, and may also have more capital available to invest after the end-of-year holiday season [[14]](https://www.investopedia.com/terms/j/januaryeffect.asp){:target="_blank"}{:rel="noopener noreferrer"}. 

Regarding the day of the week, it is expected that there are more investments on weekdays. Friday has the highest number for both states, which can be attributed to it being the last day of the work week, and there may be a lot of approvals before the weekend. In CA, Tuesday rivals Friday, whereas in NY, it is Monday and Wednesday. This may point towards different working styles in the two states. Overall, you should expect the funding to go through during the week, as opposed to the weekend.

<figure>
    <embed
       type="text/html" 
       src="/plot/month_week.html"
       width="900"
       height="500"
/>  
    <figcaption>Fig 12: Click on month and weeks respectively to get an overview of the amount of fundings broken down by these for CA and NY.</figcaption>
</figure>
There are indications that suggest that certain months and weekdays may be more popular for fundings in the US, although it's important to note that there are many factors that can influence funding trends, and these may vary depending on the industry, the size of the company, and other factors. At this point, we have covered many topics related to startups, but a big part of any startup is also the people behind it. Therefore the next section will look at the founders and their educational background.

# Founders and Their Educational Background
Is education an instrumental factor in a startup's success? The plot below shows the level over degree distributed over the startup employees. The plot shows that the majority of the managing director and the founders have an MBA. In contrast, the majority with a Ph.D. is in the board. Employees with a bachelor's degree in science are as expected the software engineers. The bachelor of art is the education with the highest degree of diversity across job positions, which makes sense as the topic within the education type is wide-ranging. Overall the plot shows a good mix of education and a tendency for the top management to have a business degree (MBA). The question is if it matters where the education is taken or if any educational institutions are the best at opening the door to the startup world?
<figure>
    <embed
       type="text/html" 
       src="/plot/e_level.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 13: Most people have a Bachelor of Arts, Bachelor of Science, and a MBA .</figcaption>
</figure>
The following figure shows an overview of which educational institutions are the most widely attended by the startups' employees. Stanford University is the most attended school, also by people from startups located in other cities, showing that this is a widely preferred university. It is actually a statistical fact that the majority of entrepreneurs in the US are graduates from Stanford University [[15]](https://www.demandsage.com/startup-statistics/){:target="_blank"}{:rel="noopener noreferrer"}. The university closely following Standard in attendance is Havard University and Berkley. Interestingly the number of Harvard attendance from CA is almost identical to the number from NY. Showing that People start businesses in different cities than where their education is from, which may mean that the choice of the city has an influence when starting a business. The overall trend is that the educational background is within an Ivy League school. This shows a correlation between starting a business and having an Ivy League education. This may be because there is a greater focus on entrepreneurship, networking and a better financial background.
<figure>
    <embed
       type="text/html" 
       src="/plot/FoundersUni.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 14: People involved in startups typically have a high-level degree from an Ivy League university.</figcaption>
</figure>
Furthermore, there is a strong correlation between the type of enterprise and the type of education people have. Most people have a background in computer science, which makes sense as most companies nowadays need knowledge of online products such as websites and apps. 
<figure>
    <embed
       type="text/html" 
       src="/plot/e_level_category.html"
       width="900"
       height="600"
/>  
    <figcaption>Fig 15: There is a strong correlation between the type of enterprise and the type of education.</figcaption>
</figure>

In conclusion, education can be a significant factor in a startup's success, particularly in top management positions, where having a business degree, such as an MBA, is common. Furthermore, the educational institution from which one graduates plays a role in the startup world. Overall, the plot and figure illustrate the importance of education and its potential impact on the success of startups.

# Is it Possible to Crack the Startup Code?
Is it the city that gives birth to startups, or do startups move to the city? And can we find the explanation of which factors the company's success depends on? The startup landscape is of a complex size. No size fits all, and there is no recipe for a successful startup. However, big cities attract more startups due to the availability of more opportunities, resources, and a larger network. Furthermore, startups often bring new technologies and innovative solutions to existing problems, which can benefit the wider community. California and New York are the primary hubs of startup activity, with Silicon Valley and Los Angeles being the most significant in California. 
The startup ecosystem in a city is complex, and the relationship between startups and cities is multifaceted. The nature of startup companies can vary significantly based on location, such as in Silicon Valley, where tech startups take up the majority. Therefore, new founders can reach advantages if they research the type of environment in a city before deciding where to start their business, as this can impact future success. Summing up, it was not found with certainty whether the city gives birth to startups or if startups move to the city, but your chance of success is better in a big city and with an education, as both expand your options. 