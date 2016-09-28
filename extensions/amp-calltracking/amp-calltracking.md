<!---
Copyright 2016 The AMP HTML Authors. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS-IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# <a name="amp-calltracking"></a> `amp-calltracking`

<table>
  <tr>
    <td width="40%"><strong>Description</strong></td>
    <td>Enables the use of Call Tracking with Dynamic Number Insertion</td>
  </tr>
  <tr>
    <td width="40%"><strong>Availability</strong></td>
    <td>Stable.</td>
  </tr>
  <tr>
    <td width="40%"><strong>Required Script</strong></td>
    <td><code>&lt;script async custom-element="amp-calltracking" src="https://cdn.ampproject.org/v0/amp-calltracking-0.1.js">&lt;/script></code></td>
  </tr>
  <tr>
    <td class="col-fourty"><strong><a href="https://www.ampproject.org/docs/guides/responsive/control_layout.html">Supported Layouts</a></strong></td>
    <td>fill, fixed, fixed-height, flex-item, nodisplay, responsive</td>
  </tr>
  <tr>
    <td width="40%"><strong>Examples</strong></td>
    <td><a href="https://ampbyexample.com/components/amp-calltracking">amp-calltracking.html</a><br /><a href="https://github.com/ampproject/amphtml/blob/master/examples/calltracking.amp.html">calltracking.amp.html</a></td>
  </tr>
</table>

## Examples

Example - Embedding CallTrackingMetrics:
```html
<amp-calltracking data-host="11774.tctm.co" data-path="t.js" layout="nodisplay"></amp-calltracking>
```
## Attributes

**data-host**

The host name for the tracking code

**data-path**

The pathname for the tracking code

## Validation

See [amp-calltracking rules](https://github.com/ampproject/amphtml/blob/master/extensions/amp-calltracking/0.1/validator-amp-calltracking.protoascii) in the AMP validator specification.
