# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:open a file with a with open method

### Step 2: open in r mode
 
### Step 3: create a loop to get the each word

### Step 4:  split function for splitting into words

### Step 5: count variablel will count the count

### Step 6: end the program

## PROGRAM:
~~~

# program to find the word count
# developed by : Panduru Somu
# Register number: 212223240111


with  open("text.txt",'r') as f1:
    count = 0
    for x in f1:
        word = x.split()
        count+=len(word)
print(count)
~~~

### OUTPUT:
![Screenshot 2024-01-02 235307](https://github.com/Pandurusomu/Word-count/assets/148988619/078a8968-de29-460a-9ced-22a17eaf3106)



## RESULT:
Thus the program is written to find the word count from a text.
