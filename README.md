# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
 create a function name count_words
### Step 2: 
 split the user text using split() method
### Step 3: 
print the length of the word using len() method
### Step 4:  
here the main function begins. take the input function from the user and store it in user_input variable
### Step 5: 
To count the words execute the above function by function calling. use print() to print the output
### Step 6: 
excecute the program
## PROGRAM:
```
Developed by: Nirosha M
register No : 23014438

def count_words(text):
    words = text.split()
    return len(words)

if __name__=="__main__":
    user_input=input("Enter a text:")
    word_count=count_words(user_input)
print(f"word count: {word_count}")

```
### OUTPUT:

![Alt text](<Annotation 2023-12-26 090843.png>)

## RESULT:
Thus the program is written to find the word count from a text.
