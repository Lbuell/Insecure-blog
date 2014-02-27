# Fixing the TERRIBLE Blog!!


By [Liam Buell](https://github.com/Lbuell/)

Challenge:

Check out the "insecure" branch of ivan_the_terribles_blog.

Explore the SQL Injection Vulnerability and run a brakeman report. 

 

On your own project, run brakeman and note any security issues. There may be some false positives.

Fix any real security holes in your project.  

Embed a brakeman report in your README, and a question / collabs / reflection on rails security.


### Solutions:

Used Brakeman to scan for holes, upgraded to Rails 4 and Ruby 2.1.1 which solved most of the security issues.  I also pushed it up to heroku
and used a few free security scans and they found no issues.   

## Authors


* Forked from Brooks/Icans Github by Liam Buell


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## Brakeman Results

Summary

Scanned/Reported	Total

Controllers	4

Models	3

Templates	21

Errors	0

Security Warnings	0 (0)

Ignored Warnings	0

