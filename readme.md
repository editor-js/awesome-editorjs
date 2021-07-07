[![](./assets/editor-awesome.png)](https://editorjs.io/)

# Awesome Editor.js [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome Editor.js tools, libraries and resources.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by contributing!

## Contents

* [Tools](#tools)
  * [Block Tools](#block-tools)
    * [Text and typography](#text-and-typography)
    * [Lists](#lists)
    * [Media & Embed](#media--embed)
    * [Table](#table)
    * [Code](#code)
    * [Button](#button)
    * [Layout](#layout)
  * [Inline Tools](#inline-tools)
  * [Block Tune Tools](#block-tune-tools)
  * [Plugins](#plugins)
* [Libraries](#libraries)
  * [JavaScript](#javascript)
    * [Vue.js](#vuejs)
    * [React](#react)
    * [Angular](#angular)
  * [PHP](#php)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Go](#go)
  * [Swift](#swift)
  * [Kotlin](#kotlin)
  * [Plugins for CMS](#plugins-for-cms)
* [Tutorials and sources](#tutorials-and-sources)
* [Projects Using Editor.js](#projects-using-editorjs)
  * [Open source projects](#open-source-projects)
<!-- * [Apps / Websites](#apps-websites) -->
<!-- * [Commercial Products](#commercial-products) -->

## Tools

### Block Tools

#### Text and typography

* [@editorjs/paragraph](https://github.com/editor-js/paragraph) — text block base tool 
* [@editorjs/header](https://github.com/editor-js/header) — header block
* [@editorjs/quote](https://github.com/editor-js/quote) — tool for quotes
* [@editorjs/warning](https://github.com/editor-js/warning) — warning tool can be used as editorials notifications or appeals
* [@editorjs/delimiter](https://github.com/editor-js/delimiter) — delimiter tool
* [editorjs-alert](https://github.com/vishaltelangre/editorjs-alert) - tool for adding colorful alert messages
* [paragraph-with-alignment](https://github.com/kaaaaaaaaaaai/paragraph-with-alignment) - text block base tool with alignment control. FYI [editorjs-alignment-blocktune](https://github.com/kaaaaaaaaaaai/editorjs-alignment-blocktune)
* [header-with-anchor](https://github.com/Aleksst95/header-with-anchor) - header block with the ability to set an anchor text

#### Lists

* [@editorjs/list](https://github.com/editor-js/list) — ordered or unordered (bulleted) lists
* [@editor-js/nested-list](https://github.com/editor-js/nested-list) — Multi-leveled lists
* [@editorjs/checklist](https://github.com/editor-js/checklist) — checklists for your texts
* [editorjs-sublist](https://github.com/codinova-tech/editorJs-list) — editor.js sublists

#### Media & Embed

* [@editorjs/image](https://github.com/editor-js/image) — image block
* [@editorjs/simple-image](https://github.com/editor-js/simple-image) — add images to article by pasting image URLs. no server-side uploader required
* [@editorjs/link](https://github.com/editor-js/link) — link with preview
* [@editorjs/attaches](https://github.com/editor-js/attaches) — attach files to your article
* [@editorjs/embed](https://github.com/editor-js/embed) — pasted patterns handling and inserts iframe with embedded content
* [simple-image-editorjs](https://github.com/PaulKinlan/simple-image) — fork of the SimpleImage repository. It adds in extra functionality such as a toolbar to add images (rather than just drag and drop) and uses blob URL's to improve memory usage
* [editorjs-github-gist-plugin](https://github.com/ranemihir/editorjs-github-gist-plugin) — add Github Gists to Editor.js
* [editorjs-social-post-plugin](https://github.com/ranemihir/editorjs-social-post-plugin) — embed uploaded posts from different social media platforms to Editor.js
* [editorjs-inline-image](https://github.com/kommitters/editorjs-inline-image) — embed images from image files, URLs or Unsplash
* [mr8bit/carousel-editorjs](https://github.com/mr8bit/carousel-editorjs) — Carousel/Gallery Block for the Editor.js
* [mdgaziur/EditorJS-LaTeX](https://github.com/mdgaziur/EditorJS-LaTeX) — LaTeX block support for EditorJS

#### Table

* [@editorjs/table](https://github.com/editor-js/table) — table constructor tool
* [editorjs-table](https://github.com/4rw44z/editorjs-table) - Table contructor tool with great editing row/column options.

#### Code

* [@editorjs/code](https://github.com/editor-js/code) — tools for code examples
* [@editorjs/raw](https://github.com/editor-js/raw) — include raw HTML code to your article
* [editor-js-code](https://github.com/paraswaykole/editor-js-code) — a fork of Code Tool for the Editor.js that allows to include code examples along with language codes that are supported by PrismJs in your articles
* [editorjs-codemirror](https://github.com/alexiej/editorjs-codemirror) — Code Mirror for the Editor.js allows to include code examples in your articles.
* [@bomdi/codebox](https://github.com/BomdiZane/codebox) — code syntax highlighting tool for Editor.js

#### Button

* [editorjs-button](https://github.com/kaaaaaaaaaaai/editorjs-button) — Create a button with a link and text.

#### Layout

* [editorjs-layout](https://github.com/hata6502/editorjs-layout) — Layout block tool for Editor.js.

### Inline Tools

* [@editorjs/marker](https://github.com/editor-js/marker) — tool for highlighting text-fragments
* [@editorjs/inline-code](https://github.com/editor-js/inline-code) — tool for marking monospace code-fragments
* [@editorjs/underline](https://github.com/editor-js/underline) — underlining text fragments
* [editorjs-hyperlink](https://github.com/trinhtam/editorjs-hyperlink) — A tool link with target & rel attribute for Editor.js
* [editorjs-inline-spoiler-tool](https://www.npmjs.com/package/editorjs-inline-spoiler-tool) — inline text spoiler
* [editorjs-inline-tool](https://github.com/natterstefan/editorjs-inline-tool) — create an inline tool for (editorjs.io) with text formatting tags (eg. bold, strong, em, u, ...)
* [editorjs-inline](https://github.com/hata6502/editorjs-inline) — Inline-Editor.js Tool for Editor.js
* [editorjs-inline-template](https://github.com/hata6502/editorjs-inline-template) — Inline-template Tool for Editor.js
* [editorjs-style](https://github.com/hata6502/editorjs-style) — Inline-style Tool for Editor.js
* [editor-mention](https://github.com/groupher/editor-mention) — Editor.js Mention tool

### Block Tune Tools

* [editorjs-alignment-blocktune](https://github.com/kaaaaaaaaaaai/editorjs-alignment-blocktune) — Add text alignment to any Block Tools.
* [editorjs-anchor](https://github.com/VolgaIgor/editorjs-anchor) — Add anchor field to any Block Tools

### Plugins

* [editorjs-drag-drop](https://github.com/kommitters/editorjs-drag-drop) — Drag/Drop feature for Editor.js
* [editorjs-undo](https://github.com/kommitters/editorjs-undo) — Undo/Redo feature for Editor.js
* [editorjs-markdown-parser](https://github.com/stejul/editorjs-markdown-parser) - Two plugins which allow you to export/import Markdown file

## Libraries

### JavaScript

* [editorjs-parser](https://github.com/MichaelMikeJones/editorjs-parser) — a library to parse Editorjs clean data to HTML in Node and Browser
* [editorjs-html](https://github.com/pavittarx/editorjs-html) — a utility to parse editorjs clean data to HTML

#### Vue.js

* [vue-editor-js](https://github.com/ChangJoo-Park/vue-editor-js) — editor.js for Vue users 

#### React

* [react-editor-js](https://github.com/Jungwoo-An/react-editor-js) — the unofficial editor-js component for React
* [@stfy/react-editor.js](https://github.com/stfy/react-editor.js) — React wrapper component for Editor.js
* [editorjs-blocks-react-renderer](https://github.com/moveyourdigital/editorjs-blocks-react-renderer) - React component to render blocks to semantic HTML5 tags

#### Angular

* [@tinynodes/ngx-editorjs](https://www.npmjs.com/package/@tinynodes/ngx-editorjs) — This library provides Angular support for EditorJS.

### PHP

* [editorjs-php](https://github.com/editor-js/editorjs-php) — server-side data validation, HTML sanitization and convertation output JSON to the Block objects
* [orchid-editorjs-field](https://github.com/AlexSabur/orchid-editorjs-field)
* [yii2-editorjs-widget](https://github.com/zakurdaev/yii2-editorjs-widget) — Editor.js widget for Yii 2
* [EditorjsBundle](https://github.com/tbmatuka/EditorjsBundle) — Symfony bundle for Editor.js
* [editorjs2html](https://github.com/aswal94/editorjs2html) — Convert blocks of editorjs into html. The parser has been written in php
* [nova-editor-js](https://github.com/advoor/nova-editor-js) — Editor JS field for Laravel Nova
* [codex-to-html](https://github.com/Archakov06/codex-to-html) — Converter EditorJS JSON to HTML
* [magento2-editorjs](https://github.com/Wamoco/magento2-editorjs) — Editor.js module for Magento 2

### Python

* [django-editorjs-fields](https://github.com/2ik/django-editorjs-fields) — Django admin plugin for using Editor.js

### Ruby

* [editor_js](https://rubygems.org/gems/editor_js) — it validates, parses, and renders content from editorjs

### Go

* [micheleriva/editorjs-go](https://github.com/micheleriva/editorjs-go) — Fast markdown/HTML generator for Editor.js
* [davidscottmills/goeditorjs](https://github.com/davidscottmills/goeditorjs) - An extensible HTML/markdown generator for editorjs.

### Swift

* [editor.js-kit-ios](https://github.com/Upstarts/editor.js-kit-ios) - iOS framework for parsing and rendering blocks

### Kotlin

* [editor.js-kit-android](https://github.com/Upstarts/editor.js-kit-android) - Android framework for parsing and rendering blocks

### Plugins for CMS

* [Front Editor](https://wpfronteditor.com/) - Front Editor plugin for [WordPress](https://wordpress.com)
* [EditorJS](https://octobercms.com/plugin/reazzon-editor) - Backend formwidget for [OctoberCMS](https://octobercms.com)

## Tutorials and sources

* [editorjs.io](https://editorjs.io) — offical docs
* [Tutorial: Integrating Editor.js into your react application](https://www.walkthrough.so/pblc/snKICMzxzedr/codelab-integrating-editor-js-into-your-react-application)
* [Tutorial: Creating a custom editorjs block tool with React](https://www.walkthrough.so/pblc/QCawSCKwOQLn/creating-a-custom-editorjs-block-tool-with-react)
* [editorjs-examples](https://github.com/hata6502/editorjs-examples) — Examples of using Editor.js

## Projects Using Editor.js

👉 [Add your project!](https://github.com/editor-js/awesome-editorjs/edit/master/readme.md)

* [⟑ djit.su](https://djit.su) — hyper-reactive notebook interface
* [Poda](https://poda.io) — Project planning and roadmaping
* [Walkthrough](http://walkthrough.so/) - Write great codelab style tutorials.
* [Unicorn Platform](https://unicornplatform.com/) - Create landing pages and write blogs.
* [Slid](https://slid.cc) - Video note-taking tool for online learners.

### Open source projects

* [CodeX Docs](https://github.com/codex-team/codex.docs) — documentation engine
* [CodeX Media](https://github.com/codex-team/codex.media) — platform for building modern website for educational or media organizations
* [CodeX Notes](https://github.com/codex-team/codex.notes) — crossplatform desktop notes application based on Electron and Editor.js
* [OmniaWrite.com](https://OmniaWrite.com) — a text editor engineered for creative writing
* [automad.org](https://automad.org) — a flat-file content management system and template engine
* [Noter](https://noter.sambitsahoo.com) - A State of the Art realtime and collaborative note taking platform


<!--
### Apps/Websites
-->

[Back to top](#contents)
