---
title: Managing Issues
layout: doc
---

# Managing Issues

New issues are filed frequently, and how we respond to those issues directly affects the success of the project. Being part of the project team means helping to triage and address issues as they come in so the project can continue to run smoothly.

## Things to Keep in Mind

1. **Be nice.** Even if the people are being rude or aggressive on an issue, as a project team member you must be the mature one in the conversation. Do your best to work with everyone no matter their style. Remember, poor wording choice can also be a sign of someone who doesn't know English very well, so be sure to consider that when trying to determine the tone of someone's message. Being rude, even when someone is being rude to you, reflects poorly on the team and the project as a whole.
1. **Be inquisitive.** Ask questions on the issue whenever something isn't clear. Don't assume you understand what's being reported if there are details missing. Whenever you are unsure, it's best to ask for more information.
1. **Not all requests are equal.** It's unlikely we'll be able to accommodate every request, so don't be afraid to say that something doesn't fit into the scope of the project or isn't practical. It's better to give such feedback if that's the case.
1. **Close when appropriate.** Don't be afraid to close issues that you don't think will be done, or when it's become clear from the conversation that there's no further work to do. Issues can always be reopened if they are closed incorrectly, so feel free to close issues when appropriate. Just be sure to leave a comment explaining why the issue is being closed (if not closed by a commit).

## When an Issue is Opened

When an issue is first opened, follow these steps:

1. Is it clear what is being requested? If no, ask for more information. If yes, then:
    * Label bug reports with the "bug" label (also use the "accepted" label if you can reproduce and verify the bug)
    * Label requests for changes to existing features with the "enhancement" and "proposal" labels
    * Label requests for completely new features with the "feature" and "proposal" labels
    * Use an appropriate label for the part of the project the issue refers to
1. If it's a bug, be sure the issue includes the following (ask for any missing information):
    * The ESLint version being used
    * The configuration being used and the actual source that reproduces the problem
    * The actual ESLint output (not a summary, have them copy-paste it)
    * What they expected to happen
1. If it's an enhancement or feature request, be sure the issue mentions the primary use case (the problem they are trying to solve) and not just a suggestion for a technical change (which needs to be a solution to a problem). If the use case isn't clear, ask for more information. Frequently, "What problem are you trying to solve?" can clarify that.
1. If it's just a question (one that would normally go to the mailing list or chatroom), feel free to answer the question and close the issue when the conversation is over.
1. If you can verify that the issue is a duplicate of another issue, mention this in a comment and close the issue. Be sure to reference the issue number of the issue they should refer to, such as, "Duplicate of #1234."
1. Regardless of the above, always leave a comment. Don't just add labels, engage with the person who opened the issue by asking a question (request more information if necessary) or stating your opinion of the issue. If it's a verified bug, ask if the user would like to submit a pull request.

**Note:** Don't add an "accepted" label to an issue unless it's a bug that you've been able to reproduce and verify (you're sure it's a bug). The "accepted" label will be added by a project admin if it's appropriate for the roadmap.

## Evaluating an Issue

If you're a project admin, then you'll need to evaluate incoming requests for inclusion in the formal roadmap. You should label an issue as "accepted" when all of the following are true:

1. The feature or enhancement is in scope for the project and should be added to the roadmap
1. You are committed to including the change within the next year
1. You are reasonably certain of who will do the work

When a suggestion is too ambitious or would take too much time to complete, it's better not to accept the proposal. Stick to small, incremental changes and lay out a roadmap of where you'd like the project to go eventually. Don't let the project get bogged down in big features that will take a long time to complete.

## When to Close an Issue

There are several times when it's appropriate to close an issue:

1. The issue is a duplicate of an existing issue
1. The issue is just a question rather than a task to be completed
1. The issue has been open for a year or more with no sign of progress
1. No one has committed to working on the issue for the roadmap
1. The request is outside the scope of the project

In general, it's better to close issues sooner rather than later. It gives people better feedback about the issue affects the project roadmap.
