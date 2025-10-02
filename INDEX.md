---
Company: CompTIA
Course: A+
Teacher: Professor Messer
Exam Code: 220-1201
Difficulty: Easy
Topic: Index
---
### 1. Mobile Devices

```dataview
LIST
FROM "CompTIA A+/1 - Mobile Devices"
	WHERE file.name != "INDEX" 
	SORT file.name ASC
```


### 2. Networking

```dataview
LIST
FROM "CompTIA A+/2 - Networking"
WHERE file.name != "INDEX"
  AND !contains(file.path, "images")
SORT file.name ASC
```
