# Instructing Robots with Foundation Models

As a project to explore the capabilities of LLM in robotics, we utilize Prompted LLM (ChatGPT) to generate simplified task plans and simulate them in specific environments. This figure illustrates the main goal of this project, showcasing the flow of interaction and information between these three entities: the user, ChatGPT(LLM), and the simulation enviroment(robot)![figue](https://github.com/xingggu/Instructing-Robots-with-Foundation-Models/blob/main/Videos%20and%20Images/Scheme%20of%20user_LLM_simEnv.png) 

We have the user, who initiates the interaction by prompting ChatGPT and communicating the available objects and realizable actions within the world of the simulation enviroment. This interaction allows the user to demand a task later on, which, although not highly specific, provides a general idea of what they want to accomplish. After that, ChatGPT generates the appropriate task planning and code based on the user’s demand, which will then be passed on to the simulation environment, represented by the robot, which will compute and execute it. In this project, we choose **Webots** as our simulation enviroment. Finally, the user is able to observe the end results from the simulation environment and evaluate whether the robot has successfully performed the appropriate task planning or not. This feedback loop enables the user to assess the robot’s performance and make judgments based on their observations. 

More precisely, our endeavor revolves around the development of a simulated mini burger restaurant: **Cyber Burger King**, where a proficient humanoid robot manipulator adeptly prepares burgers based on minimal tasks specifications, as the video Cyber Burger King shows. The prompting instructions are depicted in video **Promptings**.
