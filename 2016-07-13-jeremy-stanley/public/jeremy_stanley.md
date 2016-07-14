## Decision Science / Data Products

_Q: In your [Doing Data Science Right] article, you mentioned the distinction between Data products and Decision Science. In my opinion, virtually every aspiring DS hires nowadays want to do Machine Learning and want to build data products, but relatively few want to pursue the more traditional path of analytics or Decision Science. Part of it has to do with PR and how the field is percieved, but I couldn't quite explain whether it is really that building Data Products is really sexier or that there is an unfair bias. Do you see a similar bias when recruiting DS for your team? If so, how do you correct for this bias?_

A: It's probably a combination of several things:

* There are some people who don't and cannot think as rigorously, and unfortunately some of them self selected into the Decision Science field because it blends with many other analytics related functions. Sometimes these people can damage the field itself, not because Decision Science is not useful, but because of the negative qualities they bring into the field.

* On the other hand, there are super technical savvy people who focused too much on the models, and have no empathy for the customer needs. Some can build models with very high AUC, but what the model is solving doesn't translate to the actual problem that the business is trying to solve. An example he brought up is that if you are trying to figure out which subset of your users are incentivized to shop using coupons, you shouldn't predict who has the highest probability of buying, because they might buy regardless (with or without) coupons. In fact, using something like a uplift model is probably more appropriate.

Navigating Between These Two Fields:
    
* You cannot be a good Data Product focused DS without having all the necessary skills for doing decision science. I think he was referring to both the technical (EDA, data munging skills) as well as the project management skills (know what to build, setting roadmap ... etc), so where we make the distinction. You really need to have the same foundational skill in order to become successful. His argument reminds me of this [article](http://www.sharpsightlabs.com/machine-learning-prerequisite-isnt-math/).

* Finally, he said that most of us are not good at either one when we start. It's really that first 2 - 5 years that allow you to get exposure and improve.

## Building a Data Science Team

_Q: I can especially echo with the pros and cons of centralized and de-centralized (embedded) teams based on my personal experience. Many companies nowadays are trying to take a hybrid approach where a group of individual DSs are "deployed" to a particular general product area. The idea is to have people to be embedded while enjoying a semi-team support and structure. Do you see other organizational innovations in how to manage Data Scientists in our industry?_

Jeremy has built both Engineering and Data Science Team in the past. He has built a 6 person DS team and fold it under engineering, and subsequently lead the entire Engineering org, and have gone through this several times in his career. As a result, He get to see what (not) worked.

He commented that how DS is structured is often very related to how Engineering teams are set up. In many cases, the way that Engineering is set up provide constraints and bounds on how DS team should operate. This is certainly true at Instacart as well, because many DS functions like Engineers, and vice versa.

At instacart, DS and Engineers report to the same tech lead (and she may be a DS or a Engineer, or both). The team is usually fully staffed and full stacked (PM, Tech Lead, DS, Engineer, Mobile Engineer, and embedded Designer). The team collectively owns the mission. The mission can vary, depending on the team:
    
* Activiation of new user
* Retention of existing user
* Shopper Experience and Shopper's app
* Fulfillment
* Supply & Demand Forecasting ... etc

The philosophy is to have everyone own the Data Science piece of the product work. DS report to the Tech lead, who then do the performance evaluation. Jeremy's role is to facilitate these teams, help them to cross-functionally consume each others work (if they are data product, prediction, optimization algorithms), and he is responsible for recruiting and resourcing for the entire DS organization.

Generally, they look for people who have ownership, and are willing to build things from end-to-end. More importantly, they need to have customer empathy, and have the desire to impact and want to solve the right problems.

## Balancing Contributing at Work and Career Development

* It's important to have the ability to identify when to use what to solve a problem. e.g. Know when to use heuristic, when to use optimization, and when to use machine learning. The only way to learn it is by experience, you will fail many times, but for the few times that it work, you will learn so much.

* It's much better to learn a technique when you know you need it on the job, rather than learning it out of a vaccume! Because you will be more motivated, you will apply it, and you will get a sense of how it works and will want to improve.

* Alternatively, a good strategy is to create a white box and try things out. If for every 3 attempts you explore things for a week and you can create something that move metrics by 10%, people will let you explore. It's fundamentally about trust and whether they are willing to let you explore what can make impact.

[Doing Data Science Right]:http://firstround.com/review/doing-data-science-right-your-most-common-questions-answered/