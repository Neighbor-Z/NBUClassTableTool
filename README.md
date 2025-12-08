# NBU Class Table Tool - SwiftUI

A SwiftUI rewrite of the NBU course table to ICS calendar file tool.

## Features

- Modern SwiftUI interface with dark mode support
- Fetches course schedule from University's ehall system
- Generates ICS calendar files for import into calendar applications
- Supports both undergraduate and graduate students

## Requirements

- macOS 12.0 or later

## Usage

1. Enter your student ID (学号)
2. Enter your password (密码)
3. Enter the term (学期), e.g., "2025-2026-1"
4. Enter the first Monday of the semester (首个周一), e.g., "2025-09-08"
5. Click "获取" (Fetch) to retrieve your course schedule
6. Choose a location to save the generated ICS file

## Technical Notes

- Uses async/await for network operations
- Implements AES-CBC encryption for password authentication
- Handles HTML parsing for login form extraction
- Generates standard ICS calendar format files

## Original Project

Based on the Python [project](https://github.com/Neighbor-Z/nbu-course-table-to-ics-local/)

