# Penetreation Testing with Kali Linux & OSCP Certification

Resources used while prepareing for and during the PWK Lab  --> 54/54 lab boxes rooted, 4/5 exam hosts* 


3 months out:
- I purchased a VIP subscription to hackthebox (HTB) and worked my way through some of the recommended boxes. I worked my way from the easier boxes to the harder ones. At first I would follow along with IppSec's videos, eventually leading to only watching the videos when I got stuck or after I rooted the box to see what I might have missed.
  - https://forum.hackthebox.eu/discussion/612/oscp-practice
  - https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA/videos
- Later on TJ_Null put together a graphic
  - https://www.reddit.com/r/oscp/comments/alf4nf/oscp_like_boxes_on_hack_the_box_credit_tj_null_on

- I also purchased a 3 month subscription to virtualhackinglabs (VHL). In retrospect a month of VHL would have been enough. However, at the $100/month price just buy a year of HTB VIP instead (unless you're looking to spend money). HTB offers a lot more content that you'll be able to take advantage of after passing OSCP. 
  - https://www.virtualhackinglabs.com
  
- It was recommend to also try a list of vulnhub VMs, however after failing to get the first 3 to work (networking) I gave up on the the vulnhub list.
  - https://www.abatchy.com/2017/02/oscp-like-vulnhub-vms

1 week out:
- At this point I had around 20 boxes rooted in HTB and another 26 in VHL. I felt like I had a good beginner knowledge base for the upcoming lab. At this point I downloaded the PWK VM, set it up to my liking (config files, settings, NO UPDATES, etc) and took the rest fo the week off to relax.

0 day: 2 March 19
- The first 8 days of my time was spent going through the pdf, exerecises and videos. I'd read a chapter in the pdf, watch the videos, and do the exercises in that order. I wasn't able to finish all exercises in thoese 9 days, but I did continue working on them randomly when I needed a break from the lab. Eventually I got them all finished and documented for the extra points (I'd NOT recommend going for the 5 points, for myself it took almost 2 days to document and format the report). On day 9 I rooted my first lab machine and finished all the exercises.
- There are 4 ranges within the lab: the first if the biggest an your VPN will land you in it, the second network consists of a few hosts, the third has a few more hosts than the second but also has a connection to an inner network. 

Jumping in! 11 March - 10 April
- Because I'm bad with decisions, I moved on 11 March and didn't get internet installed for 3 days. Duiring that time I rewatched the Buffer Overflow video a few times, taking notes and walked through dostackbufferoverflowgood several times. During the next 28 days I gained access to the 2 smaller networks rooting 28 boxes over 150 hours of lab time.
  - https://github.com/justinsteven/dostackbufferoverflowgood
- After around 20 roots (manually running scans for enumeration) I joined an awesome community. One of the Admins developed a tool called Autorecon. This tool automated all enumeration (you provide the IP) and saves the results to a folder. You just sift through the results for what's interesting. At this point Autorecon really stepped up by root speed. Twice I was able to root 4 boxes a day. Autorecon is great, BUT you have to know what to look for. Otherwise it will drown you with information.
  - https://discord.gg/qm9fxYU
  - https://github.com/Tib3rius/AutoRecon
  
Finishing strong! 11 April - 11 May
- Around this time I updated my computer (again bad with decisions) from a 2015 MacBook Pro to a beast (i9 9900k, 32gb RAM, 1tb 970 evo m.2, 2080ti, 2x Asus pg279qz, uplift sit/stand desk). A day was spent building and installing software, I knew I was going to wipe the desktop after the exam so software installation was quick.
- Early on I finished up both of the smaller networks, and gained access to the inner network. While the inner network seems to be less populated there were new techniques and concepts taught here which were not ocvered elsewhere in the labs. Definitly make an attempt to get here.
- After 185 hours I rooted 25 more boxes, bringing my total to 54. There IS a 55th box, however it's not "official" and not many people have rooted it. When I was last in the lab I was able to connect to the vulnerabler service, I'm able to get the exploit to work locally with a replicated VM, but I'm unable to exploit the service in the lab. Close but oh well. 

Motivation? 12 May - 31 May
- Getting burnt out is real, after rooting my last box I took a week off to decompress. Afterwards I finsihed on my lab report, re-did the buffer overflow and dostackbufferoverflowgood to make sure my template and methodolgy was good. I also reviewed my notes from some of the harder boxes I ran across in the lab.

Ready? 6 June 19
- I stocked up on energy drinks (Bang and Monster), along with suchi, and pizza. My plan was to eat my normal breakfast with a bang, have sushi for lunch with a monster in the late afternoon. Cold pizza in the evening and for breakfast the next morning with another bang to finish the exam.

GO! 7 June 19
- I scheduled my exam to start at noon. 15 minutes prior the email came, everything was setup in minutes, followed by the remaining minutes just waiting. 



