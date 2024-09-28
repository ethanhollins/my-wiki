#  <%* tR += "<%+ tp.file.title %\>" %>
<div style="font-size: 10pt;">
<strong>Creation Date</strong>: <% tp.file.creation_date("dddd Do MMM YYYY HH:mm:ss") %><br>
<strong>Last Modified</strong>: <%* tR += "<%+ tp.file.last_modified_date(\"dddd Do MMM YYYY HH:mm:ss\") %\>" %> <br>
<strong>Author</strong>: Ethan Hollins
</div> 
---

## Subtopic 1: Specific Concept or Feature
Write your researched commentary on this particular topic here. Ensure to provide valuable insights, concise explanations, and clearly organized content.

- If the information comes from any particular resources (articles, books, videos, etc.), ensure you properly **cite**[^1] your sources.
- Whenever referencing another page in your wiki, link directly using Obsidian's internal linking system, like so: [[Related Wiki Page]].

### Example Code Snippet
Whenever relevant, executable example code should be saved in the **examples** folder. Include a snippet of the code that is contextually important, and link to the full file for reference.

```Python
if __name__ == "__main__":
	print("Hello World!")
``` 
Source: [some_example.py](examples/some_example.py)


[^1]: [The Best Book Ever](https://www.thebestbookever.com)