## GSoC '21 Report | Vednat Pol | XWiki | Snap Package for XWiki
<div align="center">
<img src="https://github.com/VedantPol/GSoC_2022_Report_XWiki/blob/main/utils/images/MergedImages.png" alt="XWiki-logo" height=250px width=600px>
</div>

## General Information 📝
<b>Organization:</b> [XWiki](https://www.xwiki.org/xwiki/bin/view/Main/WebHome) <br>
<b>Project:</b> [packaging-snap](https://github.com/xwiki-contrib/packaging-snap) <br>
<b>Tasks:</b> 
1. Create a snap package of XWiki.
2. Generation of a snap package for each version of XWiki should be integrated into the release process.


<b>Student:</b> [Vedant Pol](https://github.com/VedantPol) <br>
<b>Mentors:</b> [Thomas Mortagne](https://github.com/tmortagne) & [Clément Aubin](https://github.com/aubincleme) 
<br>
<b>My proposal: </b> [Click here](https://drive.google.com/file/d/1nYScpN_QuGX3nvTpKXyUwSK1SoJc_-Z2/view?usp=sharing)

## Abstract :scroll: 
This summer, I was selected for GSoC to work on project Snap-package for [XWiki](https://www.xwiki.org/xwiki/bin/view/Main/WebHome).
XWiki is an open source software development platform based on the wiki principles, under the LGPL license. In addition to being a full-featured wiki, it is also a second generation wiki allowing effortless development of collaborative web applications. On top of this platform a plethora of applications are developed, targeted mainly on aiding enterprise-level needs.

## Goals :dart:
- The already existing options for xwiki installaion were tricky to update/upgrade and required much more manuall intervention. While packages that were easy to upgrade like the xwiki-debian package were not avaliable on all linux distribution .To solve this problem we could use the universal [Snap package](https://snapcraft.io/). By creating a snap package of XWiki we could ensure that xwiki was avalible on all distributions and is easy to upgrade/update.
- Reaching more people/user using the snapcraft store and increasing xwiki userbase.
- Integrate the genration of snap with the release such that it is easy to maintain and provide updates.

## Results :rocket:
The [XWiki snap](https://snapcraft.io/xwiki) is published on the [snapcrat store](https://snapcraft.io/). The snap can be installed and used on all major linux distributions. The XWiki snap can be updated/upgraded without any manual interventation. 
The XWiki snap gets around **66 installs every week**. Thus increasing the XWiki users.
 <div align="center">
<img src="https://github.com/VedantPol/GSoC_2022_Report_XWiki/blob/main/utils/images/xwiki-download-data.png" alt="XWiki-logo" height=600px width=850px>
</div>


