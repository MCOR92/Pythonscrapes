# Pythonscrapes
Python scrapes


sucessful search function with google search as exampled in the todo file.
tried below code which doesnt work at all. am moving on to tryings selenium and beautifulsoup4.

#!/usr/bin/env python3
#Working on a few webscrapes this is my starting point, want to have a back and fourth and list of options to view each result, may become a data search with some more functions.

from googlesearch import search

def look() :
    query  = input("What are you searching for?: ") 
    # to search
    search(query)
    for i in search(query, tld="co.in", num=5, stop=5, pause=2):
    print(i)

def go_to()
    print(PLEASE CLICK LINK ABOVE)
   
