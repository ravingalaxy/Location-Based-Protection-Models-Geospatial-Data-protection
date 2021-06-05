# Location Based Protection Models (Geospatial Data Protection)
<a href="https://ravingalaxy.github.io/Location-Based-Protection-Models-Geospatial-Data-protection/" target = "_new">Live Project </a>
## Abstract
With the rapid development of Internetservices, mobile communications, and IoT 
applications, Location-Based Service (LBS) has become a very part in our daily lives in today’s 
time. However, when users want benefit with LBSs, the analysis and analytics of user’s location 
data and path following information may breach their privacy and also trajectory data is powerful 
to many crowdsourcing tasks. For example, Uber and other services use the driver’s geolocation 
to match the client’s requests. However, there are very many issues about the privacy of publishing 
the geospatial data. To address these types of problem here in this report we described three 
(Location Based Differential Privacy Method, Privacy-Preserving Method Based on 
Historical Proximity Location and Predictive Differentially-Private Mechanism) related 
method which are very helpful to solve the issue and protect the location-based privacy of people 
in real world.

## Introduction
As the technology is growing day by day and while performing any type of online 
communication or transaction users are allowed to share their exact location to the server. For 
example, a company that uses the user’s geolocation data as references for allocating 
crowdsourcing tasks. The company has developed good algorithms for allocating tasks based on 
accurate geolocation data. One of the new business requirements is that the client can visualize a 
few nearby crowdsourcing works before the client finalizes the order. Displaying the geolocation 
on google maps and alike services is doable. However, the data is sensitive and cannot be directly 
disclosed to anyone. The location-based privacy is an important issue for current and upcoming 
time and there many research papers which provide to maintain the location-based privacy. 
## Literature Review
Here in this report, we are using three methods to solve the protect the location-based 
privacy of the people which are follows:
1. <a href = "https://arxiv.org/pdf/1212.1984.pdf"> Location Based Differential Privacy Method: </a><br>
This privacy protection method sets an accurate representation of protecting the user's 
geolocation within radius r and depends on the privacy parameter e which decide the privacy level 
based on r, and is consistent with the standard version of the known differential privacy protection 
concept. In addition, we introduce a method to achieve geo-separation by adding randomly 
controlled noise to the user region. This method of privacy based on geo segmentation ensures 
without compromising the quality of application results.
In this paper the authors present a framework for achieving privacy in location-based 
applications, taking into account the level of protection required and the additional information 
that the attacker may have. At the heart of their proposal is a new concept of privacy, which they 
call geo-indistinguishability, and a method, based on the Laplace version of the bivariate function,
to disrupt the real situation. They have strongly emphasized the legal treatment of privacy 
guarantees, both in providing a strong definition of geo-indistinguishability, and in providing 
mathematical evidence that their approach satisfies such conditions. 
They also showed how geo-indistinguishability is related to the popular notion of alternative privacy. 
But the problem with this method is that it is little bit slow and can be improve if other 
functionality like prediction on the basis of some condition before adding the noise can make it 
faster. Which is done further in Predictive Differentially-Private Mechanism.
In the future the authors aim to broaden their approach to complex applications, perhaps 
involving the cleaning of multiple (potentially related) areas. An important factor to consider when 
creating noise in many details is the fact that their interaction may reduce the level of protection. 
They aim to develop strategies to control potential privacy losses and allow for the fullness of their 
approach.
2. <a href = "https://www.hindawi.com/journals/wcmc/2020/8892079/"> Privacy-Preserving Method Based on Historical Proximity Location : </a> <br>
The main idea of how to Preserve Privacy According to Proximity Location History is to 
place in one existing historical location near the current location user. This method ensures that 
the user can access location-based services without submitting actual location information, which 
can improve the level of privacy while reducing counting and communication on the server side. 
In addition, this method can not only provide privacy protection for query questions but also protects the privacy of the trajectory from furtherance. Compared to other privacy measures such 
as anonymity and dummy location, this method improves the quality and performance of the query 
while maintaining a satisfactory confidentiality level.
This paper proposed a solution for privacy protection in both short and continuous 
questions. With nearby historical user locations sent to local service providers by query instead of 
the actual location, user location details are not fully known to local service providers throughout 
the process of requesting location-based services, so higher confidentiality is available. Compared 
to anonymity and the preferred method of choosing a pseudonym, this method is simpler and more 
feasible, and can achieve better query performance and higher query quality. The author's proposal 
also provides a new solution to address the problem of maintaining a balance between privacy 
level, question efficiency, and quality of services. It is possible for the attacker to provide a general 
indication of the user's movement by analyzing the change in the scope of the user's recorded query 
to local service providers. This is difficult in current trajectory privacy practices, and is also 
focused on future research work.
3. <a href="https://arxiv.org/pdf/1311.4008.pdf"> Predictive Differentially-Private Mechanism </a> <br>
In this method the authors show that the sequence convergence can actually be used by a predictive 
function that attempts to predict a new location based on previously reported locations. The 
proposed method assesses the quality of the predicted area using private inspections; in the event 
of a success the prediction is reported otherwise the location is acquired with new sound. If there 
is a significant correlation in the follow-up to the installation, additional testing costs are small 
compared to the budget savings, which leads to more efficiency. Here We explore the process in 
terms of getting a locally based service while roaming the city. Using a simple predictive function 
and a geo-indistinguishability scheme, we show that the predictive method can offer greater 
improvements than noise used independently.
## Data Description
<a href = "https://snap.stanford.edu/data/loc-gowalla.html" >Gowalla </a > is a website with a social network where users share their locations by logging in. 
The friendly network is not targeted and compiled using the public API, and has 196,591 sites and 
950,327 domains. We have collected a total of 6,442,890 entries for these users during the period 
February 2009 - October 2010.


