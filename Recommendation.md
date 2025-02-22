# Introduction

A list of privacy tools that will help you remain private online, or maybe help you remain anonymous online if done right. The recommendation list has included software (and services)
that has been carefully reviewed, used (not guaranteed), researched, and tested (also not guaranteed), and for the sake of anyone wanting to use those: There is no such thing as a silver bullet when it comes to privacy.
But, these tools (software and services) will make tracking you a (very) difficult task, and if done right, you might be untrackable and be fully anonymous, but of course, it's not 100% and not guaranteed, so take it with a grain of salt please.

-----

# Table of Contents
1. [Operative Systems](#1.-operative-system)
  - GNU/Linux
    - Recommended
    - Non-SystemD Distros
    - Special Linux Distributions
    - Not Recommended
  - BSD (Berkeley Software Distribution)
  - Android Custom Rom AOSP
  - Desktop Enviroments
3. Web Browser
  - Desktop Web Browser
    - Not Recommended
  - Mobile Web Browser
    - Not Recommended
  - Web Browser Addons
    - Not Recommended
  4. Private Communications
  - Electronic Mail
    - Not recommended
  - Email Clients
  - Instant Messangers
  - NOT FINISHED, I will do it later!

-----

# 1. Operative System
## A. GNU/Linux

> [!IMPORTANT]
> During installation, make sure to use full-disk encryption, which must be an LVM Encryption (if there is a specific installer that doesn't have LVM, just use encryption instead), and use a PassPhrase that has over 5-7 words long that doesn't include in the dictionary (Which is the dictionary attack). This is to prevent thieft, cyber attack, and the law enforcement from searching your data on your computer.

> [!IMPORTANT]
> So, not every linux distribution is going to be all free software, free as in free beer, free as an freedom (again), or even try to protect you're privacy, Every GNU/Linux distribution needs to be investigated further before usage, the only tools I recommend is WireShark (Yes, it's a cyber-security tool but here is the thing), to scan your own network (try pressing "all" in the GUI), to do so, use "sudo wireshark" for scanning your own network and press "all" to see all your network status. If you see any unusual signs such as telementry, data server centers, or sending an IP address to a unknown network then reframe from using it and start looking for alternatives.   

GNU/Linux Check List:

Derivative: (Independent/Mention Distro)
Spyware: (Yes/No)
Telemetry: (Yes/No)
Woke: (Yes/No)
SystemD: (Yes/No)
Free Software: (Proprietary/Freedom/Both or Mixed)
Corporate Ties: (Funding/Owned/No/Yes) (Funding: Funded by a Corporate Entity. Owned: Owned by a specific Corporate Entity, e.g Red Hat Inc./SUSE)
Politics: (Yes/No)
Meets my Required Packages (Software): (Yes/No) (Basically a software you want to use, if there is no software that you want or you use regularly)
FOSS: (Yes/No)

(Outdated) Distro Choosers: [DistroChooser.de](https://distrochooser.de/) and [LibreHunt.org](https://librehunt.org/).

### I. Recommended
![image](https://github.com/user-attachments/assets/1ffe653d-d35b-4239-ae8d-e3d00283e21f)
Linux Mint

Overview: A GNU/Linux distro that works out of the box, it's user friendly desktop makes it perfect, without a hassle, but contains bloutware. Unlike Windows, it respects you're privacy and doesn't contain spyware/telemetry, it's also lightweight! They also focus on stability over latest Technologies or any Rolling Releases, they are also non-woke, no injustices or any politics involved in the project. It's also based on Ubuntu LTS.

Recommendation: If you are new to linux, use this distribution for your day to day operations, and maybe not dual-boot due to Windows interference with dual-boot management, which makes it a privacy risk. 

![image](https://github.com/user-attachments/assets/77ffdc48-d540-4080-a6b4-db0e2ee0983f)
OpenMandriva Lx

Overview: GNU/Linux that also works out of the box, it's user-friendly desktop environment (KDE Plasma 6) is appealing and very customisable. Uses a package manager "DNF Yumi" (From Fedora Package Management, old edition), and it's a independent project, no derivatives involved, but a past members of contributors and maintainers from Mandriva or Mandrake Linux. They have been recently declared as a "non-woke" distribution by Lunduke Journals, so they only focus on the code and the software itself. They are also a sponsored organization by OpenMandriva Association, which is a reputable and trustworthy (as far as I can tell) organization that is non-woke, no users being banned left and right in the forms (aaccording to my questioning), so it's safe to make a account there
(Aka their forms).

Recommendation: It's safe to use this distribution and their discussion boards, if you are new to linux to linux, that is non-woke, then feel free to use this distribution, it might be different then the rest of the distributions but trust me, it's different and unique in design. (Or does it?)

![image](https://github.com/user-attachments/assets/ddebb8d9-b5a4-4336-9fa3-a66d5c6646c7)
Debian GNU/Linux

Overview: Sometimes called the "grand daddy of all distros" it is a universal operating system that was made back in the 1990's (Around 1993 or so), also the second oldest distro after Slackware (Slackware not exactly recommended since it's not as mainstream as it once was). It is a freedom software based distribution, making it (in my opinion) the most recommended distro for Free Software Foundation (Not anymore, due to their extreme policies of "free software requirements"), it's also somewhat super lightweight, with a fast majority of their repos of software and packages being 90,000 (or more) packages (either free or non-free). Due to their philosophy of being free software, there has been some controversy lately: Looking at these both sources: [1 (Spanish)](https://laboratoriolinux.es/index.php/-noticias-mundo-linux-/distribuciones/37447-debian-abandona-x-una-decision-peligrosa-para-el-proyecto.html?highlight=WzIwMjJd) [2](https://lunduke.substack.com/p/debian-linux-doubles-down-on-wokeness), debain left X.com because of their "woke" ideologies, or rather their three main policies. Their main Desktop Enviroment is GNOME (Due to their default selection in their installer), which is user-friendly and quite intuitive.

Recommendation: Recommended only for Intermediate users, their great free software philosophy, and their debian security manual is quite interesting (to me, at least), overall it is also recommended by the [whonix.org](https://www.whonix.org/wiki/Host_Operating_System_Selection) and the [PRISM Break](https://prism-break.org/en/categories/gnu-linux/#operating-systems), so for any people who wish to seek privacy, security, solid stability, free software, and best of all: All 90,000 packages of debian repositories then go ahead and use Debian GNU/Linux.

Suitable Alternatives: Devuan GNU/Linux, Linux Mint Debian Edition.

### II. Non-SystemD Distributions

> [!NOTE]
> A special category of mine, bascially there are only two distros that are considered Non-SystemD distributions, and one of them have their own choosen init systems (If you are reading this: It is **only** recommended to use those distributions if you care about the init systems and want to get away with [SystemD insecurities and problems, especially it's controversies](https://en.wikipedia.org/wiki/Systemd).), such as SysV, OpenRC, s6, etc. Those are also non-woke so don't worry about that.

![image](https://github.com/user-attachments/assets/5efcf627-595f-462f-8bcd-72bc1eec02b6)

Artix Linux

Overview: Artix Linux is a non-systemD distro, based on Arch Linux, and despite it being stable and secure linux distro, they are still a rolling release distribution, that is non-woke and maybe a little bit mainstream. What's so special about it is that you can select any init system in their download page, this may include: Dinit, OpenRC, Runit, and s6, as well as SysV (Wrong they don't have SystemV available, only in Devuan). They also have a selectable Desktop Enviroments that also include init systems, such as: Base (A terminal command line interface), Cinnamon, Community Gtk and Qt (Made by developers), Lxde, Lxqt, Mate, KDE Plasma, and Xfce. In testing they have Base-lowmem (Server only command line interface), GNOME (Heavy dependent on SystemD), and i3.

Recommendation: Use this distro if you want a simple alternative to Arch Linux, that is non-woke and has the latest technologies and packages that you want to use. Recommended to use KDE Plasma or Cinnamon if you want something that's popular or used a lot, if you want something that's lightweight use Xfce or MATE. For Init systems, choose what interests you. In my opinion OpenRC or dinit might be interesting, but I would rather choose OpenRC for that specifc reason.

More to come...

