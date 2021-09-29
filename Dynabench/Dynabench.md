# Dynatask - The new pattern of setting the benchmarking in AI community

There is time when facebook has launched this one year ago. 
This is basically first kinf of platform that rethinks in the field of AI.
With the help of This,we can now create own custom tasks to better evaluate the performance of natural language processing...
It is more flexible,Dynamic and realistic settings for free.
#####################

Basically there is new feature present in the dynatask....
It makes easy to leaverage human annotators to actively fool NLp models.
Identify weaknesses through natural interactions.
These apporoach reflects the way people behave and react as the benchmarks set by the previous standarization.
The main point is concentrated more on fixed data points and are prone to saturation.
Baiscally we can also use evaluation-as-a-service capcapabilities and compare models on our dynamic leaderboard...
which goes beyond just accuracy and explores a more holistic measurement of fairness, robustness, compute, and memory.
##############

Dynabench is benchmarking platform that tackles many well-known problems in the field of AI just like model evaluation.
The main objective of the dynabench to overcome the problem raised by:
      a) Saturation
      b) Bias
      c) Alignment
      d) Leaderboard culture
      e) Reproducibility
      f) Accessiblity
      g) Backward compatibility
      h) Utility

 Dynabench was launched initially with four tasks:
 1) Natural language inference : - Created by Yixin Nie and Mohit Bansal of UNC Chapel Hill
 2) Question answering :-Created by Max Bortolo, Pontus Stenetorp, and Sebastian Riedel of UCL.
 3) Sentiment analysis :-Created by Atticus Geiger and Chris Potts of Stanford.
 4) Hate speech detection :-Created by Bertie Vidgen of Turing Institute and Zeerak Waseem Talat of University of Sheffield/Simon Fraser University.

#####
Basically in the last year ,Facebook has launched :
 1) Visual question answering task
 2) Low-resource machine translation tasks
 3) Powered the multilingual translation       challenge at the Workshop for Machine translations...

The dynamic data is collected ,so far there is eight published papers , 400k raw examples has been classified and four open source large scale data sets has been present..

These feature of dynabench opens up a lot of opportunities...
a)Just like it requires only little bit of coding experience.
b)easily customize annotation interfaces.
c)enable interactions with models hosted on Dynabench.
d)makes dynamic adversarial data collection considerably more accessible to the research community..

         High-quality and holistic model evaluation is critical to the long term success of AI, and we believe that Dynabench as a collaborative effort will play an important role in the future of benchmarking.
 
# The Overall Use of Dynabench:
1) Dynatask is highly flexible and customizable. A single task can have one or more owners, who define the settings of each task.
       a) For example, Users can choose which existing data sets they want to use in the evaluation-as-a-service framework.
       b) They can select from a wide variety of evaluation metrics to measure model performance, including not only accuracy but also robustness, fairness, compute, and memory.
       c)Anyone can upload models to a task’s evaluation cloud, where scores and other metrics are computed on the selected data sets.
       d)Once those models have been uploaded and evaluated, they can be placed in the loop for dynamic data collection and human-in-the-loop evaluation.
       e)Task users can also collect data via the web interface on dynabench.org or with annotators (such as Mechanical Turk).

#########################

The steps we have to performed in the benchmarking of Natural Language Inference tasks:

Step 1: Log into your Dynabench account and fill out the “Request new task” form on your profile page.

Step 2:Once approved, you will have a dedicated task page and corresponding admin dashboard that you control, as the task owner.

Step 3: On the dashboard, choose the existing datasets that you want to evaluate models on when they are uploaded, along with the metrics you want to use for evaluation.

Step 4: Next, submit baseline models, or ask the community to submit them.

Step 5: If you then want to collect a new round of dynamic adversarial data, where annotators are asked to create examples that fool the model, you can upload new contexts to the system and start collecting data through the task owner interface.

Step 6: Once you have enough data and find that training on the data helps improve the system, you can upload better models and then put those in the data collection loop to build even stronger ones.


##### Started with Dynatask
1)Dynabench is centered on community. To empower the AI community to explore better, more holistic, and more reproducible approaches to model evaluation..
2) Main aim is to make it easy for anyone to construct high quality human-and-model-in-the-loop data sets.
3)With Dynatask, you can move beyond accuracy-only leaderboards toward a more holistic evaluation of AI models..
4)Create new examples that fool existing models, upload new models for evaluation, or request your own Dynabench task now.

###############
Dynabench, an open-source platform for dynamic dataset creation and model
benchmarking.

It runs in a webbrowser and supports human-and-model-in-the-loop dataset creation.

Dynabench addresses:-
A critical need in our community: 
Contemporary models quickly achieve outstanding performance on benchmark tasks but nonetheless fail on simple challenge examples and falter in real-world scenarios...

##
With Dynabench, dataset creation, model development,
and model assessment can directly inform
each other, leading to more robust and informative benchmarks...

##
While it used to take decades for machine learning
models to surpass estimates of human performance
on benchmark tasks,

As with the rest of AI, NLP
has advanced rapidly thanks to improvements in

:::::::::
computational power, as well as algorithmic breakthroughs, ranging from attention mechanisms to Transformers  to pre-trained language models..
::::::::

##
Equally important has been the
rise of benchmarks that support the development of
ambitious new data-driven models and that encourage apples-to-apples model comparisons.

In light of these developments, one might be
forgiven for thinking that NLP has created models with human-like language capabilities. Users know that, despite our progress, we are actually far from this goal.

We believe the time is ripe to radically rethink
benchmarking. In dynabench we have to takes a
position and seeks to offer a partial solution.

The vital role leads to introduction of Dynabench, an open-source, web-based
research platform for dynamic data collection and
model benchmarking.  

####
Dynabench hosts tasks for which
we dynamically collect data against state-of-the-art models in the loop, over multiple rounds. The
stronger the models are and the fewer weaknesses
they have, 
the lower their error rate will be when interacting with humans, 
giving us a concrete metric—

Bsically, how well do AI systems perform when interacting with humans? This reveals the shortcomings
of state-of-the-art models, and it yields valuable
training and assessment data which the community 
can use to develop even stronger models.

######
######
Dynabench is a platform that encompasses different tasks. 
>>>>>>>>> Data for each task is collected over multiple
          rounds, each starting from the current state of the art.            
>>>>>>>>>>In every round, we have one or more target
          models “in the loop.” These models interact with
          humans, be they expert linguists or crowdworkers,
          who are in a position to identify models’ shortcomings by providing examples for an optional context.
          Examples that models get wrong, or struggle with,
          can be validated by other humans to ensure their
          correctness. The data collected through this process can be used to evaluate state-of-the-art models,and to train even stronger ones, hopefully creating a virtuous cycle that helps drive progress inthe field. 

          <<<<<>>>>>>>>>>>>>>>>>>>
         As a large-scale collaborative effort, the platform
         is meant to be a platform technology for humanand-model-in-the-loop evaluation that belongs to
         the entire community. 
         In the current iteration, the
         platform is set up for dynamic adversarial data collection, where humans can attempt to find modelfooling examples. 
         This design choice is due to the
         fact that the average case, as measured by maximum likelihood training on i.i.d. datasets, is much
         less interesting than the worst (i.e., adversarial) case, which is what we want our systems to be able
         to handle if they are put in critical systems where
         they interact with humans in real-world settings.

   >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>      
However, Dynabench is not limited to the adversarial setting, and one can imagine scenarios where
                 humans are rewarded not for fooling a model or
               ensemble of models, but for finding examples that
               models, even if they are right, are very uncertain
               about, perhaps in an active learning setting.   
              Similarly, the paradigm is perfectly compatible with
              collaborative settings that utilize human feedback,
              or even negotiation.  
              
              The crucial aspect of this proposal is the fact that models and humans interact
             live “in the loop” for evaluation and data collection.

     >>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>        


# Features and Implementation Details

>>>>>>>Dynabench offers low-latency, real-time feedback on the behavior of state-of-the-art NLP models.
The technology stack is based on PyTorch (Paszkeet al., 2019), with models served via TorchServe.


1) The platform not only displays prediction probabilities, but through an “inspect model” functionality,
allows the user to examine the token-level layer
integrated gradients (Sundararajan et al., 2017), obtained via the Captum interpretability library.

                For each example, we allow the user to explain
                what the correct label is, as well as why they think
                it fooled a model if the model got it wrong; or why
                the model might have been fooled if it wasn’t. All
                collected model-fooling (or, depending on the task,
                even non-model-fooling) examples are verified by
                other humans to ensure their validity.

Task owners can collect examples through the web interface, by engaging with the community, or
through Mephisto,3  which makes it easy to connect,
e.g., Mechanical Turk workers to the exact same
backend. All collected data will be open sourced,
in an anonymized fashion...


### Initial task featured by Dynabench:

##Natural language inference. 
Built upon the semantic foundation of natural logic (Sánchez Valencia, 1991, i.a.) and hailing back much further (vanBenthem, 2008), 

NLI is one of the quintessential
natural language understanding tasks. NLI, also
known as ‘recognizing textual entailment’ (Dagan
et al., 2006), is often formulated as a 3-way classification problem where the input is a context sentence paired with a hypothesis, and the output is a
label (entailment, contradiction, or neutral) indicating the relation between the pair.
    
    
    
    .>>>>>>>>>>We build on the ANLI dataset (Nie et al., 2020)
       and its three rounds to seed the Dynabench NLI
       task. 
      During the ANLI data collection process, the annotators were presented with a context (extracted
      from a pre-selected corpus) and a desired target label, and asked to provide a hypothesis that fools the
      target model adversary into misclassifying the example. 


If the target model is fooled, the annotator
was invited to speculate about why, or motivate why
their example was right. 
With the launch of Dynabench, the several innovations: not only do we select candidate contexts
from a more diverse set of Wikipedia featured articles but we also use an ensemble of two different
models with different architectures as target adversaries to increase diversity and robustness. 

>>>>>>>>>>>>>>>Moreover, the ensemble of adversaries will help mitigate
issues with creating a dataset whose distribution is
too closely aligned to a particular target model or
architecture. 
Additionally, we are collecting two
types of natural language explanations: why an example is correct and why a target model might be
wrong. 
We hope that disentangling this information will yield an additional layer of interpretability
and yield models that are as least as explainable as
they are robust.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Question answering. 
The QA task takes the same format as SQuAD1.1 


         1) Given a context and a question, extract an answer from the context as a continuous span of
            text. The first round of adversarial QA (AQA) data
            comes from “Beat the AI” (Bartolo et al., 2020).
         2) During annotation, crowd workers were presented
            with a context sourced from Wikipedia, identical to
            those in SQuAD1.1, and asked to write a question
            and select an answer. 
         3) The annotated answer was compared to the model prediction using a wordoverlap F1 threshold         and, if sufficiently different,
         considered to have fooled the model. 
         4)The target
         models in round 1 were BiDAF (Seo et al., 2017),
         BERT-Large, and RoBERTa-Large.
>>>>>>>

>>>>>>>>>>The model in the loop for the current round is
RoBERTa trained on the examples from the first
round combined with SQuAD1.1. 

>>>>>>>>Despite the
super-human performance achieved on SQuAD1.1,
machine performance is still far from humans on
the current leaderboard. 

>>>>>>>>>>>>>In the current phase, we
seek to collect rich and diverse examples, focusing
on improving model robustness through generative
data augmentation, to provide more challenging
model adversaries in this constrained task setting.


>>>>>>>>>>>>
We should emphasize that we don’t consider this
task structure representative of the broader definition even of closed-domain QA, and are looking to expand this to include unanswerable questions longer and more complex passages, Yes/No questions



####

<<<<Sentiment analysis>>>>

The sentiment analysis
project is a multi-pronged effort to create a dynamic benchmark for sentiment analysis and to
evaluate some of the core hypotheses behind Dynabench. Potts et al. (2020) provide an initial report
and the first two rounds of this dataset.

            >>>>>>> The task is structured as a 3-way classification
                    problem: positive, negative, and neutral. 
            >>>>> The motivation for using a simple positive/negative dichotomy is to show that there are still very challenging phenomena in this traditional sentiment space.
            >>>>>The neutral category was added to avoid (and
                helped trained models avoid) the false presupposition that every text conveys sentiment information (Pang and Lee, 2008). 


######                  
1) In this first phase, we examined the question of
how best to elicit examples from workers that are
diverse, creative, and naturalistic.
2) In the “prompt”
condition, we provide workers with an actual sentence from an existing product or service review
and ask them to edit it so that it fools the model.
In the “no prompt” condition, workers try to write
original sentences that fool the model.
3) We find
that the “prompt” condition is superior: workers
generally make substantial edits, and the resulting
sentences are more linguistically diverse than those
in the “no prompt” condition.

4)
In a parallel effort, we also collected and validated hard sentiment examples from existing corpora, which will enable another set of comparisons
that will help us to refine the Dynabench protocols
and interfaces. 

5)We plan for the dataset to continue to grow, probably mixing attested examples
with those created on Dynabench with the help of
prompts. With these diverse rounds, we can address a wide range of question pertaining to dataset
artifacts, domain transfer, and overall robustness of
sentiment analysis systems..


#######
>>>Hate speech detection. 
                  The hate speech task classifies whether a statement expresses hate
                  against a protected characteristic or not. 
Detecting hate is notoriously difficult given the important
role played by context and speaker the variety of ways
in which hate can be expressed (Waseem et al.,
2017). 
                   Few high-quality, varied and large training
                   datasets are available for training hate detection
                   systems (Vidgen and Derczynski, 2020; Poletto
                   et al., 2020; Vidgen et al., 2019).
Let organised four rounds of data collection and
model training, with preliminary results reported in
Vidgen et al. (2020). 
In each round, annotators are
tasked with entering content that tricks the model
into giving an incorrect classification. 

###
The content
is created by the annotators and as such is synthetic
in nature. At the end of each round the model is
retrained and the process is repeated. For the first
round, we trained a RoBERTa model on 470,000
hateful and abusive statements4
####
 This helps to identify decision boundaries within the model, and minimizes the risk of
overfitting given the small pool of annotators.
Over the periods, content becomes increasingly adversarial (shown by the fact that target models have lower performance on later rounds data)
and models improve (shown by the fact that the
model error rate declines and the later rounds’ models have the highest accuracy on each round). We
externally validate performance using the HATECHECK suite of diagnostic tests.
####################

### Caveats and Objections

There are several obvious and valid objections one can raise. We do not have all the answers, but we can try to address some common concerns.

Q) >>>>>What if annotators “overfit” on models? 

1)A potential risk is cyclical “progress,” where improved
models forget things that were relevant in earlier
rounds because annotators focus too much on a particular weakness. 
2)Continual learning is an exciting
research direction here: we should try to understand distributional shift better, as well as how to
characterize how data shifts over time might impact learning, and how any adverse effects might
be overcome. 
3)Because of how most of us have been trained, it is natural to assume that the last
round is automatically the best evaluation round,
but that does not mean that it should be the only
round: in fact, most likely, the best way to evaluate progress is to evaluate on all rounds as well
as any high-quality static test set that exists, possibly with a recency-based discount factor. 
4)To make
an analogy with software testing, similar to checklists (Ribeiro et al., 2020), it would be a bad idea
to throw away old tests just because you’ve written
some new ones.
5) As long as we factor in previous rounds, Dynabench’s dynamic nature offers a way
out from forgetting and cyclical issues: any model
biases will be fixed in the limit by annotators exploiting vulnerabilities.
Another risk is that the data distribution might
be too heavily dependent on the target model in
the loop. 
6)When this becomes an issue, it can be
mitigated by using ensembles of many different architectures in the loop, for example the top current
state-of-the-art ones, with multiple seeds.

>>>>>>Q2) What about generative tasks? 
For now Dynabench focuses on classification or span extraction
tasks where it is relatively straightforward to establish whether a model was wrong. 
If instead
the evaluation metric is something like ROUGE or
BLEU and we are interested in generation, we need
a way to discretize an answer to determine correctness, since we wouldn’t have ground truth annotations; which makes determining whether a model
was successfully fooled less straightforward. 
>>>>However, we could discretize generation by re-framing
it as multiple choice with hard negatives, or simply
by asking the annotator if the generation is good
enough. 

>>>>In short, going beyond classification will
require further research, but is definitely doable.

          1) Dynamic benchmarking is indeed expensive, but it is worth putting the numbers
in context, as all data collection efforts are expensive when done at the scale of our current benchmark    tasks. 
        2) For instance, SNLI has 20K examples
that were separately validated, and each one of
these examples cost approximately $0.50 to obtain
and validate (personal communication with SNLI
authors).
       3) Similarly, the 40K validated examples in
       MultiNLI cost $0.64 each (p.c., MultiNLI authors).
    By comparison, the average cost of creation and
    validation for ANLI examples is closer to $1.00
     (p.c., ANLI authors). This is a substantial increase
at scale. 

However, dynamic adversarial dataset may also last longer as benchmarks. If true, then
the increased costs could turn out to be a bargain.

              >>>>>>>>   We should acknowledge, though, that dynamic
                       benchmarks will tend to be more expensive than
                      regular benchmarks for comparable tasks, because
                     not every annotation attempt will be model-fooling
                     and validation is required. 
            >>>>>>>>>> Such expenses are likely
to increase through successive rounds, as the models become more robust to workers’ adversarial
attacks. 

########
The research bet is that each example
obtained this way is actually worth more to the
community and thus worth the expense.

##### Conclusion
The introduction of Dynabench, a research platform for
dynamic benchmarking.
          Dynabench opens up exciting new research directions, such as investigating the effects of ensembles in the loop, distributional shift characterisation, exploring annotator
          efficiency, investigating the effects of annotator expertise, 
          and improving model robustness to targeted
          adversarial attacks in an interactive setting.
         
         ##### It also facilitates further study in dynamic data collection,
         and more general cross-task analyses of humanand-machine interaction. 
         The current iteration of 
         the platform is only just the beginning of a longer
         journey. In the immediate future, they are trying to aim to achieve
         the following goals:
         Anyone can run a task. Having created a tool
         that allows for human-in-the-loop model evaluation
         and data collection, we aim to make it possible for
         anyone to run their own task. To get started, only
         three things are needed: a target model, a (set of)
         context(s), and a pool of annotators.

##### ,,,,,>>>>>>>>>..         
Multilinguality and multimodality. As of now,
Dynabench is text-only and focuses on English, but
we hope to change that soon.

>>>>>>>>>Live model evaluation. Model evaluation
should not be about one single number on some
test set.
          If models are uploaded through a standard
interface, they can be scored automatically along
many dimensions.

>>>>>>>>>>>>>>>>>>>
             We would be able to capture
             not only accuracy, for example, but also usage of
             computational resources, inference time, fairness,
             and many other relevant dimensions. This will in
             turn enable dynamic leaderboards, for example
             based on utility (Ethayarajh and Jurafsky, 2020).


<<<<<<<<.....>>>>>>>>
This would also allow for backward-compatible
comparisons, not having to worry about the
benchmark changing, and automatically putting
new state of the art models in the loop, addressing
some of the main objections.


     1) One can easily imagine a future where, in order
to fulfill reproducibility requirements, authors do
not only link to their open source codebase but also
to their model inference point so others can “talk
with” their model. 
     2)This will help drive progress, as
it will allow others to examine models’ capabilities
and identify failures to address with newer even
better models. 
     3)If we cannot always democratize
      the training of state-of-the-art AI models, at the
      very least we can democratize their evaluation.

