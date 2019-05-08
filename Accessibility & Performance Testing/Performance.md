# Google Lighthouse

## 1. Introduction of Google Lighthouse
Lighthouse is an open-source, automated tool for improving the quality of web pages. You can run it against any web page, public or requiring authentication. It has audits for performance, accessibility, progressive web apps, and more.
You can run Lighthouse in Chrome DevTools, from the command line, or as a Node module. You give Lighthouse a URL to audit, it runs a series of audits against the page, and then it generates a report on how well the page did. From there, use the failing audits as indicators on how to improve the page. Each audit has a reference doc explaining why the audit is important, as well as how to fix it.

## 2. Using Google Lighthouse

* In Chrome DevTools(https://developers.google.com/web/tools/lighthouse/#devtools). Easily audit pages that require authentication, and read your reports in a user-friendly format.
* From the command line(https://developers.google.com/web/tools/lighthouse/#cli). Automate your Lighthouse runs via shell scripts.
* As a Node module(https://developers.google.com/web/tools/lighthouse/#programmatic). Integrate Lighthouse into your continuous integration systems.

## 3. Demo test website
1. Goto https://hoclieu.sachmem.vn
2. Press F12/ Open Google Dev Tools, select Audit panel
3. On Device tab : Check Desktop
   On Audit tab : Check Performance
4. Click run Audits
5. Save report file as JSON.

## 4. Youtube tutorial
https://www.youtube.com/watch?v=T1d6JnaOK8Y
