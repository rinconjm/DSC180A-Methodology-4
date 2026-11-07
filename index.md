# Janice Rincon
## jrinconrodriguez@ucsd.edu
### D01: AI4Good | Dr. Ali Arsanjani

1. **What is the most interesting topic covered in your domain this quarter?**
    The most interesting topic we have covered in out domain Fractal Chain of Thought, which is a prompting technique created by our mentor.
    Instead of using linear reasoning, like CoT, the LLM can look at the task in different context aperatures and iteratively optimize it search, allowing it to identify relationships and synthesize complex information.

2. **Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
    For the Quarter 2 project, I would like to continue to build on the Veracity Engine by expanding its reasoning capabilities by integrating knowledge graphs, temporal graphs, and decision graphs. Our current framework uses FCoT to analyze and evaluate the article, but I think we can improve how the system understands relationships between claims and evidence. Knowledge graphs would allow us to represent entity-entity relationships and could identify supporting or contradictory claims. Temporal graphs would not only provide a timeline for the events stated within the article, but also could provide historical context if we open aperture wide enough. Lastly, decision graphs would allow us to model the logical structure of the article, which could help the LLm's evaluation process be more transparent. 

3. **What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
    A change I'd make to the approach taken in Quarter 1 Project is to be more organized and clear in terms of system design.
    As we are building a veracity engine that will have multiple inputs from varying sources and will require API calls at different stages (potentially), I would like to take the time to figure out how each system should work and fit with the other blocks of the engine. I think this is really important moving forward since it will allow our team to work better in parallel as everyone will own a certain block.

4. **What other techniques would you be interested in using in your project?**
    I would love to incorporate more traditional machine learning / conventional NLP techniques, such as sentiment analysis or BERT, that are small to train and relatively cheap to run, to assist the initial context to be more precise. Right now, our Quarter 1 project relies on purely LLM prompts, I think having a more deterministic structure would be great to wrangle the LLM and stabilize its outputs. 
    In addition, a testing framework would be a really helpful as our veracity engine is meant to score articles for bias, truthfulness, so we need to be able to evaluate the accuracy and consistence of the outputs. 