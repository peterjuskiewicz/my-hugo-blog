+++
draft = false
date = 2019-09-30T13:39:17+02:00
title = "מהו HTTP"
description = "יסודות הפרוטוקול"
slug = ""
authors = ["Peter Juskiewicz"]
tags = ["אינטרנט"]
categories = []
externalLink = ""
series = []
+++

## HTTP

HTTP (Hypertext Transfer Protocol) הוא פרוטוקול המשמש להעברת היפרטקסט (Hypertext) ברשת האינטרנט העולמית (World Wide Web).  
הוא מגדיר כיצד הודעות מעוצבות ומועברות, וכיצד שרתי אינטרנט ודפדפנים אמורים להגיב לפקודות שונות.  
HTTP פועל במודל של **בקשה-תגובה (Request–Response)**: לקוח (בדרך כלל דפדפן אינטרנט) שולח בקשת HTTP לשרת עבור משאב — כגון דף אינטרנט או קובץ — והשרת משיב עם התוכן המבוקש ועם **קוד סטטוס (Status Code)** המצביע על תוצאת הבקשה.

HTTP הוא **פרוטוקול חסר מצב (Stateless)**, כלומר כל בקשה מלקוח לשרת היא עצמאית ואינה שומרת מידע על אינטראקציות קודמות.  
הפרוטוקול מהווה את הבסיס לתקשורת נתונים ברשת, ומשמש לרוב עם גרסתו המאובטחת **HTTPS**, המספקת תקשורת מוצפנת ובטוחה.

למידע נוסף, בקרו באתר [Cloudflare](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)!
