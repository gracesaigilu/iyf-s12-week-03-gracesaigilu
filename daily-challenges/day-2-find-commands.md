# Day 2: Find Command Mastery

1. Find all CSS files in projects folder:
`find . -type f -name "*.css"`

2. Find all files modified in the last 7 days:
`find . -type f -mtime -7`

3. Search for "flex" in all CSS files:
`grep -rnw . -e "flex" --include="*.css"`

4. Count occurrences of "div" in HTML files:
`grep -o -i "div" $(find . -type f -name "*.html") | wc -l`

