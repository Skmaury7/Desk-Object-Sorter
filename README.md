# AI Desk-Object-Sorter

## Project Description  
This project uses Google's Teachable Machine to help identify common desk objects using a webcam. I trained the model to recognize three items. A pen. A pair of scissors. A book.

## Classes Identified  
* Pen  
* Scissors  
* Book  

## Discussion and Reflection  

### 1. Model Performance and Iteration  
**How the first model worked:** The first version was not very accurate. It mostly guessed “book” no matter what I showed it.  
**How I improved it:** I added more images, especially for the pen and scissors, and used different angles and backgrounds.  
**What changed:** The model improved significantly. By the end, it recognized all three objects correctly most of the time, even in different lighting.

### 2. Challenges and Observations  
**Easiest object:** The book was easiest because it was big and easy to photograph from different angles.  
**Hardest object:** The pen was harder because it is small and looks different depending on the angle. Sometimes the model confused it with scissors.  
**What happened with unknown objects:** The model still tried to guess one of the classes, but the confidence score was lower. That showed me it does not really know how to say “I don’t know.”

### 3. Bias in AI  
If I only used one type of object in training, it probably would not recognize other variations of that same type of item. That is how bias can happen from limited data.  
I also noticed that if the lighting and/or background changed too much, the model got less accurate. This showed how training in only one setting can make the model less reliable.

### 4. Model Limitations and Usefulness  
**Limitations:** The model only works on the exact types of objects I trained it on. It can also get confused if two items look similar.  
**Why exporting is helpful:** It is useful to download the trained model files because it lets me save and share the model without having to retrain it every time. Putting the files on GitHub also makes it easier to work on the project later or let someone else test or improve the model. It shows how machine learning projects can be saved and reused in other places, like websites or apps.

### 5. Real-World Applications and Ethics  
**Possible uses:**  
1. Helping sort supplies in a classroom  
2. Basic organization tools for offices  
3. Making simple assistive tools for people who have trouble remembering or identifying items, like in a memory care unit  

**One ethical concern:** One ethical concern is that the model is based only on how things look on my desk. That means it might not work well for someone else who has a different kind of pen or book or different lighting and background. This shows how AI can be biased if it only learns from one person’s environment, which makes it less fair or useful for others.

## Challenges Faced or Interesting Discoveries  
I learned that how the scissors were positioned made a big difference. The model did better when they were open. I also found that holding the pen in my hand helped a lot compared to showing it flat on the table.

## Screenshot  
<img width="1249" alt="image" src="https://github.com/user-attachments/assets/45b1f6ca-b659-4b81-b703-598a7fdc259c" />

