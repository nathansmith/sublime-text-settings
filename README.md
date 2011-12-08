These are my settings for Sublime Text 2.

http://sublimetext.com/2

I made this repo for myself, so I have an easy way to back them up. But if you like 'em, or want to tweak to your liking, cool beans.

On OS X, these files would reside in:

`~/Library/Application Support/Sublime Text 2/Packages/User/`

---

I am using the RailsCasts (TextMate) theme, which works fine in Sublime. You can download that theme here:

http://railscasts.com/about

---

Note: I am using SublimeLinter, which auto-validates JavaScript files via JSHint (as well as other languages).

https://github.com/Kronuz/SublimeLinter

So, that's what this code pertains to:

    "jshint_options": {
      "evil": false,
      "expr": true,
      "eqeqeq": true
    }