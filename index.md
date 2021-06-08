## Welcome to the Chat Generator Landing Page

A test framework team has been tasked with identifying a chat generator tool capable of simulating customer chat interactions with Contact Center (CC) agents. The project I have selected is to develop a test generator capable of simulating up to 20k customer chat interactions. The generator will first establish a session with the CC via several API calls and if successful will wait for an agent to answer their interaction. Once the agent answers, the generator will send a chat message and wait for the agent's response. This cycle will continue for a predefined number of loops (specified by the tester) before terminating the interaction.

A React UI will be responsible for setting the test parameters, starting/stopping each test run, and providing live test statistics and resource usage of the chat generator

To complete the test environment, a Continuous Integration /Continuous Deployment (CI/CD) pipeline (Jenkins) will automate the build and deployment of the chat generator and React applications into docker containers, each time a change is pushed to a GitHub repository



### Demo video:
[GitHub Flavored Markdown](https://vimeo.com/549611226/8f1a0c597f)

### Chat Generator NodeJS (back end)
[GitHub Flavored Markdown](https://github.com/DermotSheerin/chat-generator-ix.git)

### React UI (front end)
[GitHub Flavored Markdown](https://github.com/DermotSheerin/react-ix-load-tester.git)


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DermotSheerin/chatGenProject/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
