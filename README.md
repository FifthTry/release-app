# Release App Using `fastn`

The Demo Release App is designed to help you manage release notes in a manner similar to [GitHub's managing releases in a repository](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository). 
It features a form for adding release details and a page to display all release information.

## Video Walkthrough
For a step-by-step guide on how to achieve this, please [watch the video walkthrough](https://youtu.be/cKhFE2d6cSk).

## Features

- **Add Release Details**: A form to input the details of each release.
- **Display Releases**: A dedicated page to view all the release details.

## What will you learn?

You will learn how to use `fastn` to perform SQL operations such as creating tables, writing to tables, and reading from tables. 
This will enable you to handle full backend operations in addition to frontend development using `fastn`.

## Getting Started

Follow the instructions in the video to set up and run the Release App using fastn.

### How to Use

1. Clone the repository:

```sh
git clone <repository-url>
cd release-app
```

2. Install dependencies:

Follow the instruction on [Install `fastn`](https://fastn.com/install) to install `fastn`.

3. Run the app:

```
fastn serve
```

4. Add Release Notes:

- Navigate to the form page: http://127.0.0.1:8000/.
- Fill in the release details.
- Submit the form. 
- This will redirect you to the release note page.

5. View Release Notes:

Go to the releases page: http://127.0.0.1:8000/releases/ to see a list of all releases.
