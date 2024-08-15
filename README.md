# AI Agents in LangGraph

This project provides a comprehensive exploration of AI agents using the LangGraph framework.

## What is an Agent?
An **agent** is like a smart helper that can work on its own to get things done. It’s designed to understand its surroundings, make decisions, and take actions without needing constant guidance from a person.

### Main Features of Agents:
1. **Autonomous**: Agents can operate on their own, making decisions and taking actions independently.
2. **Perceptive**: They observe their environment through sensors or data inputs, like a smart thermostat that senses temperature.
3. **Decision-Making**: Based on what they perceive, agents decide the best course of action, like a navigation app choosing the fastest route.
4. **Action-Oriented**: After deciding, agents act to influence their environment, whether it's sending a message, adjusting a setting, or moving an object.
5. **Adaptable**: Some agents can learn and improve over time, adapting to new situations just like a personalized recommendation system that gets better with use.

In short, agents are autonomous, perceptive, and action-oriented entities designed to help achieve goals by making smart decisions on their own.

## Covered in the notebooks
1. [LangGraph Components](/langgraph_components.ipynb)
2. [Agentic Search](/agentic_search.ipynb)
3. [Persistence and Streaming](/persistence_and_streaming.ipynb)
4. [Human in the loop](/human_in_the_loop.ipynb)
5. [Essay Writer](/essay_writer.ipynb)
6. [Helper code for the GUI](/helper.py)

## Extra-Extra

### 1. Multi-Agent Systems
![multiagent](images\multi_agent.png)  

**Analogy: A Team of Detectives Working on a Case**
- Imagine a team of detectives working together to solve a complex case. Each detective specializes in different aspects: one might handle interviews, another analyzes evidence, and a third conducts surveillance.
- **Shared State**: They all share information in a central case file, so everyone knows what the others have discovered.
- **Distributed State**: Alternatively, each detective might keep their own notes but share key findings during team meetings.

**Key Idea**: Like a team working on different parts of a problem, each agent in a multi-agent system works on its own tasks, but they collaborate to achieve a common goal.

**Practical Applications**:
1. **Autonomous Drones**: Swarms of drones working together in disaster management.
2. **Smart Grids**: Optimizing energy distribution and consumption.
3. **E-commerce Personalization**: Enhancing user experiences on shopping platforms.
4. **Collaborative Robots (Cobots)**: Efficient production lines in manufacturing.
5. **Healthcare Management**: Coordinated patient care systems.
6. **Urban Traffic Control**: Managing autonomous vehicles in smart cities.
7. **Financial Market Analysis**: Coordinated trading and risk management.
8. **Game AI**: Enhanced non-player character (NPC) interactions.
9. **Supply Chain Optimization**: Streamlining logistics and inventory management.
10. **Collaborative Filtering Systems**: Personalized content recommendations.

### 2. Supervisor
![supervisor](/images/supervisor.png)

**Analogy: A Sports Coach Overseeing a Team**
- Think of a sports coach during a game. The coach doesn't play but watches all the players (agents) on the field, making sure they're following the strategy, performing well, and adjusting tactics as needed.
- The coach might call timeouts to give instructions, change players, or alter the game plan if something isn't working.

**Key Idea**: The Supervisor is like the coach who oversees and manages the agents, ensuring they perform correctly and making adjustments when necessary.

**Practical Applications**:
1. **Call Center Management**: Monitoring and managing customer service bots.
2. **Manufacturing Quality Control**: Overseeing production robots to ensure quality.
3. **IT System Monitoring**: Detecting and responding to server issues.
4. **Online Learning Platforms**: Tracking student progress and offering feedback.
5. **Retail Inventory Management**: Ensuring timely restocking based on sales data.
6. **Energy Management**: Optimizing smart building systems for efficiency.
7. **Logistics and Transportation**: Managing delivery fleets for optimal performance.
8. **Social Media Monitoring**: Detecting and managing harmful content.
9. **Healthcare Operations**: Overseeing hospital resource allocation.
10. **Customer Feedback Analysis**: Triggering actions based on feedback trends.

### 3. Flow Engineering
![flow_engineering](/images/flow_engineering.png) 

**Analogy: Traffic Management in a City**
- Imagine a city’s traffic control system. Traffic engineers design the flow of vehicles through the city using traffic lights, signs, and lanes.
- They ensure that cars move efficiently from one part of the city to another, avoiding bottlenecks and minimizing delays. If one route is congested, they might redirect traffic or adjust light timings to improve the flow.

**Key Idea**: Flow engineering in a system is like managing traffic in a city, ensuring that tasks (or data) move smoothly through the system without delays or conflicts.

**Practical Applications**:
1. **Warehouse Automation**: Streamlining the movement of goods.
2. **Data Pipeline Management**: Ensuring smooth data flow in big data systems.
3. **Software Development**: Optimizing CI/CD pipelines for seamless deployments.
4. **Healthcare Patient Flow**: Managing patient movement through hospitals.
5. **Telecommunications Networks**: Allocating bandwidth to avoid network congestion.
6. **Public Transportation Systems**: Optimizing schedules and routes for efficiency.
7. **E-commerce Checkout Processes**: Reducing friction in online shopping carts.
8. **Manufacturing Process Optimization**: Ensuring smooth production workflows.
9. **Content Delivery Networks (CDNs)**: Efficient global distribution of digital content.
10. **Urban Infrastructure Planning**: Designing cities to handle current and future demands.

### 4. Language Agent Tree Search
![language_agent_tree_search](/images/language_agent_tree_search.png)

**Analogy: A Chess Player Considering Possible Moves**
- Picture a chess player thinking several moves ahead. The player looks at the current position and considers various possible moves (branches), imagining how the opponent might respond to each.
- The player mentally explores these potential moves, choosing the one that seems to offer the best chance of winning the game.

**Key Idea**: Language Agent Tree Search is like a chess player exploring different potential actions or paths before choosing the best one to achieve a desired outcome.

**Practical Applications**:
1. **Legal Document Analysis**: Exploring legal interpretations and drafting documents.
2. **Medical Diagnosis Assistance**: Suggesting diagnoses based on symptoms.
3. **Strategic Business Planning**: Evaluating business strategies and market trends.
4. **Creative Writing and Content Generation**: Exploring different storylines and characters.
5. **Customer Support Automation**: Optimizing responses to customer queries.
6. **Financial Portfolio Management**: Exploring investment strategies and risk factors.
7. **Game Development and AI**: Enhancing storytelling and player experiences.
8. **Contract Negotiation**: Assisting in drafting and negotiating terms.
9. **Education and Tutoring**: Personalizing lessons for students.
10. **Crisis Management**: Choosing the best action plan in emergency situations.


### 5. Plan and Execute
![plan_execute](/images/plan_and_execute.png)
