<h1>HACKNYU 2019</h1>

## Inspiration
In today's world, it is hard to keep track of subscriptions and know how much you spend monthly in total. Do you know how much you spend on Netflix, HBO, Amazon, Pandora, Spotify, makeup, etc? Did you ever pay for subscriptions you forgot to cancel?
Our team came up with this chrome extension to help users make budgeting easier.

## What it does
SubTract automatically scrapes billing data from services you subscribe to and reminds you when your payments are due and displays whether your subscriptions are free/paid.

## How we built it
Our team created a chrome extension using HTML, CSS, js, and Chrome-built in storage API
Our team used javascript to:
  1. Fill in billing date and price when the user goes to the subscription page.
  2. Automatically alert user one day before the billing is due. 

Our team used HTML and CSS to: 
   1. Format the display of the extension
   2. Create a table to manually input subscription data 

## Challenges we ran into
Chrome Local Storage is restrictive in terms of what type of data structure you can store. It's also difficult to parse the exact tags for important information (for example, recurring date and price) in the subscription webpage. Thus, we have to parse the whole HTML source code as a text, send it as a message and search for the relevant terms there.
We can't load a lot of useful libraries into our browser extension.
No one in our team was proficient in javascript. 

## Accomplishments that we're proud of
We share ideas and help each other solve problems whenever one of us is stuck. It is also the first time that most of us used GitHub to coordinate on a group project. The end result is that we know how to create a browser extension and using GitHub efficiently.

## What we learned
We learned the chrome extension ecosystem and javascript.

## What's next for SubTrakt
Save subscription data on cloud storage (Google Cloud, AWS). Implement a budget limit and sending an email alert if you go over your budget limit.  Port the extension to other browsers such as Firefox, Safari and Edge.
