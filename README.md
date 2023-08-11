# Course - Webmardi connecting Notion

## 🛠 Requirements
- PHP

## 🧨 Getting Started

The project must works running the php built-in web server.

```bash
php -S localhost:9000 -t ./
```

And then browsing to the host and port you specified (in the above example, `http://localhost:9000`).

## 🎨 Build your own Webmardi connection to Notion

Start codding your own integration bind to a Notion database by editing the following files

```md
├── events
│   ├── [PAST-EVENT-ID]--canonical.php
├── index.php
└── events.php
```

## 🎯 Objectives

**Homepage**

- Highlight the upcoming event
- List of the last 4 events (past)

**List of past events only**

- List of all events in chronological order (most recent at the top)

**Details page of a past event**

- Presentation of the event
- Presentation of the Speaker
- Presentation of the Location

## 🧪 Experiment with the Notion sample connections

You may found some help about connecting with Notion on https://github.com/WengerK/course--php-notion-api
