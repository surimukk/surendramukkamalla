SUR endramukkamalla.com — deployment package

Upload this folder structure exactly:

index.html
insights/
  petabyte-enterprise-data-ai-platform.html
  ai-coding-assistants-agentic-engineering.html

What changed:
- The homepage Insights section now contains only the two real articles.
- Each homepage Read Article link points to the matching file under /insights/.
- Article navigation links return to the homepage Work, Architecture, Insights and About sections.
- The petabyte article now includes a Back to Insights link.
- Existing embedded diagrams/images remain inside each HTML file, so no separate image files are required.

Cloudflare Pages:
Replace your existing root index.html with this index.html and upload the insights folder beside it.
