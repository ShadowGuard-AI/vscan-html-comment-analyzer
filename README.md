# vscan-html-comment-analyzer
Parses HTML files and reports sensitive information or debug messages inadvertently left in HTML comments, such as credentials, database connection strings, or internal API endpoints. - Focused on Lightweight web application vulnerability scanning focused on identifying common misconfigurations and publicly known vulnerabilities

## Install
`git clone https://github.com/ShadowStrikeHQ/vscan-html-comment-analyzer`

## Usage
`./vscan-html-comment-analyzer [params]`

Findings report the pattern type and location with the matched value masked, in both stdout and the `-o` output file; matched values are never printed or saved in clear. If the input file cannot be read or the URL fetch fails, the tool exits 1. URL fetches use an explicit 10 second timeout.

## Parameters
- `-h`: Show help message and exit
- `-o`: No description provided
- `-v`: No description provided

## License
Copyright (c) ShadowStrikeHQ
