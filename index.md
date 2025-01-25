{% capture my_include %}{% include_relative acadien_resume.md %}{% endcapture %}
{{ my_include | markdownify }}
