#Today I Learned
This is a place to stash notes and tidbits of things I learned today. They may be long, they may be tiny bits. Some of these may evolve into blog posts, many will not.

**1/26/16:**
* TIL that Node is simply (not exactly simply) the Chrome V8 JS engine separate fromt the browser. (from [What Is Code](http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/#grabbag)).

**1/27/16:**
* This article may have been written before Microsoft jumped into OSS with both feet. It keeps Apple and MS in the same boat, controlling the tools of production for thier environments. Visual Studio Code and VS Community have opened up the MS IDE to a whole new world of OSS programmers, though. (And, in turn, MS is paying people to build VS tooling for OS languages like Python.)
* That bugs are a part of programming and nobody talks about that at first, "like not brining up your medical history on a first date." (love that!)
* That Bloomberg put the [code for the website](https://github.com/BloombergMedia/whatiscode) on GitHub!!

**1/28/16:**
* A really neat line that makes your cli prompt pretty and with a date: PS1="\n\[\e[0;37m\][\h] \e[0;35m\]\d\e[0m\]\n\[\e[0;31m\]\u\[\e[0;34m\] in \[\e[1;33m\]\w\[\e[m\]\[\e[0;31m\]\n\[\033[35m\]$\[\033[00m\] "

**1/29/16**
* I am (nearly) intentionally creating a merge conflict here -- looking forward to cleaning that up
* It never works to create nested git repos -- I thought I just didn't know how to do it the right way. It turns out that the right way is to never, ever nest your git repos.

**2/7/16**
* That I need to focus my efforts. Currently, I am spread across far too many domains and improvement efforts to really succeed in any of them. I'm trying to be sure to cover all of my bases and support, build and grow all areas of my life and my many facets of my professional life and I'm spread far too thin.

**2/8/16**
* nifty little trick for pulling out the keys to use as numberical indexes
* # Write a program that moves the information from the array in to the empty hash

contact_data = [["joe@email.com", "123 Main st.", "555-123-4567"],
                 ["sally@email.com", "404 Not Found Dr.", "123-234-3454"]]

contacts = {"Joe Smith" => {}, "Sally Johnson" => {}} 

contacts["Joe Smith"] = {email: contact_data[0][0], address: contact_data[0][1], phone: contact_data[0][2]}
contacts["Sally Johnson"] = {email: contact_data[1][0], address: contact_data[1][1], phone: contact_data[1][2]}

p contacts

puts joe_email = contacts["Joe Smith"][:email]
puts sally_num = contacts["Sally Johnson"][:phone]

**2/13/16**
Starting django on Mac:
left off here: https://github.com/yyuu/pyenv/blob/master/README.md#homebrew-on-mac-os-x
Gotta love environments!

**2/14/16**
New plan (perhaps belongs in the blog, but whatever. Weekdays, work through django tutorial on Surface. Weeknights and weekends, Ruby Ruby Ruby.

**2/20/16**
Going to break that plan a bit becuase I won the scholarship to Launch School. So it's going to be Launch School, Launch School, Launch School. With the help of GitHub, rvm and a little luck, I can keep everything in sync.
