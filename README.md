
# FORCE11 Software Citation Implementation Working Group

Sign up and obtain more information on the [Home Page](https://www.force11.org/group/software-citation-implementation-working-group).
The group is open to everyone who wants to help promote the implementation of
the FORCE11 [software citation principles](https://doi.org/10.7717/peerj-cs.86).
All active group members are listed [here](https://www.force11.org/group/7784/members).
The mailing list for group members is [softwarecitationimplementationwg@force11.org]( mailto:softwarecitationimplementationwg@force11.org).

Use the group [GitHub repository](https://github.com/force11/force11-sciwg) for
documentation and discussion.

The group started in May 2017 and was originally planning to wrap up work in December 2018 - we have extended the group to enable new task forces to complete.

## Description

This group builds on the previous [Software Citation Working Group](https://www.force11.org/group/software-citation-working-group),
which developed and publicized an initial set of software citation principles ([https://doi.org/10.7717/peerj-cs.86](https://doi.org/10.7717/peerj-cs.86)).

The activities of the Software Citation Implementation Working Group will be conducted with
relevant stakeholders (publishers, librarians, archivists, funders, repository developers,
other community forums with related working groups, etc.) to:

1. endorse the principles
2. develop sets of guidelines for implementing the principles
3. help implement the principles
4. test specific implementations of the principles.

During this process, the principles may also be updated based on feedback from the activities.

## Co-Chairs

- [Daniel S. Katz](https://github.com/danielskatz)
- [Neil Chue Hong](https://github.com/npch)
- [Martin Fenner](https://github.com/mfenner)

## Virtual and In-person Meetings

Monthly virtual meetings are generally held at 06:00 PDT / 07:00 MDT / 08:00 CDT / 09:00 EDT / 13:00 UTC / 14:00 BST / 15:00 CEST / 16:00 EEST / 23:00 AEST on the first Tuesday of the month.

Meeting agendas and minutes can be found at: https://github.com/force11/force11-sciwg/tree/master/meetings

We use Zoom to run these meetings.
- [Join from PC, Mac, Linux, iOS or Android](https://zoom.us/j/826409840)
- Join by telephone: [full list of dial-in numbers](https://zoom.us/zoomconference)
   - Australia: +61 (0) 2 8015 2088
   - Canada: +1 647 558 0588
   - France: +33 (0) 1 8288 0188
   - Germany: +49 (0) 30 3080 6188
   - UK: +44 (0) 20 3695 0088
   - USA: +1 408 740 3766 or +1 646 876 9923 or +1 669 900 6833
- Meeting ID: 826 409 840

### Taskforce Meetings

There are also regular calls for task forces spun out of the SCI WG.

At present, these are:
 - Software Citation Guidance Task Force meets virtually on the third Wednesday of the month, at 15:00 UTC / 16:00 BST via [Zoom](https://zoom.us/j/585238617) (contact Neil Chue Hong for more details)
 - The Best Practices for Software Registries Task Force brings together domain software registry and repository managers and editors — those who can implement changes on their registries — to develop a list of best practices for such services through discussions of how we manage, edit, maintain, and market our resources.
   - This group meets virtually on the second Thursday of the month, at 15:00 UTC and 22:00 UTC (contact Alice Allen to be added to reminders calls)
 - CodeMeta Task Force meets virtually on the last Wednesday of the month, at 14:00 GMT via [Zoom](https://zoom.us/j/978215790) (contact Martin Fenner for more details) 

### In-person Meetings

We also organize in-person workshops either co-located with other events, or where
we have obtained funding to organize workshops. These in-person workshops focus on 
specific topics, e.g. handling software citations in publishers systems.

In addition we have also organized sessions in appropriate conferences, e.g.
[WSSSPE5](http://wssspe.researchcomputing.org.uk/) (September 2017 Manchester and
October 2017 Auckland), [FORCE2017](https://www.force11.org/meetings/force2017)
(October 2017 Berlin), [FORCE2018](https://www.force11.org/meetings/force2018), [FORCE2019](https://www.force11.org/meetings/force2019).
The goal of these sessions is to inform the wider community
about the work of the group, and to collect feedback.

## Timeline

- **Launch**. Identify communities to reach out to and engage as early adopters.
  Have all relevant stakeholders join the working group. Agree on scope,
  high-level goals, and how the group operates.
- **Architecture**. Resolve relevant architecture issues, via in-person workshop
  for more complex issues.
- **Pilot Implementations**. Build and launch pilot implementations.
- **Evaluation**. Describe the work we have done and the lessions learned in a paper.

We will use these as milestones in the [GitHub issue tracker](https://github.com/force11/force11-sciwg/issues), and link issues accordingly.

## What we need

- Reference manager support
- Citation style support (most citation styles don't handle software specifically,
  Citeproc doesn't have type software/computer program)
- Publisher support (ensure software references are not stripped, make them
  machine readable/discoverable)
- Reference implementations for software versioning
- File with citation metadata in bibtex or json format (e.g. codemeta) in code repository root

## Related initiatives and projects

- [Codemeta](http://codemeta.github.io/)
- [Astrophysics Source Code Library](http://ascl.net/)
- [SBGrid](https://sbgrid.org)
- [swMATH](http://www.swmath.org)
- [CIG](https://geodynamics.org)
- [AAS tutorial on Citing Repositories in AAS Journals (AJ/ApJ)](https://github.com/AASJournals/Tutorials/blob/master/Repositories/CitingRepositories.md)
- [NITRC (Neuroimaging Informatics Tools and Resources Clearinghouse)](https://www.nitrc.org)
- [Austrialian National Data Service (ANDS)](https://researchdata.ands.org.au)
- Australian Software Citation interest group
- [Zenodo](https://zenodo.org)
- [figshare](https://figshare.com)
- The [Network for Computational Modeling in the Social and Ecological Sciences](https://www.comses.net) maintains a
  [Computational Model Library](https://www.openabm.org/models) with versioned releases of agent based models. A new
  version of the Computational Model Library is currently [under development](https://github.com/comses/core.comses.net),
  applying principles from this working group and serving as an example implementation of a citable code archive.
- [Software Heritage](https://www.softwareheritage.org/)
- [ESIP Software and Services_Citation_Guidelines_and_Examples](https://esip.figshare.com/articles/Software_and_Services_Citation_Guidelines_and_Examples/7640426)



## Potential early adopter groups

What are the early adopter groups who could be persuaded to write papers following software citation principles and using software citation tools?

- astronomy
  - [Large Synoptic Survey Telescope](https://www.lsst.org)
- math
- geosciences
- structural biology
- neuroimaging
- genomics
- [ACAT workshop](https://indico.cern.ch/event/567550/) - tools for applied physics, badge if they cite software
- [Research Software Engineers](http://rse.ac.uk/) - also [de-RSE](https://www.de-rse.org/en/) and [NL-RSE](https://nl-rse.org/)
