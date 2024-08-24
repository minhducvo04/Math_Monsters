# Math_Monsters
Calhacks 2024 Project
The idea of the problem is to make solving Maths problems like playing video games.

## Features:
- Reward system: Using AI-generated monster images as tokens to collect as the users complete a certain number of correct answer
- Gacha system: In order to compete with addictive games, we think implementing some uncertainty into the system will create the scarcity to the rare icons which is expected to increase the eagerness to continue 'playing' and doing more problems.
- Problem banks: We are using Mathpix API to generate problems with suggested solutions.
- Grading system: Since we have no funding, we use GPT models to grade the students work by comparing with suggested solution from Mathpix API. For more complicated problems from high school levels and above, we ask the Wolfram Alpha first (using their API) and then using GPT models to compare the results.
- Community system (To be announced): We want to have some events/ minigames to put the 'monsters' to play

## Frameworks:
- 100% of the code is written in Python
- GPT models for comparing results and grading
- WolframAlpha API
- AWS Bedrock for Image Generation
- Mathpix API for problem + solution generation
- Gradio for display
