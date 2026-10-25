# tranducle.github.io

Source of the academic homepage of **Tran Duc Le** (Assistant Professor, University of Wisconsin-Stout), published at <https://tranducle.github.io/>.

Built with Jekyll on GitHub Pages, based on the [academicpages](https://github.com/academicpages/academicpages.github.io) / Minimal Mistakes theme (MIT License, see `LICENSE`).

## Where to edit

| Page | File |
|---|---|
| Home / About & News | `_pages/about.md` |
| Research | `_research/research.md` |
| Publications | `_publications/publications.md` |
| Teaching | `_teaching/teaching.md` |
| Qualification | `_qualification/qualifications.md` |
| Service | `_service/service.md` |
| Top menu | `_data/navigation.yml` |
| Sidebar profile, site settings | `_config.yml` (`author:` block) |
| CV and other PDFs | `files/` (CV: `files/CV_Tran_Duc_Le.pdf`, also reachable at `/cv/`) |
| Images | `images/` |

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```
