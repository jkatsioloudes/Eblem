# Eblem

## Who is Who


## Installation and Running


## Motivation
Implemented in my free time from mid August to mid September 2017 as part of my genuine interest in Cyber Security, especially penetration testing.
After I played around with some Kali Linux tools, I have identified a gap in performing high quality OSINT search wholly from the command line and
by a few clicks to get a browser with many tabs containing useful information.  My short term aim is to make the life of a pentester easier by providing,
constantly improving and maintaining an optimised and effective toolset with various powerful features.  My main long term goal is to contribute to
the cybersecurity progress that has yet to come in both software and hardware systems.  I will start doing so by firstly offering a more optimised OSINT
automation by a possible combination or extension of a famous and must have existing OSINT tool with features from Eblem and also I aspire of writing
or contributing into another tool that uses machine learning and AI algorithms with cybersecurity data sets to enable unsupervised decision making.

## Current version
### Powerful searches in one click
Specifically, there exist 4 flags that perform everything:
- -i for individuals
- -d for domains
- -c for companies
- -e for emails
- In addition, all of the above include social media and search engine search inclusive.

### Constantly improving user experience
- A well documented help menu explaining all the available options with examples.
- Individual flags to perform all available features in isolation.

### Targeting individuals
- Real time social media search matching the provided keyword in recent posts on everything that exists out there.
- Specific social media search using Facebook, Linkedin, Twitter (including tweets and analytics for provided user), Instagram, Pinterest, Youtube, Tumblr and Reddit.
- Multiple people search engines from various countries using just a name or both a name and a location.
- Get insights on lifetime reddit user activity by providing a username.
- Search engine search in google, duckduckgo, baidu, bing, qwant, clustering multi search, excite search (newest posts) and fact bites (old posts).
- Github and 'nerdy data' search to search keywords on published source code.
- Search about the email validity of any email and reverse email lookup.
- Perform all of the above using just one flag.

### Targeting companies
- Same social media search as above when applicable.
- Company search using multiple company search engines returning difficult to find and often confidential information about companies.
- Annual reports, slideshows, PDFs and other insights.
- Search for company's email format.
- Search engine search in google, duckduckgo, baidu and bing.
- Perform all of the above using just one flag.

### Targeting domains
- Whois lookup.
- DNS lookup.
- Web vulnerability scan.
- View archived versions of a website since its its day 1.
- View robots.txt file including links not indexed by search engines.
- Perform all of the above using just one flag.

### Other features
- Shodan.io search.
- Perform search engine search and social media search alone very easy.  These searches are included in the 'ALL in One' flags.

## Directories explained
### search
- companies.py: Includes functions able to target companies such as the edgar search.
- domains.py: Includes functions to retrieve domain info such as whois lookup and a vulnerability scanner.
- engines.py: Includes search engines such as google and people search engines such as pipl.
- other.py: Includes non directly related to OSINT functionality such as shodan search.
- socialMedia.py: Includes social media search and posts gathering in various ways.
- utilities.py: Includes functions that help in all other classes.
- query.py: The parent class from which the rest of the classes inherit, contains functionality about query manipulation.

### tests
- Clear, concise and extensive tests for each of the above class and function.
- Include specific class tests, end to end and robustness testing.

### help
- Explains with a description and an example each available function.

### intro
- Contains the welcome screen of the tool.

### main
- The main thread of the program responsible for running it.

## Future versions
- Aiming on target's mail and if pawned try to retrieve credentials.
- Advanced google dorks.
- IP address of target.
- And many more.

## Disclaimer
This tool should be used in the white hat way, however, I have no responsibility if someone will use for malicious purposes.

## License
I own all the copyrights of this project.  Feel free to contact me and suggestions new features or anything you like.
