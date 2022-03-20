# regex-resources
A collection of Regex resources and patterns

# Python

| Pattern     | Description    |
|-----|------|
| [E][N]\s\d{3,8}\s-[\s\w]     | Search for EN Standards in the format EN 10855 -   |
| [^.?!]*(?<=[.?\s!])WORD(?=[\s.?!])[^.?!]*[.?!]   | Complete sentence containing "WORD"   |
| EN\s*I*E*C*\s*\d{2,8}-*\d*-*\d*-*\d*:*\d*[+]*[A]*\d*:*\d*[+]*[A]*\d*:*\d*[+]*[A]*\d*:*\d*  | Seach for standard including as per EN above but including everyting including EN IEC 1234-29-2:2009+A01:2010+A02:2011 |
