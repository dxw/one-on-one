# Welcome to your 1:1 repository

This repository will house all 1:1 notes, documented goals and growth things,
and anything else important that comes up between you and your manager.

## How does it work?

We save meeting notes in this private repo. They are helpful to refer back to
for both of us. Only the two of us have access to this repository. If you get a
new manager, you can transfer the repository over so that you can have a
consistent process, and so that your new manager can have access to any previous
notes.

On the day of your 1:1 (configurable), a GitHub action creates a PR with a
markdown file for the next 1:1. We can each add notes to this as commits as they
come to mind. Then, during our 1:1, we can reference those notes and past notes
and add new notes and actions. You can then review and merge the PR, marking the
notes as seen and complete.

## Steps for using this template

1. [Create a new private repository from this template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

   You (the individual contributor) should do this, so the repository follows
   you across managers. You should do this in your own GitHub user account, or
   any admin at dxw can see the contents!

1. Invite me (the manager) to the repository as an admin, so I have full
   permission to modify and update the repository

   It's a shared resource to aid our communication.

1. Update the [day of the week](.github/workflows/one-to-one-notes.yml#L5) and
   [environment variables](.github/workflows/one-to-one-notes.yml#L12) with real
   values matching your 1:1 schedule and the people involved

   We recommend setting the time to a few hours after your 1:1, so there's time
   to review and merge before the automation creates a new branch.

1. Replace the action headings in
   [the template](meeting-notes/templates/one-to-one.md) with both of our names

   For example:

   ```md
   ...

   ## Actions

   ### Alex

   - [ ] TODO

   ### Reilly

   - [ ] TODO
   ```

1. Delete this section
