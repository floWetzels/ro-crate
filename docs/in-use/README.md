# Template for RO-Crate-in-use pages

See example: <https://www.researchobject.org/ro-crate/in-use/rohub.html>

First upload logo in SVG or PNG format to [assets.ung](../assets/img), naming it same as the new page, e.g. `example.svg` to match `example.md` - you may also add a `example-screenshot.png` to illustrate how RO-Crate is used.

Then in this folder, create a new file here using the below template, e.g. `example.md`. Add a short paragraph and link to the new page from [index.md](index.md).

Replace _Example_ and _example.org_ below with name/link for the new project.


## Template

_See the [raw markdown](https://raw.githubusercontent.com/ResearchObject/ro-crate/master/docs/in-use/README.md) to copy, from below till end of page, to the new `example.md`_

---
title: Example
parent: RO-Crate In Use
---
<!--
   Copyright 2019-2022 RO-Crate contributors
   <https://github.com/ResearchObject/ro-crate/graphs/contributors>

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->

# Example

[![Example logo](../assets/img/example.svg)](https://example.org/)

[Example](https://reliance.rohub.org/) (EXAMPLE-ACRONYM), is a...

Example uses RO-Crate for ... as ....

Example works with Project X, .....

![Example screenshot with RO-Crate(../assets/img/example-screenshot.png)


## RO-Crate in Example

(Show practically how RO-Crate is used, link to profile of RO-Crate, etc.)

The Example API supports [RO-Crate export](http://example.org/docs/ro-crate) as...

Example also plans to do...

Example:
```
curl -H "Accept: application/ld+json" https://example.com/ro-crate/a72f314d

{
  "@context": { … },
  "@graph": [
   …
    {
      "@id": "./",
      "hasPart": […],
      "@type": "Dataset",
    }
   …
}
```


## Resources

* [Example Homepage](https://example.org/)
* [Example documentation](https://example.org/docs/)
* [RO-Crate profile for Example](https://example.org/crate-profile)
* [Example Tutorials](https://example.org/docs/tutorial)
* [Example presentation](http://example.org/)

## Publications

Alice Land, Bob Bunny (2020):  
**Example and RO-Crate**.  
_Example Journal_ **0**(1)
<https://doi.org/10.1234/example>  
[[preprint](http://example.com/preprint.pdf)]