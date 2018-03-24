# Welcome!

I am Mr_Lawrence. I have recently stepped out of the classroom as a high school math teacher and am now a new developer in the .NET environment. I will initially be practicing my SharePoint platform and .NET framework skills, then branching out to topics centered about gaming, AI, and machine learning. 

# Alright... First things first... What is SharePoint?

What is SHAREPOINT?!? I'm glad you asked ;). SharePoint is a platform developed by Microsoft that functions as a collaborative content management system that developers can use to create web applications. SharePoint is hosted on servers that are joined in the farm.

# What is a Farm? 

A FARM is the lowest level in the SharePoint topology (well...next to the hardware). Topology? Ooh big word...smh. That's just the way the network of servers are arranged in the farm. These farms are composed of a web front-end(WFE), application(APP), and database(DB). Basically, SharePoint is logically arranged in a Farm which can have several tiers:
    
    1. 1-tier farm: Small Farm - big things can come in small packages
        -WFE, APP, and DB are hosted on the same server --> one server
    
    2. 2-tier farm: Medium Farm - for the medium appetite --> at least two servers
        -WFE & APP on one server...DB hosted separately
    
    3. 3-tier farm: Large Farm - for the big dogs --> dedicated servers for ALL
        -WFE gets a server, APP gets a server, DB gets a server...sorry...no Oprah jokes here...that is all.
    
#Ok cool...ummm, but how are we getting this ball on the roll?

CAPACITY PLANNING to the rescue. There are five stages: M.D.P.D.M. ... AHA!!! a palindrome!
    
    1. Model: what data is used, how to get data, how do we use the data
        a. what kinda WORKLOAD we talking here?
        b. better check those IIS logs
        c. gotta set some performance targets
        AHHH!!! It's too much...or naw.
        
    2. Design: what TOPOLOGY? SAT word...LOOK IT UP!!! This is where you get the shiny stuff.
        a. PROCESSOR is the brains of this operation
        b. MEMORY is crucial...we're working with data here people!
        c. NETWORKing is the key to life...and your farm
        d. Where you gonna STORE that data when you finish?
    
    3. PTO: Pilot, Test, Optimize...yeah...they get one stage.
        a. Piloting the model is not like the real thing...but we're talking about practice
        b. TP.TE.TT - test plan, test environment, tests and tools...T's PET...memory mechanism...think about it
        c. optimize...make it better...duh
    
    4. Deploy: get it to the people homie...SharePoint has a few deployment methods and tools...checkout their site below.
    
    5. Monitor & Maintain: just make sure the people do what they came to do in the farm, but just like a real farm, it may grow!!!
[Microsoft](https://technet.microsoft.com/en-us/library/ff758645.aspx) could tell you better than I could though. They did make this daggum thing
    
#Ok... we're set up and ready for production...wait...what if we want to practice first?

I'm sure you were thinking it, right? Er...well...just in case. There are three types of SharePoint environments:
    
    1. CSD: Code, Solve, Develop - this is where you practice, my friend
    2. QA: Quality Assurance - after you develop cool stuff, you'll test it here
    3. PRO: Production - now you're playing with the big kids
    
#Excellent...you should feel like a superhero now...in fact, you have a secret "lair" within the SharePoint farm called...drumroll...
                                                        CENTRAL ADMINISTRATION!!! 
... ok, it's not the FORTRESS of SOLITUDE or whatever, but it can help you do a few things:
    
    1. admin site               4. manage farm
    2. manage web apps          5. manage apps
    3. back-up and restore      6. manage 3rd party tools
    7. create site collections and web applications
    
See [Microsoft](https://technet.microsoft.com/library/cc303422(v=office.16).aspx) for more info. They're the real MVP here. I'll be back with more. I think that'll be enough for now.
    
I have a website as well. I've used it as a tutorial site for the longest, but I'll be converting it over to my portfolio site.

[Check me out](greenhotep.com). I've just got my tutorial rates and some cube videos on there...FOR NOW... Anyway, PEACE.
