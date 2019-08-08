.. role:: vscode
.. role:: intellij
.. cssclass:: topic

Viewing Reports
===============

.. include:: ../change_filter.rst

.. cssclass:: vscode dynamic-content

:vscode:`Viewing Reports from VS Code`
======================================

Once the specifications are run you will get immediate feedback in the output screen of VS Code.

Once you've run the sample spec, you can view the HTML report of the tests run by following either of the steps below:

Open the html report by clicking on the view summary link in VS Code

.. figure:: ../images/VSCode_report_link.png
    :alt: VSCode execution report link

OR

In the editor's command pallete type Gauge: Show Last Run Report to view the report in the browser

.. figure:: ../images/VSCode_show_last_run_report.png
    :alt: VSCode show last run report command

Here's what a Gauge report looks like.

.. figure:: ../images/HTML_report.png
    :alt: HTML report

.. cssclass:: intellij dynamic-content

:intellij:`Viewing Reports from Intellij IDEA`
==============================================

Once the specifications are run you will get immediate feedback in the output screen of Intellij.

Once you've run the sample spec, you can view the HTML report of the tests run by opening the :highlighted-syntax:`index.html` file available in :highlighted-syntax:`$PROJECT_ROOT/reports/html-report/index.html`

Here's what a Gauge report looks like.

.. figure:: ../images/HTML_report.png
    :alt: HTML report

Next Step: Running a Specification
==================================

And, that concludes our getting started journey for Gauge. Hopefully this helped you install and set-up your first Gauge project. Gauge comes with powerful language & tool support as well as a versatile reporting functionality. We've covered the basics for all of these features in this guide.

As a next step, the following resources are available:

.. cssclass:: text-box

    * `Write Specifications  <../writing-specifications.html>`__: This section has more in-depth detail on writing Gauge specifications and connecting them with the test scripts of your choice.

    * `Examples <../examples-and-tutorials.html>`__: The examples section contains example projects of different languages and tools to help you get started with exactly what you need.
    
    * `Taiko Documentation <https://taiko.gauge.org/>`__:  The Taiko documentation site has all information you need to start recording test scripts using Taiko.


.. container:: page-navigator

    .. container:: navigate-previous

        `Running a Specification <running-a-specification.html>`__