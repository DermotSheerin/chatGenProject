## Welcome to the Chat Generator Landing Page
### Developer: Dermot Sheerin

A test framework team has been tasked with identifying a chat generator tool capable of simulating customer chat interactions with Contact Center (CC) agents. The project I have selected is to develop a test generator capable of simulating up to 20k customer chat interactions. The generator will first establish a session with the CC via several API calls and if successful will wait for an agent to answer their interaction. Once the agent answers, the generator will send a chat message and wait for the agent's response. This cycle will continue for a predefined number of loops (specified by the tester) before terminating the interaction.

A React UI will be responsible for setting the test parameters, starting/stopping each test run, and providing live test statistics and resource usage of the chat generator

To complete the test environment, a Continuous Integration /Continuous Deployment (CI/CD) pipeline (Jenkins) will automate the build and deployment of the chat generator and React applications into docker containers, each time a change is pushed to a GitHub repository



### Demo video:
[Demo Video](https://vimeo.com/549611226/8f1a0c597f)

### Chat Generator NodeJS (back end):
[Chat Generator Repo](https://github.com/DermotSheerin/chat-generator-ix.git)

### React UI (front end):
[Chat Generator UI](https://github.com/DermotSheerin/react-ix-load-tester.git)

### Project Report
[Chat Generator Report](https://github.com/DermotSheerin/chatGenProject/blob/main/Dermot_Sheerin.pptx)

### Project Slides
[Chat Generator Presentation Slides](https://github.com/DermotSheerin/chatGenProject/blob/main/Final%20Report%20DermotSheerin.pdf)

