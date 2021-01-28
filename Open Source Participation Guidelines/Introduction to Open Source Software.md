# Introduction to Open Source Software

## What is Open Source Software (OSS)?

#
### Attributes of open source software
###

OSS is software freely available in source code form that is often created and maintained by a collaborative, virtual community on the Internet and is usually downloadable for free over the Internet or available on CD-ROM at nominal cost.

OSS has several important features that distinguish it from other kinds of software:

- You cannot be prohibited from redistributing OSS.
- You cannot be prohibited from distributing modifications to OSS.
- No royalties can be imposed on you for using OSS.

##
### Open source and copyright law
###

Copyright law gives the author rights:

- The author determines appropriate uses of a work.
- For example, you cannot reproduce or modify a work without the author's permission.
- The author may grant permission using a license, for example, an open source license.

A license grants permission, but it may also impose obligations.

##
### The Open Source Definition (OSD)
###

The not-for-profit Open Source Initiative (OSI) is dedicated to promoting and maintaining a formal definition of OSS called the "Open Source Definition" (OSD). The OSD defines ten (10) criteria that a software license must meet in order to be considered an OSS license.


**Free Redistribution**

The license cannot prevent anyone from selling or giving away the software and cannot impose any royalties or fees on use of the code.


**Source Code**

The source code must be made available in some well-publicized way for no more than a reasonable reproduction cost (preferably downloadable from the Internet without charge but this is not a necessity). 


**Derived Work**

The license must allow modifications and derivative works to be distributed under the same terms as the original software license.

**Integrity of The Author's Source Code**

The license can restrict source code from being distributed in modified form provided it allows the distribution of "patch files." The license must allow distribution of software built from modified source code but can require derived works to carry different names or version numbers from the original.

**No Discrimination Against Persons or Groups**

The license must not discriminate against any person or group of persons.

**No Discrimination Against Fields of Endeavour**

The license must not restrict anyone from making use of the program in a specific field of endeavour.

**Distribution of License**

The rights attached to the program must apply to all to whom the program is redistributed.

**License Must Not Be Specific to a Product**

The rights attached to the program must not depend on the program being part of a particular software distribution.

**The License Must Not Restrict Other Sofrware**

The license must not place restrictions on any other software that is distributed along with the licensed software.

**License Must Be Techonolgy-Neutral**

Accepting the license terms (prior to downloading) must not depend on a particular technology.

## Open data and OSS

### How is open data different?

Open data is not the same as OSS, but shares many of the same principles. Open data is data that anyone can access, use, and share. 

- Open source projects often make use of open data, for example data used to train a model in AI applications.
- Open data is also offered under a license, usually a license type specific to open data.
- The Community Data License Agreement (CDLA) was drafted with significant input from IBM.
    - The CDLA-Sharing license ensures data and modifications remain freely available under the CDLA-Sharing terms. It is the preferred license for IBM data contributions.
    - The CDLA-Permissive license allows distribution and publication of the data and any modifications under any license, including commercial licenses.

As with open source, an open data license grants permission, but it may also impose obligations. Open data follows the same approval process as open source, with additional checks for privacy, personal information, and other aspects specific to data. 

Data can be provided under a variety of licenses, many of which are not open and have restrictive terms. Discuss your data use case with your local attorney if you have questions. 

## Other types of third party software

### Public Domain

The Public Domain is the collection of works that are not protected by copyright and therefore may be appropriated or used by anyone without infringing copyright.

-  A work may not be protected by copyright as a result of its term of protection having expired, failure to comply with legal requirements, or inapplicability of copyright protection. Public Domain works are said to belong to the community at large.
- OSS does not equal "Public Domain" (frequent misconception).
- If source code is available, treat this as open source software; be sure to follow the Open Source Approval Process. 

### Freeware

Freeware is copyrighted, but may not have source code available. Without source code, it cannot be examined, it may have unintentional side effects, defects, malicious code, and so on.

- Freeware is typically not OSS.
- Freeware is software offered in executable (binary) format for free, under a license that retains other rights to the copyright owner.
- Freeware should not be confused with Free Software or Open Source Software since it will generally not include rights to distribute or modify. 

### Commercial Software

Commercial software is copyrighted and distributed by a commercial software vendor.

- Commercial Software is not OSS.
- Commercial software containing OSS requires appropriate review. 

Contact legal for any presumably ‘Freeware’ or Commercial software. Third party software must be listed in the Certificate of Originality (COO) if being redistributed in a product. Be aware that any type of third party software may have legal obligations.

The OSS community has a very precise definition of “open source”. That definition is embodied in the various OSS licenses in use today.

There are also “pseudo” open source licenses: licenses that appear to be open source but have the addition of unique restrictions that do not fit the definition of open source.

## 
## Common OSS Risks

### Learn about the risks of using OSS

While there are some benefits of using OSS, there are also a number of risks common to all OSS. The open source approval process is designed to uncover and reduce potential risks before distribution.

**Will We have the necessary rights or protection for an IZBM product?**

Uncertain pedigree: in some cases, it may be difficult to determine if contributions to an open source project are properly licensed by the original author.

**No warranty or indemnification**

Provided "AS IS:" Thus, IBM bears possible risk of infringement upon distribution.

**"Copyleft", also known as the "Viral Effect"**

Improper handling or use of certain OSS code (for example, Affero General Public License (AGPL), GNU General Public License (GPL), or GNU Lesser General Public License (LGPL) code) with or within IBM proprietary code may necessitate that IBM distribute our proprietary source code under the terms of licenses, such as the AGPL, GPL, or LGPL.


**Possible relinquishing of IBM's Intellectual Property rights**

Some licenses require a patent license grant (competitors may be able to use your inventions in their products without paying IBM a licensing fee). Even if not explicit, most licenses are assumed to have implicit grants. To maintain openness, IBM-approved OSS contributors are encouraged to submit invention disclosures relating to all innovative features.

**"Contamination" (future development implications)**

If you view source code and create substantially similar material in the future, that new material could be considered a "copy" and subject to the OSS license terms.

- Special caution should be taken when looking at GPL (or other "copyleft" licensed) code. Copies of GPL licensed code must be distributed under the GPL license and cannot be relicensed.
- To the extent the license, for example the BSD license, permits relicensing under a proprietary license, it is not an issue.

