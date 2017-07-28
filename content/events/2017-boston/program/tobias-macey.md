+++
Talk_date = ""
Talk_start_time = ""
Talk_end_time = ""
Title = "Open Sourcing Your Infrastructure"
Type = "talk"
Speakers = ["tobias-macey"]
+++


Sharing and transparency is one of the core tenets of DevOps. One outgrowth of this principle is a plethora of open source software and tooling, as well as blog posts and conference talks. Despite all of this available information, it can be difficult to understand how to put together the puzzle for a particular infrastructure, which is where reference implementations can provide greater learning and understanding than copy/pasting multiple blogs together. The trouble with much of the available reference material and example architectures is that they only cover initial setup or the first steps along the path of building a production environment. One answer to this problem is to open source the actual configuration and design of real-world systems. This serves multiple purposes that are beneficial from the level of the individual to the level of the business. You can use these points to help address resistance about releasing your work: 
- People working outside of the company can gain a greater understanding of the challenges being faced, which also helps when recruiting 
- When soliciting advice or help from the community it is easy to link to the specific piece of code or configuration that is causing the problem 
- Knowing that your work is public encourages loose coupling and more conscientious management of sensitive information which makes your code easier to maintain

While this idea may seem naïve and impossible to pursue in some companies, there is a continuum along which you can participate. If you have a brand new project you may be able to release everything publicly from day one, but if you have an established infrastructure then you can still factor out modules that can be shared.
