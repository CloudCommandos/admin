# CloudCommandos Documentation Guidelines

Good documentation is important to ensure our documentation stays relevant, easy to update and comprehend. For text and code editing, ‘Atom’ is used to facilitate for any editing. 
Always ‘Markdown Preview’ on your .md file when you are using Atom as it helps to preview the whole .md when you are editing. Previewing makes it easy to view the result of the work before doing a Pull Request.  

Specify clearly the changes made on the comment section when doing a Pull Request.  

When a document is being edited simultaneously by multiple users, the first user who commits will not have any issue. 
The next user who wants to commit will have issue and is unable to do the commit. 
The user should resolve the conflict and do the necessary amendment before committing.  

**Always Pull before Push.** Version control is critical when multiple users edit a common document.

## Standardisation on Markdown syntax
Here are some of the common Markdown syntax that should be followed when editing the .md file.
### Header
<pre>
# H1
## H2
### H3
</pre>
### Emphasis
<pre>
This is **Bold**
This is *Italic* or _Italic_
</pre>
This is **Bold**  
This is *Italic* or _Italic_

### Lists
<pre>
1. First ordered
1. Second ordered
(insert 3 spaces at the front)* unordered sub-list

1. Third ordered
(insert 3 spaces at the front)1. ordered sub-list 1
(insert 3 spaces at the front)1. ordered sub-list 2
1. Fourth ordered
</pre>

1. First ordered
1. Second ordered
   * unordered sub-list

1. Third ordered
   1. ordered sub-list 1
   1. ordered sub-list 2
1. Fourth ordered  
 
### Code
For single line command, use 
<pre>
`echo "Hello"`
</pre>

`echo "Hello"`

For code block with bash, use the following:
<pre>
```bash
apt-get install nginx
cd /etc
```
</pre>

```bash
echo "Hello Cloud"
cd /etc
```

### Link
Create a hyperlink on the title when the content is reference from a site.
<pre>
[Google Homepage](https://www.google.com)
</pre>

[Google Homepage](https://www.google.com)

### Table
Creating table using pipes and hyphens. Only 3 hyphens are required to create a column.
<pre>
| Column 1 | Column 2 | Column 3|
|---|---|---|
| row 1 | row 1 | row 1 |
</pre>

| Column 1 | Column 2 | Column 3|
|---|---|---|
| row 1 | row 1 | row 1 |

Aligning of the text in the column:
<pre>
| Column 1 | Column 2 | Column 3|
|:---|:---:|---:|
| row 1 | row 1 | row 1 |
</pre>
| Column 1 | Column 2 | Column 3|
|:---|:---:|---:|
| left| center | right |
