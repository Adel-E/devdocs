---
group: software-update-guide
title: Error message reference
ee_only: True
redirect_from:
  - /safe-upgrade-tool/errors.html
functional_areas:
  - Upgrade
---

This error message reference provides information about errors that can occur while executing the [Upgrade Compatibility Tool]({{site.baseurl}}/upgrade-compatibility-tool/introduction.html).

The {{site.data.var.uct}} error messages are categorized by level (*critical issues*, *errors*, and *warnings*) and type  (*core code*, *custom code*, and *GraphQL schemas*). Each type contains the following information:

*  *Error code*:  The {{site.data.var.ee}} assigned identifier for the error message.
*  *Error description*:  A description that summarizes the cause of the error.
*  *Error suggested action*:  If applicable, provides guidance to troubleshoot and resolve the error.

{%include upgrade/uct-error-reference.md%}
