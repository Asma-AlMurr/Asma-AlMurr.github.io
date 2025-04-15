---
title: "Assignment 2"
last_modified_at: 2025-02-03
categories:
  - Blog
tags:
  - Assignments
---

# Analyzing Exports in the Zanzibar Gazette 1919

## Introduction

The Zanzibar Gazette's export data from September 1919 offers a vital historical snapshot of Zanzibar’s trade economy during a transformative period. Zanzibar, an island off the coast of East Africa, was a central hub in the global spice trade and other exports, including ivory and animal products. This project aims to explore the export activities documented in the Gazette, using advanced AI tools like ChatGPT and Gemini to automate data extraction and analysis. The project delves into the economic impact of Zanzibar’s exports, the role of technology in analyzing historical data, and the challenges posed by AI in handling such complex datasets.

## Why I Chose This Document (Exports September 1919)

The Zanzibar Gazette’s export data from September 1919 was chosen for its rich historical value. This document serves as a primary source, offering insight into the economic activities of Zanzibar, particularly in its role as a key player in the spice and ivory trade. By focusing on this particular issue, I aimed to explore the breadth of Zanzibar's export commodities and their significance in the context of global trade during the early 20th century. Zanzibar's strategic position in the Indian Ocean and its established trade routes with Europe, Asia, and Africa made it a vital node in the global market. Analyzing the data from the Gazette offers a detailed view of how Zanzibar interacted with these regions, providing insights into the commodities that shaped the island’s economy and its global connections.

## The Table: Organizing the Data

The table created from the Zanzibar Gazette data is the cornerstone of this analysis. It organizes various export details, including merchandise categories, export destinations, weight, number of packages, value in Zanzibar Rupees (1919), and their converted value in U.S. Dollars. The table also categorizes each entry by export importance and includes historical tags. For example, items like ivory and rhino horns are classified as "Luxury Commodities," while items like copra and coconuts are listed under "Tropical Commodities."

This structured table not only serves as a historical record but also enables deeper analysis by allowing comparisons between different product categories and their economic significance. The process of organizing this data made it easier to visualize Zanzibar's role in global trade, as the various categories can be analyzed for their economic impact. This also highlights the diversity of Zanzibar’s exports, ranging from luxury items to agricultural products, and their significance in shaping Zanzibar's interactions with other regions.

## Article “Provocations from the Humanities for Generative AI Research”

Incorporating the article *Provocations from the Humanities for Generative AI Research* into this essay allows me to address the intersection between technology and humanities in historical data analysis. The article critiques the limitations of AI models in generating meaningful insights from historical data. Specifically, the authors highlight that while AI can process large datasets, it often lacks the ability to truly understand the cultural and historical context behind the data it processes.

In my project, AI tools like ChatGPT and Gemini helped automate the extraction of data from the Zanzibar Gazette, but as the article suggests, these tools struggled to interpret the full significance of the data. For instance, while AI models could extract merchandise categories and their values, they couldn't fully account for the economic and geopolitical factors that shaped Zanzibar’s trade at the time. This insight from the article aligns with my experience, where the automation of data extraction provided structure but lacked depth in understanding the historical context. The article’s critique underscores the importance of human interpretation when working with AI-generated data.

> **Quote from the Article**:  
> “Models make words, but people make meaning” (Provocations, page 5).  
> This quote resonates with my work as it emphasizes that while AI tools can assist in generating data, it is ultimately the researcher who gives that data its meaningful context. In my case, while ChatGPT and Gemini helped process the export data, it was up to me to interpret the cultural, economic, and geopolitical significance behind the data.

## Prompt Engineering: Maximizing AI Tool Performance

A key aspect of this project was the process of prompt engineering to improve the effectiveness of the AI tools used in the analysis. Initially, I created simple prompts asking ChatGPT and Gemini to extract and organize the data from the Zanzibar Gazette. However, I quickly encountered challenges such as incomplete extractions and mismatched data. To improve results, I refined my prompts by making them more specific. For example, I instructed Gemini to break the extraction task into parts and process each image separately, which allowed for better results. I also asked ChatGPT to categorize the merchandise by type and assign export importance based on the product’s historical context.

These refinements helped generate more accurate results, but there were still limitations in the AI’s ability to handle complex historical data. Both tools struggled with converting Zanzibar Rupees into modern U.S. Dollars, and the OCR data extraction process was not flawless. This required substantial manual intervention to clean the data and ensure its accuracy. Despite these challenges, the prompt engineering process was crucial in obtaining a usable dataset that could be analyzed further.

> **Quote from the Article**:  
> “LLMs generate text by predicting sequences of words. These predictions are based on both observed patterns and on human preferences and feedback. The result is often output that is factually wrong yet linguistically fluent and seemingly coherent—these are the hallucinations.” (Provocations, page 6).  
> This quote is directly applicable to my experience with AI tools. While AI tools like ChatGPT generated fluent and seemingly coherent data, I often had to intervene to correct factual inaccuracies, especially when converting currency or correcting geographical data.

## Automation Performance and Data Cleaning

The automation of data extraction through AI was quite effective but required significant data cleaning to ensure the results were accurate. Both ChatGPT and Gemini struggled with the quality of the original scanned images from the Zanzibar Gazette. In particular, the OCR process often misread numbers and geographical data, leading to errors in the extracted tables. After using Gemini and ChatGPT to generate initial datasets, I had to manually verify and correct the data, particularly the merchandise values and shipping regions.

Despite these challenges, the AI tools provided a good starting point by organizing the data and identifying key merchandise categories. The main task was to ensure the accuracy of the numerical values, product names, and geographical information, which involved cross-referencing the AI outputs with the original images from the Gazette. This manual cleaning process was time-consuming but necessary to ensure the dataset’s reliability for further analysis.

### ChatGPT Performance Analysis

> **Prompt 1**: "Turn these images of exports from the Zanzibar Gazette into a visual table"  
*Only did 16 rows*

> **Prompt 2**: "Turn these images of exports from the Zanzibar Gazette into a visual table by extracting all the rows, and including the region it is being exported to, then making it a readable table."  
*Completed 50 first and downloaded to Apple Numbers*

ChatGPT 4.5, the newest beta model available in the paid version, showed good potential in digitizing historical data from the provided Gazette images. It took approximately 4 minutes to process and display the extracted data. The AI accurately captured numerical values and identified merchandise items, which was impressive given the complexity and somewhat compromised quality of the original document. However, there were notable limitations. The first attempt yielded only 16 rows of data, significantly fewer than the total available entries. After requesting a more comprehensive extraction, ChatGPT was able to produce approximately half (around 50 entries) of the total dataset. Yet, despite this progress, ChatGPT continued to encounter errors, particularly a "mismatch in the data arrays" that disrupted further extraction. This recurring issue led to a loop of corrections without substantial progress, resulting in the first image being partially processed. As a result, I decided to switch tools and use Gemini to complete the task.

### Gemini Performance Analysis

> **Prompt 1**: "Convert the entire list of exported items from this Gazette into a visual table, including merchandise names, regions exported to, weights, number of packages, and their respective values."  
*Only did first 50 rows*

> **Prompt 2**: "Now combine both of the tables into one big downloadable table"  
*All rows completed and downloaded to sheets*

Gemini, in contrast, provided a much more efficient and accurate experience. It generated the required results within seconds, significantly outperforming ChatGPT in speed and accuracy. I had to break the extraction task into two parts due to Gemini's limitation of analyzing one image at a time. However, Gemini promptly extracted and structured the data from each image independently, identifying the merchandise items, regions, and numerical values with minimal manual intervention. When I instructed Gemini to combine both sets of extracted data into a unified table, it did so smoothly, without encountering the alignment or data mismatch errors that occurred with ChatGPT. Throughout the entire process, Gemini was stable and efficient, requiring fewer corrections and providing a reliable dataset for further analysis. Its ability to interpret OCR data and transform it into a structured table made Gemini the preferred tool for completing the task.

### Data Cleaning and Manual Intervention

Cleaning the dataset after OCR extraction required substantial manual effort due to inconsistencies and inaccuracies in the blurred text from the historical Gazette. I had to manually correct mismatched data, such as redundant or incorrect merchandise entries that resulted in discrepancies between the AI output and the actual dataset. Additionally, numerical values, package counts, and region labels needed verification against the original Gazette images. I carefully inserted missing or ambiguous data points where the OCR process fell short. This meticulous process ensured the dataset's accuracy, allowing for a precise and reliable visualization of the historical export data. This cleaning was crucial for making sure the final dataset was ready for analysis, as both AI tools provided structured outputs but required human intervention to ensure the data's integrity.


>“I find the new models are the best and then they tend to deteriorate or hallucinate more often as they are trained on new noisy data or the engineers stop paying attention to them while they focus on newer versions.” -R.K (former student)

This quote by R.K. highlights an insightful observation about the lifecycle of AI language models. It underscores a common challenge: while newer models initially demonstrate remarkable accuracy and capabilities, there's a risk that their performance may degrade over time due to exposure to noisy or lower-quality data. This phenomenon, often referred to as "model drift," occurs when continual training incorporates inaccuracies or biases from uncontrolled data, causing the model to produce less reliable outputs or to "hallucinate" facts more frequently. Moreover, R.K.’s point also addresses an important aspect of resource allocation in AI development. As engineers shift their attention towards developing the next generation of models, existing ones may receive less rigorous monitoring, tuning, and fine-tuning, further contributing to their decline in reliability. This observation emphasizes the importance of sustained maintenance, rigorous quality control, and periodic retraining using carefully curated datasets to maintain a model's accuracy and reliability over time. It's a valuable reminder that continuous attention, rather than just initial deployment, is crucial for the long-term success and stability of AI systems.


## Mapping the Data: Identifying Patterns and Clusters

Once the data was organized and cleaned, I used mapping tools to visualize the export destinations and their concentrations. Mapping the data revealed some interesting patterns, particularly in areas where trade was most concentrated, such as the Arabian Peninsula and parts of East Africa. These regions showed higher densities of export points, which aligns with historical trade routes that connected Zanzibar to key markets in these regions.

Mapping additional columns, such as product types, export importance, and geographic regions, allowed for a more nuanced visualization. While the data didn’t reveal strong clusters, it did show the diverse spread of goods being traded and helped to highlight Zanzibar’s central role in global commerce. The mapping also reinforced the idea that Zanzibar’s trade was closely tied to specific geographical regions, with different commodities being exported to different areas based on market demand.

## Future Analysis: Scaling Up the Project

If I were to scale this project to analyze exports over multiple years, the results would provide valuable insights into the long-term trends of Zanzibar's economy. Expanding the dataset would allow for the identification of shifts in trading patterns, changes in commodity demand, and the influence of external factors such as political changes or colonial policies on Zanzibar’s trade. This larger scale would offer a clearer picture of Zanzibar’s evolving economic landscape and its role in the global market during the early 20th century.

Additionally, analyzing exports over several years would allow for a deeper exploration of the factors that shaped Zanzibar’s economic success. By comparing data across different years, it would be possible to identify the impact of specific global events or local policies on trade patterns and commodity prices.

## Ideal Source for Future Projects

While the Zanzibar Gazette provided rich data for this project, an ideal source for future projects would be a collection of trade records from other major East African port cities, such as Mombasa or Dar es Salaam. These records would provide a comparative view of the regional trade dynamics in East Africa and help contextualize Zanzibar’s economic activities. Additional sources like colonial government reports, customs declarations, or merchant logs would also be valuable for gaining a more comprehensive understanding of Zanzibar’s trade practices and global interactions.

## Conclusion

The Zanzibar Gazette’s export data from September 1919 offers a detailed look at Zanzibar’s economy and its role in global trade during the early 20th century. By using AI tools like ChatGPT and Gemini to automate the extraction and analysis of this data, I was able to uncover valuable insights into the merchandise that shaped Zanzibar’s economic activity. The process also highlighted the limitations of AI, particularly in interpreting historical data, which underscores the importance of human intervention in data analysis. Moving forward, expanding this project to cover multiple years and incorporating additional sources would provide a deeper understanding of Zanzibar’s economic evolution and its interactions with global markets.
