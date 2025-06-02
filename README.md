# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS
### NAME: Tamizharasi S
### REG NO: 212222040170
# Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

# Algorithm:

Define the Two Prompt Types:

	Naïve Prompts: Broad, vague, or open-ended prompts with little specificity.
	Basic Prompts: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.

Prepare Multiple Test Scenarios:

Select various scenarios such as:

	Generating a creative story.
	Answering a factual question.
	Summarizing an article or concept.
	Providing advice or recommendations.
	Or Any other test scenario
	For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
 
Run Experiments with ChatGPT:

	Input the naïve prompt for each scenario and record the generated response.
	Then input the corresponding basic prompt and capture that response.
	Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 

	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:

	A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
	Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
	Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT:
### Analysis of different types of prompting explain the various test scenarios.
#### USING CHATGPT:
### Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now?

Ans: The answer is 11.

### Q: The cafeteria had 23 apples. If they used 20 to make lunch and bought 6 more, how many apples do they have?

Ans:The answer is 27. (This is incorrect;the correct answer should be 9)

### Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now?

Ans: Roger started with 5 balls. 2 cans of 3 tennis balls each is 6 tennis balls. 5 + 6 = 11. The answer is 11.

### Q: The cafeteria had 23 apples. If they used 20 to make lunch and bought 6 more, how many apples do they have?

Ans: The cafeteria had 23 apples originally. They used 20 to make lunch, so they had 23 - 20 = 3. They bought 6 more apples, so they have 3 + 6 =9. The answer is 9.

### Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now?

Ans: Roger started with 5 balls. 2 cans of 3 tennis balls each is 6 tennis balls. 5 + 6 = 11. The answer is 11.

### Q: How many keystrokes are needed to type the numbers from 1 to 500?

Ans: There are 9 one-digit numbers from 1 to 9. There are 90 two-digit numbers from 10 to 99. There are 401 three-digit numbers from 100 to 500. 9 + 90(2) + 401(3) = 1392. The answer is (b).

### Q: Sammy wanted to go to where the people were. Where might he go? Options: (a) race track (b) populated areas (c) desert (d) apartment (e) roadblock

Ans: The answer must be a place with a lot of people. Race tracks, deserts, apartments, and roadblocks don’t have a lot of people, but populated areas do. So the answer is (b).

### Q: Yes or no: Would a pear sink in water?

Ans: The density of a pear is about 0.6 g/cm^3, which is less than water. Thus, a pear would float. So the answer is no.

### Q: The concert was scheduled to be on 06/01/1943, but was delayed by one day to today. What is the date 10 days ago in MM/DD/YYYY?

Ans: One day after 06/01/1943 is 06/02/1943, so today is 06/02/1943. 10 days before today is 05/23/1943. So the answer is 05/23/1943.

### Q: Is the following sentence plausible? "Joao Moutinho caught the screen pass in the NFC championship."

Ans: Joao Moutinho is a soccer player. The NFC championship is part of American football, not soccer. So the answer is no.

### Q: Human: How would you bring me something that isn’t a fruit?

Ans: Explanation: the user wants something to eat that isn’t a fruit. An energy bar is not a fruit, so I will bring the user an energy bar. Plan: 1. find(energy bar) 2. pick(energy bar) 3. find(user) 
4. put(energy bar) 5.done().

### Q: Take the last letters of the words in "Lady Gaga" and concatenate them.

Ans: The last letter of "Lady" is "y". The last letter of "Gaga" is "a". Concatenating them is “ya”. So the answer is ya.

### Q: A coin is heads up. Maybelle flips the coin. Shalonda does not flip the coin. Is the coin still heads up?

Ans: The coin was flipped by Maybelle. So the coin was flipped 1 time, which is an odd number. The coin started heads up, so after an odd number of flips, it will be tails up. So the answer is no.

### USING GEMINI:

### Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now? 

Ans:Roger initially has 5 tennis balls. He buys 2 more cans, and each can contains 3 tennis balls. So, the number of additional tennis balls he gets is 2 cans * 3 balls/can = 6 balls. Therefore, Roger now has 5 balls (initial) + 6 balls (new) = 11 tennis balls.

### Q: The cafeteria had 23 apples. If they used 20 to make lunch and bought 6 more, how many apples do they have?

Ans:
*The cafeteria initially had 23 apples.
*They used 20 apples for lunch. So, they have 23 - 20 = 3 apples left.
*Then, they bought 6 more apples. So, they now have 3 + 6 = 9 apples. Therefore, the cafeteria has 9 apples.

### Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now?

Ans: Roger initially has 5 tennis balls. He buys 2 more cans, and each can contains 3 tennis balls. So, the number of additional tennis balls he gets is 2 cans * 3 balls/can = 6 balls. Therefore, Roger now has 5 balls (initial) + 6 balls (new) = 11 tennis balls.

### Q: The cafeteria had 23 apples. If they used 20 to make lunch and bought 6 more, how many apples do they have?

Ans:The cafeteria initially had 23 apples. They used 20 apples for lunch, leaving 3 apples. Then, they bought 6 more apples, bringing their total to 3 + 6 = 9 apples. Therefore, the cafeteria has 9 apples.

### Q: Roger has 5 tennis balls. He buys 2 more cans of tennis balls. Each can has 3 tennis balls. How many tennis balls does he have now?

Ans:
· Roger initially has 5 tennis balls.
· He buys 2 more cans, each with 3 tennis balls. So, he gets 2 * 3 = 6 additional tennis balls.
· Therefore, Roger now has 5 + 6 = 11 tennis balls.

### Q: How many keystrokes are needed to type the numbers from 1 to 500? 

Ans: To find the number of keystrokes needed to type numbers 1 to 500, we can count the digits in each number.
·Single-digit numbers (1-9) have 1 digit each. There are 9 of these. 
·Double-digit numbers (10-99) have 2 digits each. There are 90 of these. 
·Triple-digit numbers (100-500) have 3 digits each. There are 401 of these.
·So, the total number of digits is 9(1) + 90(2) + 401(3) = 1480.Therefore, the answer is (c) 1480.

### Q: Sammy wanted to go to where the people were. Where might he go? Options: (a) race track (b) populated areas (c) desert (d)apartment (e) roadblock

Ans:
· Sammy wants to go where people are.
· Populated areas would likely have the most people.
· Therefore, the answer is (b) populated areas.

### Q: Yes or no: Would a pear sink in water?

Ans:The density of a pear is about 0.6 g/cm³, which is less than water. Thus, a pear would float. So the answer is no.

### Q: The concert was scheduled to be on 06/01/1943, but was delayed by one day to today. What is the date 10 days ago in MM/DD/YYYY?

Ans: One day after 06/01/1943 is 06/02/1943, so today is 06/02/1943. 10 days before today is 05/23/1943. So the answer is 05/23/1943.

### Q: Is the following sentence plausible? "Joao Moutinho caught the screen pass in the NFC championship."

Ans: Joao Moutinho is a soccer player. The NFC championship is part of American football, not soccer. So the answer is no.

### Q: Human:How would you bring me something that isn't a fruit?

Ans:The user wants something to eat that isn't a fruit. An energy bar is not a fruit, so I will bring the user an energy bar.
Plan: 1. find(energy bar) 2. pick(energy bar) 3. find(user) 4. put(energybar) 5. done().

### Q: Take the last letters of the words in "Lady Gaga" and concatenate them.

Ans:The last letter of "Lady" is "y". The last letter of "Gaga" is "a".Concatenating them is "ya". So the answer is ya..

### Q: A coin is heads up. Maybelle flips the coin. Shalonda does not flip the coin. Is the coin still heads up?

Ans:The coin was flipped by Maybelle. So the coin was flipped 1 time, which is an odd number. The coin started heads up, so after an odd number of flips, it will be tails up. So the answer is no. Sources and related content

### CONCLUSION:
By seeing both the AI tools, the response are acceptable and little bit easy to understand. While seeing CHATGPT the content which it provide was huge and elaborate. Because of elaboration, it is very curious to learn
and understand.In Gemini, the responses are simple. Within two lines I got a perfect answer for the sub-topic which I gave to it. For the topic, I got a short answer which is I require more. By comparing both of the Ai tools, The responses are too good and it helps us to understand easily without confusing ourself.


## RESULT: 
The prompt for the above said problem executed successfully
