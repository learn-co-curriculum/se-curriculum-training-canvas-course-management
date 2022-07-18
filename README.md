# Blueprint Management

## Learning Goals

- Associate a Canvas blueprint course with a student-facing course
- Sync changes from a Canvas blueprint course to a student-facing course

## Introduction

Each "phase" of the program corresponds to one "course" in Canvas. Our
curriculum is maintained in special [blueprint courses][] in Canvas, which
allows us to have a single source of truth for the most recent version of
curriculum and to push changes to multiple courses from the blueprint whenever
maintenance is needed.

## Associating and Syncing Courses

It is the curriculum team's responsibility to ensure that every course in Canvas
is **associated** and **synced** with the correct blueprint, at the right time,
prior to students beginning the course.

### How to Associate a Course

<!-- TODO: record video -->

Creating an **association** between a course and a blueprint means that the
course can be **synced** whenever there are changes to the blueprint. For
example, if a course has already started and a student notices a typo in a
lesson, we can correct that lesson in the blueprint and sync the changed version
with all courses that are associated with that blueprint.

This guide demonstrates how to associate a course with the correct blueprint:

- [How do I associate a course with a blueprint?][associating courses guide]

Note that as soon as a new course is associated and saved, it will also
automatically be synced.

### Timing Of Association

We use the following timelines to ensure content is available in student-facing
courses at the appropriate times:

- Live
  - Prework: **when requested by Ops**. We don't have a set timeline for this
    and probably should.
  - Phases 1 - 5: **one week prior to the start of the phase**
  - Data Structures and Algorithms: **one week prior to the start of the
    program**
- Flex
  - Prework: **sixteen weeks prior to the start of the program**
  - Phases 1 - 5: **one week prior to the start of the program**
  - Data Structures and Algorithms: **one week prior to the start of the
    program**

Courses are considered "active" while a cohort is working on lessons within that
course. In the Live program, cohorts changes phases every three weeks;
therefore, courses are only active for three weeks at a time (with the exception
of the Data Structures and Algorithms course, which remains active for the
duration of the program).

In the Flex program, since students move through phases at unpredictable paces,
all phases are considered "active" for 60 weeks. This long time period for
"active" courses comes with some challenges. Whenever we need to make
significant curriculum updates to courses that students in the Flex program may
actively be working on, we need to communicate closely with the Flex delivery
team to ensure that students and instructors are aware of the impact of those
changes.

Once a course is no longer "active", the association between the course and the
blueprint can be removed. Removing the association helps ensure that blueprint
updates don't negatively affect students who have completed a course, and makes
it easier to maintain a working list of active courses.

## Course Tracking: Monday Board

<!-- TODO: record video -->

Course associations are manually tracked in [this Monday
board][canvas monday board]. This board is helpful because it allows us to see
which courses are active, and ensure that we associate courses at the right time
for students.

The dates for each course/cohort in the Monday board are added manually by
referencing the [global calendar][].

## Syncing Updates

The main reason we use the blueprint functionality in Canvas is because it gives
us the ability to make all of our updates in the blueprint course, and push
those updates out to all associated student-facing courses easily.

This [blueprint syncing guide][blueprint syncing guide] shows the process and
also explains what is and is not synced when a blueprint is updated. In general,
changes to individual lessons can be synced easily; some other types of changes,
such as rearranging content, changing the published state, or changing module
requirements for an active course have a more complicated set of rules. When
you're unsure whether or not a change in the blueprint is reflected in the
associated courses, it's best to verify manually.

## Exercise

Time to get some practice in! The course you're working in now is set up as a
blueprint course. That means it's possible to associate new courses with this
course and sync them.

Use the [Canvas blueprint association guide][associating courses guide] to
associate this blueprint with this empty student-facing course:

- https://learning.flatironschool.com/courses/6051

Once you've successfully created the association, make an edit to one of the
lessons in this blueprint course. Then, use this [blueprint syncing
guide][blueprint syncing guide] to sync your change with the newly associated
course.

## Resources

- [Canvas blueprint creation guide][blueprint courses]
- [Canvas blueprint association guide][associating courses guide]
- [Canvas blueprint syncing guide][blueprint syncing guide]
- [Monday Board][canvas monday board]
- [Global Calendar][global calendar]

[blueprint courses]:
  https://community.canvaslms.com/t5/Admin-Guide/How-do-I-enable-a-course-as-a-blueprint-course-as-an-admin/ta-p/138
[associating courses guide]:
  https://community.canvaslms.com/t5/Admin-Guide/How-do-I-associate-a-course-with-a-blueprint-course-as-an-admin/ta-p/183
[blueprint syncing guide]:
  https://community.canvaslms.com/t5/Admin-Guide/How-do-I-sync-course-content-in-a-blueprint-course-as-an-admin/ta-p/171
[canvas monday board]: https://flatiron.monday.com/boards/2372093654
[global calendar]:
  https://docs.google.com/spreadsheets/d/1ZF0aGxftAIc9RvnR5Sz2o6iW4NfgSoKACpkfINZJZfk/edit#gid=0
[live sub accounts]:
  https://learning.flatironschool.com/accounts/657/sub_accounts
[flex sub accounts]:
  https://learning.flatironschool.com/accounts/667/sub_accounts
