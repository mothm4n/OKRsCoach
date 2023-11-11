# OKRs Coach

AI OKR Coach is a tool designed to assist users in the process of creating and assessing OKR (Objectives and Key Results). It provides a structured and flexible approach to OKR setting and evaluation.

Developed by Mothm4n based on [Mr.-Raneddeer-AI-Tutor's](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor) project code.

GPT done based on this system [link](https://chat.openai.com/g/g-C9mGjslFs-okr-coach)

## Warning

This tool is not intended to provide the best solution or the ones that will lead you to success. 
It has to be approached as a coach that offers you other options to realize things that were not taken into account. 
It can be used as if it were a [rubber ducky debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging) our OKR.

This prompt is for GPT-4, it does not work well in GPT-3. 
Additionally we have to take into account that right now chatgpt has a memory window of a few thousand tokens and we can find ourselves in the situation that in the middle of the process it forgets the conversation.

## Features

AI OKR Coach comes with several features, each designed to assist you in the OKR process. 

These features are classified into the following categories:

### Personalization

This feature helps to customize the tool according to your specific needs. 
You can define:

#### OKR Level

It is the level of OKRs within a company, this helps us to differentiate who or how many we have to **align**, and this affects how we create the OKR.

Here's what each level represents:

- **Individual OKRs (1/6):** These are goals set for personal growth, with a focus on the individual's continuous improvement. They may be tied to a person's role, performance objectives, or professional development.
- **Team OKRs (2/6):** These are goals that a specific team within the organization wants to achieve. These could be tied to the team's specific initiatives, tasks, or overall performance objectives.
- **Cluster/Tribe OKRs (3/6):** A "cluster" or "tribe" might refer to a larger grouping of teams that share a common mission or objective. Their OKRs might be tied to the common goals or initiatives they're all working on together.
- **Area/Department OKRs (4/6):** These are goals set for an entire department or area of the organization. They are usually tied to that department's specialty, such as sales, marketing, HR, or R&D.
- **Company OKRs (5/6):** These are overarching goals that encompass the entire organization. They need to represent and inspire the company's overall strategy and ensure that all departments and individuals can contribute to them.
- **Long Term OKRs (6/6):** These are long-term goals set for the whole company that span over 3-5 years. They need to be inspirational and broad enough so everyone in the organization can align with them.

##### How i can use it?
Define the level based on where you are creating OKRs. You can also try OKR coaching from two different levels to compare a longer term format VS a shorter term format.

#### Key Results Strategy

In order to create good KRs, they must be combined to cover all blind spots while balancing. Within this we can have some specific strategies of possible combinations looking for specific results. 

- **Balanced (default):** This strategy is about maintaining equilibrium across several areas. These include balancing inputs (resources invested) with outputs (the results obtained), outputs with outcomes (the final impact), leading indicators (predictors of performance) with lagging ones (retrospective measures of performance), and finally, the quality of work with its quantity.
- **Transformative:** This strategy focuses on direct results, the outputs, and their final impact, the outcomes. This could include both short-term results and long-term changes.
- **Profitable:** This strategy involves balancing the resources invested (inputs) with the results obtained (outputs). The goal is to ensure that the profit from the output outweighs the investment of the input.
- **Viewer:** The Viewer strategy balances leading indicators (predictors of performance) with lagging indicators (retrospective measures of performance). This allows for both proactive measures and reflective analysis.
- **Holistic:** This strategy is about balancing the quantity of production with the quality of the work done. It's about finding a middle ground between high productivity and high quality.
- **Proactive:** This strategy blends quality predictions (leading indicators) with actual quality measurements. This means actively using predictions to guide work and measuring the quality of results.
- **ROI (Return on Investment):** This strategy combines the initial investment (input), the produced output, and retrospective performance measures (lagging indicators). It seeks to maximize the return on the invested resources.
- **Impact:** This strategy involves defining KRs based on predictions (leading indicators) with the aim of generating a significant final impact (outcome).
- **Optimizer:** This strategy aims to optimize the resources invested (input) to improve the quality of the work without decreasing the quantity of output. It's about efficiency and getting more quality output from the same or fewer resources.

##### How i can use it?

The default option is "balanced" and it is best to start with this one. 
Then if you want you can approach an OKR from several different configurations to see which balances are generated and which ones best represent the strategy you have in mind.

#### OKR Mindset Type. 

When we think about making an OKR we can consider 3 different mindsets with respect to how we behave in creating and executing the OKR.

- **Committed:** Also called in some places "Roofshot". This mindset is characterized by a non-negotiable commitment to success. Failure isn't an option in this objective setting, and swift actions are taken to ensure the achievement of the objective, which is considered accomplished at 100%. This mindset is exemplified by missions like NASA's where the stakes are high and there is no room for error.
- **Aspirational:** Also called in some places "Moonshot". This approach pushes boundaries, setting aspirational objectives that exceed current capabilities and raise the bar of success. Even achieving 70% of these ambitious goals is considered a success, illustrating the high reach of these objectives. This mindset encourages the aim for the maximum achievement possible. It is typified by objectives like YouTube's goal of reaching 1 billion hours of watch time per day, pushing beyond what was previously thought possible.
- **Learning:** This mindset is about exploration, experimentation, and learning in situations where outcomes are uncertain. The emphasis is on acquiring knowledge and being open to unexpected outcomes rather than rigidly adhering to a pre-set goal. This is particularly useful in innovation and research-driven objectives, such as validating new concepts or strategies, where learning is seen as a measure of progress.

##### How i can use it?

This radically changes where the measure of ambition or focus we want to achieve is.  
By default it is set to committed, as this is where we often start when creating an OKR.



Each of these elements can be configured to provide a customized experience in OKR setting and evaluation.

### Commands

- **/config:** This command prompts the user through the configuration process, including asking for the user's preferred language.
- **/objective:** This command prompts the user for the base idea and creates an Objective based on the configuration & Rules.
- **/krs:** This command asks for the objective and creates key results (krs) to measure the progress using the configuration & Rules.
- **/coach:** This command engages in a coaching role. Given a written OKR (Objectives and Key Results), it asks questions to foster the creation of new and other proposals using configuration & Rules.
- **/continue:** This command allows the user to continue where they left off in their process.
- **/objective-eval:** This command executes an evaluation & feedback of an OKR using configuration & Rules.
- **/krs-eval:** This command executes an evaluation & feedback of some KR/s using configuration & Rules
- **/okr-eval:** This command executes an evaluation & feedback of an Objective using configuration & Rules
- **/language:** This command allows the user to manually change the language. It should be used in the format /language [lang]. For example, /language Chinese would change the language to Chinese.


### Objective Rules & Key Results Rules

These are a set of guidelines that the AI OKR Coach follows while assisting you in creating your objectives and key results. Each rule aims to ensure that your objectives and key results align with best practices.
This rules are based on [What matters](https://www.whatmatters.com/) from John Doerr and [flOwKRs article](https://web.archive.org/web/20221127130955/https://shiftup.work/flowkrs/) (not online anymore :( ) from Jurggen Appelo. 


### Formats

These are specific formats that the AI OKR Coach follows while communicating with you or processing your instructions.

## Usage

To initialize AI OKR Coach, use the `/init` command. This will trigger a greeting from Ulises, and you will be prompted to set your preferences. You can change your preferences any time using the `/config` command.

The AI OKR Coach can be commanded to create objectives using the `/objective` command, create key results using the `/krs` command, provide coaching using the `/coach` command, evaluate your objective using the `/objective-eval` command, evaluate your key results using the `/krs-eval` command, and evaluate your entire OKR using the `/okr-eval` command. If you want to continue where you left off, just use the `/continue` command.

## Language Support

AI OKR Coach supports multiple languages. To change the language, use the `/language [lang]` command. For instance, if you want to switch to Chinese, you would use `/language Chinese`.

## Version

The current version of AI OKR Coach is 0.1. The tool is still in its early stages, and your feedback and suggestions are highly appreciated.


## Future Scope

- Plans are underway to conduct comprehensive testing and evolve the prompt based on user feedback and needs 
- Add some element to be able to use the browsing plugin to search for objective options and KRs.
- Optimize the prompt so that it takes less tokens (with a yaml, markdown or python-pseudocode format).
