---
title: "read me"
author: Till Grallert
date: 2016-05-19 10:31:19 +0300
---


MODS Boilerplate provides a first display of MODS XML files in the browser based on XSLT 1 and without need for pre-processed HTML. For a first impression see the [example file in this repository](https://rawgit.com/tillgrallert/mods-boilerplate/master/example/oclc_4770057679-v_5-bibl.MODS.xml).

The code has been developed in the context of the [Digital Muqtabas](https://github.com/tillgrallert/digital-muqtabas), [Digital Ḥaqāʾiq](https://github.com/tillgrallert/digital-haqaiq) and [Digital Manār](https://github.com/tillgrallert/digital-manar) projects.

The display is built around modular css files that are all loaded through a central call to `custom.css`.


# Installation / use:

The code can either be used by downloading / cloning the repository and integrating it into one's own project or by simply linking `xslt-boilerplate/teibp.xsl` of this repository in the head of one's XML files.

There are three variants, each in its own branch:

## 1. master

This branch is meant to be installed as part of the project it is used to render. All links to files are relative links only.

```
<?xml-stylesheet type="text/xsl" href="https://rawgit.com/tillgrallert/mods-boilerplate/online/xslt-boilerplate/mods-bp.xsl"?>
~~~

## 2. online

This branch needs no local installation. It can be used to load the online boilerplate for any MODS XML file.

```
<?xml-stylesheet type="text/xsl" href="https://rawgit.com/tillgrallert/mods-boilerplate/online/xslt-boilerplate/mods-bp.xsl"?>
~~~