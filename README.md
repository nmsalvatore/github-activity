# GitHub User Activity

This is a CLI application, built with Go, which pulls GitHub user activity. The project is one of the Roadmap.sh [backend projects](https://roadmap.sh/backend/projects). Specifications for the project can be found [here](https://roadmap.sh/projects/github-user-activity).

## Installation

Make sure [Go is installed](https://go.dev/doc/install), then build the binary with `make`.

## Usage

Run the application by calling `./github-activity` from the project directory. The application accepts a GitHub username as its sole argument and will log the user's recent GitHub activity.

### Example

```bash
./github-activity nmsalvatore

// Output:
// - Pushed 3 commits to nmsalvatore/github-activity
// - Opened a new issue in nmsalvatore/github-activity
// - Starred nmsalvatore/github-activity
// - ...
```
