<!doctype html>
<html><head><title>Wecome</title><meta charset="UTF-8"><link href="http://fonts.googleapis.com/css?family=Crimson+Text:400,400italic,700,700italic|Roboto:400,700,700italic,400italic" rel="stylesheet" type="text/css"><style>/*
 * Copyright 2014 Quip
 *
 * Licensed under the Apache License, Version 2.0 (the "License"); you may
 * not use this file except in compliance with the License. You may obtain
 * a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
 * WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
 * License for the specific language governing permissions and limitations
 * under the License.
 */

body {
    font-size: 15px;
    color: #333;
    background: #fff;
    padding: 60px 95px;
    max-width: 900px;
    margin: 0 auto;
    text-rendering: optimizeLegibility;
    font-feature-settings: "kern";
    font-kerning: normal;
    -moz-font-feature-settings: "kern";
    -webkit-font-feature-settings: "kern";
}

/* Headings */
h1, h2, h3, th {
    font-family: Roboto, sans-serif;
    font-weight: 700;
    margin: 0;
    margin-top: 1.25em;
    margin-bottom: 0.75em;
}

h1 {
    font-size: 35px;
    line-height: 42px;
}

h1:first-child {
    margin-top: 0;
}

h2 {
    font-size: 18px;
    line-height: 22px;
}

h3 {
    text-transform: uppercase;
    font-size: 13px;
    line-height: 16px;
}

/* Body text */
body, p, ul, ol, td {
    font-family: 'Crimson Text', serif;
    font-size: 16px;
    line-height: 20px;
}

blockquote, q {
    display: block;
    margin: 1em 0;
    font-style: italic;
}

blockquote a, q a {
    text-decoration: underline;
}

blockquote {
    padding-left: 10px;
    border-left: 4px solid #a6a6a6;
}

q {
    color: #a6a6a6;
    line-height: 40px;
    font-size: 24px;
    text-align: center;
    quotes: none;
}

q a {
    color: #a6a6a6;
}

code, pre {
    font-family: Consolas, "Liberation Mono", Menlo, "Courier Prime Web", Courier, monospace;
    background: #f3f3f3;
}

code {
    padding: 1px;
    margin: 0 -1px;
    border-radius: 3px;
}

pre {
    display: block;
    line-height: 20px;
    text-shadow: 0 1px white;
    padding: 5px 5px 5px 30px;
    white-space: nowrap;
    position: relative;
    margin: 1em 0;
}

pre:before {
    content: "";
    position: absolute;
    top: 0;
    bottom: 0;
    left: 15px;
    border-left: solid 1px #dadada;
}

/* Lists */
div[data-section-style="5"],
div[data-section-style="6"],
div[data-section-style="7"] {
    margin: 12px 0;
}

ul {
    padding: 0 0 0 40px;
}

ul li {
    margin-bottom: 0.4em;
}

/* Bulleted list */
div[data-section-style="5"] ul {
    list-style-type: disc;
}
div[data-section-style="5"] ul ul {
    list-style-type: circle;
}
div[data-section-style="5"] ul ul ul {
    list-style-type: square;
}
div[data-section-style="5"] ul ul ul ul {
    list-style-type: disc;
}
div[data-section-style="5"] ul ul ul ul ul {
    list-style-type: circle;
}
div[data-section-style="5"] ul ul ul ul ul ul {
    list-style-type: square;
}

/* Numbered list */
div[data-section-style="6"] ul {
    list-style-type: decimal;
}
div[data-section-style="6"] ul ul {
    list-style-type: lower-alpha;
}
div[data-section-style="6"] ul ul ul {
    list-style-type: lower-roman;
}
div[data-section-style="6"] ul ul ul ul {
    list-style-type: decimal;
}
div[data-section-style="6"] ul ul ul ul ul {
    list-style-type: lower-alpha;
}
div[data-section-style="6"] ul ul ul ul ul ul {
    list-style-type: lower-roman;
}

/* Checklist */
div[data-section-style="7"] ul {
    list-style-type: none;
}

div[data-section-style="7"] ul li:before {
    content: "\2610";
    position: absolute;
    display: inline;
    margin-right: 1.2em;
    margin-left: -1.2em;
}

div[data-section-style="7"] ul li.parent:before {
    content: "";
}

div[data-section-style="7"] ul li.parent {
    font-weight: bold;
}

div[data-section-style="7"] ul li.checked {
    text-decoration: line-through;
}

div[data-section-style="7"] ul li.checked:before {
    content: "\2611";
    text-decoration: none;
}

/* Tables */
div[data-section-style="8"] {
    margin: 12px 0;
}

table {
    border-spacing: 0;
    border-collapse: separate;
    border: solid 1px #7c7c7c;
    box-shadow: 0 1px 2px rgba(0, 0, 0, .25);
    table-layout: fixed;
    position: relative;
}

table th, table td {
    padding: 2px 2px 0;
    min-width: 1.5em;
    word-wrap: break-word;
}

table th {
    border-bottom: 1px solid #ccc;
    background: #f0f0f0;
    font-weight: bold;
    vertical-align: bottom;
    color: #3a4449;
    text-align: center;
}

table td {
    padding-top: 0;
    border-left: 1px solid #e1e1e1;
    border-top: 1px solid #e1e1e1;
    vertical-align: top;
}

table td.bold {
    font-weight: bold;
}

table td.italic {
    font-style: italic;
}

table td.underline {
    text-decoration: underline;
}

table td.strikethrough {
    text-decoration: line-through;
}

table td.underline.strikethrough {
    text-decoration: underline line-through;
}

table td:first-child {
    border-left: hidden;
}

table tr:first-child td {
    border-top: hidden;
}

/* Images */
div[data-section-style="11"] {
    margin-top: 20px;
    margin-bottom: 20px;
    margin-left: auto;
    margin-right: auto;
}

div[data-section-style="11"][data-section-float="0"] {
    clear: both;
    text-align: center;
}

div[data-section-style="11"][data-section-float="1"] {
    float: left;
    clear: left;
    margin-right: 20px;
}

div[data-section-style="11"][data-section-float="2"] {
    float: right;
    clear: right;
    margin-left: 20px;
}

div[data-section-style="11"] img {
    display: block;
    max-width: 100%;
    height: auto;
    margin: auto;
}

hr {
    width: 70px;
    margin: 20px auto;
}
</style></head><body><h1 id='LHQACAj1j4j'>Wecome</h1>

link:<br/>www.baidu.com

e-mail:2336221276@qq.com<br/>

</body></html>
