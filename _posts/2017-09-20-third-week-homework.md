---
layout: post-light-feature
title: Third Assignment Blog
description:Response to "Right to Be Forgotten Online Could Spread" and code.
categories: articles
date: 2017-09-20

---

s = "Summer searches of a writer and incoming college student."
print s.upper() #titling with an all uppercase sentance

import csv #importing the cvs
import random 
import time


search_term_list = [] #creating a list of my July through Sept. Google searches
with open ('2017_July_September_results.csv.csv','rb') as csvfile:
	reader = csv.reader(csvfile, delimiter = '\t')
	for row in reader:
		search_term_list.append(','.join(row))

L=search_term_list #lisitng item in the 24 position of the list six times at start
print L[24]*6

for item in search_term_list: #swapping uppercase and lowwer case for terms shorter than 8 characters then listing them all at once
	if len(item)<8:
		print (item.title().swapcase())

while True: #printing a random search every five seconds
	print random.choice(search_term_list)
	time.sleep(5)

Here is the code. It isn`t all that complex, but I did have fun with it. It took a lot of testing, rerunning, and realizing I need to include 'print' for items to show to get it to this point. I had a lot of trouble, but I found myself actually enjoying this. I really liked that whenever something was wrong with my code I was told the issue when I tried to run it, though I had a lot of issues at first and I would only be told of one at a time so it took me a while to get this far. It isn`t amazing, nor is it exactly what I wanted, but I am rather proud of what I got. I also managed to use my own search history, though it is only a little over two months worth. 


Responding to the article and the question "Do you think that the right to be forgotten and a right to information are at odds with each other?", I believe there is a grey area people want to ignore. A lot of personal data that is truly personal such as banking information isn`t neccesary for the general public or for the history of humanity. Very few people stand out enough that very personla information is relevant to our history. Removing searches that give away too much information may actually grant greater access to information as there is less to search through. Also the data is simply removed from search results, it isn`t wiped away all together so it is still there and thus there will eventually be a way to find it.
Another big issue in the article also seems to be an argument that freedom of speech will be hindered. Most articles and online news are centered on public figures and public events, thus they won`t be taken down with this right to be forgotten. Also freedom of speech is more than freedom of speech, it is freedom of speech as long as it does not impede upon the rights of others which includes the right to privacy. What useful or beneficial information do we get from knowing that this specific person did this specific horrible thing ? The event can be noted and shared without giving away anything such as names, locations, or pictures of the people involved thus saving the important parts of the information from being wiped away because lets face it, we will forget the people long before we forget the incident. It also creates a sense of comfort online allowing people to be more open and thus producing more data that is possibly more accurate. 
Of course with the grey area there are negatives to fit along the positives. There is no way to decide to draw the line because what each person considers personal varies. People may also argue to take down anything that they don`t like for containing personal information even if the information provided isn`t personal and/or the imformation provided is important. Taking away too much can rob people of learning opportunities or take part of our history away because we don`t know what too much would be and have no clue how this will impact us. You don`t know what something is worth until it is gone. There is also issues with borders. How defined are borders online? It seems like we have no idea and thus could cause conflict if there isn`t a worldwide agreement which is basically impossible. 
There is also issues like background checks. How much information should an employer be able to get on you? And if you wipe yourself off the internet would someone being willing to hirer you? The right to be forgotten, if taken to far, can easily run into the individuals life a lot more than when that information was public 
The two aren`t at total odds, while they clash some, it seems more neccesary to have both and find a balance. They work together about as much as they clash if not a bit more.  It cuts some of the junk we have to wade through down, opening us to more centered and accurate research, and protects both important information and individuals if we balance the right to be forgotten and the right to information.
