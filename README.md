# ReportingTool_V1.1.jar AUTOMATION Tool


[![Build Status](https://secure.travis-ci.org/wet-boew/wet-boew.png?branch=master)](http://travis-ci.org/wet-boew/wet-boew)

**Testing Web Application page(s) for Accessibility issue(s)**

The purpose of this tool is to generate testing results into an Excel spreadsheet. It is proven that the Spreadsheet results generated by this Reporting Tool helps the developer to understand and fix each issue. The reports generated by this automation tool offer a Quality Assurance review results for Web Accessibility Standard (W3C WCAG 2.0 AA) and Web Interoperability.  This automation tool provided results that represent about 70% of the testing.  Please note that Manual testing is still required after the Automation results is done.  The 3 tools that will be driven by the Reporting Tool are: WPSS, CSE HTML Validator Pro and W3C Service validation.  All tests can be performed using each single tool separately. This tool does not generate Web Usability reports at this time. 

**Installation Procedures:**
Download the Automation Tool package then click on the InstallationSetUp.bat to create all required 5 files below in the directory QA-WS-Tool of your ROOT C drive. Ensure that the WPSS Tool and the CSE HTML Validator Pro are correctly installed. The 5 files required in your C:\QA-WS-Tool directory are: 
* 1.	Input.xls  (Just Add your Url page(s) (for Testing) in this spreadsheet then execute the ReportingTool_v1.x.jar)
* 2.	Output-CSE.xls
* 3.	Output-W3C-xls
* 4.	Output-WPSS.xls
* 5.	ReportingTool_v1.x.jar (To Execute the Reporting tool, just double-click on the jar file)

**Software Requirements:**  The following Softwares are required prior the execution of the Reporting Tool jar file:
* Java Runtime version 7 (32 bit) or above
* CSE HTML Validator Pro 14
* WPSS v3.10.0 or above 
* Firefox 21 or above
* Windows 7
* IE 9.0

**WCAG 2.0 Success Criteria Checklist:**  The following are required for a Web page to satisfy a WCAG 2.0 Success Criterion: 
* **12 Guidelines, 38 Success Criteria** (http://www.tbs-sct.gc.ca/ws-nw/wa-aw/wa-aw-assess-methd-eng.asp)

## Other WCAG2 Tools follows:

* **WPSS tool v3.10 Executable included** (https://github.com/langloisga/TestingWCAG2/archive/master.zip)
* **W3C Markup Validation Service** http://validator.w3.org/#validate-by-input
* **WCAG Contrast Checker** https://addons.mozilla.org/en-US/firefox/addon/wcag-contrast-checker/
* **CSE HTML Validator** http://www.htmlvalidator.com/
* **OpenAjax Alliance** https://addons.mozilla.org/en-us/firefox/addon/openajax-accessibility-exte/
* **Total Validator** http://www.totalvalidator.com/downloads/index.html
* **WAVE Tool Bar** https://addons.mozilla.org/en-us/firefox/addon/wave-toolbar/
* **Accessibility Tool bar** https://addons.mozilla.org/en-US/firefox/addon/accessibility-evaluation-toolb/
* **Web Developers Tool bar** https://addons.mozilla.org/en-US/firefox/addon/web-developer/
* **Firebug** https://addons.mozilla.org/en-US/firefox/addon/firebug/
* **SortSite** http://try.powermapper.com/demo/sortsite.aspx
* **Color Contrast tool** http://juicystudio.com/services/luminositycontrastratio.php
* **ColorZilla** https://addons.mozilla.org/en-US/firefox/addon/colorzilla/
* **W3C Feed Validation Service** http://validator.w3.org/feed/#validate_by_input
* **W3C CSS Validation Service** http://jigsaw.w3.org/css-validator/#validate_by_input

 
**Popular Assistive Technology Products follows:**
* **JAWS** http://www.freedomscientific.com/downloads/jaws/jaws-downloads.asp
* **NVDA** http://www.nvda-project.org/wiki/Download
* **ChromeVox** http://www.chromevox.com/

## Background

The Secretary of the Treasury Board announced in January 2010 that the existing CLF 2.0 Standards 
would be replaced by three new standards: the Standard on Web Accessibility, the Standard on Web Usability,
and the Standard on Web Interoperability. This announcement signalled that the Government of Canada would 
move towards adopting WCAG 2.0 - the most current internationally recognized guidelines on Web accessibility.  

**Government of Canada Web Standards and Guidelines**
* *Standard on Web Accessibility* (http://www.tbs-sct.gc.ca/ws-nw/wa-aw/index-eng.asp)
* *Standard on Web Usability* (http://www.tbs-sct.gc.ca/ws-nw/wu-fe/index-eng.asp)
* *Standard on Web Interoperability* (http://www.tbs-sct.gc.ca/ws-nw/wi-iw/index-eng.asp)
* *Guidance on Implementing Web Accessibility* (http://www.tbs-sct.gc.ca/ws-nw/wa-aw/wa-aw-guid-eng.asp)
* *Guidance on Implementing Web Usability* (http://www.tbs-sct.gc.ca/ws-nw/wu-fe/wu-fe-guid-eng.asp)
* *WET Template* (https://github.com/wet-boew/wet-boew)
* *Web Content Accessibility Guidelines (WCAG) 2.0* (http://www.w3.org/TR/WCAG20)
* *WCAG Quick Reference* (http://www.3pha.com/wcag2)

## Benefits of using Web Experience Toolkit (WET) include:
* Reduce costs using ready-made Web tools and solutions for building and maintaining innovative websites (including Web applications).
* Decrease website (including Web applications) development times by using a wide range of supported website (including Web applications) layouts and designs.
* Use existing website (including Web applications) features that respect accessibility (WCAG 2.0 AA and WAI-ARIA), usability, and interoperability.
* Apply advanced and innovative technologies to push the envelope for website (including Web applications) functionality:
        HTML5, CSS3, jQuery (JavaScript framework);
        Ever-growing list of open source plugins and widgets.
* Use open source software that is free for use by institutions and external Web communities.

Build Web pages using the most recent version of the [Web Experience Toolkit (WET)] (https://github.com/wet-boew/wet-boew) is
highly recommended. WET is a collection of ready-made tools and solutions for building and maintaining 
innovative websites (including Web applications) that are accessible, usable, and interoperable.
