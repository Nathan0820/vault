---
title: Welcome to my digital garden!
publish: true
---

This is my collection of notes, thoughts, and ideas. I use this space to learn in public and share what I'm working on.

Feel free to explore and see how my ideas connect and evolve over time.

### Recently updated
<%
const recent = await render(
  `RecentNotes`,
  {
    limit: 5,
    showTags: false,
    linkToMore: "tags/note"
  }
)
%>

<%= recent %>
