# Link Test

1. `[no spaces](filename-no-spaces.md)` --> [no spaces](filename-no-spaces.md)
2. `[with spaces](filename with spaces.md)` --> [with spaces](filename with spaces.md)
3. `[encoded spaces](filename%20with%20spaces.md)` --> [encoded spaces](filename%20with%20spaces.md)
4. `[spaces within quotes]("filename with spaces.md")` --> [spaces within quotes]("filename with spaces.md")
5. `[escaped spaces](filename\ with\ spaces.md)` --> [escaped spaces](filename\ with\ spaces.md)

Notes:
- (1) correctly links to the generated HTML file
- (2) is not considered a valid link in the MD file, but correctly converts to a link to the HTML file
- (3) is consoidered a valid MD link, however it __does not convert to a link to the HTML file__
- (4) and (5) don't work at all, as expected (they're not valid MD links)

