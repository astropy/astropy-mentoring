# Astropy mentoring program

```{warning}
The Astropy mentoring scheme is still being set up, and this
documentation is not ready for use.
```

## Goals of the program

While the Astropy project has been successful in attracting code contributions
and feedback from the community, one of the biggest challenges for the
sustainability of the project is training people to take on formal roles and
responsibilities in the project, such as taking on maintainer roles for packages
or sub-packages, or taking on other formal roles in the project.

The Astropy mentoring program provides a lightweight but formal framework to
encourage, recruit, and train both new maintainers for the astropy core and
coordinated packages, as well as people into other formal project roles.

There are two primary goals for the mentoring program:

* To increase the number of people in maintainer and other roles in the Astropy community.
* To provide a more structured way to facilitate succession of people into vacant roles.

This mentoring program is not intended to provide mentoring for e.g. first code
contributions to the project or providing training for git or other parts of the
contribution workflow.

The program is also not intended to be compulsory for people wanting to
take on a formal role, but is meant to be available for people who would benefit
from mentoring before taking on the role.

## How the program works

### Identifying mentees

A potential mentee is someone who is interested in ultimately taking on one of
the formal roles in the project (as listed on the [team page](https://www.astropy.org/team.html)).

There are two main ways such a person could become a mentee in the program:

* they could either decide themselves to apply to the mentoring program to
  indicate that they are interested in being paired up with a mentor and taking on
  a formal role.
* one of the existing people in a role could identify someone they would like to mentor
  into joining them in that role and encourage this person to apply to the mentoring scheme.

Having both routes for nominations is important, as exiting maintainers may not
have noticed a regular contributor or realized they were interested in taking on
more responsibility, and at the same time some contributors might not realise
that it is an option for them to take on more responsibility in the project.

In either case, the first formal step is for the mentee to fill out an
online application form to apply to the program.

### Pairing up with a mentor

Once the mentoring program receives an application, the mentoring coordinator
reaches out to potential mentors. A mentor is ideally someone who already holds
the role that the mentee is interested in also joining, but in cases where the
role is unfilled, it could be someone in a similar role (for example, if one of
the core sub-packages has a role which is vacant, another core package developer
might be able to act as a mentor).

If a willing and available mentor is identified, they fill out a form to also be
registered in the mentoring scheme (if they have not already done so
previously). However, it may be that there are no individuals available to
mentor -- thus we cannot guarantee that everyone who wants to become a mentee
would be able to do so.

### Mentoring program guidance

Once a mentee and mentor are paired up, they are sent links to
handbooks for the mentoring program. These include
recommendations/suggested guidance such as related to communication, tracking
progress, and so on. However, many aspects are be left up to the mentee and
mentor to decide on, and a large fraction of the handbook is guidance
not requirements. The mentor is responsible for making sure that regular
meetings are held with the mentee and to offer guidance and support in a way
most suitable to the mentee.

### Progress check-in and reviews

The mentoring program will send automated monthly check-ins with mentors and
mentees by email to ask if there are any issues that need to be raised with the
mentoring coordinator (with the default of not needing to reply if everything is
going well).

Every three months, the mentor will be sent an automated email to ask them to
assess progress progress and determine whether the mentee is ready to 'graduate'
to the formal role - and they should reply to the email with their conclusions.

### 'Graduation'

Once the mentor has determined that the mentee is ready to join the formal role,
they should go through the standard project process to nominate someone to a role.
Once the role is approved, the formal mentoring program ends, but we encourage
the former mentee and mentor to continue communicating regularly.

## Applications and tracking progress

Mentees will apply for the mentoring scheme by opening an issue on the
astropy-mentoring GitHub repository. This issue will use a template to ensure
that the applicant provides the information necessary for possible mentors and
the mentoring coordinator to assess the application. When the issue is created,
the mentoring coordinator will automatically be assigned to the issue, so that
they can promptly begin looking for a suitable mentor. Once a suitable mentor is
found, they will also be assigned to the issue.

The issue will remain open during the mentorship and will serve as a way to
track the mentee's progress in a way that is transparent and  easily accessible
by all parties. The monthly and three-monthly check-ins will be conducted by
comments left on the issue, to which the mentor and mentee can respond as 
necessary, with the option to move to a more appropriate platform (e.g. email)
if a more detailed or private discussion is required.

At the end of the mentorship, the mentee should open a PR to the repo adding
their name to the list of successful participants, and this PR should close the
issue.

## Documents

```{toctree}
mentee_handbook
mentor_handbook
```
