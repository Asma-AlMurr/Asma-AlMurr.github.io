---
title: "Assignment 2"
last_modified_at: 2025-02-03
categories:
  - Blog
tags:
  - Assignments
---

# Analyzing Exports in the Zanzibar Gazette 1919

-  [Link to Google Sheets Data Set](https://docs.google.com/spreadsheets/d/1jeGCwgaVEl6kIYqp_drMBUdYMZfKW62KINJNu6e3ONM/edit?usp=sharing)
-  [Link to Assignment planning document](https://docs.google.com/document/d/1_oL0zZSKZlHh7l9-Oi7sSMXpzjcFw_mbSzRjmW_f3As/edit?usp=sharing)
-  Note: My data set is also available in my assets folder!


## Introduction

Zanzibar, a small yet historically significant island off the coast of East Africa, played a central role in global trade during the early 20th century. In September 1919, the Zanzibar Gazette documented the island's bustling export economy, which included valuable commodities like spices, ivory, and animal products. This essay takes a closer look at these export activities, examining not only the economic impact of these goods but also how modern technology, like AI tools such as ChatGPT and Gemini, can help us uncover insights from historical data. By exploring the challenges and successes of using AI to analyze such a complex dataset, this project aims to shed light on how Zanzibar's exports shaped global markets—and how the intersection of history and technology can offer a new perspective on the past.

## Why I Chose This Document (Exports September 1919)

The Zanzibar Gazette is a historical newspaper that documents the trade and export activities of Zanzibar. It serves as an official record of commercial, social, and political events, particularly related to Zanzibar’s role as a significant export hub. The table  I used consisted of 111 rows of merchendise data. This type of source is primary, offering a firsthand account into the economic landscape of the time. I chose the export data from September 1919 for its rich historical value and a insight to Zanzibar's role in the spice and ivory trade. It also includes information about the geographical locations associated with exports. The data reflects the economic activity of the period, detailing specific products, quantities, and possibly trade partners or destinations. By focusing on this particular issue, I aimed to explore the breadth of Zanzibar's export commodities and their significance in the context of global trade during the early 20th century. Zanzibar's strategic position in the Indian Ocean and its established trade routes with Europe, Asia, and Africa made it a vital node in the global market. Analyzing the data from the Gazette offers a detailed view of how Zanzibar interacted with these regions, providing insights into the commodities that shaped the island’s economy and its global connections.

![gazt1](/assets/images/gazt1.jpg)
![gazt2](/assets/images/gazt2.jpg)



## The Table: Organizing the Data

The table I created from the Zanzibar Gazette data is the backbone of this analysis. It organizes various export details, including merchandise categories, export destinations, weight, number of packages, and value in Zanzibar Rupees (1919). The data was indirectly communicated. The Zanzibar Gazette lists various merchandise, but there were often gaps in the data or a need to infer relationships between items and trade activities. For example, I had to create new columns such as product categories, USD price conversions, export importance, and geographical locations based on context clues from the original text. This involved assuming certain connections, like grouping related products (e.g., food items or animal products) and identifying likely export routes based on historical context. I found it easier to categorize each entry by export importance and include historical tags. For example, items like ivory and rhino horns are classified as "Luxury Commodities," while items like copra and coconuts are listed under "Tropical Commodities."

This structured table not only serves as a historical record but also enables deeper analysis by allowing comparisons between different product categories and their economic significance. The process of organizing this data made it easier to visualize Zanzibar's role in global trade, as the various categories can be analyzed for their economic impact. This also highlights the diversity of Zanzibar’s exports, ranging from luxury items to agricultural products, and their significance in shaping Zanzibar's interactions with other regions.

![my1.jpg](/assets/images/my1.jpg)
![my2.jpg](/assets/images/my2.jpg)

## Article “Provocations from the Humanities for Generative AI Research”

Incorporating the article [*Provocations from the Humanities for Generative AI Research*](https://arxiv.org/abs/2502.19190) into this essay allows me to address the intersection between technology and humanities in historical data analysis. The article critiques the limitations of AI models in generating meaningful insights from historical data. Specifically, the authors highlight that while AI can process large datasets, it often lacks the ability to truly understand the cultural and historical context behind the data it processes.

In my project, AI tools like ChatGPT and Gemini helped automate the extraction of data from the Zanzibar Gazette, but as the article suggests, these tools struggled to interpret the full significance of the data. For instance, while AI models could extract merchandise categories and their values, they couldn't fully account for every single row on the table and started to make up random values. This insight from the article aligns with my experience, where the automation of data extraction provided structure but lacked depth and accuracy in understanding the historical document. The article’s critique underscores the importance of human interpretation when working with AI-generated data.

> **Quote from the Article**:  
> “Models make words, but people make meaning” (Provocations, page 5).  

This quote resonates with my work as it emphasizes that while AI tools can assist in generating data, it is ultimately the researcher who gives that data its meaningful context. In my case, while ChatGPT and Gemini helped process the data, it was up to me to interpret the cultural, economic, and geopolitical significance behind the values and ensure they were accurate.

## Prompt Engineering: Maximizing AI Tool Performance

A key aspect of this project was the process of prompt engineering to improve the effectiveness of the AI tools used in the analysis. Initially, I created simple prompts asking ChatGPT and Gemini to extract and organize the data from the Zanzibar Gazette. However, I quickly encountered challenges such as incomplete extractions and mismatched data. To improve results, I refined my prompts by making them more specific. For example, I instructed Gemini to break the extraction task into parts and process each image separately, which allowed for better results. I also asked ChatGPT to categorize the merchandise by type and assign export importance based on the product’s historical context.

These refinements helped generate more accurate results, but there were still limitations in the AI’s ability to handle complex historical data. Both tools struggled with converting Zanzibar Rupees into modern U.S. Dollars, and the OCR data extraction process was not flawless. This required substantial manual intervention to clean the data and ensure its accuracy. Despite these challenges, the prompt engineering process was crucial in obtaining a usable dataset that could be analyzed further.

> **Quote from the Article**:  
> “LLMs generate text by predicting sequences of words. These predictions are based on both observed patterns and on human preferences and feedback. The result is often output that is factually wrong yet linguistically fluent and seemingly coherent—these are the hallucinations.” (Provocations, page 6).  

This quote is directly applicable to my experience with AI tools. While AI tools like ChatGPT generated fluent and seemingly coherent data, I often had to intervene to correct factual inaccuracies, especially when converting currency or correcting geographical data.

## Automation Performance and Data Cleaning

The automation of data extraction through AI was quite effective but required significant data cleaning to ensure the results were accurate. Both ChatGPT and Gemini struggled with the quality of the original scanned images from the Zanzibar Gazette. In particular, the OCR process often misread numerical data, leading to errors in the extracted tables. After using Gemini and ChatGPT to generate initial datasets, I had to manually verify and correct the data, particularly the merchandise values and shipping regions.

Despite these challenges, the AI tools provided a good starting point by organizing the data and identifying key merchandise categories. The main task was to ensure the accuracy of the numerical values, product names, and geographical information, which involved cross-referencing the AI outputs with the original images from the Gazette. This manual cleaning process was time-consuming but necessary to ensure the dataset’s reliability for further analysis.

### ChatGPT Performance Analysis

> **Prompt 1**: "Turn these images of exports from the Zanzibar Gazette into a visual table"  
*Only did 16 rows*

![chattable1.jpg](/assets/images/chattable1.jpg)

> **Prompt 2**: "Turn these images of exports from the Zanzibar Gazette into a visual table by extracting all the rows, and including the region it is being exported to, then making it a readable table."  
*Completed 50 first rows*

![chattable2.jpg](/assets/images/chattable2.jpg)

ChatGPT 4.5, the newest beta model available in the paid version, showed good potential in digitizing historical data from the provided Gazette images. It took approximately 4 minutes to process and display the extracted data. The AI accurately captured numerical values and identified merchandise items, which was impressive given the complexity and somewhat compromised quality of the original document. However, there were notable limitations. The first attempt yielded only 16 rows of data, significantly fewer than the total available entries. After requesting a more comprehensive extraction, ChatGPT was able to produce approximately half (around 50 row) of the total dataset. Yet, despite this progress, ChatGPT continued to encounter errors, particularly a "mismatch in the data arrays" that disrupted further extraction. This recurring issue led to a loop of corrections without substantial progress, resulting in the first image being partially processed. As a result, I decided to switch tools and use Gemini to complete the task.

### Gemini Performance Analysis

> **Prompt 1**: "Convert the entire list of exported items from this Gazette into a visual table, including merchandise names, regions exported to, weights, number of packages, and their respective values."  
*Only did first 50 rows*

![gem1.jpg](/assets/images/gem1.jpg)

> **Prompt 2**: "Now combine both of the tables into one big downloadable table"  
*All rows completed and downloaded to sheets*

![gem2.jpg](/assets/images/gem2.jpg)

Gemini, in contrast, provided a much more efficient and accurate experience. It generated the required results within seconds, significantly outperforming ChatGPT in speed and accuracy. I had to break the extraction task into two parts due to Gemini's limitation of analyzing one image at a time. However, Gemini promptly extracted and structured the data from each image independently, identifying the merchandise items, regions, and numerical values with minimal manual intervention. When I instructed Gemini to combine both sets of extracted data into a unified table, it did so smoothly, without encountering the alignment or data mismatch errors that occurred with ChatGPT. Throughout the entire process, Gemini was stable and efficient, requiring fewer corrections and providing a reliable dataset for further analysis. Its ability to interpret OCR data and transform it into a structured table made Gemini the preferred tool for completing the task.

### Data Cleaning and Manual Intervention

Cleaning the dataset after OCR extraction required substantial manual effort due to inconsistencies and inaccuracies in the blurred text from the historical Gazette. I had to manually correct mismatched data, such as redundant or incorrect merchandise entries that resulted in discrepancies between the AI output and the actual dataset. Additionally, numerical values, package counts, and region coordinates needed verification against the original Gazette images. I carefully inserted missing or ambiguous data points where the OCR process fell short. This meticulous process ensured the dataset's accuracy, allowing for a precise and reliable visualization of the historical export data. This cleaning was crucial for making sure the final dataset was ready for analysis, as both AI tools provided structured outputs but required human intervention to ensure the data's integrity.

This made me think of answering the quote by a former student of Professor Wrisley, because I saw how it tied into my analysis and figured it was an important factor to consider.


>“I find the new models are the best and then they tend to deteriorate or hallucinate more often as they are trained on new noisy data or the engineers stop paying attention to them while they focus on newer versions.” -R.K (former student)

This quote by R.K. highlights an insightful observation about the lifecycle of AI language models. It underscores a common challenge: while newer models initially demonstrate remarkable accuracy and capabilities, there's a risk that their performance may degrade over time due to exposure to noisy or lower-quality data. This phenomenon, often referred to as "model drift," occurs when continual training incorporates inaccuracies or biases from uncontrolled data, causing the model to produce less reliable outputs or to "hallucinate" facts more frequently. Moreover, R.K.’s point also addresses an important aspect of resource allocation in AI development. As engineers shift their attention towards developing the next generation of models, existing ones may receive less rigorous monitoring, tuning, and fine-tuning, further contributing to their decline in reliability. This observation emphasizes the importance of sustained maintenance, rigorous quality control, and periodic retraining using carefully curated datasets to maintain a model's accuracy and reliability over time. It's a valuable reminder that continuous attention, rather than just initial deployment, is crucial for the long-term success and stability of AI systems.

### How I Created My Dataset In Collaboration With The AI Tool:
I used Gemini to visualize the dataset from the Zanzibar Gazette document, as it provided more accurate numerical results compared to other tools. Gemini's table structure helped me create a coherent and organized dataset, serving as a guide for structuring my own. I also utilized Gemini to suggest additional categories for organizing the data, helping ensure that the table captured all relevant details by asking things like... 

>“List ideas on how I can make my dataset more structured and organized” 

or attaching my table and asking...

>“How could I improve this dataset?"
 
 This was essential for making the data both readable and comprehensive. In addition, I sought to improve the presentation of the table by implementing color coding, which I achieved by organizing the merchandise into sections such as "Food Products," "Animal Trade," and "Manufactured Goods." I then assigned specific colors, like red for food items, to visually differentiate between these categories.

ChatGPT was instrumental in refining the dataset further. I asked it to provide historical tags for the merchandise categories and assign an appropriate level of export importance for each item. I got this idea by asking...

>“How can I further structure my categories and add a level of organization to the rows.” 

ChatGPT helped categorize the items by their historical significance, from luxury commodities like ivory and rhino horns to agricultural products like copra and wax. Additionally, I used ChatGPT and Overpass Turbo to geocode potential shipping ports, gardens and farms, focusing on regions such as Africa and India, where Zanzibar likely used ports or farms for exporting goods, then copying the coordinates by hand. This was an essential step to link the merchandise with their most probable export coordinates. I used this information provided by ChatGPT and Overpass Turbo to enrich the dataset.

### Challenges
One of the major challenges I faced was converting the Zanzibar Rupees from 1919 to present-day value in U.S. Dollars. While ChatGPT was not helpful in providing accurate conversions, Gemini proved more effective. I used it to get more reliable and precise values, as the process of converting the historical currency to modern values would have been difficult manually. Both AI tools struggled with extracting information from the Gazette documents, particularly the OCR/ text layer quality of the scanned images. While Gemini performed better than ChatGPT, I still had to manually fix many of the extracted numbers to ensure accuracy. This was a surprising shortcoming, given the tools' advanced capabilities, but it provided valuable insight into the limitations of AI-driven data extraction.

![error.jpg](/assets/images/error.jpg)

## Overpass Turbo and Kepler:
Overpass Turbo was an essential tool for locating key places in the regions with the most dense export data in my project. I used it to find specific locations related to the export data, including terms like...

> "Port," "Farm," and "Garden" 

All these places were focused near Africa, the region with the highest concentration of exports in the dataset. By focusing on these terms, Overpass Turbo helped identify specific geographic areas that were most likely tied to Zanzibar's trade routes during the early 20th century. These locations, while broad in the Gazette, could be pinpointed more precisely with the tool, allowing me to enhance the accuracy of my analysis.

For further visualization, I used Kepler to map the data after converting the Zanzibar Gazette’s export information into a GEOJSON file with the help of ChatGPT, which I didnt know it could do so smoothly. Since the original Gazette only specified general regions or continents without pinpointing exact ports, I used Overpass Turbo to find relevant ports in these regions. By applying the coordinates of these ports to my dataset, I was able to create a more accurate map of Zanzibar’s export destinations. However, due to the repetitive nature of these regions, the map shows fewer points, as they are clustered in areas that Zanzibar most likely used for its exports. The key pinned location, marked in red, represents Zanzibar, helping to visualize its central role in global trade during the period of 1919.

![farm.jpg](/assets/images/farm.jpg)
![garden.jpg](/assets/images/garden.jpg)
![port.jpg](/assets/images/port.jpg)


## Mapping the Data: Identifying Patterns and Clusters

Once the data was organized and cleaned, I used mapping tools to visualize the export destinations and their concentrations. Mapping the data revealed some interesting patterns, particularly in areas where trade was most concentrated, such as the Arabian Peninsula and mainly parts in Africa. These regions showed higher densities of export points, which aligns with historical trade routes that connected Zanzibar to key markets in these regions.

Mapping additional columns, such as product types, export importance, and geographic regions, allowed for a more nuanced visualization. While the data didn’t reveal strong clusters, it did show the diverse spread of goods being traded and helped to highlight Zanzibar’s central role in global commerce. The mapping also reinforced the idea that Zanzibar’s trade was closely tied to specific geographical regions, with different commodities being exported to different areas based on market demand. For example in the table, I saw most manufactured goods stayed in the region of Africa.

![kepler.jpg](/assets/images/kepler.jpg)


## Future Analysis: Scaling Up the Project

If I were to scale this project to analyze exports over multiple years, the results would provide valuable insights into the long-term trends of Zanzibar's economy. Expanding the dataset would allow for the identification of shifts in trading patterns, changes in commodity demand, and the influence of external factors such as political changes or colonial policies on Zanzibar’s trade. I could also track the rise and fall of certain goods, By comparing data across different years, it would be possible to identify the impact of specific global events or local policies on trade patterns and commodity prices.

## Ideal Source for Future Projects

While the Zanzibar Gazette provided rich data for this project, an ideal source for future projects would be a collection of trade records from other major East African port cities, such as Mombasa or Dar es Salaam. These records would provide a comparative view of the regional trade dynamics in East Africa and help contextualize Zanzibar’s economic activities. Additional sources like colonial government reports, customs declarations, or merchant logs would also be valuable for gaining a more comprehensive understanding of Zanzibar’s trade practices and global interactions.

## Conclusion

The Zanzibar Gazette’s export data from September 1919 offers a detailed look at Zanzibar’s economy and its role in global trade during the early 20th century. By using AI tools like ChatGPT and Gemini to automate the extraction and analysis of this data, I was able to uncover valuable insights into the merchandise that shaped Zanzibar’s economic activity. The process also highlighted the limitations of AI, particularly in interpreting historical data, which underscores the importance of human intervention in data analysis. Moving forward, expanding this project to cover multiple years and incorporating additional sources would provide a deeper understanding of Zanzibar’s economic evolution and its interactions with global markets.

## Citations:
[Provocations from the Humanities for Generative AI Research](https://arxiv.org/abs/2502.19190) 

MLA 9:
Klein, Lauren, et al. “Provocations from the Humanities for Generative AI Research.” ArXiv.org, 2025, arxiv.org/abs/2502.19190. Accessed 8 Mar. 2025.


