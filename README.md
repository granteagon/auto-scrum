# auto-scrum
AI Agent Scrum Pod

This project aims to build a AI powered srum pod using a collection of AI agents performing different tasks.  We will also make the effort to build in smart memory to give the right amount of information needed for the agent to complete a given task.

## Our Approach

This is a brand new repository, so we will likely come up with ideas that eventually get replaced by a dependency, but this is the approach we are trying to accomplish.

### Agent Teams

User should have the ability to construct a team of agents and describe their relationships, communication methods, groups and boundaries.  We shall also provide agent team and individual templates that can be used, improved and modified over time.

Note to self: See if there is somewhere we can pull this from already.

Full Tech Company Example: [CEO, Product Owner, Sales Director, Customer Researcher, Scrum Master, Developer, QA, Technical Writer, Social Media Marketer, SEO, Designer, TA, DevOps, Staffing, Branding, Accountant, CFO]

Scrum Team Example: [Product Owner, Scrum Master, Technical Architect, Developer, QA, Technical Writer, Designer]

### Product Phases
Users should be able to use templates for and self-create project phases, assign agent individuals to those teams as well as define checkpoints and completion requirements.

### Conversations
- Need to hold memory in a database
- Should be able to summarize a set of conversation items to reduce payload for agents that do not need detail at the step
- Ability to select the right team member for the question at hand
- The ability to designate leadership agents to make decisions

### Agent Persona Builder

Agents should be kept in a library and may eventually be spun off into a new repository/dependency.  A user should be able to define the mission statement (prompt) for an agent.  We should also include an Agent Builder Agent that will take the prompt, refine it with or without user input and then train that agent using materials like books, blog articles and the like to gather the materials used to drive decision making.  For example, if the user wants to create an Innovator Agent patterned after Steve Jobs, then we'll go find everything he ever said and was written about him to create a database used to drive the decision making ability of the Innovator Agent.