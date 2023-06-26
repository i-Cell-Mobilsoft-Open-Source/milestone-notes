# Milestone Notes

This GitHub Action creates meaningful release notes based on the issues associated with a specific milestone in your repository. With it, you can automatically generate an overview of the changes included in each release when you close a milestone.

## Features

- Generates a markdown formatted release note.
- Automatically categorizes issues by labels.

## Getting Started

### Prerequisites

This action requires GitHub Actions to be set up on your repository. If you're new to GitHub Actions, see the [official GitHub documentation](https://docs.github.com/en/actions) for more information.

### Installation

```yaml
- uses: i-Cell-Mobilsoft-Open-Source/milestone-notes@master
  with:
  	token: ${{ secrets.GITHUB_TOKEN }}
```

### License

This project is licensed under the terms of the MIT License. See the [LICENSE](https://github.com/i-Cell-Mobilsoft-Open-Source/milestone-notes/LICENSE.md) file for details.

### Support

If you encounter any problems or have suggestions, please open an issue!
