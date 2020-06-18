# Welcome to your 1:1 repository

This repository will house all 1:1 notes, documented goals / growth things, and
anything else important that comes up between you and your manager.

## How does it work?

Meeting notes are saved in this private repo. They are very helpful to refer
back to for both of us during review season. Only the two of us have access to
this repository. If you get a new manager, you can transfer the repository over
so that you can have a consistent process, and so that your new manager can have
access to any previous notes.

Every Monday (configurable), a GitHub action creates a PR with a markdown file
containing questions about the week ahead. We can each add notes to this as
commits as they come to mind, and then, during our 1:1, reference them and add
new notes and actions. You can then review and merge the PR, marking the notes
as seen and complete.

## Steps for using this template

1. [Create a new private repository from this template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)

   You (the report) should do this, so the repository follows you across
   managers.

1. Invite me (the manager) to the repository as an admin so I have full
   permission to modify and update the repository

   It's a shared resource to aid our communication.

1. Update the [day of the week](.github/workflows/one-to-one-notes.yml#L5) and
   [settings](.github/workflows/one-to-one-notes.yml#L12) with real values
   matching your 1:1 schedule and the people involved

1. Replace the action headings in
   [the template](meeting-notes/templates/one-to-one.md) with both of our names

1. Delete this section
