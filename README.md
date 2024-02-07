# admin-tools

## Deployment
- [MDS](https://twocanoes.com/products/mac/mac-deploy-stick/) - Deploy a Mac in 7 Seconds _(Twocanoes Software)_
- [macvdmtool](https://github.com/AsahiLinux/macvdmtool) - This tool lets you get a serial console on an Apple Silicon device and reboot it remotely, using only another Apple Silicon device running macOS and a standard Type C cable _(AsahiLinux)_
- [bootstrappr](https://github.com/munki/bootstrappr) - A bare-bones tool to install a set of packages on a target volume. _(munki)_
- [installr](https://github.com/munki/installr) - A tool designed for use in Recovery boot to do a "fresh" install of macOS and additional packages. _(munki)_



  [MDS](https://twocanoes.com/products/mac/mac-deploy-stick/) - Deploy a Mac in 7 Seconds_(Twocanoes Software)_

## MDM			
| MicroMDM |	micromdm	https://micromdm.io	Mobile Device Management server
| munkimdm |	munkimdm	https://github.com/munkimdm/munkimdm	Flask app for connecting Munki and MicroMDM
| NanoMDM |	micromdm	https://github.com/micromdm/nanomdm	Minimalist Apple MDM server heavily inspired by MicroMDM
			
User Experience			
DEPNotify (Jamf)	Joel Rennich	https://gitlab.com/Mactroll/DEPNotify	Small light weight notification app that was designed to let your users know what's going on during a DEP enrollment
IBM Notifier	IBM	https://github.com/IBM/mac-ibm-notifications	macOS agent used to display custom notifications and alerts to the end user
Setup-Your-Mac (Jamf)	dan-snelson	https://github.com/dan-snelson/Setup-Your-Mac	Setup Your Mac aims to simplify initial device configuration by leveraging swiftDialog and Jamf Pro Policy Custom Events to allow end-users to self-complete Mac setup post-enrollment.
Baseline	SecondSonConsulting	https://github.com/SecondSonConsulting/Baseline	An MDM agnostic zero touch solution for macOS
dockutil	kcrawford	https://github.com/kcrawford/dockutil	command line tool for managing dock items
Xcreds	Twocanoes Software	https://twocanoes.com/products/mac/xcreds/	IdP Password Syncing
Privileges	rtrouton	https://github.com/SAP/macOS-enterprise-privileges/releases/tag/1.5.3	Set a fixed timeout, in minutes, for the Dock tile's Toggle Privileges command. After this time, the admin rights are removed and set back to standard user rights. A value of 0 disables the timeout and allows the user to permanently toggle privileges.
swiftDialog	bartreardon	https://github.com/bartreardon/swiftDialog/releases	The info box is the area underneath where --icon is displayed using a secondary shade and is useful for displaying any incidental information like system information
SwiftDefaultApps	Lord-Kamina	https://github.com/Lord-Kamina/SwiftDefaultApps	Replacement for RCDefaultApps, written in Swift.
outset	macadmins	https://github.com/macadmins/outset	Automatically process packages and scripts during boot, login, or on demand.
			
Configuration and Monitoring			
ProfileCreator	ProfileCreator	https://github.com/ProfileCreator/ProfileCreator	macOS app to create standard or customized configuration profiles
LowProfile	ninxsoft	https://github.com/ninxsoft/LowProfile	A Mac utility to help inspect Apple Configuration Profile payloads.
PPPC-Utility	jamf	https://github.com/jamf/PPPC-Utility	Application for creating configuration profiles containing the Privacy Preferences Policy Control payload for macOS
SwiftDefaultApps	Lord-Kamina	https://github.com/Lord-Kamina/SwiftDefaultApps	Replacement for RCDefaultApps, written in Swift
tccutil	jacobsalmela	https://github.com/jacobsalmela/tccutil	Command line tool to modify OS X's accessibility database (TCC.db)
Apple Configurator	Apple	https://apps.apple.com/ru/app/apple-configurator/id1037126344?mt=12	-
Ansible	Red Hat	https://www.ansible.com	Open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code
Zabbix	Zabbix	https://www.zabbix.com	Open-source software tool to monitor IT infrastructure such as networks, servers, virtual machines, and cloud services
Inventory	munkireport	https://github.com/munkireport/inventory	Inventory module for MunkiReport
Sal	salopensource	https://github.com/salopensource/sal	Modular reporting for Endpoints
extensionsmanager	krypted	https://github.com/krypted/extensionsmanager	This project is to provide single pane of glass telemetry into extensions on macOS.
			
System Updates			
nudge	macadmins	https://github.com/macadmins/nudge	A tool for encouraging the installation of macOS security updates
MIST	ninxsoft	https://github.com/ninxsoft/Mist	A Mac command-line tool that automatically downloads macOS Installers / Firmwares
S.U.P.E.R.M.A.N.	Macjutsu	https://github.com/Macjutsu/super	S.U.P.E.R.M.A.N. optimizes the macOS software update experience
			
Software Installation			
Munki	Walt Disney Animation Studios	https://github.com/munki/munki	Managed software installation for macOS
MunkiReport	munkireport	https://github.com/munkireport/munkireport-php	A reporting tool for munki
AutoPKG	autopkg	https://github.com/autopkg/autopkg	Automating packaging and software distribution on macOS
Installomator	installomator	https://github.com/Installomator/Installomator	Installation script to deploy standard software on Macs
Homebrew	Homebrew	https://github.com/Homebrew	The Missing Package Manager for macOS (or Linux)
Platypus	sveinbjorn	https://sveinbjorn.org/platypus	Developer tool that creates native Mac applications from command line scripts such as shell scripts or Python, Perl, Ruby, Tcl, JavaScript and PHP program
Packages	WhiteBox	http://s.sudre.free.fr/Software/Packages/about.html	Whenever you need to create an installation package or distribution for Mac OS X 10.5 or later, Packages is the powerful and flexible solution you're looking for.
Simple-Package-Creator	rtrouton	https://github.com/rtrouton/Simple-Package-Creator	-
quickpkg	scriptingosx	https://github.com/scriptingosx/quickpkg	wrapper for pkgbuild to quickly build simple packages from an installed app, a dmg or zip archive
			
Security			
Objective-See's Tools	Objective-See	https://objective-see.org/tools.html	Free, open-source, tools to secure your Mac
Signing Manager	Twocanoes Software	https://twocanoes.com/products/mac/signing-manager/	System for securing code and package signing certificates
Santa	Google	https://github.com/google/santa	A binary authorization system for macOS
osxcollector	Yelp	https://github.com/Yelp/osxcollector	A forensic evidence collection & analysis toolkit for OS X
SilentKnight	Eclecticlight	https://eclecticlight.co/lockrattler-systhist/	automatic checking of security systems
manageSecureTokens	TravellingTechGuy	https://github.com/TravellingTechGuy/manageSecureTokens/blob/master/manageSecureTokens.sh	
SuspiciousPackage	Mothers Ruin Software	https://mothersruin.com/software/SuspiciousPackage/relnotes.html	
Crescendo	SuprHackerSteve	https://github.com/SuprHackerSteve/Crescendo	Crescendo is a swift based, real time event viewer for macOS. It utilizes Apple's Endpoint Security Framework.
escrow-buddy	macadmins	https://github.com/macadmins/escrow-buddy	A macOS authorization plugin that helps MDM administrators ensure valid FileVault keys are escrowed for all their Macs.
			
Active Directory / Open Directory			
Kerberos SSO User Guide	Apple	https://www.apple.com/business/docs/site/Kerberos_Single_Sign_on_Extension_User_Guide.pdf	-
NoMAD	Joel Rennich	https://gitlab.com/Mactroll/NoMAD	macOS menu bar application that provides all the functionality of being bound to AD, and more, without having to be bound
macosLAPS	joshua-d-miller	https://github.com/joshua-d-miller/macOSLAPS	Swift binary that will change a local administrator password to a random generated password. Similar behavior to LAPS for Windows
bugle	ABridoux	https://github.com/ABridoux/bugle	A command-line tool to post and listen to distributed notifications to execute scripts.
			
Scripts and Repos			
jamf-recovery-lock	shbedev	https://github.com/shbedev/jamf-recovery-lock	Python script to set Recovery Lock key for Apple M1 computers
reissueFVKey	-	https://tarot.shortcut.ru/community/jamf/-/tree/main/reissueFVKey	Скрипт перевыпуска и отправки ключа восстановления FileVault на небольшой Flask-сервер
Search-Scripts-In-Jamf	laurentpertois	https://github.com/laurentpertois/Search-Scripts-In-Jamf	Search for a string in all the scripts and or extension attributes in your Jamf Pro instance
brutalkeychain	krypted	https://github.com/krypted/brutalkeychain	Recover lost keychain passwords
python-jamf	University of Utah - Marriott Library - Apple Infrastructure	https://github.com/univ-of-utah-marriott-library-apple/python-jamf	library for connecting to a Jamf Server that maps directly to the Jamf Pro Classic API
Jamf Open Source Community	Jamf	https://github.com/jamf	-
diskspace	scriptingosx	https://github.com/scriptingosx/diskspace	macOS command line tool to return the available disk space on APFS volumes
FastScripts 3	red sweater	https://redsweater.com/fastscripts/	All your scripts at your fingertips
CIS-Script	mvdbent	https://github.com/mvdbent/CIS-Script	This CIS Script is build to report and remediate based on the your organisation score.
IOSSecuritySuite	securing	https://github.com/securing/IOSSecuritySuite	iOS platform security & anti-tampering Swift library
			
Knowledge			
Deployment Reference for Mac	Apple	https://support.apple.com/en-gb/guide/deployment-reference-macos/welcome/web	
Apple Device Support Tutorials	Apple	https://it-training.apple.com/tutorials/apt-support	
Jamf 100 Course	Jamf	https://docs.jamf.com/education-services/jamf-100-course/4.1/Section_1__Overview.html	
macos_security	usnistgov	https://github.com/usnistgov/macos_security/releases	macOS Security Compliance Project
Awesome iOS Security 	Cy-clon3	https://github.com/Cy-clon3/awesome-ios-security	A collection of awesome tools, books, courses, blog posts, and cool stuff about iOS Application Security and Penetration Testing.
