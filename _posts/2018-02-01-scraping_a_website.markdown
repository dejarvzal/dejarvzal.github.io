---
layout: post
title:      "Scraping a website."
date:       2018-02-01 17:07:49 +0000
permalink:  scraping_a_website
---


The internet has a wealth of data that can be used for a variety of things and as the resourceful humans that we are, we find all sorts of ways to use this data.  Most of the data, however, is not easily accessible.  Luckily, there are several ways to access the data.  Scraping is one of them.

Scraping, as the name suggests, is peeling back the layers to get to what’s beneath.  Web scraping is just that.  Peeling back the layers of the content on a website to get the data that you need.  You can also look at it as taking output originally intended for one purpose and extracting data from it to use that data in your program.

The information on the internet is presented to you as unstructured data in the form of HTML documents.  When you scrape, you pull this data into a structured format and use what you need.  If you think about it, all search engines scrape content from websites and display it in their own format for you to access the information you want.  

One good thing about scraping is that you can jump right in.  You don’t have to wait for a site to make an API public or contact anyone at the company to make a request.  You just browse the site and inspect the content until you find the data that you need. It is worth noting that web scraping may be against the terms of use for some websites, so it is good practice to check first before scraping.

Ruby and Nokogiri work well together to scrape data from the internet and you’ll find it relatively easy to use.  Ruby is a very straight forward Objected Oriented programming language.  Nokogiri is a ruby gem that transforms a webpage into a ruby object and makes web scraping very easy.  It parses data with CSS selectors.  One thing to note is that scraping brings down the data and parsing makes sense of the data.  

Once you find a page on the website that has the content you want, you can use your browser’s developer tools to inspect the content to find the selectors you will use to capture your data.  This can be challenging as sometimes, the selectors you will need to use are several layers down in the code and difficult to decipher.  This was the case with a site I attempted to scrape recently.  With trial and error and persistence, you can find the right selector to use.

In the end, it was worth it to continue to challenge myself to scrape the data from a particularly troublesome website.  I have learned that web scraping is as much an art as it is a science.

