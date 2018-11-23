# drop-nefarious-country
Bunch of shell scripts that basically drop traffic from entire countries via IPTables..

# Why?
Initially created due to inane bot activity from Iranian owned IPs - not massively nefarious, they're trying to hit the previous user of an IP and they've completely lost control of all things security. We don't do business with Iran as a matter of law anyway so no harm in doing this. The fact the traffic is coming from Iran - and _only_ Iran but multiple assigned companies tells me it's either a nation state actor (Revolutionary Guards seems likely) OR they've completely lost control of their networks. Either way.

# Why not drop-iran?
Keeping it generic just in case any other countries are either as useless or have nefarious intent. I will accept pull requests for other countries, accuracy fixes and the like as long as there's some not original research (whois the range is fine) - they don't have to be nefarious as a nation state really but I'm not going to do something like try to handle all the IP ranges the US has assigned for example, it simply isn't worth the time.

# What are your sources?
Nirsoft have a handy list that matches up with my experience https://www.nirsoft.net/countryip/ir.html

# What's your problem with Iran?
I have no problem with Iran just this nonsense traffic is getting right on my tats. Whatever they're trying to hit has long-since vacated the IP and their C&C hasn't noticed at least 48 hours. Militarised cyber-warfare is one thing but at least hit your target. Right now Iran isn't.
