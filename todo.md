
# TODO

1. DONE Update the Yeoman ASP.NET templates
1. DONE Install ASP.NET
1. DONE Try building out a coreclr app and publish to Azure
1. DONE Update the global.json file to target Beta8
 1. Update both the demos.md file and the code snippets
1. Export the code snippets to the repo

1. Just plan on installing Beta7 and building out another demo app with that for deploying to Azure???
1. Use Visual Studio instead of Mac OS X???
 1. http://docs.asp.net/en/latest/getting-started/installing-on-windows.html#install-asp-net-with-visual-studio
 1. Build the app in Mac OS X and publish from Windows using VS???
1. Just skip deploying to Azure???

1. Update references to `dnx kestrel` to `dnx web`

1. Update the Sandbox image
 1. Update the Yeoman ASP.NET templates
 1. Remove the old GitHub repo
 1. Clone the new GitHub repo
 1. Update the code snippets
 1. Update the bash_profile with call to `source dnvm.sh`

1. Reset the Dry Run image
1. Run through slides
1. Run through demo
1. Test publishing to Azure
1. Reset the Live image

New Features to Test

1. Referencing a dependency that specifies a newer version of the runtime will
now cause a specific error to display
1. dnx-watch
1. Others???

## ASP.NET Updates

Blog post announcing the release of Beta8
	http://blogs.msdn.com/b/webdev/archive/2015/10/15/announcing-availability-of-asp-net-5-beta8.aspx

Beta8

* New hosting model
* Only Kestrel is available now
* IIS will be used as a reserve proxy
* VS tooling improvements

RC

* Logging improvements
* Ability to dial up or down logging per ASP.NET section
* Pretty printed console logging (i.e. green, yellow, red)
* More Kestrel perf improvements

How to find out about changes

* Announcements repo on GitHub is a list of all of the changes
* Release notes

Path to RTM

* The goal is that an app that runs on RC will run on RTM without any (or few) changes

## Questions

## Preparation

1. DONE Install Mac OS X on external drive
1. DONE Install Yosemite update
1. DONE Install Xcode, TextExpander, sqlitebrowser, Chrome
1. DONE Setup SSH keys
1. DONE Setup .bash_profile
1. DONE Download presentation slides and PDF
1. DONE Make copy of the partition
1. DONE Setup GitHub repo
1. DONE Setup Azure Web App

## Right before presentation...

1. Clone GitHub repo
1. Have Safari open to my repo
1. Have private Chrome tab open to Azure
1. Make sure that MiFi is setup
1. Test WiFi speeds
1. Disable power save features on the Surface
