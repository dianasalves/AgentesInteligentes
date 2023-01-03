# IntelligentAgents

  
  The lawnmower agent(s) are reactive (memoryless) and have one goal: to mow cells with grass. Each agent is able to perceive whether the cell immediately in front of 
him, to his right and to his left, has the grass cut or not. Through the perceptions each agent can perform the actions of movement forward, rotation to its right (90º) 
and rotation to its left (-90º). 
    
 The available version is characterized by the following behavior: 
        • while finding squares in green, the lawnmower always goes forward in a direction initialized randomly in the set: [0º,90º,180º,270º]; 
        • when you find a square with grass already cut (brown) in front of it with grass to cut on your right, rotate it 90º; 
        • when you find a square with grass already cut (brown) in front of it with grass to cut on your left, rotate it by -90º; 
        • if none of the above conditions are met, the lawnmower moves on; 
        • cutting a square of grass changes its color from green to brown. 
        • the interface contains a monitor to view the total number of movements performed by the agent. 
        • 3 lawnmower operate simultaneously. 
        • There are two types of agents: lawnmowers and pests. Hypothetically, there is a type of lawn pest that causes grass to grow super-fast in a random location. 
          Whenever the plague advances one square, the grass is replaced. The pest performs random rotation actions of 90º and -90º according to a probability to be 
          defined.
