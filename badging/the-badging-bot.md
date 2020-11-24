# The badging-bot

## Command & Functionality

We integrate a GitHub app called `badging-bot` to help us coordinate the workflow. The main function is improving the efficiency of the reviewing process with some automated integration. You can also interact with `badging-bot`using several commands.

### Functions of badging-bot

* Guide applicants/reviewers
* Assign reviewers for a submission
* Open respective checklists for reviewers
* Check current badge status
* Generate the final badge link
* Close the submission issue when an application is finalized

### Instances when the bot is triggered

[https://github.com/badging/event-diversity-and-inclusion/issues/46](https://github.com/badging/event-diversity-and-inclusion/issues/46)

This is a mock submission illustrating the review process, look how and when `badging-bot` is triggered:

* **A new submission is created**: once the issue of a new submission is successfully initiated, `badging-bot` will do three things:
  * greet the applicant and provide guiding information, [see example](https://github.com/badging/event-diversity-and-inclusion/issues/46#issuecomment-674938374)
  * assign reviewers according to `reviewers.md`
  * open a checklist for the assigned reviewer, [see example](https://github.com/badging/event-diversity-and-inclusion/issues/46#issuecomment-674938396)
* **A command is typed down in a review issue comment:** when someone creates an issue comment with a command and only that command, the bot will be triggered and respond in a new comment. 

### Commands

#### 1. /result

* Type this command and only this command in an issue anytime during the review when you wish to check the current badge status.
* All roles are allowed to use this command.

```text
#show the current badge status
/result
```

#### 2. /end

* Type this command and only this command in an issue when the review is at an end.
* Only moderators are allowed to use this command.

```text
#obtain t5he final badge and close the issue
/end
```



