# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

I think about fifty million cases.

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

I think about half million COVID-related deaths.

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

I think California may have the highest number of COVID cases and Wyoming has the lowest.

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

Yes, they surprise me. The numbers of COVID cases and deaths are much higher than my guesses. While I knew that a considerable number of people has been infected with COVID, I still underestimated the extent of the pandemic's reach. For the states, I guessed that California has the highest number of COVID cases, which lines up with the actual result. But I did not know that American Samoa has the least as I didn't know the state before.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

King county has the highest number of cases in the Washington state. It doesn't surprise me because King county is the most populous county in Washington.

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

Because in some states, there are several counties that are tied for the lowest number of deaths related to COVID.

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

I think the number and size of inconsistencies is not very large. And people can still use this data because the numbers of COVID cases are in the millions but the difference between county_total_cases and cases is only a few thousand at most. I think this difference can be ignored.

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

I am interested in knowing which date had the highest number of new COVID cases in King County, Washington. Since I live in King County, I would like to see if the calculated result is the same as my perception. I am able to answer my question with code and the answer is 2022-01-18, which matches with my recollection of the peak of COVID.

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

I was surprised by the total number of COVID cases and curious about the pattern of change in the number of COVID cases over time. I think I will use the same analysis order as this project for my next data wrangling project - from the big aspects to the small ones, I think it is very organized.
