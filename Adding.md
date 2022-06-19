# Adding a package

Yo. Wanna add a package? Well you're  
at the **right** place! The simple command for a package is:
`xeon add <code-link>`.  
  
So, you may be wondering what's the code link. Well, you can put something like a Pastebin :D
The code, is quite compilcated. It contains Python programming experience, so learn about it.
Here is some documented example code:

```
## Lorem ispum dolor sit amet

# Package details
pkgname = "example" # Package name, make it short.
pkgver = 1.0 # Version of the package
pkgd = "Example program, used in Xeon docs." # Brief package descr.
pkgdir = "/usr/share/example" # Used for removing packages.

# Package build code - Actual Python 3 code
pkgbuild = """
           import example
           example.download(f"{pkgname}{pkgver}",key="69Yu_dGhL-21m")
           """

# Author details - OPTIONAL
author = "sckshwarg" # Your name
mail = "sckshwarg@example.org" # Email

# Extra options
app = True # Enables application shortcut, use True | False
appicon = "https://example.org/69Yu_dGhL-21m/icon" # App icon, use a raw icon from a website.
appexec = "/usr/bin/example" # Which file to execute when the app is clicked
appname = "Example Program" # What the shortcut should be named as
appcategory = ["foo","bar"] # Which categorys should this app be in
```

## More app customization?

Yes, that's right. You can create your own .desktop file!  
Using `customapp = True`, and your .desktop file code in:  
  
```
customappc = """
             Desktop code here
             """
```
  
you can customize your application as much as you want.

## That's it!

Well, that was fast. You have made a package!
