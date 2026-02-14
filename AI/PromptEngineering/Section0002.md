# 5 principles of prompting


## => Giving direction
* **Describe the desired style in detail, or reference a relevant persona.**

* Prompting ChatGPT

![alt text](image-1.png)

Above do a reasonable job

better one -  

![alt text](image-2.png)



## Prompt Template
1. 
```txt
Brainstorm a list of product names for a {product_description}, in the style of {famous_inventor}.

Return the results as a comma separated list, in this format:
Product description: A shoe that fits any foot size
Product names: [list of 3 product names]

## Examples
{product_examples}
```

2. 
```txt
Please rate the product names based on their catchiness, uniqueness, and simplicity. Rate them on a scale from 1-5, with 5 being the highest score. Respond only with a table containing the results.
```

![alt text](image-3.png)

![alt text](image.png)

> We can test different parts of this template. And that's the key to understanding prompt engineering . To see how it responds to performance
> Based on your better domain knowledge you can give it better direction

* Impact on Results

![alt text](image-4.png)

### Image Models - Stable Diffusion

![alt text](image-5.png)

![alt text](image-6.png)

![alt text](image-7.png)

![alt text](image-8.png)

> Giving direction is the first thing you should try. Because if you can steer the model towards something that's unique and original then you are going to get much better results specific to your use case

## => Specify Format
* Define what rules to follow, and the required structure of the response

![alt text](image-9.png)

* Impact on reuslts

![alt text](image-10.png)

* For image models

![alt text](image-11.png)

* Impact on results -  

![alt text](image-12.png)

> It take some testing toget what you want in terms of your vision

## => Provide Examples
* Insert a diverse set of test cases where the task was done correctly

* zero shock or few shock method
> Giving direction like steve jobs and format for comma separated is easy. but giving examples is bit of work . you have to find good examples and cherry pick them and put them into the prompt

* Text models -  

![alt text](image-13.png)


![alt text](image-14.png)

![alt text](image-15.png)

* By giving examples you make it more reliable but at the cost of creativity. You are constraining the creativity

![alt text](image-16.png)

* Image models

![alt text](image-17.png)

> in image models you can give example image.

![alt text](image-18.png)

## => Evaluate Quality

* Identify errors and rate responses, testing what drives performance

![alt text](image-19.png)

![alt text](image-20.png)

* Imapact on Results

![alt text](image-21.png)

* Image models

In midjourny or stable diffusion - evaluation is built in the platform

* Prompt Template - 

![alt text](image-22.png)

![alt text](image-23.png)

> Select the image which you like and then use that image as base image later for the variation which you like

* Impact on results - 

![alt text](image-24.png)

CFG scale / prompt strength

> Testing those parameters where the sweet spot is really a big key for image generation

## => Divide Labor
* Split Tasks into multiple steps, chained together for complex goals

> Basically the prompt that comes after.

![alt text](image-25.png)

> It has context from previous part of the session

![alt text](image-26.png)

* Image models
> So if you see an artist that are using AI, they're not getting it right in one prompt. They're trying lots of different prompt

> e.g. remove the background and then give to the model

![alt text](image-27.png)

* Impact onn results

![alt text](image-28.png)

## => Applying the Five Principles + Worksheet & Onej pagers
