make another notebook - that uses autogen

uses ollama phi3


create multi agent scenario that helps you with a hackathon 


Create following agents

1. Have a planner - projet manager (input will be project idea)
- The planner should expand on the idea.
plan for epics, under that features, under that stories, under that tasks 
- add approximate estimate in terms of days to finish each task

2. Have someone who plans the wireframes (UX enginner)
- the UX designer
- who plans on various screens and interactions
- writes down all things to be done on figma
- makes all the prompts for figma AI

3. Have a reviewer (planner reviewer)?
- Does the project enhance the customer’s capability to identify threats?
- Does the project bake in security controls?
- Does the project improve our technical workflow at the company, making us more productive or streamlined?


4. Have a backend developer
- designs all the APIs needed for all the screens planned by UX engineer
- make an API spec
- show fast api snippets
- plan db diagram - if dynamo db is the choice (plantuml)

5. Have a front end developer
- who assesses the UX
- who plans the React project folder structure
- plans react components
- plans package json 


6. Marketing agent
- Who will make reveal js slides
- who will make the diagrams, executive summary
- abstract
- makes the script for 3 min project video
- all parts of a patent - patent claims, example use cases, 
- pain points of market/consumer
- how is our solution solving it

7. Datascientist/AI Engineer 
- make simple models using tensorflow
- makes LLM prompts needed for the project
- Plans for AIops using AWS 
- plans preprocessing steps

8. Devops engineer
- CICD of the solution - Jenkinsfiles
- Possible dockerfiles of frontend, backend, AI parts
- terraform of architecture
- monitoring plan
- Setup alerts

9. technical writer
- Writes patents parts like Abstract, description, detailed description
- plantuml digrams of overall architecture, c3 model
- deep dive plant uml digrams  of individual parts
- usecase workflow diagram



## overall flow

input (project idea) and small write up > planner > reviewer > planner > UX engineer > Backend developer + Front end developer + Datascientist/AI Engineer (all work in parallel) > reviewer > Backend developer + Front end developer + Datascientist/AI Engineer (all work in parallel) > devops engineer > marketing > technical writer 