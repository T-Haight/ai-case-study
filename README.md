# Buoy Health Case Study
![alt text](https://github.com/user-attachments/assets/592cce0c-c9b7-4b09-bc95-3c65abc81640)

<!--Make sure to include headers, sub headers, bold some text, include hyper links, logo of the company, additional metrics related to the company, some pictures etc  (you can use some of the resource included above for the syntaxes).-->

## Origin
<!--
* Name of company
* When was the company incorporated?
* Who are the founders of the company?
* How did the idea for the company (or project) come about?
* How is the company funded? How much funding have they received?
-->
Everybody has been sick, had an injury, or some form of health concern, and didn't know what the problem was at first. It's 
become common practice for people when they first notice symptoms, to look it up on the internet. 
Given that the typical person doesn't have any expertise in the medical field to know what 
questions to even ask, and the broad nature of online search algorithms, the 
results are almost definitely not found in a manner that a doctor would lay 
them out. Depending on what someone searches and the links they click on, the 
information they receive can vary drastically, but it's people's best attempt at finding 
a quick answer, which is all they want. This strategy can often convince someone of having a worst case scenario, and feeling uneccessarily 
alarmed, heading to the doctors. Hospitals are constantly busy with patients, and 
ones with serious conditions have to wait longer for their much needed treatment, because of 
those who needlessly show up based on a distressful internet search. The opposite effect can also 
happen for those who don't trust Google and choose to wait to see a doctor. If they needed urgent treatment but they wait too long, they could face serious ramifications. That's where Andrew Le, M.D. got the idea for his company, Buoy Health. 

### Foundations
Andrew Le was on his last rotation as a medical student at Harvard when he witnessed a concerning number 
of patients coming into the ER after misinterpreting information they found online, 
and watched them make poor health decisions. At that same time, his father found 
out he had a mini stroke, but not until months after it had happened. He later found out that his father considered searching his symptoms when he had them, but he didn't trust Google. That was the emotional breaking point that lead Andrew into devoting his time and energy towards developing a better tool for people to check on their symptoms, and what better time than the rise of A.I. technology. 
Andrew Le finished his doctorate of medicine, and in 2014 went on sabbitical, 
spending his time at Harvard Innovation Labs with a team of three 
other people, Adam Lathram (consulting & current President), Nate Ren (marketing), 
and Eddie Reyes (technical), and together they founded Buoy. The first funding they received was 
from an invester they met at a donor event after presenting their work, and it grew 
from there. Since then, they've raised ["over $67 million, with prominent healthcare investors 
including Optum, Cigna, Humana, WR Hambrecht + Co., and F-Prime."](https://techcrunch.com/sponsor/connection/from-point-a-to-point-unbelievable-how-buoy-health-scaled-from-idea-to-unbelievable-a-i-success-story/)


## Business Model
<!--
* What specific problem is the company or project trying to solve?
* Who is the company's intended customer? Is there any information about the market size of this set of customers?
* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
-->
Misinformation and disinformation is more prevelant in today's day and age than 
ever before, and it really comes at a cost in the healthcare industry. When 
someone misdiagnoses themself, it can cost them time and money, seeing a doctor they 
shouldn't have seen. Medical staff and other sick patients are paying the price 
in that scenario as well. It could also cost people their own health and well-being
for not seeing a doctor they should have seen one. So having a quick and reliable way to 
get medical advice is priceless. That's what Buoy seeks out to deliver with it's 
A.I. assistant, *Symptom Checker.* Buoy Symptom Checker is an online A.I. 
chatbot, that listens and understands your concerns, identify's what's wrong, and 
forms a plan for you. It's made for everyone, all you need is an internet browser. The AI is built and designed by doctors and data scientists, and ["sources
from over 18,000 clinical papers, covering 5 million patients and spanning 1,700 conditions."](https://www.mobihealthnews.com/content/digital-health-startup-buoy-launches-ai-powered-symptom-checking-chatbot)
According to a peer reviewed article from the Nation Center for Biotechnology Information, Buoy's symptom checker
uses natural language processing (NLP) to interpret all that data, and intelligently decides which of the 30,000 questions to ask next, using the principle of greatest reduction of diagnostic uncertainty [[NCBI Article]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7748958/). 

![alt text](https://cdn.sanity.io/images/0b678gck/~production/b769056d574305ccdd8e5d140fdfd25bdf93ce75-624x1065.png?w=300&q=30&auto=format&dpr=1)
![alt text](https://cdn.sanity.io/images/0b678gck/~production/58a179bdb5118cbc64250bf16f0c9dcf7dfcb0da-624x1065.png?w=300&q=30&auto=format&dpr=1)
![alt text](https://cdn.sanity.io/images/0b678gck/~production/77e826a80731b7ace83c38872bc03afe74597970-624x1065.png?w=300&q=30&auto=format&dpr=1)



## Competitor Comparison and Trends
<!--
* What field is the company in?
* What have been the major trends and innovations of this field over the last 5&ndash;10 years?
* What are the other major companies in this field?
-->
There are over hundreds of healthcare chatbot companies in the medical field, but not all are focuses on *symptom checking* technology. Some of Buoy's top competitors are Ada, WebMD Symptom Checker, Symptomate, and Babylon Health. Other notable ones include Healthily, Docus, Ubie, Isabel, and Mayo Clinic Symptom Checker.
A lot of these companies were established around the same time as Buoy, between 2012 and 2016. They don't vary too much in terms of availability, most are free and available on a browser or app. One difference between each competitor which may certainly have an impact on performance, is which clinics and hospitals they extract medical data from. 
As far as A.I. goes, all companies likely use some form of natural language processing on the large datasets they feed in. The major differences are in the machine learning algorithms and statistical models (type of neural networks, number of nodes/layers, etc.), the amount and type of data it uses to train on (some do images and/or videos on top of text), and of course the actual context of the data, all key factors in performance. Most companies have a step-by-step process for the user to go through, as it provides a predetermined set of question/responses using the similar principles and logic as described earlier for Buoy. However, there is only one company, **Docus** that I noticed which allows the user to type in custom responses, and the natural language understanding A.I. will interpret what you're saying, and provide a personalized analysis. Docus's AI only offers a very limited free trial of 3 custom responses, then you have to pay a subscription fee. Now you may be wondering, how well do these A.I.'s perform in a primary care vignette setting? Well according to an analysis done by OpenMD, evaluating 5 companies (Ada, Buoy, Isabel, Sympotomate, and WebMD) across 3 studies published between 2020-2021, Ada has the highest diagnostic accuracy (77%) and Buoy had the lowest (52%). Another [vignette study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11091811/) compared 6 symptom checkers, including Buoy and Ada, to 3 real physicians, and according to those results none of them were as good as real doctors. Ada performed better than Buoy by a fair margin in that one too, but it's still safe to say that none are at the level of real doctors. One thing that does set Buoy apart from it's competitors is that as of 2022, it has its own marketplace which ["includes more than three dozen care solutions that span comprehensive physical, mental, and specialized health needs."](https://www.prnewswire.com/news-releases/need-a-buoy-buoy-health-launches-the-future-of-personalized-care-with-a-digital-health-marketplace-301578477.html?tc=eml_cleartime) Buoy intends to simplify people's relationship with the healthcare system and avoid the insurance hoops and ladders. They also work directly with employers, and handle all health care bills and health benefit contracts, saving the employer the hassle of working with multiple digital health vendors.  

## Achievements
<!--
* What has been the business impact of this company so far?
* What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?
* How is your company performing relative to competitors in the same field?
-->
In an early peer-reviewed study done in 2019 at the Medical College of Wisconsin, ["We found that the proportion of patients who were uncertain about the level of care decreased from 34% to 21% [after checking with Buoy AI Assistant]."](https://www.buoyhealth.com/multi-symptom-checker) That study also showed a decrease in the urgency of intended level of care by over 25%. So there seems to be evidence that it gives people an increase in security and confidence about the level of care they need, and it's usually less than they initially expected. Those was two of their main goals, and they've only reached more since then. Buoy made a big impact in 2020 during the Covid-19 pandemic, offering a tool to screen people who were at risk of carrying the disease. Throughout Andrew Le's career as the CEO of Buoy, he ["was named by Business Insider as one of 30 healthcare leaders under 40 to watch, a Digital Innovator by Employee Benefits News, one of Boston Business Journal’s Top 40 Under 40 leaders, and recognized as a TEDMED Hive Innovator."](https://techcrunch.com/sponsor/connection/from-point-a-to-point-unbelievable-how-buoy-health-scaled-from-idea-to-unbelievable-a-i-success-story/) As of now, Buoy has over 2 million monthly users [PR Newswire](https://www.prnewswire.com/news-releases/need-a-buoy-buoy-health-launches-the-future-of-personalized-care-with-a-digital-health-marketplace-301578477.html#:~:text=BOSTON%2C%20June%2030%2C%202022%20/,any%20care%20they%20might%20receive.)
## Recommendations
<!--
* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
* Why do you think that offering this product or service would benefit the company?
* What technologies would this additional product or service utilize?
* Why are these technologies appropriate for your solution?
-->
Buoy has shifted towards more marketing and business initiatives, partnering with companies to build their **Marketplace** and working with employers instead of indivual users. I'm not sure the exact reasoning why, but two of the 4 co-founders no longer work for Buoy, Nate Ren (marketing), and Eddie Reyes (technical); this is just speculation, but there could be a link between them leaving and the shift in the company. If I had to make recommendations for the company as an outsider, who doesn't have access to their finances, I would first recommend making an app version of the symptom checker. They've talked about it for years, and almost all their competitors have one. Next, would be to invest in improving the accuracy of symptom checker. It does [well as far as coverage of conditions, suggesting next steps](https://bmjopen.bmj.com/content/10/12/e040269.long), but those suggestions aren't that valuable if the conditions aren't accurately predicted. Ada has proven it's possible to achieve better results, and that's probably the most important metric needed to stay relevant in the field. One bold suggestion would be to follow in the steps of Docus, and implement a more free form communication with the A.I. since that's rare and more appealing to consumers. If you are an employer looking for benefit programs, or if you don't have insurance and are interested in their niche health care options, it may be worth checking out Buoy for those reasons. If you are someone who just wants to check if they need to see a doctor, I would recommend checking out Buoy's symptom checker, but also check with Ada and at least one other to compare. These tools can be very powerful when used together, and may just save you and other people a lot of trouble.  


### Sources
[Company Website](https://www.buoyhealth.com/company)
[Junto Health](https://www.juntohealth.org/blog-posts/founder-feature-buoy-health)
[TechCrunch](https://techcrunch.com/sponsor/connection/from-point-a-to-point-unbelievable-how-buoy-health-scaled-from-idea-to-unbelievable-a-i-success-story/)
[National Library of Medicine(1)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7748958/)
[Medical Futurist](https://medicalfuturist.com/top-10-health-chatbots/)
[PR Newswire - Need a Buoy? Buoy Health Launches the Future of Personalized Care with a Digital Health Marketplace](https://www.prnewswire.com/news-releases/need-a-buoy-buoy-health-launches-the-future-of-personalized-care-with-a-digital-health-marketplace-301578477.html?tc=eml_cleartime)
[Mobi Health New](https://www.mobihealthnews.com/content/digital-health-startup-buoy-launches-ai-powered-symptom-checking-chatbot)
[PR Newswire - Rising Epidemic in the United States](https://www.prnewswire.com/news-releases/buoy-health-calms-coronavirus-fear-serves-up-population-health-data-to-help-control-the-rising-epidemic-in-the-united-states-301024768.html)
[BMJ Journals(1)](https://bmjopen.bmj.com/content/10/12/e040269)
[National Library of Medicine(2)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11091811/)
[BMJ Journals(2)](https://bmjopen.bmj.com/content/10/12/e040269.long)
