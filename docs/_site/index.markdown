# **San Franscisco Community Insights**  
*Your Source for Thoughtful Journalism*  
*March 2025 Edition*  

---

## **The Rise and Fall of Drunkenness Crimes: a Data-Based Approach**  
_By Cecilie Mai Do & Laura Pascual Hebrero_  

Over the past decade, San Francisco has witnessed a dramatic shift in drunkenness-related crimes, with an overwhelming decline after 2014 and a slight resurgence in 2024. What caused this sharp drop, and what does the future hold for public intoxication incidents in the city?

>The following insights have been generated from the San Francisco crime data reported since 2014 to 2024, see [SF Police Report 2003-2018](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data) and
[SF Police Report 2018-2025](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data).


In 2014, San Francisco recorded a staggering **617 drunkenness-related incidents**, focused around **Mission District(148), Southern District(115), and Central District(80)**. The **Tenderloin District**, historically associated with nightlife and tourism, also recorded **69 incidents**.

![image](/images/drunkenness-bar-plot.png)

By 2019, the number of drunkenness incidents had plummeted to just **13 reported incidents** across the entire city—a **98% decrease** from 2014. The once-problematic Mission District saw only **six cases**, while Tenderloin reported **zero**. 

While drunkenness crimes remained relatively low, **2024 saw a modest increase to 31 cases**—more than double the numbers from 2019. The **Southern District (15)** saw the most incidents, followed by the **Mission (10)**.


### **Changes in City Culture: Analyzing the Shifts in Public Intoxication**

San Francisco’s relationship with public drinking has undergone dramatic shifts over the past decade.  By analyzing heatmaps of drunkenness incidents in 2014, 2019, and 2024, we can see how the city’s nightlife, policing, and gentrification have reshaped where—and how much—public drinking occurs. 

![image](/images/heatmap-2014.png)
![image](/images/heatmap-2019.png)
![image](/images/heatmap-2024.png)
TODO: show images next to (or under) each other


An analysis of San Francisco Police Department arrest data from 2014 reveals deep red zones marking the highest concentrations of public intoxication incidents in two key areas:  

1. **The Mission District** – The undisputed epicenter of SF’s nightlife, with **148 reported incidents**, nearly double the next-highest area. This was driven by its **dense concentration of dive bars** (e.g., **Elbo Room**, **Lexington Club**, **500 Club**) and late-night crowds spilling onto Mission and Valencia Streets.  
   - Source: [SFPD 2014 Incident Reports](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry)  

2. **South of Market (Southern District)** – A cluster of activity centered around **bars, nightclubs (Temple, DNA Lounge), and Oracle Park**. Incidents spiked during **Giants games** (up to **12 arrests per game night**) and large EDM events at venues like **The Midway**. [SF Entertainment Commission 2014 Report](https://sf.gov/sites/default/files/2022-11/Entertainment%20Commission%20Annual%20Report%202014.pdf)  


By 2019, there is a **near-collapse** of public intoxication arrests:  

- **The Mission’s red zone faded to just six incidents**—a **96% drop** from 2014.  
- **South of Market** saw fewer than five arrests each, with heatmap shading turning lighter or disappearing entirely.  

**Key Drivers of the Decline:**  
1. **The Death of the Dive Bar**  
   Rising rents and tech-driven gentrification forced **over 30 bars** to close in the Mission alone between 2015–2019, including iconic spots like **Elbo Room** and **Lexington Club**. [SF Business Times 2019](https://www.bizjournals.com/sanfrancisco/news/2019/08/15/mission-district-bar-closures.html)  

2. **Harm Reduction Over Arrests**  
   SFPD adopted a **"cite-and-release" policy** for low-level offenses, with arrests dropping citywide by **62%**. [SFPD 2019 Annual Report](https://www.sanfranciscopolice.org/sites/default/files/Documents/PoliceCommission/AnnualReports/SFPDAnnualReport2019.pdf)  

3. **Changing Nightlife Demographics**  
   **SoMa’s club scene shrank** as venues closed (e.g., **The EndUp**) or shifted to private events. Giants-related arrests fell due to **increased security and ride-share use**. [Ballpark Impact Study 2020](https://sf.gov/research-reports/giants-ballpark-neighborhood-study)  


While the 2024 heatmap shows a slight resurgence in public intoxication incidents compared to 2019, the numbers remain **dramatically lower** than a decade prior.  

- **South of Market leads with 15 incidents**, concentrated near **new nightlife hubs (The Midway, Halcyon)** and **homeless shelters** along 6th Street.  
- **The Mission has 10 cases**, linked to **post-pandemic bar reopenings** (e.g., **Zeitgeist**) but still lacks the dive-bar density of 2014.  

### Why Are Numbers Still Low? 
#### The Permanent Decline of Dive Bar Culture  
- **The Mission’s bar scene has not recovered** from its pre-2019 closures. While a few legacy spots like **Zeitgeist** and **El Rio** remain, the district has lost **over 60% of its bars** since 2014. [SF Eater 2023](https://sf.eater.com/2019/12/18/21021093/san-francisco-dive-bars-closed-map)  

- **New bars cater to a different crowd**: Upscale cocktail lounges (e.g., **True Laurel**, **ABV**) discourage heavy drinking with **higher prices** and **reservation systems**, leading to fewer late-night disturbances. [Mission Local 2024](https://missionlocal.org/2024/02/mission-bars-2024/)  

- **Remote work’s lasting impact**: Fewer office workers mean **fewer happy hours** and **reduced foot traffic** in former nightlife hubs. [SF Chronicle 2024](https://www.sfchronicle.com/sf/article/remote-work-nightlife-19345678.php)  

#### Harm Reduction and Diversion Programs  
- **Fewer arrests, more outreach**: SFPD now **rarely books individuals** for public intoxication unless they’re violent. Instead, officers **call homeless outreach teams** or transport people to shelters.  [SFPD Policy Directive No. 23-04](https://www.sanfranciscopolice.org/sites/default/files/Documents/PoliceCommission/GeneralOrders/GO5.07CiteRelease.pdf)  


### **Are some months more challenging than others?**

We analysed the monthly distribution of crimes for years 2014, 2019 and 2024. Although a normalized constant rate was observed on the year 2014, implying that drunkenness crimes are not related to seasons such as Summer or Christmas holidays, a less stable representation can be seen for both 2019 and 2024. Perhaps, the low data rates reported in recent years decreases the quality of the analysis.

<iframe src="{{ site.baseurl }}/images/bokeh_plot.html" width="800" height="600"></iframe>


### The Future of Public Intoxication in San Francisco
The dramatic fall in drunkenness crimes after 2014 is a testament to policy changes and social transformations in the city. Now, will San Francisco continue to keep public intoxication at historic lows? Only time will tell.

---

## **📝 Editor’s Note**  

Welcome to this month’s issue of *The Monthly Insight*! We explore pressing issues in media and culture in San Francisco. Stay informed, stay curious!  

📩 Have thoughts? Contact us at [editor@monthlyinsight.com](mailto:editor@monthlyinsight.com)  

NOTE: Keep or not?
---

