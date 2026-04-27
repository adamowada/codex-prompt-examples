# codex-prompt-examples
## Adam Owada

### Planning

```text
We're on the dev branch. The first few milestone feature branches have been merged into dev. I'd like you to perform a deep dive into the codebase and the documentation, and compile a report that answers:
- What is the defined MVP
- Where are we in the development process?
- What are the remaining milestones before reaching the defined MVP?
```

```text
Thank you. Please give a detailed explanation for "2. Production Auth, Memberships, And Invitations" as a milestone, including "done when".

Repeat for Milestone 3.
```

```text
The next major milestone is: <milestone_title>. Don't code anything yet. Create a thorough, multi-stage plan, to take the current code base to the "done when" and goal of this milestone.

<milestone_description>
```

### Coding and Testing

```text
Implement stages 6 and 7. Make sure you write tests for each stage, and validate your work with the tests and smoke tests. Regression tests should be in place before major features are added or changed. If there is anything you need from the user to progress you must let me know. After these 2 stages are done, write a short developer style commit message describing the work.
```

### Code Review (new thread)

```text
Perform a deep dive code review into the `feature/corrective-actions` branch. Run the testing suite, check testing coverage, and check if there is any planning doc drift. Testing coverage should be extensive. Is this branch, as a milestone, complete and ready for a PR into dev?
```

In my experience it always finds SOMETHING to "fix". Review its suggestions carefully.

```
Fix everything.
```



