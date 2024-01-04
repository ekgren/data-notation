\---  
Title: Dano Interactive Document  
Author: Dr. Notebook  
Date: 2024-03-01  
Tags: MDX, Notebook, Interactive  
\---  

## Headings
To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (\<h3>), use three number signs (e.g., ### My Header).

```
Markdown                HTML	                    Rendered Output
# Heading level 1   	<h1>Heading level 1</h1>	Heading level 1
## Heading level 2	    <h2>Heading level 2</h2>	Heading level 2
### Heading level 3	    <h3>Heading level 3</h3>	Heading level 3
#### Heading level 4	<h4>Heading level 4</h4>	Heading level 4
##### Heading level 5	<h5>Heading level 5</h5>	Heading level 5
###### Heading level 6	<h6>Heading level 6</h6>	Heading level 6
```


## Paragraphs
To create paragraphs, use a blank line to separate one or more lines of text.

I really like using Markdown.

I think I'll use it to format all of my documents from now on.	

\<p>I really like using Markdown.\</p>

\<p>I think I'll use it to format all of my documents from now on.\</p>	

## Blockquotes
To create a blockquote, add a > in front of a paragraph.

\> Dorothy followed her through many of the beautiful rooms in her castle.
> Dorothy followed her through many of the beautiful rooms in her castle.

## Code
```python
# Simple Python code
for i in range(3):
    print(f"Number: {i}")
```

__python  
\# Simple Python code  
for i in range(3):  
    print(f"Number: {i}")  
__/python  
__stdout  
Number: 0  
Number: 1  
Number: 2  
__/stdout  
  

## Chatml  
```chatml
<|im_start|>system
You are an assistant.
<|im_end|>
<|im_start|>assistant
This is impressive! Can MDX format handle LaTeX as well?
<|im_end|>
<|im_start|>user
Absolutely, let's take a look at a LaTeX example next.
<|im_end|>
```
  
## LaTeX
$$E=mc^2$$  
  
## Other formats
\_\_json  
{  
  "feature": "Complete Notebook Functionality",  
  "status": "Implemented"  
}  
\_\_/json

```json  
{  
  "feature": "Complete Notebook Functionality",  
  "status": "Implemented"  
}  
```
