# URL
### Method: GET
```bash
https://api.tkdx.in/owsearch
```
* All returned records will be sorted in descending order by `publication_date`.

# Get all files by keywords
### Parameters:
```json
keywords=malware
```
* If Keyword parameter is empty then it will return a single batch of records; our current batch size is 10.

### Response(s):
- JSON with results field containing documents:
```json
{
	"results":  [
		{
			"ActualUrl":  "https://doxbin.com/upload/GloryRomani",
			"ContactDetails":  {
				"emails":  "jilyoungdesigns@gmail.com, muriel.young@yahoo.com, glo@imbecile.cloud",
				"phones":  "919-988-0045"
			},
			"CrawlDate":  "2024-05-10T13:35:12.505000",
			"Domain":  "doxbin.com",
			"author":  null,
			"base64imagedata":  [],
			...
		},
		...
	]
}
```

# Get all files by keywords and Filter by start date
### Parameters:
```json
keywords=malware&start_date=2024-01-01
```

### Response(s):
- JSON with results field containing documents:
```json
{
	"results":  [
		{
			"ActualUrl":  "https://doxbin.com/upload/GloryRomani",
			"ContactDetails":  {
				"emails":  "jilyoungdesigns@gmail.com, muriel.young@yahoo.com, glo@imbecile.cloud",
				"phones":  "919-988-0045"
			},
			"CrawlDate":  "2024-05-10T13:35:12.505000",
			"Domain":  "doxbin.com",
			"author":  null,
			"base64imagedata":  [],
			...
		},
		...
	]
}
```

# Get all files by keywords and Filter by end date
### Parameters:
```json
keywords=malware&end_date=2024-03-20
```

### Response(s):
- JSON with results field containing documents:
```json
{
	"results":  [
		{
			"ActualUrl":  "https://doxbin.com/upload/GloryRomani",
			"ContactDetails":  {
				"emails":  "jilyoungdesigns@gmail.com, muriel.young@yahoo.com, glo@imbecile.cloud",
				"phones":  "919-988-0045"
			},
			"CrawlDate":  "2024-05-10T13:35:12.505000",
			"Domain":  "doxbin.com",
			"author":  null,
			"base64imagedata":  [],
			...
		},
		...
	]
}
```

# Get all files by keywords and Get files between start and end date
### Parameters:
```json
keywords=malware&start_date=2024-01-01&end_date=2024-03-20
```

### Response(s):
- JSON with results field containing documents:
```json
{
	"results":  [
		{
			"ActualUrl":  "https://doxbin.com/upload/GloryRomani",
			"ContactDetails":  {
				"emails":  "jilyoungdesigns@gmail.com, muriel.young@yahoo.com, glo@imbecile.cloud",
				"phones":  "919-988-0045"
			},
			"CrawlDate":  "2024-05-10T13:35:12.505000",
			"Domain":  "doxbin.com",
			"author":  null,
			"base64imagedata":  [],
			...
		},
		...
	]
}
```
