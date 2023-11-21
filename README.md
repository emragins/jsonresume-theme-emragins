# jsonresume-theme-emragins
Cloned from https://github.com/dineshdhamija/jsonresume-theme-dinesh and modified to fit my resume, which is that of a consultant who's moved around a lot, both in terms of projects and technologies.

Of note, this is
* compact
* allows for projects under work
* repurposes skill levels to be used as headings
* adds `basics.achievements` to show a list of notable accomplishments at the top

Tries to fit as much information as possible onto a single page without making sections look cluttered.

There is still a lot I want to do with this. 

## Example

http://themes.jsonresume.org/theme/emragins

## Running

```
# resume-cli
sudo npm install -g resume-cli
git clone https://github.com/emragins/jsonresume-theme-emragins.git
cd jsonresume-theme-emragins
resume serve

# resumed

```
You can print directly from the served html.

## Options

* adds `meta.showProfiles` to show/hide social profiles


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

