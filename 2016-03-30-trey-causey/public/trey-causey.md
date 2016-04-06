### Q: My impression is that you are very comfortable with doing not only Type A (Analysis/Insights driven work) due to your academic training, but also Type B (Build/production driven) works due to your industry experience. 

* **Have you made the Type A v.s. Type B career path decision explicitly in your career?**
* **If so, how did you reach that decision?**
* **If so, how did you make that transition?**

_He doesn't necessarily think that he is good at both Type A & Type B work. I think what gravitates him toward Type B is that he was mostly in a **start-up** environment, where he is not only the only data analyst, but also responsible for everything related to data. Over time, he developed these skills just enough so his codes would work, can be reviewed, shared, and applied in other contexts._ 

_He did mention that going down this path also means that he has less time to build models, think about problems analytically, and **when you gain some, you also lose some. It's all about trade-offs**_ 

_On a related note, we talked about the pros and cons of being a **generalist v.s. specialist**. He generally agrees with my assertions that in large companies, there are more dividends to be paid if you specialized, particularly if you are aiming to be a technical leader. **On the other hand**, if your goal is people management, leaderships, then being a generalist actually is probably a better option, because you know how everything fits together better than the specialist._

**_Reflection: I think the key question for me is the following: Do you want to be a technical leader or a management leader. Are there examples of people transition from technical leader to management leader?_**

### Q: Zooming in on Type A work, you emphasized on the importance of thinking about things like endogeneity, causal inference, and experimental and quasi-experimental design, and I can't agree more ([here] is another related article on this topic). 

* **Why aren't people emphasizing more on these techniques, if they are so important?**
* **Is it because technology companies can just run A/B tests so randomized controlled trials are free?**
* **Is it because doing careful causal inference is too costly in the industry setting so people default back to doing correlational studies?**
* **Do you think causal inference is the critical skills that would make a good Type A DS an exceptional one. Is this skill critical to success?**

_1. For Trey, he thinks the reason that causal inference is not widely talked about is because:_

* _It's not sexy, it's not new like deep learning or big data, so people talk less about it. It's a superficial reason, but probably true. The media can be self selected on the super hot new things._

* _Tech companies can run A/B test easily, so they think randomized controlled experiment will do it all._

_2. Areas where he thinks causal inference can be helpful:_

* _It's impossible to run A/B tests_

* _It already has been run, and it's too costly to re-run again_

* _The experiment design is problematic, so we need to use causal inference technique to fix it_

* _One thing he didn't mentioned (but Emily did) is that we can use A/B test to set up Instrumental Variable methods._ 

**_Reflection: I am still confused by this though, say we have an experiment that drives email opening, and we care about retention. Why would we use IV to understand email on retention, instead of just measuring the impact of whatever feature change on retention? Maybe it's because the latter is not about email on retention, it's about that specific feature on retention._**

_3. He thinks the biggest advantage about learning causal inference is that:_

* _It helps you to better design other experiments_
* _It helps you to critique analysis with more critical eyes_
* _It makes you a more rigorous thinker_

_4. There's also the dichotomy of "prediction" and "interpretability". CS people want to build prediction model, Economists want to understand causality. They come from very different places._

**_Reflection: I think it's also cultural. DS started with CS people, gradually you have statistics people joining, and then you have the economists joining the field. Fields are shaped and promoted by prolific thinkers and writers, so it's not that they are not important, I think it is availability bias because economists were not contributing in the early years of DS._**


[here]: https://www.google.com/url?hl=en&q=http://yanirseroussi.com/2016/02/14/why-you-should-stop-worrying-about-deep-learning-and-deepen-your-understanding-of-causality-instead/&source=gmail&ust=1459957078732000&usg=AFQjCNHvoUNZhLfy55M_P2B3RoMB4U12zw