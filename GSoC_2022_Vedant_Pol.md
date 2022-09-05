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
The [XWiki snap](https://snapcraft.io/xwiki) is published on the [snapcrat store](https://snapcraft.io/). The snap can be installed on all major linux distributions and updated/upgraded without any manual interventation. Since XWiki snap is based on the xwiki-jetty package it is fairly easy to maintain.
 <div align="center">
<img src="https://github.com/VedantPol/GSoC_2022_Report_XWiki/blob/main/utils/images/xwiki-download-data.png" alt="XWiki-downoad-data" height=600px width=850px>
</div>
The XWiki snap gets around **66 installs every week** thus increasing the XWiki reach.

## Contributions :gift:
Here are some stats of my contributions to project DepClean during GSoC:

- I made a total of 24 PRs during GSoC, out of which 23 got successfully merged and 1 got closed.
- In those 24 successfully merged PRs, I made a total of 85 commits during the program.
- Overall up to now I had contributed with `7,018 ++ 2,557 --` lines of codes to this project .

<p align="center">
<a href = "https://github.com/xwiki-contrib/packaging-snap/graphs/contributors"><img src = "https://github.com/VedantPol/GSoC_2022_Report_XWiki/blob/main/utils/images/lines-of-code-Vedant_Pol.png" alt="Github contribution-snap"/></a>
</p>

Here is the **list of commits** that I made during GSoC .You can see them [here](https://github.com/xwiki-contrib/packaging-snap/commits/main).

### List of jira issues on which I majorly worked upon during GSoC
- [XWiki-mysql-Snap's mysql breaking](https://jira.xwiki.org/projects/XSNAP/issues/XSNAP-2?filter=allopenissues)
- [xwiki-base more generic and support other databases] (https://jira.xwiki.org/projects/XSNAP/issues/XSNAP-3?filter=allopenissues)
- [arguments in XWiki-jetty] (https://jira.xwiki.org/projects/XSNAP/issues/XSNAP-4?filter=allissues)

## Link to the snap package and documentation I made during GSoC
- [XWiki snap published on SnapStore](https://snapcraft.io/xwiki)
- [XWiki snap github contrib repository](https://github.com/xwiki-contrib/packaging-snap)
- [XWiki snap user guide documentation](https://dev.xwiki.org/xwiki/bin/view/GoogleSummerOfCode/XWiki%20Snap%20Guide/)
- [XWiki snap developer guide documentaion](https://dev.xwiki.org/xwiki/bin/view/GoogleSummerOfCode/XWiki%20Snap%20Guide/XWiki%20Snap%20developer%20guide/)
- [XWiki GSoC 2022 progress page](https://dev.xwiki.org/xwiki/bin/view/GoogleSummerOfCode/Vedant%20Pol-Documenting%20%20student%27s%20progress/)

## Communication (List of important forum post I created during GSoC) :speaking_head: 

- [1 GSoC(2022) Introduction-Vedant Pol](https://forum.xwiki.org/t/gsoc-2022-introduction-vedant-pol/10434)
- [2 GSoC 2022 community bonding period Summary](https://forum.xwiki.org/t/gsoc-2022-community-bonding-period-summary/10496)
- [3 Request for a new contrib repository -Snap package of XWiki](https://forum.xwiki.org/t/request-for-a-new-contrib-repository-snap-package-of-xwiki/10658/7)
- [4 GSoC 2022 (XWiki Snap) Milestone](https://forum.xwiki.org/t/gsoc-2022-xwiki-snap-milestone/10715)
- [5 XWiki Releasing to the Snap Store](https://forum.xwiki.org/t/xwiki-releasing-to-the-snap-store/10726)
- [6 XWiki Snap Published on snap Store](https://forum.xwiki.org/t/xwiki-snap-published-on-snap-store/10735)
- [7 XWiki updated Snap Published on snap Store](https://forum.xwiki.org/t/xwiki-updated-snap-published-on-snap-store/10837)

## Future plans :timer_clock:
The last three months of my life were unforgettable. This time was very precious to me, and I hope that it was so too
for my community. After GSoC, I would like to continue the same spirit of the contribution that I maintained during GSoC.
I would like to get involved more in the community and will be happy to guide new developers as well. I will also like
to work on some new (if any) or existing projects from my organization. In the end, I will try my best to be more 
and more helpful to the community. :innocent: If anyone wants any kind of help or wants to connect with me, then he/she is just
[two clicks away](https://twitter.com/wingman_pol).

## Key takeaways :brain: 
There's a lot that I learned from GSoC, I mean what can be better than working on a community product that is used by
around 10k users. This is the list of my key takeaways from this program.
- Got experience of working on a community product.
- Learned lots of new things in Java, and also learned some new concepts in OOPS.
- Learned lots of new things about project management tools like Gradle and Maven and also learned about dependency management.
- Got experience developing Snap packages
- Also learned a lots about DEVOPS work flow.
- Learned about how to work in a team or with a broad community on single or multiple projects.

## Acknowledgement :clap:
On this ending note, I want to thank my mentors [Thomas Mortagne](https://github.com/tmortagne)& [
Clément Aubin](https://github.com/aubincleme) for constantly supporting me from the very beginning of my contributions.
I am very thankful for their patient behavior whenever I got stuck and their suggestions that helped me in resolving them.
I would also like to thank [Manuel Leduc](https://github.com/manuelleduc) and [Michael Hamann](https://github.com/michitux) for their valuable advice and input that aided me in completing tehis project.
Also, I am thankful to the whole XWiki family who provided me this wonderful opportunity of working on such an amazing project.

In the end, I would like to thank Google for organizing such a wonderful program and also kudos to me who successfully
completed this program. :wink:











