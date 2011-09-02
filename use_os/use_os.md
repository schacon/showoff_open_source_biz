!SLIDE

# quick poll #

!SLIDE

# open source maintainers? #

!SLIDE

# open source contributors? #

!SLIDE

# use / modify open source at work? #

!SLIDE bullets incremental
# You Should #

* use open source libraries
* open source company code
* use open source to recruit
* use open source to find developers
* learn from the open source model


!SLIDE subsection center
# use open source libraries #

!SLIDE 
# do not reinvent the wheel #

!SLIDE center
![](img/octocat.png)
## github.com ##

!SLIDE center
![](img/search.png)

!SLIDE center
![](img/searchlang.png)

!SLIDE

# 800,000 original projects #

	>> Repository.count(:conditions => 
		{ :parent_id => nil, :public => 1 })
	=> 805411

!SLIDE 
# get more stable, tested code than NIH #

!SLIDE 
# faster development than NIH #

!SLIDE 
# become part of a community #

!SLIDE bullets incremental

# contribute back #

* fork
* commit
* push 
* (pull request)

!SLIDE commandline incremental

	$ date
	Fri Aug 13 10:26:39 EDT 2010

	$ git clone git://github.com/test-org/test-proj
	Cloning into test-proj...
	$ cd test-proj/

	$ vim README 
	$ git commit -am 'made it better'
	[master dbeb245] made it better
	 1 files changed, 2 insertions(+), 0 deletions(-)

	$ (fork it on github)

	$ git remote add mine git@github.com:schacon/test-proj.git
	$ git push mine master:feature_name
	...
	To git@github.com:schacon/test-proj.git
	   9457e38..dbeb245  master -> feature_name

	$ date
	Fri Aug 13 10:27:49 EDT 2010


!SLIDE commandline

<pre>
$ date
Fri Aug 13 <span class="red">10:26:39</span> EDT 2010

$ git clone git://github.com/test-org/test-proj
Cloning into test-proj...
$ cd test-proj/

$ vim README 
$ git commit -am 'made it better'
[master dbeb245] made it better
 1 files changed, 2 insertions(+), 0 deletions(-)

$ (fork it on github)

$ git remote add mine git@github.com:schacon/test-proj.git
$ git push mine master:feature_name
...
To git@github.com:schacon/test-proj.git
   9457e38..dbeb245  master -> feature_name

$ date
Fri Aug 13 <span class="red">10:27:49</span> EDT 2010
</pre>

!SLIDE

# one minute #

!SLIDE

# this is why dvcs is changing OS landscape #

!SLIDE 
# GitHub examples #

!SLIDE list

### vendor/gems ###

<center>
<table class="listtb"><tr><td>
BlueCloth-1.0.0<br/>
addressable-2.1.1<br/>
ar-extensions-0.8.1<br/>
archive-tar-minitar<br/>
aws-hack-s3-0.5.1<br/>
aws-s3-0.5.1<br/>
color-1.4.0<br/>
creole-0.3.6<br/>
diff-lcs-1.1.2<br/>
eycap-0.3.1<br/>
ezcrypto-0.7.2<br/>
faker-0.3.1<br/>
faraday-0.3.1<br/>
fastercsv-1.4.0<br/>
googlebase-0.2.1<br/>
googlecharts-1.3.6<br/>
machinist-1.0.6<br/>
</td><td>
http_token_authentication<br/>
maruku-0.6.0<br/>
mechanize-0.7.5<br/>
mime-types-1.15<br/>
mocha-0.5.6<br/>
money-1.7.1<br/>
multipass-1.2.3<br/>
oauth2-0.0.8<br/>
org-ruby-0.5.3<br/>
redis_namespace<br/>
redis_rb<br/>
rtimeout-1.0.1<br/>
rubypants-0.2.0<br/>
running_man<br/>
solr-ruby-0.0.8<br/>
test-spec-0.4.0<br/>
unicorn-0.97.0<br/>
</td></tr></table>
</center>
