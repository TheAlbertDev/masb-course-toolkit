{% set socials_text -%}
{%- if exercise_title -%}
I just completed the "{{ exercise_title }}" MASB Course hands-on exercise! 🎉
{%- else -%}
I just completed a MASB Course hands-on exercise! 🎉
{%- endif %}

{{ repository_url }}

#masb #TheAlbertDev
{%- endset -%}

<div align="center">

# 🎉 Congratulations {{ login }}! 🎉

<img src="https://raw.githubusercontent.com/thealbertdev/masb-course-toolkit/v1/markdown-templates/images/thealbertdevbot_celebration.png" height="400px" />

### 🌟 You've successfully completed the exercise! 🌟

## 🚀 Share Your Success!

**Show off your new skills and inspire others!**

<a href="https://twitter.com/intent/tweet?text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20X-1da1f2?style=for-the-badge&logo=x&logoColor=white" alt="Share on X" />
</a>
<a href="https://bsky.app/intent/compose?text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20Bluesky-0085ff?style=for-the-badge&logo=bluesky&logoColor=white" alt="Share on Bluesky" />
</a>
<a href="https://www.linkedin.com/feed/?shareActive=true&text={{ socials_text | urlencode }}" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Share%20on%20LinkedIn-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Share on LinkedIn" />
</a>

---

&copy; 2026 TheAlbertDev &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
