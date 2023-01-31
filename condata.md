# Establishing Contextual Dataset Retrieval - transferring concepts from document to dataset retrieval (ConDATA)

**Team**: Zeljko Carevic, Roy Dwaipayan  
**Leader**: Dr. Philipp Mayr  

Duration: 1.1.2019 – 15.01.2022  
Funded by: DFG, Geschäftszeichen: MA 3964/10-1  

Information Retrieval Systems (IRS) face new challenges due to the growth and diversity of data and users. In fact, an IRS analyses the query submitted by the user and explores collections of data with unstructured or semi-structured nature (e.g. text, image, video, Web page etc.) in order to deliver items that best match his/her intent and interests. Those challenges are more enhanced when the result of the query is no longer a known type such as Webpage or literature reference but rather a dataset or data collection. Dataset retrieval represents a new and a challenging research area because of the particularity of the output type which is not a text that can be easily indexed and retrieved.  
Our contextualisation approach is visualised in a simplified schematic way. At the start of each session, only little information is available about the user and his information needs. This is characterized by a low session context on the system side and a high uncertainty on the user side. Over time the user interacts with the system by entering query terms, looking at datasets and accepting recommendations from the system. With each interaction the systems knowledge about the user and his information needs is growing and resulting in a more concrete representation of the user via the session context. At the same time the uncertainty is reduced and the search results are tailored according to the user’s search interests.

We aim in this project to include the user context based on issued queries, reformulated queries, seen documents etc. in order to provide the user with a personalised ranking of datasets relevant to his interests. Another example for a contextualisation in real-life applications is so-called query expansion where a user’s search query is expanded to related terms which are derived from the user’s context.
The main goal of the ConDATA project is to employ well established contextualisation approaches from the field of document retrieval to the field of dataset retrieval in order to personalise search results. To achieve this, we propose a user-centered retrieval approach in which we analyse the user behaviour of researchers during dataset retrieval tasks. This overall goal is divided into the following sub-goals:  

* Sub-Goal 1: User behaviour in dataset retrieval. The goal is to analyse the search behaviour of users during a dataset retrieval task to determine strategies that are commonly employed.
* Sub-Goal 2: Data representation. The goal is to create an indexed and retrievable representation which is feasible to describe a dataset.
* Sub-Goal 3: Develop a user profile modeling approach. By utilising implicit relevance feedback the goal is to develop a rich user profile that enables an abstract representation of the users search interest and search behaviour.
* Sub-Goal 4: Evaluation in a living lab environment  

The objective is to utilize a user-driven implementation process which is evaluated in a living lab environment (**GESIS Search, https://search.gesis.org/**). Our goal is to compare different contextualisation approaches to determine which is most suitable for dataset retrieval using a living labs approach in which different methods are evaluated using real life search tasks.  

The overall contribution of the project will be a recommendation of successful techniques, approaches and concepts and implementations (in GESIS Search) of contextualized data set retrieval which are suitable to contextualise dataset retrieval. The contextualisation will be developed using state-of-the-art methods which are widely implemented and thus can easily be reproduced by other researchers in the field.


**Publications**:  
* Roy, D., Carevic, Z., & Mayr, P. (2022). Studying retrievability of publications and datasets in an integrated retrieval system. Proceedings of the 22nd ACM/IEEE Joint Conference on Digital Libraries. JCDL ’22: The ACM/IEEE Joint Conference on Digital Libraries in 2022. https://doi.org/10.1145/3529372.3530931
* Roy, D., Mitra, M., Mayr, P., & Chowdhury, A. (2022). Local or Global? A Comparative Study on Applications of Embedding Models for Information Retrieval. In CODS-COMAD 2022: 5th Joint International Conference on Data Science & Management of Data (9th ACM IKDD CODS and 27th COMAD) (pp. 115–119). https://doi.org/10.1145/3493700.3493701
* Krämer, T., Carevic, Z., Roy, D., Klas, C.-P., & Mayr, P. (2021). ConSTR: A Contextual Search Term Recommender. 2021 ACM/IEEE Joint Conference on Digital Libraries (JCDL), 295–296. https://doi.org/10.1109/JCDL52503.2021.00042
* Krämer, T., Papenmeier, A., Carevic, Z., Kern, D., & Mathiak, B. (2021). Data-Seeking Behaviour in the Social Sciences. International Journal on Digital Libraries. https://doi.org/10.1007/s00799-021-00303-0 
* Agrawal, S., Roy, D., & Mitra, M. (2021). Tag embedding based personalized point of interest recommendation system. Information Processing & Management, 58(6), 102690. doi.org/10.1016/j.ipm.2021.102690
* Carevic, Z., Roy, D., & Mayr, P. (2020). Characteristics of Dataset Retrieval Sessions: Experiences from a Real-Life Digital Library. In M. Hall, T. Merčun, T. Risse, & F. Duchateau (Eds.), Digital Libraries for Open Knowledge (Vol. 12246, pp. 185–193). Springer International Publishing
* Biswas, C., Ganguly, D., Roy, D., & Bhattacharya, U. (2019). Privacy Preserving Approximate K-means Clustering. Proceedings of the 28th ACM International Conference on Information and Knowledge Management  - CIKM ’19, 1321–1330. https://doi.org/10.1145/3357384.3357969 
* Roy, D., Saha, S., Mitra, M., Sen, B., & Ganguly, D. (2019). I-REX: A Lucene Plugin for EXplainable IR. Proceedings of the 28th ACM International Conference on Information and Knowledge Management  - CIKM ’19, 2949–2952. doi.org/10.1145/3357384.3357859
* Cabanac, G., Frommholz, I., & Mayr, P. (2020). Bibliometric-Enhanced Information Retrieval 10th Anniversary Workshop Edition. In J. M. Jose, E. Yilmaz, J. Magalhães, P. Castells, N. Ferro, M. J. Silva, & F. Martins (Eds.), Advances in Information Retrieval (Vol. 12036, pp. 641–647). Springer International Publishing. http://link.springer.com/10.1007/978-3-030-45442-5_85
* Carevic, Z., 2020. Contextualised Stratagem Browsing in Digital Libraries.  Ph.D. Thesis doi.org/10.17185/duepublico/72522 
* Chandrasekaran, M. K., & Mayr, P. (2019). Report on the 4th Joint Workshop on Bibliometric-enhanced Information Retrieval and Natural Language Processing for Digital Libraries at SIGIR 2019. SIGIR Forum, 53(2), 3–10.
* Cabanac, G., Frommholz, I., & Mayr, P. (2019). Report on the 8th International Workshop on Bibliometric-enhanced Information Retrieval (BIR 2019). SIGIR Forum, 53(1), 21–28.
