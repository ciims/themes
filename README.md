# CiiMS Themes Repository

This repository contains a collection of all the approved themes for [CiiMS ](https://github.com/charlesportwoodii/ciims), and serves as the primary distribution method for all themes

## How this repository works

This repository contains an ```index.json``` file, which contains a master list of all the approved themes for CiiMS. In the dashboard, when you look to install an new theme, this file is referenced as the master approved list of themes that can be installed through the installer.

## Contributing

To contribute to this repository, first build a theme (see https://github.com/charlesportwoodii/ciims-themes-default as an example of what themes look like). Once you are happy with your theme, tag/version it using [semantic versioning](http://semver.org/). Once versioned, submitted a pull request to this repository. Your pull request should modify ```index.json``` with your card information, and should have the following information at minimum.

```
"ThemeName": {
	"name": "<name_as_defined_in_composer.json>",
	"version": "<semver_tag_version>",
	"repository": "https://github.com/<user>/<repo>"
}
```

A good example is as follows:
```
"Default": {
	"name": "ciims-themes/default",
	"version": "3.0.8",
	"repository": "https://github.com/charlesportwoodii/ciims-themes-default",
},
```

## DISCLAIMER
By submitting your card to this repository, you agree to allow CiiMS to deal with 
your card without restriction, including without limitations to the right to use, 
copy, modify, distribute, and make available to the extent necessary to publish your card.

All cards submitted to this repository are subject to scrutiny and analysis before acceptance.
CiiMS reserves the right to decline or reject a pull request for any reason, including
but not limited to: content that is unlawful, threatening, abusive, harassing, defamatory, 
libelous, deceptive, fraudulent, invasive of another's privacy, tortious, offensive, profane, 
contains or depicts pornography that is unlawful, or is otherwise inappropriate as determined 
by us in our sole discretion; that you know is false, misleading, untruthful or inaccurate;
constitutes unauthorized or unsolicited advertising; impersonates any person or entity, 
including any of our employees or representatives; includes anyone’s identification documents 
or sensitive financial information; or which attempts comprimise the security of any installed
instanced or user(s).

Inclusion of your card in this repository is in no way an endorsement of the submitted card, the
card authors, or associated names and brands.

## License
The MIT License (MIT)

Copyright (c) 2014 Charles R. Portwood II

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.