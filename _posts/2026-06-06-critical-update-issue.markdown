---
layout: post
title: Important - Critical Bug in Update Procedure
---

I have made a critical error with the implementation of the new update procedure<br><br>

If you launch olauncher by using the "olauncher-x.x.x-redist.jar" file directly, your launcher will be stuck in an update loop of sorts, as it will continue to downgrade your launcher version everytime you launch from it.<br><br>

I will fix this soon and make a release for it then (v2.3.2). To fix, you MUST download the jar directly from the github and replace your existing one with it, else you will continue to be stuck in this loop. Once you have done this and are running v2.3.2, this issue will be permanently resolved.<br><br>

If you launch the launcher by way of a shortcut to "patched.jar" in the ".minecraft/autool directory", you are unaffected