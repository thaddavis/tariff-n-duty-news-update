# TLDR

Automating Duty Research

## PREREQS

- Coding Agent
  - Claude Code ($100/month) [https://code.claude.com/docs/en/quickstart]
  - OpenCode ($10/month) [https://opencode.ai/]
  - etc.
- VSCode (FREE)
- Playwright MCP (FREE)
  - https://playwright.dev/
- and finally a product you have built (this demo assumes a web application)

## "How to use"

- Setup Playwright MCP
- Start Prompting!

## Begin prompting

```txt - Example Prompt 1
# TASK

Your task is to perform research regarding the latest developments in duty rules, regulations, and changes in order to build a report for delivery to the operators of an international shipping container logistics business. The goal is to save the operators time and make them aware of key changes they should be aware of so that they are able to calculate how any changes to duty rules and regulations affect their bottom line, profit, and revenue.

Below are the sources you are able to browse. You also have Playwright MCP help you navigate through these sites in order to find relevant information.

After performing research, deliver an email via AWS SES to the list of subscribers with the final report.

## FINAL REPORT FORMAT

The format of the final report should have three sections:
1. Last 24 hours
  - Lists key updates that have happened in the last 24 hours.
2. Last 7 days
  - Lists key updates that have happened in the last 7 days.
3. Last 2 weeks
  - Lists key updates that have happened in the past two weeks.

## SOURCES

- https://www.federalregister.gov/
- https://hts.usitc.gov/
- https://rulings.cbp.gov/home

## SUBSCRIBERS

- tad@cmdlabs.io

## REPLY TO

- noreply@cmdlabs.io
```

## Scratch space

- https://www.federalregister.gov/
- https://hts.usitc.gov/
- https://rulings.cbp.gov/home