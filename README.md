# jsonresume-theme-emragins
Cloned from jsonresume-theme-dinesh.
A compact theme for JSON Resume, designed for printing. 

Tries to fit as much information as possible onto a single page without making sections look cluttered.


## Example

http://themes.jsonresume.org/theme/emragins

## Running

```
sudo npm install -g resume-cli
git clone https://github.com/emragins/jsonresume-theme-emragins.git
cd jsonresume-theme-emragins
resume serve
```
You can print directly from the served html.

## Options

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See included resume.json for more details.

