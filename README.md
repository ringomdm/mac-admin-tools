 # ⭐️ Awesome free and useful macadmin tools 👨🏻‍💻

## Contents
- [Deployment](#dpl)
- [MDM](#mdm)
- [User Experience](#ue)
- [Configuration and Monitoring](#cam)
- [System Updates](#su)
- [Software Installation](#si)
- [Security](#sec)
- [Active Directory / Open Directory](#adod)
- [Scripts and Repos](#sar)

## <h2 id="dpl">Deployment</h2>
- [MDS](https://twocanoes.com/products/mac/mac-deploy-stick/) - Deploy a Mac in 7 Seconds _(Twocanoes Software)_
- [macvdmtool](https://github.com/AsahiLinux/macvdmtool) - This tool lets you get a serial console on an Apple Silicon device and reboot it remotely, using only another Apple Silicon device running macOS and a standard Type C cable _(AsahiLinux)_
- [bootstrappr](https://github.com/munki/bootstrappr) - A bare-bones tool to install a set of packages on a target volume _(munki)_
- [installr](https://github.com/munki/installr) - A tool designed for use in Recovery boot to do a "fresh" install of macOS and additional packages _(munki)_

## <h2 id="mdm">MDM</h2>
- [MicroMDM](https://micromdm.io) - Mobile Device Management server _(micromdm)_
- [munkimdm](https://github.com/munkimdm/munkimdm) - Flask app for connecting Munki and MicroMDM _(munkimdm)_
- [NanoMDM](https://github.com/micromdm/nanomdm) - Minimalist Apple MDM server heavily inspired by MicroMDM _(micromdm)_

## <h2 id="ue">User Experience</h2>			
- [DEPNotify (Jamf)](https://gitlab.com/Mactroll/DEPNotify) - Small light weight notification app that was designed to let your users know what's going on during a DEP enrollment _(Joel Rennich)_
- [IBM Notifier](https://github.com/IBM/mac-ibm-notifications) - macOS agent used to display custom notifications and alerts to the end user _(IBM)_
- [Setup-Your-Mac (Jamf)](https://github.com/dan-snelson/Setup-Your-Mac) - Setup Your Mac aims to simplify initial device configuration by leveraging swiftDialog and Jamf Pro Policy Custom Events to allow end-users to self-complete Mac setup post-enrollment. _(dan-snelson)_
- [Baseline](https://github.com/SecondSonConsulting/Baseline) - An MDM agnostic zero touch solution for macOS _(SecondSonConsulting)_
- [dockutil](https://github.com/kcrawford/dockutil) - command line tool for managing dock items _(kcrawford)_
- [Xcreds](https://twocanoes.com/products/mac/xcreds/) - IdP Password Syncing _(Twocanoes Software)_
- [Privileges](https://github.com/SAP/macOS-enterprise-privileges) - For Mac users in enterprise environments, this application gives users control over the administration of their machine by elevating their level of access to administrator privileges on macOS. Users can set a timeframe in the application's settings to perform specific tasks, such as installing or removing an application. _(SAP)_
- [swiftDialog](https://github.com/bartreardon/swiftDialog/releases) - The info box is the area underneath where --icon is displayed using a secondary shade and is useful for displaying any incidental information like system information _(bartreardon)_
- [SwiftDefaultApps](https://github.com/Lord-Kamina/SwiftDefaultApps) - Replacement for RCDefaultApps, written in Swift _(Lord-Kamina)_
- [outset](https://github.com/macadmins/outset) - Automatically process packages and scripts during boot, login, or on demand _(macadmins)_
- [PrivilegesDemoter](https://github.com/sgmills/PrivilegesDemoter) - Allow users to self manage admin privileges, while reminding them to operate as standard whenever possible _(sgmills)_

## <h2 id="cam">Configuration and Monitoring</h2>			
- [iMazing Profile Editor](https://imazing.com/profile-editor) - Create, Edit, and Sign Apple Configuration Profiles _(iMazing)_
- [ProfileCreator](https://github.com/ProfileCreator/ProfileCreator) - macOS app to create standard or customized configuration profiles _(ProfileCreator)_
- [LowProfile](https://github.com/ninxsoft/LowProfile) - A Mac utility to help inspect Apple Configuration Profile payloads _(ninxsoft)_
- [PPPC-Utility](https://github.com/jamf/PPPC-Utility) - Application for creating configuration profiles containing the Privacy Preferences Policy Control payload for macOS _(jamf)_
- [SwiftDefaultApps](https://github.com/Lord-Kamina/SwiftDefaultApps) - Replacement for RCDefaultApps, written in Swift _(Lord-Kamina)_
- [tccutil](https://github.com/jacobsalmela/tccutil) - Command line tool to modify OS X's accessibility database (TCC.db) _(jacobsalmela)_
- [Apple Configurator](https://apps.apple.com/ru/app/apple-configurator/id1037126344?mt=12) - _(Apple)_
- [Ansible](https://www.ansible.com) - Open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code _(Red Hat)_
- [Zabbix](https://www.zabbix.com) - Open-source software tool to monitor IT infrastructure such as networks, servers, virtual machines, and cloud services _(Zabbix)_
- [Inventory](https://github.com/munkireport/inventory) - Inventory module for MunkiReport _(munkireport)_
- [Sal](https://github.com/salopensource/sal) - Modular reporting for Endpoints _(salopensource)_
- [extensionsmanager](https://github.com/krypted/extensionsmanager) - This project is to provide single pane of glass telemetry into extensions on macOS _(krypted)_
- [UI BROWSER](https://latenightsw.com/freeware/ui-browser/) - ultimate assistant for Apple’s Accessibility and AppleScript GUI Scripting technologies. It helps you to explore, monitor, and control the user interface of most applications running on macOS _(Late Night Software)_
- [LogUI](https://eclecticlight.co/wp-content/uploads/2025/03/logui127.zip) - lightweight log browser _(Eclectic Light)_
		
## <h2 id="su">System Updates</h2>			
- [nudge](https://github.com/macadmins/nudge) - A tool for encouraging the installation of macOS security updates _(macadmins)_
- [MIST](https://github.com/ninxsoft/Mist) - A Mac command-line tool that automatically downloads macOS Installers / Firmwares _(ninxsoft)_
- [S.U.P.E.R.M.A.N.](https://github.com/Macjutsu/super) - S.U.P.E.R.M.A.N. optimizes the macOS software update experience _(Macjutsu)_
- [SOFA](https://github.com/macadmins/sofa/tree/main) - SOFA | A MacAdmin's Simple Organized Feed for Apple Software Updates
- [mist-cli](https://github.com/ninxsoft/mist-cli) - A Mac command-line tool that automatically downloads macOS Firmwares / Installers

## <h2 id="si">Software Installation</h2>			
- [Munki](https://github.com/munki/munki) - Managed software installation for macOS _(Walt Disney Animation Studios)_
- [MunkiReport](https://github.com/munkireport/munkireport-php) - A reporting tool for munki _(munkireport)_
- [AutoPKG](https://github.com/autopkg/autopkg) - Automating packaging and software distribution on macOS _(autopkg)_
- [Installomator](https://github.com/Installomator/Installomator) - Installation script to deploy standard software on Macs _(installomator)_
- [Homebrew](https://github.com/Homebrew) - The Missing Package Manager for macOS (or Linux) _(Homebrew)_
- [Platypus](https://sveinbjorn.org/platypus) - Developer tool that creates native Mac applications from command line scripts such as shell scripts or Python, Perl, Ruby, Tcl, JavaScript and PHP program _(sveinbjorn)_
- [Packages](http://s.sudre.free.fr/Software/Packages/about.html) - Whenever you need to create an installation package or distribution for Mac OS X 10.5 or later, Packages is the powerful and flexible solution you're looking for. _(WhiteBox)_
- [Simple-Package-Creator](https://github.com/rtrouton/Simple-Package-Creator) - Automator application that will allow the selection of a self-contained application and creates an installer package that enables the installation of the application with pre-set permissions into /Applications - _(rtrouton)_
- [quickpkg](https://github.com/scriptingosx/quickpkg) - wrapper for pkgbuild to quickly build simple packages from an installed app, a dmg or zip archive _(scriptingosx)_
- [Apparency](https://mothersruin.com/software/Apparency/) - Inspect App info - _(Mothers Ruin Software)_
			
## <h2 id="sec">Security</h2>			
- [Objective-See's Tools](https://objective-see.org/tools.html) - Free, open-source, tools to secure your Mac _(Objective-See)_
- [Signing Manager](https://twocanoes.com/products/mac/signing-manager/) - System for securing code and package signing certificates _(Twocanoes Software)_
- [Santa](https://github.com/google/santa) - A binary authorization system for macOS _(Google)_
- [osxcollector](https://github.com/Yelp/osxcollector) - A forensic evidence collection & analysis toolkit for OS X _(Yelp)_
- [SilentKnight](https://eclecticlight.co/lockrattler-systhist/) - automatic checking of security systems _(Eclecticlight)_
- [manageSecureTokens](https://github.com/TravellingTechGuy/manageSecureTokens/blob/master/manageSecureTokens.sh) -  _(TravellingTechGuy)_
- [SuspiciousPackage](https://mothersruin.com/software/SuspiciousPackage/relnotes.html) -  _(Mothers Ruin Software)_
- [Crescendo](https://github.com/SuprHackerSteve/Crescendo) - Crescendo is a swift based, real time event viewer for macOS. It utilizes Apple's Endpoint Security Framework. _(SuprHackerSteve)_
- [escrow-buddy](https://github.com/macadmins/escrow-buddy) - A macOS authorization plugin that helps MDM administrators ensure valid FileVault keys are escrowed for all their Macs _(macadmins)_
			
## <h2 id="adod">Active Directory / Open Directory</h2>			
- [Kerberos SSO User Guide](https://www.apple.com/business/docs/site/Kerberos_Single_Sign_on_Extension_User_Guide.pdf) - - _(Apple)_
- [NoMAD](https://gitlab.com/Mactroll/NoMAD) - macOS menu bar application that provides all the functionality of being bound to AD, and more, without having to be bound _(Joel Rennich)_
- [macosLAPS](https://github.com/joshua-d-miller/macOSLAPS) - Swift binary that will change a local administrator password to a random generated password. Similar behavior to LAPS for Windows _(joshua-d-miller)_
- [bugle](https://github.com/ABridoux/bugle) - A command-line tool to post and listen to distributed notifications to execute scripts _(ABridoux)_
- [LDAP Admin Tool](https://www.ldapsoft.com/download.html) - simple and easy to use GUI administration tool for Ldap management, control and development
			
## <h2 id="sar">Scripts and Repos</h2>				
- [jamf-recovery-lock](https://github.com/shbedev/jamf-recovery-lock) - Python script to set Recovery Lock key for Apple M1 computers _(shbedev)_
- [reissueFVKey](https://tarot.shortcut.ru/community/jamf/-/tree/main/reissueFVKey) - Скрипт перевыпуска и отправки ключа восстановления FileVault на небольшой Flask-сервер _(-)_
- [Search-Scripts-In-Jamf](https://github.com/laurentpertois/Search-Scripts-In-Jamf) - Search for a string in all the scripts and or extension attributes in your Jamf Pro instance _(laurentpertois)_
- [brutalkeychain](https://github.com/krypted/brutalkeychain) - Recover lost keychain passwords _(krypted)_
- [python-jamf](https://github.com/univ-of-utah-marriott-library-apple/python-jamf) - library for connecting to a Jamf Server that maps directly to the Jamf Pro Classic API _(University of Utah - Marriott Library - Apple Infrastructure)_
- [Jamf Open Source Community](https://github.com/jamf) - - _(Jamf)_
- [diskspace](https://github.com/scriptingosx/diskspace) - macOS command line tool to return the available disk space on APFS volumes _(scriptingosx)_
- [FastScripts 3](https://redsweater.com/fastscripts/) - All your scripts at your fingertips _(red sweater)_
- [CIS-Script](https://github.com/mvdbent/CIS-Script) - This CIS Script is build to report and remediate based on the your organisation score _(mvdbent)_
- [IOSSecuritySuite](https://github.com/securing/IOSSecuritySuite) - iOS platform security & anti-tampering Swift library _(securing)_
