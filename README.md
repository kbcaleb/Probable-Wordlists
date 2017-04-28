### To Potential Cloners and Master-Zip Downloaders
This is a large repository. As of now, there are very few links and no torrents to the files contained within.
The current repo size is 24GB - be aware! When zipping and torrenting is complete, the repo will likely become under 1GB.

![Probable Wordlists Logo](https://raw.githubusercontent.com/berzerk0/Probable-Wordlists/master/ProbableWordlistLogo.png)


### Rev 1.1 Task List
* [x] Explain methodology
* [ ] Make Quick-fix for duplicates caused by newline and blankspace characters (not a full fix, more of a temporary patch)
* [ ] Super-Zip the smaller files
* [ ] Make some torrents for the big files (didn't expect it to catch on!)

### Rev 2 List
* More sources
* Bigger sources
* Non-ASCII Sources

### Laser-Guided Wordlist Generator in the works as well.

There are some great wordlists out there, but I decided to amalgamate, edit, trim and create a few of my own.

I did not steal, phish, deceive or hack in any way to get hold of these passwords. 
All lines in these files were obtained through freely available means.

# Probable Wordlists
Wordlists sorted by popularity originally created for password generation and testing

### Why slog through an encyclopedic, alphabetized wordlist when you can start with the words people are most likely to use?
#### Methodology - The Why and How

 While I was able to locate a few Password Wordlists that were sorted by popularity, the vast majority of lists, especially the larger lists, were sorted alphabetically. This seems like a major practicality flaw! If we assume that the most common password is "password," and we are performing a dictionary attack using an English dictionary, we are going to have to slog from "aardvark" through "passover" to get to "password." Now I don't know off the top of my head just how common "aardvark" is as a password - but we could be wasting a lot of time by not starting with the most common password on our list!

 I went to SecLists, Weakpass, and Hashes.org and downloaded nearly every single Wordlist containing real passwords I could find. These lists were huge, and I ended up with over 80 GB actual, human-generated and used passwords. These were split up among over 350 files of varying length, sorting scheme, character encoding, origin and other properties. I sorted these files, removed duplicates from within the files themselves, and prepared to join them all together.

 Some of these lists were composed of the other lists, and some were exact duplicates. I took care to remove any exact duplicate files - we didn't need to have any avoidable false positives. __*If a password was found across multiple files, I considered this to be an approximation of its popularity.*__ If an entry was found in 5 files, it wasn't too popular. If an entry could be found in 300 files, it was very popular. Using Unix commands, I concatenated all the files into one giant file representing keys to over 4 billion secret areas on the web, and sorted them by number of appearances in the single file. From this, I was able to create a large wordlist sorted by popularity, not the alphabet.


## Real-Passwords
These are **REAL** passwords. 
Every once in a while, a popular site has a high-profile security leak and passwords are released freely across the internet.
Some of these passwords can be found on aggregator sites where they are separated from usernames to protect the unfortunate victim.

The files in this folder come from https://github.com/danielmiessler/SecLists, https://weakpass.com/ and https://hashes.org/

*NOTE THAT FOR THIS FIRST VERSION, ALL NON-ASCII CHARACTERS HAVE BEEN REMOVED*


A more inclusive, and thus, more accurate list is in the works.

Lists sorted by popularity will include "probable" in the filename


## Dictionary-Style Lists

Wordlists including dictionaries, encyclopedic lists and miscellaneous.




## Attributions
 * [Ian Norden](https://github.com/iancnorden) for helping with duplicates and volunteering his time to make me a little less noobish
 * The folks over at [OWASP's SecLists](https://www.owasp.org/index.php/Projects/OWASP_SecLists_Project) for providing sources and inspiration
 * Sources like [Weakpass](https://weakpass.com/), [Crackstation](https://crackstation.net/), [Hashkiller](https://hashkiller.co.uk/) and [Hashes.Org](https://hashes.org/) for inspiration and lists.



## Disclaimer
 + These lists are for LAWFUL, ETHICAL AND EDUCATIONAL PURPOSES ONLY.
 + By using these lists, you agree to not hold the author responsible for your actions.
 + By using these lists, you agree to these terms and are completely culpable for your own behavior.

 + The files contained in this repository are released "as is" without warranty, support, or guarantee of effectiveness. However, I am open to hearing about any issues found within these files and will be actively maintaining this repository for the foreseeable future. If you find anything noteworthy, let me know and I'll see what I can do about it.
 
 + This is released without license, but also without intent for commercial use. 


