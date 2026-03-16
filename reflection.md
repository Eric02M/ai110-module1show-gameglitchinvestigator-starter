# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.



## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the hints were backwards").

-the hints seem to mean oppposite of what they say. When I played the first time I didn't understand what was going on. The second time I guessed number starting with 76. The hint was go higher so i hit up to 100 but it said go lower. Having tested 99 I was sure it has to be between 99 and 100 only to find it was actually 56 way below my starting point. so the hints were not matching my inputs.The second time i tested 100 and it said go higher yet the bounds are 1-100 and on testing 101 ut said go lower. Above 100 belowe 101? 

-the hard category is limited to 50 but the secret guess was 72 which is clearly out of bounds of the range.

-attempts out of sync. It displays attempts left as 1 but displays the output of secret meaning it should have been ether stopped after 1 or there is an error

-the scoring system is not really clear on how it warding points. some attempts are actually wrong but I got a +5. some wrong ones I got -5 others -25

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
  - I used Github Copilot
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
  -  It said the check_guess function is where the issue was. The messages were flipped in the return guess is greater than the correct answer. I say this is true sicne the logic of the comparison used implies if we are lower we try a higher number and vice versa. However, it is not reacting as expected. I started with 56 it said go higher then after I ran out of trials the anser was 55. It sort of gets lost at 68, 69. At 68 it says go higher. At 69it says go lower

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
  - 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How? 
  a

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
