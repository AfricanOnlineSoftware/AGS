# Amageza GPX scoring (AGS)
*Race scoring system*

---
<br>

## Installation
To install **AGS**, simply pull/clone this git repository into the "document root" of your live/staging server. Alternatively you can also download the `zip` archive and extract the contents to your server.

When the above is done, simply use a web browser to access it accordingly.
<br><br>


## Synopsis
This software is used to score a competitor's race performance based on their recorded GPS data during a race together with a race (stage) template in the standard "GPX" xml data format.

The template defines `way-points` and `rules` by which the competitor must adhere in order to achieve a good score.<br>
If competitors diverge from these rules during the race, then they are penalized by adding `time-penalty` to their `special` (liaison) time. The time penalties are predefined in the configuration of the software - which is customizable.
<br><br>


## Scope
The purpose of this software is:
- scoring each competitor by evaluating their performance against the race (stage) template
- generate over-all race (stage) data in JSON format
- output a printable score summery per competitor -per race

The initial (beta) version of this software runs in a web browser and is written in W3C recommended standards, such as HTML, CSS and JavaScript.

The HTML & CSS is used for graphical user interface and printing. The JavaScript is used for application logic such as importing the GPX data from the stage templates and each competitor's recorded GPX data and calculate distance, time, score, etc.
<br><br>


## Documentation
The "source" used to build this software with is in the `src` folder.

The "documentation" of the code, "project road-map", etc, is in the `doc` folder, written in the widely used "markdown" text format, such as this readme file.

All application files used in the browser (and possibly the server - accessible to the world-wide-web) is in the `www` folder.
