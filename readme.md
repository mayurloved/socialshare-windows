#A PhoneGap Social Sharing plugin for Windows

by [Mayur Panchal](http://www.excellentwebworld.com)



To install using cordova-cli
---


From the repo:

    $ cordova plugin add https://github.com/mayurloved/socialshare-windows.git

Sample Usage 
===

Somewhere in your code 
---

    function shareStatus()
    {
        SocialShare.shareStatus("SocialShare plugin For Windows Phone 8 by MayuR.");
    }

    function shareLink()
    {
        SocialShare.shareLink("SocialShare plugin For Windows Phone 8 by MayuR.",
                              "https://github.com/purplecabbage/social-share",
                              "By:Mayur Panchal");
    }


In your markup :
---

    <input style="display:block;margin:40px 0px" type="button" onclick="shareLink()" value="Share with Link"/>
    <input style="display:block;margin:40px 0px" type="button" onclick="shareStatus()" value="Update Text"/>
	
[![Mayur Panchal](http://excellentwebworld.com/wp-content/uploads/2013/07/logo.png)](http://www.excellentwebworld.com/ "Blogging")
